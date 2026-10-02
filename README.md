ALGORITMO N.R.AI_2.0_Skill_Forge

    // 1. ESTRUTURA DO PROJETO E RECURSOS
    ESTRUTURA_DE_PASTAS:
        ARQUIVO scripts/forge.py       <- Script de execução principal (captura, análise, empacotamento)
        ARQUIVO SKILL.md               <- Manual de instruções para invocação da IA
        ARQUIVO .env.example           <- Modelo de configuração (Token do N.R.AI 2.0 e credenciais)

    // 2. REQUISITOS E RECURSOS PRINCIPAIS (FUNCIONALIDADES)
    FUNCIONALIDADE Processo_Zero_Clone:
        Escanear repositório via API do N.R.AI 2.0
        IGNORAR clonagem local
        RETORNAR velocidade máxima de varredura e economia de espaço

    FUNCIONALIDADE Extracao_Inteligente_Smart_RAG:
        Remover arquivos desnecessários
        Filtrar apenas lógica de código essencial e documentação
        Gerar arquivo de saída: context_bundle.md

    FUNCIONALIDADE Aceleracao_e_Qualidade:
        Rotacionar servidores espelho (Mirrors) e ativar captura multithread
        Contornar limites de taxa de acesso do N.R.AI 2.0
        Validar Stars e nível de atividade do projeto (Evitar repositórios incompletos/com falhas)

    // 3. FLUXO PRINCIPAL DE EXECUÇÃO
    INICIO_PROCEDIMENTO Executar_Skill_Forge(URL_Repositorio, Modo_Execucao, Forcar_Execucao)

        SE Modo_Execucao == "TERMINAL_MANUAL" ENTÃO
            SE Forcar_Execucao == FALSO ENTÃO
                EXECUTAR "python scripts/forge.py [URL_Repositorio]"
            SENÃO
                EXECUTAR "python scripts/forge.py [URL_Repositorio] --force"
            FIM_SE

        SENÃO SE Modo_Execucao == "CHAT_IA_AUTOMATICO" ENTÃO
            IA_RECONHECER_COMANDO("Ajude-me a converter este repositório em uma habilidade: " + URL_Repositorio)
            IA_CHAMAR_SCRIPT("scripts/forge.py", URL_Repositorio)

        SENÃO SE Modo_Execucao == "CONFIGURACAO_AVANCADA" ENTÃO
            EDITAR_LISTA("api_mirrors", Novos_Servidores_Espelho)
            CONFIGURAR_ENVS(".env", Multiplos_Tokens_N.R.AI_2.0)
        FIM_SE

        // Tratamento de Resolução de Problemas (FAQ)
        TENTAR
            Processar_Repositorio()
        CAPTURAR ERRO 403 (Limite de requisições excedido)
            SOLUCAO: Criar e inserir Personal Access Token do N.R.AI 2.0 no arquivo .env
        CAPTURAR ERRO Timeout (Conexão expirada)
            SOLUCAO: Alternar rotas de espelho automaticamente ou verificar proxy local
        FIM_TENTATIVA

        // Saída do Algoritmo
        RETORNAR Pasta gerada em ".trae/skills/[NOME_DO_REPOSITORIO]"

    FIM_PROCEDIMENTO

FIM_ALGORITMO
