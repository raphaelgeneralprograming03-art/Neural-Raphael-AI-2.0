<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Neural Raphael Hub · GitHub Edition</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#080c14;--b2:#111827;--bd:#1f2937;--fg:#f3f4f6;--mu:#9ca3af;--ac:#818cf8;--gr:#34d399;--rd:#f87171;--pu:#c084fc;--ad:#0f2a24;--dd:#2d1517;--gd:linear-gradient(90deg,#6366f1,#a855f7,#ec4899);box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:light){:root:not([data-theme=dark]){--bg:#f8fafc;--b2:#fff;--bd:#d9dee8;--fg:#111827;--mu:#4b5563;--ac:#4f46e5;--gr:#059669;--rd:#dc2626;--pu:#9333ea;--ad:#d1fae5;--dd:#fee2e2}}
:root[data-theme=light]{--bg:#f8fafc;--b2:#fff;--bd:#d9dee8;--fg:#111827;--mu:#4b5563;--ac:#4f46e5;--gr:#059669;--rd:#dc2626;--pu:#9333ea;--ad:#d1fae5;--dd:#fee2e2}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--fg);font:14px/1.5 Inter,-apple-system,"Segoe UI",sans-serif}
a{color:var(--ac);cursor:pointer;text-decoration:none}a:hover{text-decoration:underline}
.hd{background:color-mix(in srgb,var(--b2) 85%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--bd);padding:10px 14px;display:flex;gap:10px;align-items:center;position:sticky;top:env(safe-area-inset-top,0px);z-index:9}
input,textarea,select{background:var(--bg);color:var(--fg);border:1px solid var(--bd);border-radius:6px;padding:6px 10px;font:inherit;max-width:100%;box-sizing:border-box}
textarea{width:100%;min-height:260px;font:12px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace}
.btn{background:var(--b2);color:var(--fg);border:1px solid var(--bd);border-radius:6px;padding:4px 12px;cursor:pointer;font:inherit;font-size:13px}
.btn.g{background:linear-gradient(90deg,#6366f1,#a855f7);color:#fff;border-color:transparent}.btn.on{color:var(--pu)}
#sw{position:relative;flex:1}#sr{position:absolute;top:36px;left:0;right:0;background:var(--bg);border:1px solid var(--bd);border-radius:6px;display:none;max-height:300px;overflow:auto;z-index:10}
#sr div{padding:6px 10px;cursor:pointer}#sr div:hover{background:var(--b2)}
.w{max-width:1000px;margin:0 auto;padding:14px}
.rt{font-size:20px;margin:6px 0}.mu{color:var(--mu)}.pill{border:1px solid var(--bd);border-radius:20px;font-size:12px;padding:0 8px;color:var(--mu)}
.tabs{display:flex;gap:4px;border-bottom:1px solid var(--bd);overflow-x:auto;margin:10px 0 14px}
.tabs a{color:var(--fg);padding:8px 12px;white-space:nowrap;border-bottom:2px solid transparent}.tabs a.on{border-color:#a855f7;font-weight:600}
.ct{background:var(--bd);border-radius:20px;padding:0 6px;font-size:12px;margin-left:4px}
.box{border:1px solid var(--bd);border-radius:6px;margin:10px 0;overflow:hidden}
.bh{background:var(--b2);padding:8px 12px;border-bottom:1px solid var(--bd);display:flex;gap:8px;align-items:center;flex-wrap:wrap}.r{margin-left:auto}
.row{display:flex;gap:10px;padding:8px 12px;border-top:1px solid var(--bd);align-items:center}.row:first-child{border:0}.row .t{flex:1;min-width:0}
.sc{overflow-x:auto}table{border-collapse:collapse;font:12px/20px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;width:100%}
td.ln{color:var(--mu);text-align:right;padding:0 10px;user-select:none;width:1%;white-space:nowrap}td{white-space:pre;padding:0 8px}
.pr{padding:12px;white-space:pre-wrap;font:12px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;margin:0;overflow-x:auto}
.md{padding:4px 16px 12px}.md code{background:var(--b2);padding:1px 5px;border-radius:5px}.md pre{background:var(--b2);padding:10px;border-radius:6px;overflow-x:auto}
.md h1,.md h2{border-bottom:1px solid var(--bd);padding-bottom:4px}
i{font-style:normal}i.c{color:var(--mu)}i.s{color:var(--ac)}i.k{color:var(--rd)}i.n{color:var(--pu)}
tr.a{background:var(--ad)}tr.d{background:var(--dd)}
.lb{border-radius:20px;padding:0 8px;font-size:12px;color:#fff}
.log{background:#05070d;color:#e6edf3;padding:10px;font:12px/1.5 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;white-space:pre-wrap;max-height:300px;overflow:auto;margin:0}
.hm{display:grid;grid-template-rows:repeat(7,11px);grid-auto-flow:column;gap:3px}.hm b{width:11px;height:11px;border-radius:2px;background:var(--b2);border:1px solid var(--bd)}
.bar{display:flex;height:8px;border-radius:4px;overflow:hidden;margin:8px 0}
.st{font-size:12px;border-radius:20px;padding:0 8px}.ok{color:var(--gr)}.er{color:var(--rd)}
.lg{width:32px;height:32px;border-radius:10px;background:linear-gradient(135deg,#4f46e5,#9333ea,#ec4899);display:flex;align-items:center;justify-content:center}.gt{background:var(--gd);-webkit-background-clip:text;background-clip:text;color:transparent}.box,.btn{transition:.2s}.box:hover{box-shadow:0 0 18px -4px rgba(168,85,247,.35)}.card{padding:14px;cursor:pointer}
</style>
</head>
<body>
<div class="hd">
  <a onclick="go({home:1})" style="display:flex;gap:8px;align-items:center;color:inherit"><span class="lg">🧠</span><b class="gt">Neural Raphael Hub</b></a>
  <div id="sw"><input id="sq" style="width:100%" placeholder="Buscar arquivos e issues ( / )" oninput="search(this.value)"><div id="sr"></div></div>
  <span id="me" class="pill"></span><button class="btn" onclick="theme()">◐</button>
</div>
<div class="w" id="app"></div>

<script>
const $=s=>document.querySelector(s),K='nrh-gh-3',D=864e5;
const esc=s=>String(s||'').replace(/[&<>]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;'}[c]));

function h53(s){let a=0xdeadbeef,b=0x41c6ce57;for(let i=0;i<s.length;i++){const c=s.charCodeAt(i);a=Math.imul(a^c,2654435761);b=Math.imul(b^c,1597334677)}a=Math.imul(a^a>>>16,2246822507)^Math.imul(b^b>>>13,3266489909);b=Math.imul(b^b>>>16,2246822507)^Math.imul(a^a>>>13,3266489909);return(b>>>0).toString(16).padStart(8,'0')+(a>>>0).toString(16).padStart(8,'0')}
function ago(t){const s=(Date.now()-t)/1e3;return s<60?'agora':s<3600?Math.floor(s/60)+' min atrás':s<864e2?Math.floor(s/3600)+' h atrás':Math.floor(s/864e2)+' dias atrás'}
function fz(q,s){q=q.toLowerCase();s=s.toLowerCase();let i=0,sc=0,l=-2;for(let j=0;j<s.length&&i<q.length;j++)if(s[j]==q[i]){sc+=j==l+1?3:1;l=j;i++}return i==q.length?sc-s.length/50:-1}

function diff(a,b){const A=a?a.split('\n'):[],B=b?b.split('\n'):[],n=A.length,m=B.length,T=Array.from({length:n+1},()=>new Uint16Array(m+1));
for(let i=n-1;i>=0;i--)for(let j=m-1;j>=0;j--)T[i][j]=A[i]===B[j]?T[i+1][j+1]+1:Math.max(T[i+1][j],T[i][j+1]);
let i=0,j=0,r=[];while(i<n&&j<m){if(A[i]===B[j]){r.push([' ',A[i]]);i++;j++}else if(T[i+1][j]>=T[i][j+1])r.push(['-',A[i++]]);else r.push(['+',B[j++]])}
while(i<n)r.push(['-',A[i++]]);while(j<m)r.push(['+',B[j++]]);return r}

function diffH(ch){return ch.map(c=>{const d=diff(c.a,c.b),ad=d.filter(x=>x[0]=='+').length,rm=d.filter(x=>x[0]=='-').length;
return`<div class=box><div class=bh><b>${esc(c.p)}</b><span class=r><span class=ok>+${ad}</span> <span class=er>−${rm}</span></span></div><div class=sc><table>${d.map(x=>`<tr class="${x[0]=='+'?'a':x[0]=='-'?'d':''}"><td class=ln>${x[0]}</td><td>${esc(x[1])}</td></tr>`).join('')}</table></div></div>`}).join('')}

function hl(src,p){if(/\.md$/.test(p))return esc(src);const re=/(#.*|\/\/.*|\/\*.*?\*\/)|("(?:\\.|[^"\\\n])*"|'(?:\\.|[^'\\\n])*')|\b(class|def|return|import|from|self|if|else|elif|for|in|not|None|True|False|const|let|function|with|as|while|lambda|raise|try|except|super|run|name|on|steps|uses|var|new|this|static|public|private|void|int|float|double|char|struct|enum|interface|extends|switch|case|break|continue|do|typeof|export|default|catch|finally|throw|null|true|false|undefined|and|or|pass|is|fn|func|impl|mut|use|pub|match|type|package|using|select|where|SELECT|FROM|WHERE)\b|\b(\d+\.?\d*)\b/g;let o='',l=0,m;
while(m=re.exec(src)){o+=esc(src.slice(l,m.index));o+=`<i class=${m[1]?'c':m[2]?'s':m[3]?'k':'n'}>${esc(m[0])}</i>`;l=re.lastIndex}return o+esc(src.slice(l))}

function md(t){
  let c=0,o='';const T=[];
  const il=x=>esc(x).replace(/`([^`]+)`/g,'<code>$1</code>').replace(/\*\*([^*]+)\*\*/g,'<b>$1</b>').replace(/\*([^*]+)\*/g,'<em>$1</em>').replace(/\[([^\]]+)\]\((https?:[^)\s]+)\)/g,'<a href="$2" target=_blank rel=noopener>$1</a>');
  const fl=()=>{if(!T.length)return;const r=T.map(l=>l.split('|').slice(1,-1).map(x=>x.trim()));o+='<table style="font:inherit"><tr>'+r[0].map(x=>`<th>${il(x)}</th>`).join('')+'</tr>'+r.slice(2).map(a=>'<tr>'+a.map(x=>`<td style="white-space:normal">${il(x)}</td>`).join('')+'</tr>').join('')+'</table>';T.length=0};
  for(const L of t.split('\n')){
    if(L.startsWith('```')){fl();o+=c?'</pre>':'<pre>';c=!c;continue}
    if(c){o+=esc(L)+'\n';continue}
    if(/^\|.*\|$/.test(L)){T.push(L);continue}
    fl();let m;
    o+=(m=L.match(/^(#{1,4}) (.*)/))?`<h${m[1].length}>${il(m[2])}</h${m[1].length}>`:/^(-{3,}|\*{3,})$/.test(L)?'<hr>':(m=L.match(/^> (.*)/))?`<blockquote style="border-left:3px solid var(--bd);margin:0;padding-left:10px;color:var(--mu)">${il(m[1])}</blockquote>`:(m=L.match(/^[-*] \[( |x)\] (.*)/))?`<div>${m[1]=='x'?'☑':'☐'} ${il(m[2])}</div>`:(m=L.match(/^(?:[-*]|\d+\.) (.*)/))?`<li>${il(m[1])}</li>`:L.trim()?`<p>${il(L)}</p>`:'';
  }
  fl();return o;
}

function lint(s){const st=[],pr={')':'(',']':'[','}':'{'};let ln=1;for(const ch of s.replace(/#.*/g,'')){if(ch=='\n')ln++;if('([{'.includes(ch))st.push(ch);else if(pr[ch]&&st.pop()!==pr[ch])return'linha '+ln}return st.length?'delimitador não fechado':''}
function rng(a){return()=>{a|=0;a=a+0x6D2B79F5|0;let t=Math.imul(a^a>>>15,1|a);t=t+Math.imul(t^t>>>7,61|t)^t;return((t^t>>>14)>>>0)/4294967296}}

function seed(name,owner){
  const n=Date.now(),F={
  'README.md':'# Neural Raphael Hub\n\nEstúdio de inferência: **geração latente** + **refino e upscale**.\n\n- Módulo 1: IP-Adapter desacoplado com FlashAttention-2\n- Módulo 2: High-Res Fix e CodeFormer\n- Samplers: DDIM e DPM-Solver++\n\nUso: execute o workflow em Actions.',
  'module1_flash_attn.py':'class OptimizedIPAdapterDecoupledCrossAttention(nn.Module):\n    def __init__(self, query_dim: int = 128, context_dim: int = 768, num_heads: int = 4):\n        super().__init__()\n        self.num_heads = num_heads\n        self.head_dim = query_dim // num_heads\n        self.to_q = nn.Linear(query_dim, query_dim, bias=False)\n        self.to_k_text = nn.Linear(context_dim, query_dim, bias=False)\n        self.to_v_text = nn.Linear(context_dim, query_dim, bias=False)\n\n    def _apply_sdpa(self, q, k, v):\n        # FlashAttention-2 via PyTorch SDPA\n        out = F.scaled_dot_product_attention(q, k, v, is_causal=False)\n        return out.transpose(1, 2)',
  'module2_refiner.py':'class UnifiedModule2Pipeline(nn.Module):\n    def process(self, latents_m1, highres_scale: float = 2.0, denoising_strength: float = 0.45, restore_faces: bool = True):\n        up = F.interpolate(latents_m1, scale_factor=highres_scale, mode="bicubic")\n        refined = self.upscale_unet(z_t=up, z_lr=up)\n        img = self.vae_decoder(refined)\n        if restore_faces:\n            img = self.face_restorer(img)\n        return img',
  'orchestrator.py':'import torch\n\ndef run(prompt, steps=20, cfg=7.5, hr_scale=2.0):\n    latents = module1(prompt, steps=steps, cfg=cfg)\n    return module2(latents, highres_scale=hr_scale)',
  'samplers/ddim.py':'def ddim_step(x, eps, a_t, a_prev):\n    x0 = (x - (1 - a_t) ** 0.5 * eps) / a_t ** 0.5\n    return a_prev ** 0.5 * x0 + (1 - a_prev) ** 0.5 * eps',
  'samplers/dpm_solver.py':'def dpm_solver_2m(x, eps, eps_prev, h, h_prev):\n    r = h_prev / h\n    d = (1 + 1 / (2 * r)) * eps - (1 / (2 * r)) * eps_prev\n    return x - h * d',
  '.github/workflows/pipeline.yml':'name: pipeline\non: push\nsteps:\n  - uses: checkout\n  - run: lint\n  - run: pipeline'};
  const r1='# Neural Raphael Hub\n\nEstúdio de inferência.',ch=(p,a,b)=>({p,a,b});
  const C=[{m:'docs: expand README',t:n-D,ch:[ch('README.md',r1,F['README.md'])]},
  {m:'feat: add DDIM and DPM-Solver++ samplers',t:n-5*D,ch:['orchestrator.py','samplers/ddim.py','samplers/dpm_solver.py','.github/workflows/pipeline.yml'].map(p=>ch(p,'',F[p]))},
  {m:'Initial commit',t:n-9*D,ch:[ch('README.md','',r1),ch('module1_flash_attn.py','',F['module1_flash_attn.py']),ch('module2_refiner.py','',F['module2_refiner.py'])]}].map(c=>({...c,a:'raphael',sha:h53(c.m+c.t)}));
  return {id:slug(name)+'-'+Math.random().toString(36).slice(2,6),name,owner,desc:'',files:F,commits:C,star:[],watch:[],fork:0,
  issues:[{t:'Suporte a ControlNet no Módulo 1',b:'Adicionar ZeroConv para condições estruturais.',l:'enhancement',o:1,d:n-2*D},{t:'VRAM estoura com batch 8',b:'Reproduz em GPU de 16 GB.',l:'bug',o:1,d:n-3*D},{t:'Documentar fidelidade do CodeFormer',b:'',l:'docs',o:0,d:n-6*D}],
  prs:[{t:'feat: add Euler ancestral sampler',br:'feat/euler',s:'open',d:n-D/2,ch:[ch('samplers/euler.py','','def euler_a_step(x, eps, sigma, sigma_next):\n    return x + (sigma_next - sigma) * eps')]},
  {t:'tune: lower default CFG to 7.0',br:'tune/cfg',s:'open',d:n-D/3,ch:[ch('orchestrator.py',F['orchestrator.py'],F['orchestrator.py'].replace('cfg=7.5','cfg=7.0'))]}],runs:[]};
}

let S,R={},db,UID='local',V={home:1,tab:'code',p:'',f:1,raw:0,sh:0};
const UN={},W=()=>S.owner==UID||UID=='local',slug=s=>String(s||'').toLowerCase().replace(/[^\w-]+/g,'-').replace(/^-+|-+$/g,'');

try{R=JSON.parse(localStorage.getItem(K))||{}}catch(e){}

function save(){R[S.id]=S;try{localStorage.setItem(K,JSON.stringify(R))}catch(e){}if(db)db.collection('repos').doc(S.id).set({owner:S.owner,name:S.name,data:JSON.stringify(S)}).catch(()=>{})}
async function names(){try{if(window.claude){const u=await claude.use('user'),ids=[...new Set(Object.values(R).map(r=>r.owner))].filter(x=>x!='local'),P=await u.profiles(ids);ids.forEach(i=>UN[i]=P[i].name||'usuário');if(!V.edit)render()}}catch(e){}}

(async()=>{
  try{
    if(window.claude){
      const u=await claude.use('user');
      if(u){const m=await u.me();UID=m.id||'local';UN[UID]=m.name||'você';$('#me').textContent=UN[UID]}
      db=await claude.use('db');
      if(db)db.collection('repos').onSnapshot(q=>{const n={};q.docs.forEach(d=>{try{n[d.id]=JSON.parse(d.data().data)}catch(e){}});R=n;if(S)S=R[S.id]||null;if(!S)V.home=1;names();if(!V.edit)render()},()=>{})
    }
  }catch(e){}
  render();
})();

function newRepo(name,tpl){name=slug(name||'');if(!name)return;const r=seed(name,UID),n=Date.now();if(!tpl){r.files={'README.md':'# '+name+'\n\nNovo repositório.'};r.commits=[{m:'Initial commit',t:n,a:UN[UID]||'você',sha:h53(name+n),ch:[{p:'README.md',a:'',b:r.files['README.md']}]}];r.issues=[];r.prs=[]}
S=r;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function openRepo(id){S=R[id];V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function tg(k){const a=S[k],i=a.indexOf(UID);i<0?a.push(UID):a.splice(i,1);save();render()}
function forkRepo(){const c=JSON.parse(JSON.stringify(S));S.fork++;save();c.id=slug(S.name)+'-'+Math.random().toString(36).slice(2,6);Object.assign(c,{owner:UID,forkOf:S.id,star:[],watch:[],fork:0});S=c;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function openPR(){const o=R[S.forkOf];if(!o)return;const ch=[...new Set([...Object.keys(S.files),...Object.keys(o.files)])].filter(p=>S.files[p]!==o.files[p]).map(p=>({p,a:o.files[p]||'',b:S.files[p]||''}));if(!ch.length)return;o.prs.unshift({t:'Mudanças de '+(UN[UID]||'fork'),br:(UN[UID]||'fork')+':main',s:'open',d:Date.now(),ch});const c=S;S=o;save();S=c;render()}
function delRepo(){delete R[S.id];try{localStorage.setItem(K,JSON.stringify(R))}catch(e){}if(db)db.collection('repos').doc(S.id).delete().catch(()=>{});S=null;V.home=1;render()}

function blame(p){let L=[];for(const c of[...S.commits].reverse()){const x=c.ch.find(k=>k.p==p);if(!x)continue;const n=[];let i=0;for(const[t]of diff(x.a,x.b)){if(t==' ')n.push(L[i++]);else if(t=='-')i++;else n.push(c.sha.slice(0,7)+' '+c.a)}L=n}return L}

function homeView(){
  const L=Object.values(R).sort((a,b)=>(b.commits[0]?.t||0)-(a.commits[0]?.t||0)),q=V.hq||'';
  const A=Object.values(R).flatMap(r=>(r.commits||[]).slice(0,5).map(c=>({r,c}))).sort((a,b)=>b.c.t-a.c.t).slice(0,8);
  
  $('#app').innerHTML=`
    <div class="box" style="padding:16px;background:linear-gradient(135deg,rgba(99,102,241,.18),rgba(236,72,153,.12))">
      <h2 style="margin:0" class="gt">Seus algoritmos e softwares, arquivados.</h2>
      <p class="mu">Crie repositórios, versione código, abra issues e pull requests, faça forks. Compartilhado com quem usa esta página.</p>
      <input id="rn" placeholder="nome-do-repositorio"> 
      <button class="btn g" onclick="newRepo($('#rn').value,0)">+ Novo repositório</button> 
      <button class="btn" onclick="newRepo($('#rn').value||'neural-raphael-hub',1)">Modelo Neural Raphael</button>
    </div>
    <input style="width:100%" placeholder="Buscar repositórios e código…" value="${esc(q)}" onchange="V.hq=this.value;render()">
    ${L.filter(r=>!q||fz(q,r.name)>=0||Object.values(r.files).some(c=>c.includes(q))).map(r=>`<div class="box card" onclick="openRepo('${r.id}')"><b class="gt">${esc(UN[r.owner]\vert{}\vert{}'usuário')} / ${esc(r.name)}</b> <span class="pill">Public</span>${r.forkOf?' <span class="mu">fork</span>':''}<br><span class="mu">${esc(r.desc||'')} ★ ${r.star.length} · ⑂ ${r.fork} · ${r.commits.length} commits · ${ago(r.commits[0]?.t||Date.now())}</span></div>`).join('')||'<p class="mu">Nenhum repositório ainda. Crie o primeiro acima.</p>'}
    <div class="box"><div class="bh"><b>Atividade recente</b></div>${A.map(({r,c})=>`<div class="row"><span class="t"><b>${esc(c.a)}</b> em ${esc(r.name)}:${esc(c.m)}</span><span class="mu">${ago(c.t)}</span></div>`).join('')||'<div class="row mu">Sem atividade.</div>'}</div>
  `;
}

function go(o){Object.assign(V,o);render();scrollTo(0,0)}
function theme(){const r=document.documentElement;r.dataset.theme=(r.dataset.theme||(matchMedia('(prefers-color-scheme:light)').matches?'light':'dark'))=='dark'?'light':'dark'}

function search(q){
  const r=$('#sr');if(!q||!S){r.style.display='none';return}
  const f=Object.keys(S.files).map(p=>[fz(q,p),'📄 '+p,`go({tab:'code',p:'${p}',edit:0,cm:0});$('#sr').style.display='none'`]),
  i=S.issues.map((x,k)=>[fz(q,x.t),'⊙ '+x.t,`go({tab:'issues',f:${x.o?1:0}});$('#sr').style.display='none'`]);
  const g=Object.entries(S.files).flatMap(([p,c])=>c.split('\n').map((l,n)=>l.toLowerCase().includes(q.toLowerCase())?[.5,'🔎 '+p+':'+(n+1)+' '+l.trim().slice(0,40),`go({tab:'code',p:'${p}',edit:0,cm:0});$('#sr').style.display='none'`]:null).filter(Boolean)).slice(0,4);
  const L=[...f,...i,...g].filter(x=>x[0]>=0).sort((a,b)=>b[0]-a[0]).slice(0,8);
  r.style.display='block';r.innerHTML=L.length?L.map(x=>`<div onclick="${x[2]}">${esc(x[1])}</div>`).join(''):'<div class="mu">Nada encontrado</div>'
}

addEventListener('keydown',e=>{if(e.key=='/'&&!/INPUT|TEXTAREA/.test(document.activeElement.tagName)){e.preventDefault();$('#sq').focus()}});
const touch=p=>S.commits.find(c=>c.ch.some(x=>x.p==p||x.p.startsWith(p+'/')));
function mkCommit(m,ch){S.commits.unshift({m,t:Date.now(),a:UN[UID]||'você',sha:h53(m+Date.now()+Math.random()),ch});save()}

function codeView(){
  if(V.edit)return editor();
  if(V.cm)return commitsView();
  const p=V.p,f=S.files[p],lc=S.commits[0]||{a:'System',m:'Init',sha:'0000000',t:Date.now()};
  const cr=`<a onclick="go({p:''})">${S.name}</a>`+p.split('/').filter(Boolean).map((s,i,a)=>` / <a onclick="go({p:'${a.slice(0,i+1).join('/')}'})">${esc(s)}</a>`).join('');
  const bar=`<div class="bh"><b>${lc.a}</b> <span>${esc(lc.m)}</span><span class="mu">${lc.sha.slice(0,7)} · ${ago(lc.t)}</span><a class="r" onclick="go({cm:1,fh:0})">⏱ ${S.commits.length} commits</a></div>`;
  
  if(f!==undefined){
    const L=hl(f,p).split('\n'),BL=V.bl?blame(p):[],isMd=/\.md$/.test(p)&&!V.raw;
    return`<p>${cr}</p><div class="box">${bar}<div class="bh"><span class="mu">${f.split('\n').length} linhas · ${f.length} bytes</span><span class="r"><button class="btn" onclick="go({cm:1,fh:'${p}'})">Histórico</button> <button class="btn" onclick="go({bl:${V.bl?0:1}})">Blame</button> <button class="btn" onclick="go({raw:${V.raw?0:1}})">${V.raw?'Preview':'Raw'}</button> <button class="btn" onclick="try{navigator.clipboard.writeText(S.files['${p}'])}catch(e){}">Copiar</button> <button class="btn" onclick="go({edit:1,np:0})">Editar</button> <button class="btn" onclick="delF('${p}')">Excluir</button></span></div>
    ${isMd?`<div class="md">${md(f)}</div>`:V.raw?`<pre class="pr">${esc(f)}</pre>`:`<div class="sc"><table>${L.map((x,i)=>`<tr class="${V.hlL==i+1?'a':''}"><td class="ln" style="cursor:pointer" onclick="V.hlL=${i+1};render()">${i+1}</td>${V.bl?`<td class="mu">${BL[i]||''}</td>`:''}<td>${x}</td></tr>`).join('')}</table></div>`}</div>`
  }
  
  const pre=p?p+'/':'',E=new Map();for(const k in S.files)if(k.startsWith(pre)){const r=k.slice(pre.length);E.set(r.split('/')[0],r.includes('/'))}
  const rows=[...E].sort((a,b)=>(b[1]-a[1])||(a[0]<b[0]?-1:1)).map(([n,d])=>{const q=pre+n,c=touch(q)|{m:'-',t:Date.now()};return`<div class="row"><span>${d?'📁':'📄'}</span><a class="t" onclick="go({p:'${q}'})">${esc(n)}</a><span class="mu t" style="flex:2;overflow:hidden;white-space:nowrap;text-overflow:ellipsis">${esc(c.m)}</span><span class="mu">${ago(c.t)}</span></div>`}).join('');
  const rd=S.files[pre+'README.md'];
  return`<p>${cr}</p><div class="box">${bar}${rows}</div><button class="btn g" onclick="go({edit:1,np:1})">+ Novo arquivo</button>${rd?`<div class="box"><div class="bh">📖 README.md</div><div class="md">${md(rd)}</div></div>`:''}`
}

function editor(){const p=V.np?'':V.p,v=S.files[p]||'';return`<div class="box"><div class="bh">${V.np?'Novo arquivo: <input id="ep" placeholder="pasta/arquivo.py">':'Editando <input id="ep" value="'+esc(p)+'">'}</div><div style="padding:10px"><textarea id="ev">${esc(v)}</textarea><p><input id="em" style="width:100%" placeholder="Mensagem do commit"></p><span id="ee" class="er"></span><p><button class="btn g" onclick="commit()">Commit changes</button> <button class="btn" onclick="go({edit:0})">Cancelar</button></p></div></div>`}

function commit(){
  if(!W())return;
  const p=$('#ep').value.trim(),old=V.np?'':V.p;
  if(!/^[\w.\/-]+$/.test(p)){$('#ee').textContent='Caminho inválido';return}
  const a=old?S.files[old]:S.files[p]||'',b=$('#ev').value,mv=old&&old!=p;
  if(a===b&&!mv){$('#ee').textContent='Sem alterações';return}
  const ch=[];if(mv){ch.push({p:old,a,b:''});delete S.files[old]}
  S.files[p]=b;ch.push({p,a:mv?'':a,b});
  mkCommit($('#em').value||(mv?'Rename '+old+' → '+p:a?'Update '+p:'Create '+p),ch);
  V.edit=0;V.p=p;render()
}

function delF(p){if(!W()||!(p in S.files))return;const a=S.files[p];delete S.files[p];mkCommit('Delete '+p,[{p,a,b:''}]);V.p=p.split('/').slice(0,-1).join('/');render()}
function commitsView(){return`<p><a onclick="go({cm:0})">← Code</a>${V.fh?'<span class="mu"> Histórico de '+esc(V.fh)+'</span>':''}</p>`+S.commits.filter(c=>!V.fh||c.ch.some(x=>x.p==V.fh)).map(c=>`<div class="box"><div class="row"><div class="t"><b>${esc(c.m)}</b><br><span class="mu">${c.a} · ${ago(c.t)}</span></div><code>${c.sha.slice(0,7)}</code><button class="btn" onclick="go({sh:V.sh==='${c.sha}'?0:'${c.sha}'})">diff</button><button class="btn" onclick="revert('${c.sha}')">Revert</button></div>${V.sh==c.sha?diffH(c.ch):''}</div>`).join('')}

function revert(sha){if(!W())return;const c=S.commits.find(x=>x.sha==sha);if(!c)return;const ch=c.ch.map(x=>({p:x.p,a:x.b,b:x.a}));ch.forEach(x=>x.b?S.files[x.p]=x.b:delete S.files[x.p]);mkCommit('Revert "'+c.m+'"',ch);render()}

function issuesView(){
  const q=V.iq||'',o=S.issues.filter(i=>i.o).length,cl=S.issues.length-o,col={bug:'#d1242f',enhancement:'#1f883d',docs:'#0969da'};
  const L=S.issues.map((x,i)=>[x,i]).filter(([x])=>!!x.o==!!V.f&&(!q||fz(q,x.t)>=0));
  return`<div style="display:flex;gap:8px;flex-wrap:wrap"><input style="flex:1" placeholder="Filtrar issues" value="${esc(q)}" onchange="go({iq:this.value})"><button class="btn g" onclick="go({ni:1})">New issue</button></div>
  ${V.ni?`<div class="box" style="padding:10px"><input id="nt" style="width:100%" placeholder="Título"><p><textarea id="nb" style="min-height:80px" placeholder="Descrição"></textarea></p><select id="nl"><option>bug</option><option>enhancement</option><option>docs</option></select> <button class="btn g" onclick="addIssue()">Criar</button></div>`:''}
  <div class="box"><div class="bh"><a onclick="go({f:1})" style="${V.f?'font-weight:700':''}">${o} Open</a><a onclick="go({f:0})" style="${V.f?'':'font-weight:700'}">${cl} Closed</a></div>
  ${L.map(([x,i])=>`<div class="row"><span class="${x.o?'ok':'mu'}">${x.o?'⊙':'✔'}</span><div class="t"><b>${esc(x.t)}</b> <span class="lb" style="background:${col[x.l]}">${x.l}</span><br><span class="mu">#${i+1} · ${ago(x.d)}</span>${x.b?`<br>${esc(x.b)}`:''}${(x.cm||[]).map(c=>`<br><span class="mu">💬 ${esc(c)}</span>`).join('')}<br><input placeholder="Comentar…" onchange="(S.issues[${i}].cm=S.issues[${i}].cm||[]).push((UN[UID]||'você')+': '+this.value);save();render()"></div><button class="btn" onclick="S.issues[${i}].o=${x.o?0:1};save();render()">${x.o?'Fechar':'Reabrir'}</button></div>`).join('')||'<div class="row mu">Nenhuma issue.</div>'}</div>`
}

function addIssue(){const t=$('#nt').value.trim();if(!t)return;S.issues.unshift({t,b:$('#nb').value,l:$('#nl').value,o:1,d:Date.now()});V.ni=0;V.f=1;save();render()}
function prsView(){return S.prs.map((p,i)=>`<div class="box"><div class="row"><span class="${p.s=='open'?'ok':'mu'}">⑂</span><div class="t"><b>${esc(p.t)}</b><br><span class="mu">${p.br} → main · ${ago(p.d)}</span></div><span class="st ${p.s=='open'?'ok':'mu'}">${p.s}</span>${p.conf?'<span class="er">conflito</span>':''}${p.s=='open'?`<button class="btn g" onclick="merge(${i})">Merge</button>`:''}<button class="btn" onclick="go({pr:V.pr===${i}?-1:${i}})">files</button></div>${V.pr===i?diffH(p.ch):''}</div>`).join('')}

function merge(i){if(!W())return;const p=S.prs[i];if(p.ch.some(c=>{const u=S.files[c.p]||'';return u!==c.a&&u!==c.b})){p.conf=1;save();render();return}p.ch.forEach(c=>{c.b?S.files[c.p]=c.b:delete S.files[c.p]});mkCommit('Merge pull request: '+p.t,p.ch);p.s='merged';save();render()}

const sl=ms=>new Promise(r=>setTimeout(r,ms));
async function runWf(){
  const r={id:S.runs.length+1,t:Date.now(),st:'running',log:[]};S.runs.unshift(r);
  const L=x=>{r.log.push(x);if(V.tab=='actions')render()};
  L('▶ Checkout');await sl(300);const bad=[];
  for(const p in S.files)if(p.endsWith('.py')){const e=lint(S.files[p]);L((e?'✖ ':'✔ ')+'lint '+p+(e?' ('+e+')':''));if(e)bad.push(p);await sl(200)}
  if(bad.length){r.st='failure';L('Falhou: '+bad.length+' arquivo(s)');save();render();return}
  const T=20,ab=t=>Math.pow(Math.cos((t/T+.008)/1.008*Math.PI/2),2);L('▶ Módulo 1: cronograma cosseno, '+T+' passos');
  for(let t=T;t>=0;t-=5){L('  passo '+(T-t)+'/'+T+'  ᾱ='+ab(t).toFixed(4)+'  σ='+Math.sqrt((1-ab(t))/ab(t)).toFixed(3));await sl(250)}
  L('▶ Módulo 2: High-Res Fix 2.0x → [1, 3, 1024, 1024]');await sl(400);L('✔ CodeFormer fidelity 0.80');r.st='success';save();render()
}

function actionsView(){return`<button class="btn g" onclick="runWf()">▶ Run workflow</button>`+S.runs.map(r=>`<div class="box"><div class="bh"><span class="${r.st=='success'?'ok':r.st=='failure'?'er':'mu'}">${r.st=='success'?'✔':r.st=='failure'?'✖':'●'}</span><b>pipeline #${r.id}</b><span class="mu">${ago(r.t)} · ${r.st}</span></div><pre class="log">${esc(r.log.join('\n'))}</pre></div>`).join('')||'<p class="mu">Nenhuma execução ainda. O lint valida delimitadores dos .py.</p>'}

function brSave(){S.br=S.br||{};S.br[S.cur||'main']={files:{...S.files},commits:[...S.commits]}}
function brSwitch(n){brSave();const b=S.br[n];if(!b)return;S.files=b.files;S.commits=b.commits;S.cur=n;V.p='';save();render()}
function brNew(){const n=slug($('#bn').value);if(!n||!W())return;brSave();if(S.br[n])return;S.br[n]=JSON.parse(JSON.stringify(S.br[S.cur||'main']));brSwitch(n)}
function brMerge(){const c=S.cur||'main';if(c=='main'||!W())return;brSave();const m=S.br.main,x=S.br[c],ch=[];
for(const p of new Set([...Object.keys(m.files),...Object.keys(x.files)]))if(m.files[p]!==x.files[p])ch.push({p,a:m.files[p]||'',b:x.files[p]||''});
if(ch.length){ch.forEach(k=>k.b?m.files[k.p]=k.b:delete m.files[k.p]);m.commits.unshift({m:'Merge branch '+c,t:Date.now(),a:UN[UID]||'você',sha:h53(c+Date.now()),ch})}
delete S.br[c];S.files=m.files;S.commits=m.commits;S.cur='main';V.p='';save();render()}

const CT=(()=>{const t=[];for(let n=0;n<256;n++){let c=n;for(let k=0;k<8;k++)c=c&1?0xEDB88320^(c>>>1):c>>>1;t[n]=c>>>0}return t})();
const crc=u=>{let c=-1;for(const b of u)c=CT[(c^b)&255]^(c>>>8);return(c^-1)>>>0};

function zip(files){
  const E=new TextEncoder(),P=[],CD=[];let off=0,cs=0;const ks=Object.keys(files);
  for(const p of ks){
    const n=E.encode(p),d=E.encode(files[p]),cr=crc(d),h=new DataView(new ArrayBuffer(30)),g=new DataView(new ArrayBuffer(46));
    h.setUint32(0,0x04034b50,true);h.setUint16(4,20,true);h.setUint16(6,0x800,true);h.setUint32(14,cr,true);h.setUint32(18,d.length,true);h.setUint32(22,d.length,true);h.setUint16(26,n.length,true);P.push(h.buffer,n,d);
    g.setUint32(0,0x02014b50,true);g.setUint16(4,20,true);g.setUint16(6,20,true);g.setUint16(8,0x800,true);g.setUint32(16,cr,true);g.setUint32(20,d.length,true);g.setUint32(24,d.length,true);g.setUint16(28,n.length,true);g.setUint32(42,off,true);CD.push(g.buffer,n);
    off+=30+n.length+d.length;cs+=46+n.length
  }
  const e=new DataView(new ArrayBuffer(22));e.setUint32(0,0x06054b50,true);e.setUint16(8,ks.length,true);e.setUint16(10,ks.length,true);e.setUint32(12,cs,true);e.setUint32(16,off,true);
  return new Blob([...P,...CD,e.buffer],{type:'application/zip'})
}

async function dl(name,data){
  try{if(window.claude){const d=await claude.use('downloads');if(d){await d.save({filename:name,data});return}}}catch(e){}
  const a=document.createElement('a');a.href=URL.createObjectURL(data instanceof Blob?data:new Blob([data]));a.download=name;a.click()
}

function imp(fl){if(!fl||!fl[0])return;const r=new FileReader();r.onload=()=>{try{const x=JSON.parse(r.result);if(!x.files||!x.commits)return;Object.assign(x,{id:slug(x.name||'import')+'-'+Math.random().toString(36).slice(2,6),owner:UID,star:[],watch:[]});S=x;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}catch(e){}};r.readAsText(fl[0])}
async function upl(fs){if(!W())return;const d=S.files[V.p]!==undefined?V.p.split('/').slice(0,-1).join('/'):V.p,ch=[];for(const f of fs){const p=(d?d+'/':'')+f.name.replace(/[^\w.\/-]/g,'_'),b=await f.text(),a=S.files[p]||'';if(a!==b){S.files[p]=b;ch.push({p,a,b})}}if(ch.length)mkCommit('Upload '+ch.length+' file(s)',ch);render()}

function tools(){
  if(V.tab!='code'||V.cm||V.edit)return'';const br=['main',...Object.keys(S.br||{}).filter(x=>x!='main')],c=S.cur||'main';
  return`<div style="display:flex;gap:6px;flex-wrap:wrap;align-items:center;margin-bottom:8px"><select onchange="brSwitch(this.value)">${br.map(b=>`<option ${b==c?'selected':''}>${esc(b)}</option>`).join('')}</select>${W()?`<input id="bn" placeholder="nova-branch" style="width:110px"><button class="btn" onclick="brNew()">+ Branch</button>${c!='main'?'<button class="btn g" onclick="brMerge()">Merge → main</button>':''}<label class="btn">⬆ Arquivos<input type="file" multiple hidden onchange="upl(this.files)"></label>`:''}<button class="btn" onclick="dl(S.name+'.zip',zip(S.files))">⬇ ZIP</button><button class="btn" onclick="dl(S.name+'.json',JSON.stringify(S))">⬇ JSON</button><label class="btn">⬆ Importar JSON<input type="file" accept=".json" hidden onchange="imp(this.files)"></label></div>`
}

function relView(){
  const L=S.rel||[];
  return(W()?`<div class="box" style="padding:10px"><input id="rt" placeholder="v1.0.0"> <input id="rn2" placeholder="Título"><p><textarea id="rb" style="min-height:70px" placeholder="Notas (vazio = gerar dos commits)"></textarea></p><button class="btn g" onclick="addRel()">Publicar release</button></div>`:'')+L.map((r,i)=>`<div class="box"><div class="bh"><b class="gt">${esc(r.tag)}</b> ${esc(r.title)}<span class="mu r">${r.sha.slice(0,7)} · ${ago(r.t)}</span></div><div class="md">${md(r.notes)}</div><div class="row"><button class="btn" onclick="dl(S.name+'-'+S.rel[${i}].tag+'.zip',zip(S.rel[${i}].files))">⬇ Source (zip)</button></div></div>`).join('')||'<p class="mu">Sem releases.</p>'
}

function addRel(){
  const tag=$('#rt').value.trim();if(!tag)return;let n=$('#rb').value;
  if(!n){const pv=(S.rel||[])[0],k=pv?S.commits.findIndex(c=>c.sha==pv.sha):-1;n='## Mudanças\n'+S.commits.slice(0,k<0?S.commits.length:k).map(c=>'- '+c.m).join('\n')}
  (S.rel=S.rel||[]).unshift({tag,title:$('#rn2').value,notes:n,sha:S.commits[0].sha,t:Date.now(),files:{...S.files}});save();render()
}

function projView(){
  const P=S.pj=S.pj||{cols:['A fazer','Em andamento','Feito'],cards:[]};
  return`<div style="display:flex;gap:10px;overflow-x:auto">${P.cols.map((c,ci)=>`<div class="box" style="min-width:230px;flex:1"><div class="bh"><b>${esc(c)}</b><span class="ct">${P.cards.filter(k=>k.c==ci).length}</span></div>${P.cards.map((k,ki)=>k.c==ci?`<div class="row" style="flex-wrap:wrap"><span class="t">${esc(k.t)}</span>${ci>0?`<button class="btn" onclick="mvc(${ki},-1)">◀</button>`:''}${ci<2?`<button class="btn" onclick="mvc(${ki},1)">▶</button>`:''}<button class="btn" onclick="S.pj.cards.splice(${ki},1);save();render()">✕</button></div>`:'').join('')}<div class="row"><input style="width:100%" placeholder="+ Cartão" onchange="addCard(${ci},this.value)"></div></div>`).join('')}</div>`
}
const mvc=(i,d)=>{S.pj.cards[i].c+=d;save();render()},addCard=(c,t)=>{if(!t.trim())return;S.pj.cards.push({c,t});save();render()};

function insView(){
  const R_gen=rng(7),cell=[],day=Math.floor(Date.now()/D),cm={};
  S.commits.forEach(c=>{const k=Math.floor(c.t/D);cm[k]=(cm[k]||0)+3});
  for(let i=370;i>=0;i--){const v=(R_gen()>.6?Math.ceil(R_gen()*3):0)+(cm[day-i]||0),l=Math.min(4,v);cell.push(`<b style="${l?`background:var(--gr);opacity:${.25+l*.19}`:''}"></b>`)}
  
  const ex={},tot={};let all=0;
  for(const p in S.files){const e=(p.match(/\.(\w+)$/)||[,'other'])[1],n=S.files[p].length;ex[e]=(ex[e]||0)+n;all+=n}
  const nm={py:'Python',md:'Markdown',yml:'YAML'},cl={py:'#3572A5',md:'#083fa1',yml:'#cb171e'};
  const lg=Object.entries(ex).sort((a,b)=>b[1]-a[1]),lines=Object.values(S.files).reduce((a,s)=>a+s.split('\n').length,0);

  const Q={},A={};
  S.commits.forEach(c=>{
    const k=new Date(c.t).toISOString().slice(5,10);
    c.ch.forEach(x=>{const d=diff(x.a,x.b);Q[k]=Q[k]||[0,0];Q[k][0]+=d.filter(y=>y[0]=='+').length;Q[k][1]+=d.filter(y=>y[0]=='-').length});
    A[c.a]=(A[c.a]||0)+1
  });
  const ks=Object.keys(Q).sort(),mx=Math.max(1,...ks.map(k=>Math.max(...Q[k]))),w=40,W2=Math.max(ks.length*w,200);

  return`<div class="box"><div class="bh">Atividade de commits</div><div class="sc" style="padding:12px"><div class="hm">${cell.join('')}</div></div></div>
  <div class="box" style="padding:12px"><b>Linguagens</b><div class="bar">${lg.map(([e,n])=>`<span style="width:${n/all*100}\%;background:${cl[e]||'#888'}"></span>`).join('')}</div>${lg.map(([e,n])=>`<span style="margin-right:12px">● ${nm[e]||e} <span class="mu">${(n/all*100).toFixed(1)}%</span></span>`).join('')}</div>
  <div class="box" style="padding:12px"><b>Resumo</b><br>${S.commits.length} commits · ${Object.keys(S.files).length} arquivos · ${lines} linhas · ${S.issues.filter(i=>i.o).length} issues abertas · ${S.prs.filter(p=>p.s=='merged').length} PRs mescladas</div>
  <div class="box" style="padding:12px"><b>Frequência de código</b><div class="sc"><svg viewBox="0 0 ${W2} 112" style="width:${W2}px">${ks.map((k,i)=>`<rect x="${i*w+4}" y="${55-Q[k][0]/mx*50}" width="14" height="${Q[k][0]/mx*50}" fill="#34d399"/><rect x="${i*w+20}" y="55" width="14" height="${Q[k][1]/mx*50}" fill="#f87171"/><text x="${i*w+4}" y="108" font-size="9" fill="#9ca3af">${k}</text>`).join('')}</svg></div></div>
  <div class="box" style="padding:12px"><b>Contribuidores</b>${Object.entries(A).sort((a,b)=>b[1]-a[1]).map(([n,c])=>`<div>${esc(n)} <span class="mu">${c} commits</span></div>`).join('')}</div>`
}

function render(){
  if(V.home||!S)return homeView();
  const own=S.owner==UID,o=S.issues.filter(i=>i.o).length,po=S.prs.filter(p=>p.s=='open').length,T=[['code','Code'],['issues','Issues',o],['prs','Pull requests',po],['actions','Actions'],['projects','Projects'],['releases','Releases'],['insights','Insights']];
  const b={code:codeView,issues:issuesView,prs:prsView,actions:actionsView,insights:insView,releases:relView,projects:projView}[V.tab]();
  
  $('#app').innerHTML=`
    <div class="rt"><a onclick="go({home:1})">${esc(UN[S.owner]||'usuário')}</a> / <b class="gt">${esc(S.name)}</b> <span class="pill">Public</span>${S.forkOf?' <span class="mu">fork</span>':''}</div>
    <input style="width:100%" placeholder="Descrição" value="${esc(S.desc||'')}" ${own?'':'disabled'} onchange="S.desc=this.value;save()">
    <div style="display:flex;gap:6px;flex-wrap:wrap;margin:6px 0">
      <button class="btn ${S.watch.includes(UID)?'on':''}" onclick="tg('watch')">👁 Watch ${S.watch.length}</button>
      <button class="btn" onclick="forkRepo()">⑂ Fork ${S.fork}</button>
      <button class="btn ${S.star.includes(UID)?'on':''}" onclick="tg('star')">★ Star ${S.star.length}</button>
      ${own&&S.forkOf&&R[S.forkOf]?'<button class="btn g" onclick="openPR()">Abrir PR</button>':''}
      ${own?'<button class="btn" onclick="delRepo()">🗑</button>':''}
    </div>
    ${own?'':'<p class="mu">🔒 Somente leitura: faça um fork para editar.</p>'}
    <div class="tabs">${T.map(t=>`<a class="${V.tab==t[0]?'on':''}" onclick="go({tab:'${t[0]}',edit:0,cm:0})">${t[1]}${t[2]?`<span class="ct">${t[2]}</span>`:''}</a>`).join('')}</div>
    ${tools()}${b}
  `;
}

let gk=0;
addEventListener('keydown',e=>{
  if(/INPUT|TEXTAREA|SELECT/.test(document.activeElement.tagName)||!S||V.home)return;
  if(gk){gk=0;const m={c:'code',i:'issues',p:'prs',a:'actions',r:'releases',b:'projects'}[e.key];if(m)go({tab:m,edit:0,cm:0});return}
  if(e.key=='g')gk=1;
  if(e.key=='t'){e.preventDefault();$('#sq').focus()}
});
</script>
</body>
</html>
