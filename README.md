
<html lang="pt-BR"><head><meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Neural Raphael Hub · GitHub Edition</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#080c14;--b2:#111827;--bd:#1f2937;--fg:#f3f4f6;--mu:#9ca3af;--ac:#818cf8;--gr:#34d399;--rd:#f87171;--pu:#c084fc;--ad:#0f2a24;--dd:#2d1517;--gd:linear-gradient(90deg,#6366f1,#a855f7,#ec4899);box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media(prefers-color-scheme:light){:root:not([data-theme=dark]){--bg:#f8fafc;--b2:#fff;--bd:#d9dee8;--fg:#111827;--mu:#4b5563;--ac:#4f46e5;--gr:#059669;--rd:#dc2626;--pu:#9333ea;--ad:#d1fae5;--dd:#fee2e2}}
:root[data-theme=light]{--bg:#f8fafc;--b2:#fff;--bd:#d9dee8;--fg:#111827;--mu:#4b5563;--ac:#4f46e5;--gr:#059669;--rd:#dc2626;--pu:#9333ea;--ad:#d1fae5;--dd:#fee2e2}
:root[data-theme=dark]{--bg:#080c14;--b2:#111827;--bd:#1f2937;--fg:#f3f4f6;--mu:#9ca3af;--ac:#818cf8;--gr:#34d399;--rd:#f87171;--pu:#c084fc;--ad:#0f2a24;--dd:#2d1517}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;background:var(--bg);color:var(--fg);font:14px/1.5 Inter,-apple-system,"Segoe UI",sans-serif}
a{color:var(--ac);cursor:pointer;text-decoration:none}a:hover{text-decoration:underline}
.hd{background:color-mix(in srgb,var(--b2) 85%,transparent);backdrop-filter:blur(8px);border-bottom:1px solid var(--bd);padding:10px 14px;display:flex;gap:10px;align-items:center;position:sticky;top:env(safe-area-inset-top,0px);z-index:9}
input,textarea,select{background:var(--bg);color:var(--fg);border:1px solid var(--bd);border-radius:6px;padding:6px 10px;font:inherit;max-width:100%;box-sizing:border-box}
textarea{width:100%;min-height:260px;font:12px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace}
.btn{background:var(--b2);color:var(--fg);border:1px solid var(--bd);border-radius:6px;padding:4px 12px;cursor:pointer;font:inherit;font-size:13px}
.btn.g{background:linear-gradient(90deg,#6366f1,#a855f7);color:#fff;border-color:transparent}.btn.on{color:var(--pu)}
#sw{position:relative;flex:1;min-width:0}#sr{position:absolute;top:36px;left:0;right:0;background:var(--bg);border:1px solid var(--bd);border-radius:6px;display:none;max-height:300px;overflow:auto}
#sr div{padding:6px 10px;cursor:pointer}#sr div:hover{background:var(--b2)}
.w{max-width:1000px;margin:0 auto;padding:14px}
.rt{font-size:20px;margin:6px 0}.mu{color:var(--mu)}.pill{border:1px solid var(--bd);border-radius:20px;font-size:12px;padding:0 8px;color:var(--mu)}.pill:empty{display:none}
.tabs{display:flex;gap:4px;border-bottom:1px solid var(--bd);overflow-x:auto;margin:10px 0 14px}
.tabs a{color:var(--fg);padding:8px 12px;white-space:nowrap;border-bottom:2px solid transparent}.tabs a.on{border-color:#a855f7;font-weight:600}
.ct{background:var(--bd);border-radius:20px;padding:0 6px;font-size:12px;margin-left:4px}
.box{border:1px solid var(--bd);border-radius:6px;margin:10px 0;overflow:hidden}
.bh{background:var(--b2);padding:8px 12px;border-bottom:1px solid var(--bd);display:flex;gap:8px;align-items:center;flex-wrap:wrap}.r{margin-left:auto}
.row{display:flex;gap:10px;padding:8px 12px;border-top:1px solid var(--bd);align-items:center}.row:first-child{border:0}.row .t{flex:1;min-width:0}
.sc{overflow-x:auto}table{border-collapse:collapse;font:12px/20px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;width:100%}
td.ln{color:var(--mu);text-align:right;padding:0 10px;user-select:none;width:1%;white-space:nowrap}td{white-space:pre;padding:0 8px}
.pr{padding:12px;white-space:pre-wrap;font:12px 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;margin:0;overflow-x:auto}
.md{padding:4px 16px 12px;overflow-x:auto}.md code{background:var(--b2);padding:1px 5px;border-radius:5px}.md pre{background:var(--b2);padding:10px;border-radius:6px;overflow-x:auto}
.md h1,.md h2{border-bottom:1px solid var(--bd);padding-bottom:4px}
i{font-style:normal}i.c{color:var(--mu)}i.s{color:var(--ac)}i.k{color:var(--rd)}i.n{color:var(--pu)}
tr.a{background:var(--ad)}tr.d{background:var(--dd)}
.lb{border-radius:20px;padding:0 8px;font-size:12px;color:#fff}
.log{background:#05070d;color:#e6edf3;padding:10px;font:12px/1.5 'JetBrains Mono',ui-monospace,Menlo,Consolas,monospace;white-space:pre-wrap;max-height:300px;overflow:auto;margin:0}
.hm{display:grid;grid-template-rows:repeat(7,11px);grid-auto-flow:column;gap:3px}.hm b{width:11px;height:11px;border-radius:2px;background:var(--b2);border:1px solid var(--bd)}
.bar{display:flex;height:8px;border-radius:4px;overflow:hidden;margin:8px 0}
.st{font-size:12px;border-radius:20px;padding:0 8px}.ok{color:var(--gr)}.er{color:var(--rd)}
.lg{width:32px;height:32px;border-radius:10px;background:linear-gradient(135deg,#4f46e5,#9333ea,#ec4899);display:flex;align-items:center;justify-content:center}
.gt{background:var(--gd);-webkit-background-clip:text;background-clip:text;color:transparent}
.box,.btn{transition:.2s}.box:hover{box-shadow:0 0 18px -4px rgba(168,85,247,.35)}.card{padding:14px;cursor:pointer}
.toast{position:fixed;left:50%;transform:translateX(-50%);bottom:calc(20px + env(safe-area-inset-bottom,0px));background:var(--rd);color:#fff;padding:8px 14px;border-radius:8px;z-index:20;max-width:90%}
</style></head><body>
<div class="hd"><a onclick="go({home:1})" style="display:flex;gap:8px;align-items:center;color:inherit"><span class="lg">🧠</span><b class="gt">Neural Raphael Hub</b></a>
<div id="sw"><input id="sq" style="width:100%" placeholder="Buscar arquivos e issues ( / )" oninput="search(this.value)"><div id="sr"></div></div>
<span id="me" class="pill"></span><button class="btn" onclick="theme()">◐</button></div>
<div class="w" id="app"></div>
<script>
const $=s=>document.querySelector(s),K='nrh-gh-3',D=864e5;
// escape completo (inclui aspas, para uso seguro em atributos) e literal JS seguro para onclick
const esc=s=>String(s??'').replace(/[&<>"']/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c]));
const ja=s=>esc(JSON.stringify(s));
function toast(t){const e=document.createElement('div');e.className='toast';e.textContent=t;document.body.append(e);setTimeout(()=>e.remove(),3200)}
// hash (cyrb53) para SHAs de commit
function h53(s){let a=0xdeadbeef,b=0x41c6ce57;for(let i=0;i<s.length;i++){const c=s.charCodeAt(i);a=Math.imul(a^c,2654435761);b=Math.imul(b^c,1597334677)}a=Math.imul(a^a>>>16,2246822507)^Math.imul(b^b>>>13,3266489909);b=Math.imul(b^b>>>16,2246822507)^Math.imul(a^a>>>13,3266489909);return(b>>>0).toString(16).padStart(8,'0')+(a>>>0).toString(16).padStart(8,'0')}
function ago(t){const s=(Date.now()-t)/1e3;return s<60?'agora':s<3600?Math.floor(s/60)+' min atrás':s<864e2?Math.floor(s/3600)+' h atrás':Math.floor(s/864e2)+' dias atrás'}
// fuzzy match (subsequência com bônus de consecutivos)
function fz(q,s){q=q.toLowerCase();s=s.toLowerCase();let i=0,sc=0,l=-2;for(let j=0;j<s.length&&i<q.length;j++)if(s[j]==q[i]){sc+=j==l+1?3:1;l=j;i++}return i==q.length?sc+1-s.length/1000:-1}
// diff: poda prefixo/sufixo comum + LCS (programação dinâmica) com limite de tamanho
function lcs(A,B){const n=A.length,m=B.length;if(!n)return B.map(x=>['+',x]);if(!m)return A.map(x=>['-',x]);
if(n*m>4e6)return[...A.map(x=>['-',x]),...B.map(x=>['+',x])];
const T=Array.from({length:n+1},()=>new Uint32Array(m+1));
for(let i=n-1;i>=0;i--)for(let j=m-1;j>=0;j--)T[i][j]=A[i]===B[j]?T[i+1][j+1]+1:Math.max(T[i+1][j],T[i][j+1]);
let i=0,j=0,r=[];while(i<n&&j<m){if(A[i]===B[j]){r.push([' ',A[i]]);i++;j++}else if(T[i+1][j]>=T[i][j+1])r.push(['-',A[i++]]);else r.push(['+',B[j++]])}
while(i<n)r.push(['-',A[i++]]);while(j<m)r.push(['+',B[j++]]);return r}
function diff(a,b){const A=a?a.split('\n'):[],B=b?b.split('\n'):[];let s=0;while(s<A.length&&s<B.length&&A[s]===B[s])s++;
let e=0;while(e<A.length-s&&e<B.length-s&&A[A.length-1-e]===B[B.length-1-e])e++;
return[...A.slice(0,s).map(x=>[' ',x]),...lcs(A.slice(s,A.length-e),B.slice(s,B.length-e)),...A.slice(A.length-e).map(x=>[' ',x])]}
function diffH(ch){return ch.map(c=>{const d=diff(c.a,c.b),ad=d.filter(x=>x[0]=='+').length,rm=d.filter(x=>x[0]=='-').length;
return`<div class="box"><div class="bh"><b>${esc(c.p)}</b><span class="r"><span class="ok">+${ad}</span> <span class="er">−${rm}</span></span></div><div class="sc"><table>${d.map(x=>`<tr class="${x[0]=='+'?'a':x[0]=='-'?'d':''}"><td class="ln">${x[0]}</td><td>${esc(x[1])}</td></tr>`).join('')}</table></div></div>`}).join('')}
// realce de sintaxe
function hl(src,p){if(/\.md$/.test(p))return esc(src);const re=/(#.*|\/\/.*|\/\*.*?\*\/)|("(?:\\.|[^"\\\n])*"|'(?:\\.|[^'\\\n])*')|\b(class|def|return|import|from|self|if|else|elif|for|in|not|None|True|False|const|let|function|with|as|while|lambda|raise|try|except|super|run|name|on|steps|uses|var|new|this|static|public|private|void|int|float|double|char|struct|enum|interface|extends|switch|case|break|continue|do|typeof|export|default|catch|finally|throw|null|true|false|undefined|and|or|pass|is|fn|func|impl|mut|use|pub|match|type|package|using|select|where|SELECT|FROM|WHERE)\b|\b(\d+\.?\d*)\b/g;let o='',l=0,m;
while(m=re.exec(src)){o+=esc(src.slice(l,m.index));o+=`<i class="${m[1]?'c':m[2]?'s':m[3]?'k':'n'}">${esc(m[0])}</i>`;l=re.lastIndex}return o+esc(src.slice(l))}
// markdown (títulos, listas, tabelas, citações, links https, negrito/itálico, código)
function md(t){let c=0,o='';const T=[],il=x=>esc(x).replace(/`([^`]+)`/g,'<code>$1</code>').replace(/\*\*([^*]+)\*\*/g,'<b>$1</b>').replace(/\*([^*]+)\*/g,'<em>$1</em>').replace(/\[([^\]]+)\]\((https?:[^)\s]+)\)/g,'<a href="$2" target="_blank" rel="noopener">$1</a>');
const fl=()=>{if(!T.length)return;const r=T.map(l=>l.split('|').slice(1,-1).map(x=>x.trim()));o+='<table style="font:inherit"><tr>'+r[0].map(x=>`<th>${il(x)}</th>`).join('')+'</tr>'+r.slice(2).map(a=>'<tr>'+a.map(x=>`<td style="white-space:normal">${il(x)}</td>`).join('')+'</tr>').join('')+'</table>';T.length=0};
for(const L of t.split('\n')){if(L.startsWith('```')){fl();o+=c?'</pre>':'<pre>';c=!c;continue}if(c){o+=esc(L)+'\n';continue}if(/^\|.*\|$/.test(L)){T.push(L);continue}fl();let m;
o+=(m=L.match(/^(#{1,4}) (.*)/))?`<h${m[1].length}>${il(m[2])}</h${m[1].length}>`:/^(-{3,}|\*{3,})$/.test(L)?'<hr>':(m=L.match(/^> (.*)/))?`<blockquote style="border-left:3px solid var(--bd);margin:0;padding-left:10px;color:var(--mu)">${il(m[1])}</blockquote>`:(m=L.match(/^[-*] \[( |x)\] (.*)/))?`<div>${m[1]=='x'?'☑':'☐'} ${il(m[2])}</div>`:(m=L.match(/^(?:[-*]|\d+\.) (.*)/))?`<li>${il(m[1])}</li>`:L.trim()?`<p>${il(L)}</p>`:''}
fl();if(c)o+='</pre>';return o}
// lint: balanceamento de delimitadores em .py (ignora strings e comentários)
function lint(s){const st=[],pr={')':'(',']':'[','}':'{'};let ln=1;
s=s.replace(/"""[\s\S]*?"""|'''[\s\S]*?'''|"(?:\\.|[^"\\\n])*"|'(?:\\.|[^'\\\n])*'|#.*/g,m=>m.replace(/[^\n]/g,''));
for(const ch of s){if(ch=='\n')ln++;if('([{'.includes(ch))st.push(ch);else if(pr[ch]&&st.pop()!==pr[ch])return'linha '+ln}return st.length?'delimitador não fechado':''}
function rng(a){return()=>{a|=0;a=a+0x6D2B79F5|0;let t=Math.imul(a^a>>>15,1|a);t=t+Math.imul(t^t>>>7,61|t)^t;return((t^t>>>14)>>>0)/4294967296}}
let S,R={},db,UID='local',V={home:1,tab:'code',p:'',f:1,raw:0,sh:0};const UN={},W=()=>S.owner==UID||UID=='local',slug=s=>s.toLowerCase().replace(/[^\w-]+/g,'-').replace(/^-+|-+$/g,'');
function seed(name,owner){const n=Date.now(),F={
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
return{id:slug(name)+'-'+Math.random().toString(36).slice(2,6),name,owner,desc:'',files:F,commits:C,star:[],watch:[],fork:0,
issues:[{n:1,t:'Suporte a ControlNet no Módulo 1',b:'Adicionar ZeroConv para condições estruturais.',l:'enhancement',o:1,d:n-2*D},{n:2,t:'VRAM estoura com batch 8',b:'Reproduz em GPU de 16 GB.',l:'bug',o:1,d:n-3*D},{n:3,t:'Documentar fidelidade do CodeFormer',b:'',l:'docs',o:0,d:n-6*D}],
prs:[{t:'feat: add Euler ancestral sampler',br:'feat/euler',s:'open',d:n-D/2,ch:[ch('samplers/euler.py','','def euler_a_step(x, eps, sigma, sigma_next):\n    return x + (sigma_next - sigma) * eps')]},
{t:'tune: lower default CFG to 7.0',br:'tune/cfg',s:'open',d:n-D/3,ch:[ch('orchestrator.py',F['orchestrator.py'],F['orchestrator.py'].replace('cfg=7.5','cfg=7.0'))]}],runs:[]}}
// normaliza repositórios vindos do localStorage, do banco ou de importação
function norm(r){if(!r||typeof r!='object'||typeof r.files!='object'||!Array.isArray(r.commits)||!r.commits.length)return null;
r.name=String(r.name||'repo');r.id=String(r.id||slug(r.name)+'-'+Math.random().toString(36).slice(2,6));
['star','watch','issues','prs','runs'].forEach(k=>{if(!Array.isArray(r[k]))r[k]=[]});r.fork=+r.fork||0;r.desc=r.desc||'';
r.issues.forEach((x,i)=>{if(!x.n)x.n=r.issues.length-i});return r}
try{const x=JSON.parse(localStorage.getItem(K))||{};for(const k in x){const n=norm(x[k]);if(n)R[k]=n}}catch(e){}
function save(r=S){R[r.id]=r;try{localStorage.setItem(K,JSON.stringify(R))}catch(e){}if(db)db.collection('repos').doc(r.id).set({owner:r.owner,name:r.name,data:JSON.stringify(r)}).catch(()=>{})}
async function names(){try{const u=await claude.use('user'),ids=[...new Set(Object.values(R).map(r=>r.owner))].filter(x=>x!='local'),P=await u.profiles(ids);ids.forEach(i=>UN[i]=(P[i]&&P[i].name)||'usuário');if(!V.edit&&!V.ni)render()}catch(e){}}
(async()=>{try{const u=await claude.use('user');if(u){const m=await u.me();UID=m.id||'local';UN[UID]=m.name||'você';$('#me').textContent=UN[UID]}db=await claude.use('db');
if(db)db.collection('repos').onSnapshot(q=>{const n={};q.docs.forEach(d=>{try{const x=norm(JSON.parse(d.data().data));if(x)n[d.id]=x}catch(e){}});R=n;if(S)S=R[S.id]||null;if(!S)V.home=1;names();if(!V.edit&&!V.ni)render()},()=>{})}catch(e){}render()})();
function newRepo(name,tpl){name=slug(name||'');if(!name)return;const r=seed(name,UID),n=Date.now();if(!tpl){r.files={'README.md':'# '+name+'\n\nNovo repositório.'};r.commits=[{m:'Initial commit',t:n,a:UN[UID]||'você',sha:h53(name+n),ch:[{p:'README.md',a:'',b:r.files['README.md']}]}];r.issues=[];r.prs=[]}
S=r;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function openRepo(id){S=R[id];V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function tg(k){const a=S[k],i=a.indexOf(UID);i<0?a.push(UID):a.splice(i,1);save();render()}
function forkRepo(){const c=JSON.parse(JSON.stringify(S));S.fork++;save();c.id=slug(S.name)+'-'+Math.random().toString(36).slice(2,6);Object.assign(c,{owner:UID,forkOf:S.id,star:[],watch:[],fork:0});S=c;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}
function openPR(){const o=R[S.forkOf];if(!o)return;const ch=[...new Set([...Object.keys(S.files),...Object.keys(o.files)])].filter(p=>S.files[p]!==o.files[p]).map(p=>({p,a:o.files[p]||'',b:S.files[p]||''}));if(!ch.length){toast('Nenhuma diferença para o PR');return}
o.prs.unshift({t:'Mudanças de '+(UN[UID]||'fork'),br:(UN[UID]||'fork')+':main',s:'open',d:Date.now(),ch});save(o);toast('PR aberto no repositório original');render()}
function delRepo(){delete R[S.id];try{localStorage.setItem(K,JSON.stringify(R))}catch(e){}if(db)db.collection('repos').doc(S.id).delete().catch(()=>{});S=null;V.home=1;render()}
function blame(p){let L=[];for(const c of[...S.commits].reverse()){const x=c.ch.find(k=>k.p==p);if(!x)continue;const n=[];let i=0;for(const[t]of diff(x.a,x.b)){if(t==' ')n.push(L[i++]);else if(t=='-')i++;else n.push(c.sha.slice(0,7)+' '+c.a)}L=n}return L}
function homeView(){const L=Object.values(R).sort((a,b)=>b.commits[0].t-a.commits[0].t),q=V.hq||'';
const A=Object.values(R).flatMap(r=>r.commits.slice(0,5).map(c=>({r,c}))).sort((a,b)=>b.c.t-a.c.t).slice(0,8);
$('#app').innerHTML=`<div class="box" style="padding:16px;background:linear-gradient(135deg,rgba(99,102,241,.18),rgba(236,72,153,.12))"><h2 style="margin:0" class="gt">Seus algoritmos e softwares, arquivados.</h2><p class="mu">Crie repositórios, versione código, abra issues e pull requests, faça forks. Compartilhado com quem usa esta página.</p><input id="rn" placeholder="nome-do-repositorio"> <button class="btn g" onclick="newRepo($('#rn').value,0)">+ Novo repositório</button> <button class="btn" onclick="newRepo($('#rn').value||'neural-raphael-hub',1)">Modelo Neural Raphael</button></div>
<input style="width:100%" placeholder="Buscar repositórios e código…" value="${esc(q)}" onchange="V.hq=this.value;render()">${L.filter(r=>!q||fz(q,r.name)>=0||Object.values(r.files).some(c=>c.includes(q))).map(r=>`<div class="box card" onclick="openRepo(${ja(r.id)})"><b class="gt">${esc(UN[r.owner]||'usuário')} / ${esc(r.name)}</b> <span class="pill">Public</span>${r.forkOf?' <span class="mu">fork</span>':''}<br><span class="mu">${esc(r.desc||'')} ★ ${r.star.length} · ⑂ ${r.fork} · ${r.commits.length} commits · ${ago(r.commits[0].t)}</span></div>`).join('')||'<p class="mu">Nenhum repositório ainda. Crie o primeiro acima.</p>'}
<div class="box"><div class="bh"><b>Atividade recente</b></div>${A.map(({r,c})=>`<div class="row"><span class="t"><b>${esc(c.a)}</b> em ${esc(r.name)}: ${esc(c.m)}</span><span class="mu">${ago(c.t)}</span></div>`).join('')||'<div class="row mu">Sem atividade.</div>'}</div>`}
function go(o){Object.assign(V,o);render();scrollTo(0,0)}
function theme(){const r=document.documentElement;r.dataset.theme=(r.dataset.theme||(matchMedia('(prefers-color-scheme:light)').matches?'light':'dark'))=='dark'?'light':'dark'}
let SR=[];
function search(q){const r=$('#sr');if(!q||!S){r.style.display='none';return}
const f=Object.keys(S.files).map(p=>[fz(q,p),'📄 '+p,()=>go({tab:'code',p,edit:0,cm:0})]),
i=S.issues.map(x=>[fz(q,x.t),'⊙ '+x.t,()=>go({tab:'issues',f:x.o?1:0,edit:0,cm:0})]);
const g=Object.entries(S.files).flatMap(([p,c])=>c.split('\n').map((l,n)=>l.toLowerCase().includes(q.toLowerCase())?[.5,'🔎 '+p+':'+(n+1)+' '+l.trim().slice(0,40),()=>go({tab:'code',p,edit:0,cm:0,hlL:n+1})]:null).filter(Boolean)).slice(0,4);
SR=[...f,...i,...g].filter(x=>x[0]>=0).sort((a,b)=>b[0]-a[0]).slice(0,8);
r.style.display='block';r.innerHTML=SR.length?SR.map((x,k)=>`<div onclick="sgo(${k})">${esc(x[1])}</div>`).join(''):'<div class="mu">Nada encontrado</div>'}
function sgo(k){SR[k][2]();$('#sr').style.display='none'}
addEventListener('click',e=>{if(!e.target.closest('#sw'))$('#sr').style.display='none'});
addEventListener('keydown',e=>{if(e.key=='/'&&!/INPUT|TEXTAREA|SELECT/.test(document.activeElement.tagName)){e.preventDefault();$('#sq').focus()}});
const touch=p=>S.commits.find(c=>c.ch.some(x=>x.p==p||x.p.startsWith(p+'/')))||S.commits[0];
function mkCommit(m,ch){S.commits.unshift({m,t:Date.now(),a:UN[UID]||'você',sha:h53(m+Date.now()+Math.random()),ch});save()}
function copyF(p){try{navigator.clipboard.writeText(S.files[p]).then(()=>toast('Copiado'),()=>{})}catch(e){}}
function codeView(){if(V.edit)return editor();if(V.cm)return commitsView();const p=V.p,f=S.files[p],lc=S.commits[0];
const cr=`<a onclick="go({p:''})">${esc(S.name)}</a>`+p.split('/').filter(Boolean).map((s,i,a)=>` / <a onclick="go({p:${ja(a.slice(0,i+1).join('/'))}})">${esc(s)}</a>`).join('');
const bar=`<div class="bh"><b>${esc(lc.a)}</b> <span>${esc(lc.m)}</span><span class="mu">${lc.sha.slice(0,7)} · ${ago(lc.t)}</span><a class="r" onclick="go({cm:1,fh:0})">⏱ ${S.commits.length} commits</a></div>`;
if(f!==undefined){const L=hl(f,p).split('\n'),BL=V.bl?blame(p):[],isMd=/\.md$/.test(p)&&!V.raw;
return`<p>${cr}</p><div class="box">${bar}<div class="bh"><span class="mu">${f.split('\n').length} linhas · ${f.length} bytes</span><span class="r"><button class="btn" onclick="go({cm:1,fh:${ja(p)}})">Histórico</button> <button class="btn" onclick="go({bl:${V.bl?0:1}})">Blame</button> <button class="btn" onclick="go({raw:${V.raw?0:1}})">${V.raw?'Preview':'Raw'}</button> <button class="btn" onclick="copyF(${ja(p)})">Copiar</button>${W()?` <button class="btn" onclick="go({edit:1,np:0})">Editar</button> <button class="btn" onclick="delF(${ja(p)})">Excluir</button>`:''}</span></div>${isMd?`<div class="md">${md(f)}</div>`:V.raw?`<pre class="pr">${esc(f)}</pre>`:`<div class="sc"><table>${L.map((x,i)=>`<tr class="${V.hlL==i+1?'a':''}"><td class="ln" style="cursor:pointer" onclick="V.hlL=${i+1};render()">${i+1}</td>${V.bl?`<td class="mu">${esc(BL[i]||'')}</td>`:''}<td>${x}</td></tr>`).join('')}</table></div>`}</div>`}
const pre=p?p+'/':'',E=new Map();for(const k in S.files)if(k.startsWith(pre)){const r=k.slice(pre.length);E.set(r.split('/')[0],r.includes('/'))}
const rows=[...E].sort((a,b)=>(b[1]-a[1])||(a[0]<b[0]?-1:1)).map(([n,d])=>{const q=pre+n,c=touch(q);return`<div class="row"><span>${d?'📁':'📄'}</span><a class="t" onclick="go({p:${ja(q)}})">${esc(n)}</a><span class="mu t" style="flex:2;overflow:hidden;white-space:nowrap;text-overflow:ellipsis">${esc(c.m)}</span><span class="mu">${ago(c.t)}</span></div>`}).join('');
const rd=S.files[pre+'README.md'];
return`<p>${cr}</p><div class="box">${bar}${rows}</div>${W()?'<button class="btn g" onclick="go({edit:1,np:1})">+ Novo arquivo</button>':''}${rd?`<div class="box"><div class="bh">📖 README.md</div><div class="md">${md(rd)}</div></div>`:''}`}
function editor(){const p=V.np?'':V.p,v=S.files[p]||'';return`<div class="box"><div class="bh">${V.np?'Novo arquivo: <input id="ep" placeholder="pasta/arquivo.py">':'Editando <input id="ep" value="'+esc(p)+'">'}</div><div style="padding:10px"><textarea id="ev">\n${esc(v)}</textarea><p><input id="em" style="width:100%" placeholder="Mensagem do commit"></p><span id="ee" class="er"></span><p><button class="btn g" onclick="commit()">Commit changes</button> <button class="btn" onclick="go({edit:0})">Cancelar</button></p></div></div>`}
function commit(){if(!W())return;const p=$('#ep').value.trim(),old=V.np?'':V.p;if(!/^[\w.\/-]+$/.test(p)){$('#ee').textContent='Caminho inválido';return}
const a=old?S.files[old]:S.files[p]||'',b=$('#ev').value,mv=old&&old!=p;
if(b===''){$('#ee').textContent='Arquivo vazio não é permitido';return}
if(mv&&S.files[p]!==undefined){$('#ee').textContent='Já existe um arquivo com esse caminho';return}
if(a===b&&!mv){$('#ee').textContent='Sem alterações';return}
const ch=[];if(mv){ch.push({p:old,a,b:''});delete S.files[old]}S.files[p]=b;ch.push({p,a:mv?'':a,b});
mkCommit($('#em').value||(mv?'Rename '+old+' → '+p:a?'Update '+p:'Create '+p),ch);V.edit=0;V.p=p;render()}
function delF(p){if(!W()||!(p in S.files))return;const a=S.files[p];delete S.files[p];mkCommit('Delete '+p,[{p,a,b:''}]);V.p=p.split('/').slice(0,-1).join('/');render()}
function revert(sha){if(!W())return;const c=S.commits.find(x=>x.sha==sha);if(!c)return;
const bad=c.ch.find(x=>(S.files[x.p]||'')!==x.b);if(bad){toast('Conflito: '+bad.p+' mudou depois deste commit');return}
const ch=c.ch.map(x=>({p:x.p,a:x.b,b:x.a}));ch.forEach(x=>x.b?S.files[x.p]=x.b:delete S.files[x.p]);mkCommit('Revert "'+c.m+'"',ch);render()}
function commitsView(){return`<p><a onclick="go({cm:0})">← Code</a>${V.fh?'<span class="mu"> Histórico de '+esc(V.fh)+'</span>':''}</p>`+S.commits.filter(c=>!V.fh||c.ch.some(x=>x.p==V.fh)).map(c=>`<div class="box"><div class="row"><div class="t"><b>${esc(c.m)}</b><br><span class="mu">${esc(c.a)} · ${ago(c.t)}</span></div><code>${c.sha.slice(0,7)}</code><button class="btn" onclick="go({sh:V.sh===${ja(c.sha)}?0:${ja(c.sha)}})">diff</button>${W()?`<button class="btn" onclick="revert(${ja(c.sha)})">Revert</button>`:''}</div>${V.sh==c.sha?diffH(c.ch):''}</div>`).join('')}
function issuesView(){const q=V.iq||'',o=S.issues.filter(i=>i.o).length,cl=S.issues.length-o,col={bug:'#d1242f',enhancement:'#1f883d',docs:'#0969da'};
const L=S.issues.map((x,i)=>[x,i]).filter(([x])=>!!x.o==!!V.f&&(!q||fz(q,x.t)>=0));
return`<div style="display:flex;gap:8px;flex-wrap:wrap"><input style="flex:1" placeholder="Filtrar issues" value="${esc(q)}" onchange="go({iq:this.value})"><button class="btn g" onclick="go({ni:1})">New issue</button></div>
${V.ni?`<div class="box" style="padding:10px"><input id="nt" style="width:100%" placeholder="Título"><p><textarea id="nb" style="min-height:80px" placeholder="Descrição"></textarea></p><select id="nl"><option>bug</option><option>enhancement</option><option>docs</option></select> <button class="btn g" onclick="addIssue()">Criar</button> <button class="btn" onclick="go({ni:0})">Cancelar</button></div>`:''}
<div class="box"><div class="bh"><a onclick="go({f:1})" style="${V.f?'font-weight:700':''}">${o} Open</a><a onclick="go({f:0})" style="${V.f?'':'font-weight:700'}">${cl} Closed</a></div>
${L.map(([x,i])=>`<div class="row"><span class="${x.o?'ok':'mu'}">${x.o?'⊙':'✔'}</span><div class="t"><b>${esc(x.t)}</b> <span class="lb" style="background:${col[x.l]||'#6b7280'}">${esc(x.l)}</span><br><span class="mu">#${x.n} · ${ago(x.d)}</span>${x.b?`<br>${esc(x.b)}`:''}${(x.cm||[]).map(c=>`<br><span class="mu">💬 ${esc(c)}</span>`).join('')}<br><input placeholder="Comentar…" onchange="addCm(${i},this)"></div><button class="btn" onclick="S.issues[${i}].o=${x.o?0:1};save();render()">${x.o?'Fechar':'Reabrir'}</button></div>`).join('')||'<div class="row mu">Nenhuma issue.</div>'}</div>`}
function addCm(i,el){const v=el.value.trim();if(!v)return;(S.issues[i].cm=S.issues[i].cm||[]).push((UN[UID]||'você')+': '+v);save();render()}
function addIssue(){const t=$('#nt').value.trim();if(!t)return;const n=Math.max(0,...S.issues.map(x=>x.n||0))+1;S.issues.unshift({n,t,b:$('#nb').value,l:$('#nl').value,o:1,d:Date.now()});V.ni=0;V.f=1;save();render()}
function prsView(){return S.prs.map((p,i)=>`<div class="box"><div class="row"><span class="${p.s=='open'?'ok':'mu'}">⑂</span><div class="t"><b>${esc(p.t)}</b><br><span class="mu">${esc(p.br)} → main · ${ago(p.d)}</span></div><span class="st ${p.s=='open'?'ok':'mu'}">${esc(p.s)}</span>${p.conf&&p.s=='open'?'<span class="er">conflito</span>':''}${p.s=='open'&&W()?`<button class="btn g" onclick="merge(${i})">Merge</button>`:''}<button class="btn" onclick="go({pr:V.pr===${i}?-1:${i}})">files</button></div>${V.pr===i?diffH(p.ch):''}</div>`).join('')||'<p class="mu">Nenhum pull request.</p>'}
function merge(i){if(!W())return;const p=S.prs[i];if(p.ch.some(c=>{const u=S.files[c.p]||'';return u!==c.a&&u!==c.b})){p.conf=1;save();render();return}
p.ch.forEach(c=>{c.b?S.files[c.p]=c.b:delete S.files[c.p]});mkCommit('Merge pull request: '+p.t,p.ch);p.s='merged';delete p.conf;save();render()}
const sl=ms=>new Promise(r=>setTimeout(r,ms));
async function runWf(){const repo=S,r={id:repo.runs.length+1,t:Date.now(),st:'running',log:[]};repo.runs.unshift(r);
const L=x=>{r.log.push(x);if(S===repo&&V.tab=='actions')render()},fin=()=>{save(repo);if(S===repo)render()};
L('▶ Checkout');await sl(300);const bad=[];for(const p in repo.files)if(p.endsWith('.py')){const e=lint(repo.files[p]);L((e?'✖ ':'✔ ')+'lint '+p+(e?' ('+e+')':''));if(e)bad.push(p);await sl(200)}
if(bad.length){r.st='failure';L('Falhou: '+bad.length+' arquivo(s)');fin();return}
const T=20,f=t=>Math.pow(Math.cos((t/T+.008)/1.008*Math.PI/2),2),ab=t=>Math.min(.9999,Math.max(1e-4,f(t)/f(0)));L('▶ Módulo 1: cronograma cosseno, '+T+' passos');
for(let t=T;t>=0;t-=5){L('  passo '+(T-t)+'/'+T+'  ᾱ='+ab(t).toFixed(4)+'  σ='+Math.sqrt((1-ab(t))/ab(t)).toFixed(3));await sl(250)}
L('▶ Módulo 2: High-Res Fix 2.0x → [1, 3, 1024, 1024]');await sl(400);L('✔ CodeFormer fidelity 0.80');r.st='success';fin()}
function actionsView(){return`<button class="btn g" onclick="runWf()">▶ Run workflow</button>`+S.runs.map(r=>`<div class="box"><div class="bh"><span class="${r.st=='success'?'ok':r.st=='failure'?'er':'mu'}">${r.st=='success'?'✔':r.st=='failure'?'✖':'●'}</span><b>pipeline #${r.id}</b><span class="mu">${ago(r.t)} · ${esc(r.st)}</span></div><pre class="log">${esc(r.log.join('\n'))}</pre></div>`).join('')||'<p class="mu">Nenhuma execução ainda. O lint valida delimitadores dos .py.</p>'}
function insView(){const RN=rng(7),cell=[],day=Math.floor(Date.now()/D),cm={};S.commits.forEach(c=>{const k=Math.floor(c.t/D);cm[k]=(cm[k]||0)+3});
for(let i=370;i>=0;i--){const v=(RN()>.6?Math.ceil(RN()*3):0)+(cm[day-i]||0),l=Math.min(4,v);cell.push(`<b style="${l?`background:var(--gr);opacity:${.25+l*.19}`:''}"></b>`)}
const ex={};let all=0;for(const p in S.files){const e=(p.match(/\.(\w+)$/)||[,'other'])[1],n=S.files[p].length;ex[e]=(ex[e]||0)+n;all+=n}all=all||1;
const nm={py:'Python',md:'Markdown',yml:'YAML'},cl={py:'#3572A5',md:'#083fa1',yml:'#cb171e'};
const lg=Object.entries(ex).sort((a,b)=>b[1]-a[1]),lines=Object.values(S.files).reduce((a,s)=>a+s.split('\n').length,0);
const Q={},A={};S.commits.forEach(c=>{const k=new Date(c.t).toISOString().slice(0,10);c.ch.forEach(x=>{const d=diff(x.a,x.b);Q[k]=Q[k]||[0,0];Q[k][0]+=d.filter(y=>y[0]=='+').length;Q[k][1]+=d.filter(y=>y[0]=='-').length});A[c.a]=(A[c.a]||0)+1});
const ks=Object.keys(Q).sort(),mx=Math.max(1,...ks.map(k=>Math.max(...Q[k]))),w=48,W2=Math.max(ks.length*w,200);
return`<div class="box"><div class="bh">Atividade de commits</div><div class="sc" style="padding:12px"><div class="hm">${cell.join('')}</div></div></div>
<div class="box" style="padding:12px"><b>Linguagens</b><div class="bar">${lg.map(([e,n])=>`<span style="width:${n/all*100}%;background:${cl[e]||'#888'}"></span>`).join('')}</div>${lg.map(([e,n])=>`<span style="margin-right:12px">● ${esc(nm[e]||e)} <span class="mu">${(n/all*100).toFixed(1)}%</span></span>`).join('')}</div>
<div class="box" style="padding:12px"><b>Resumo</b><br>${S.commits.length} commits · ${Object.keys(S.files).length} arquivos · ${lines} linhas · ${S.issues.filter(i=>i.o).length} issues abertas · ${S.prs.filter(p=>p.s=='merged').length} PRs mescladas</div>
<div class="box" style="padding:12px"><b>Frequência de código</b><div class="sc"><svg viewBox="0 0 ${W2} 112" style="width:${W2}px">${ks.map((k,i)=>`<rect x="${i*w+4}" y="${55-Q[k][0]/mx*50}" width="14" height="${Q[k][0]/mx*50}" fill="#34d399"/><rect x="${i*w+20}" y="55" width="14" height="${Q[k][1]/mx*50}" fill="#f87171"/><text x="${i*w+4}" y="108" font-size="9" fill="#9ca3af">${k.slice(5)}</text>`).join('')}</svg></div></div>
<div class="box" style="padding:12px"><b>Contribuidores</b>${Object.entries(A).sort((a,b)=>b[1]-a[1]).map(([n,c])=>`<div>${esc(n)} <span class="mu">${c} commits</span></div>`).join('')}</div>`}
// branches (com ancestral comum para merge de 3 vias)
function brSave(){S.br=S.br||{};const k=S.cur||'main';Object.assign(S.br[k]=S.br[k]||{},{files:S.files,commits:S.commits})}
function brSwitch(n){brSave();const b=S.br[n];if(!b)return;S.files=b.files;S.commits=b.commits;S.cur=n;V.p='';save();render()}
function brNew(){const n=slug($('#bn').value);if(!n||!W())return;brSave();if(S.br[n]){toast('Branch já existe');return}S.br[n]=JSON.parse(JSON.stringify(S.br[S.cur||'main']));S.br[n].base={...S.files};brSwitch(n)}
function brMerge(){const c=S.cur||'main';if(c=='main'||!W())return;brSave();const m=S.br.main,x=S.br[c],base=x.base,ch=[];
for(const p of new Set([...Object.keys(m.files),...Object.keys(x.files)])){const mv=m.files[p],xv=x.files[p];if(mv===xv)continue;
if(base){const bv=base[p];if(xv===bv)continue;if(mv!==bv){toast('Conflito em '+p+': main também foi alterada');return}}
ch.push({p,a:mv||'',b:xv||''})}
if(ch.length){ch.forEach(k=>k.b?m.files[k.p]=k.b:delete m.files[k.p]);m.commits.unshift({m:'Merge branch '+c,t:Date.now(),a:UN[UID]||'você',sha:h53(c+Date.now()),ch})}
delete S.br[c];S.files=m.files;S.commits=m.commits;S.cur='main';V.p='';save();render()}
// ZIP (método "store") com CRC32
const CT=(()=>{const t=[];for(let n=0;n<256;n++){let c=n;for(let k=0;k<8;k++)c=c&1?0xEDB88320^(c>>>1):c>>>1;t[n]=c>>>0}return t})();
const crc=u=>{let c=-1;for(const b of u)c=CT[(c^b)&255]^(c>>>8);return(c^-1)>>>0};
function zip(files){const E=new TextEncoder(),P=[],CD=[];let off=0,cs=0;const ks=Object.keys(files);
for(const p of ks){const n=E.encode(p),d=E.encode(files[p]),cr=crc(d),h=new DataView(new ArrayBuffer(30)),g=new DataView(new ArrayBuffer(46));
h.setUint32(0,0x04034b50,true);h.setUint16(4,20,true);h.setUint16(6,0x800,true);h.setUint16(12,0x21,true);h.setUint32(14,cr,true);h.setUint32(18,d.length,true);h.setUint32(22,d.length,true);h.setUint16(26,n.length,true);P.push(h.buffer,n,d);
g.setUint32(0,0x02014b50,true);g.setUint16(4,20,true);g.setUint16(6,20,true);g.setUint16(8,0x800,true);g.setUint16(14,0x21,true);g.setUint32(16,cr,true);g.setUint32(20,d.length,true);g.setUint32(24,d.length,true);g.setUint16(28,n.length,true);g.setUint32(42,off,true);CD.push(g.buffer,n);
off+=30+n.length+d.length;cs+=46+n.length}
const e=new DataView(new ArrayBuffer(22));e.setUint32(0,0x06054b50,true);e.setUint16(8,ks.length,true);e.setUint16(10,ks.length,true);e.setUint32(12,cs,true);e.setUint32(16,off,true);
return new Blob([...P,...CD,e.buffer],{type:'application/zip'})}
async function dl(name,data){const b=data instanceof Blob?data:new Blob([data]);try{const d=await claude.use('downloads');if(d){await d.save({filename:name,data:b});return}}catch(e){if(e&&e.code=='declined')return}
const a=document.createElement('a');a.href=URL.createObjectURL(b);a.download=name;document.body.append(a);a.click();a.remove()}
function imp(fl){if(!fl||!fl[0])return;const r=new FileReader();r.onload=()=>{try{const x=norm(JSON.parse(r.result));if(!x){toast('JSON inválido');return}
Object.assign(x,{id:slug(x.name||'import')+'-'+Math.random().toString(36).slice(2,6),owner:UID,star:[],watch:[]});S=x;save();V={tab:'code',p:'',f:1,raw:0,sh:0};render()}catch(e){toast('JSON inválido')}};r.readAsText(fl[0])}
async function upl(fs){if(!W())return;const d=S.files[V.p]!==undefined?V.p.split('/').slice(0,-1).join('/'):V.p,ch=[];
for(const f of fs){if(f.size>3e5){toast(f.name+': maior que 300 KB, ignorado');continue}const p=(d?d+'/':'')+f.name.replace(/[^\w.\/-]/g,'_'),b=await f.text(),a=S.files[p]||'';if(b&&a!==b){S.files[p]=b;ch.push({p,a,b})}}
if(ch.length)mkCommit('Upload '+ch.length+' file(s)',ch);render()}
function tools(){if(V.tab!='code'||V.cm||V.edit)return'';const br=['main',...Object.keys(S.br||{}).filter(x=>x!='main')],c=S.cur||'main';
return`<div style="display:flex;gap:6px;flex-wrap:wrap;align-items:center;margin-bottom:8px"><select onchange="brSwitch(this.value)">${br.map(b=>`<option ${b==c?'selected':''}>${esc(b)}</option>`).join('')}</select>${W()?`<input id="bn" placeholder="nova-branch" style="width:110px"><button class="btn" onclick="brNew()">+ Branch</button>${c!='main'?'<button class="btn g" onclick="brMerge()">Merge → main</button>':''}<label class="btn">⬆ Arquivos<input type="file" multiple hidden onchange="upl(this.files)"></label>`:''}<button class="btn" onclick="dl(S.name+'.zip',zip(S.files))">⬇ ZIP</button><button class="btn" onclick="dl(S.name+'.json',JSON.stringify(S))">⬇ JSON</button><label class="btn">⬆ Importar JSON<input type="file" accept=".json" hidden onchange="imp(this.files)"></label></div>`}
// releases (notas automáticas a partir dos commits)
function relView(){const L=S.rel||[];return(W()?`<div class="box" style="padding:10px"><input id="rt" placeholder="v1.0.0"> <input id="rn2" placeholder="Título"><p><textarea id="rb" style="min-height:70px" placeholder="Notas (vazio = gerar dos commits)"></textarea></p><button class="btn g" onclick="addRel()">Publicar release</button></div>`:'')+L.map((r,i)=>`<div class="box"><div class="bh"><b class="gt">${esc(r.tag)}</b> ${esc(r.title)}<span class="mu r">${esc(r.sha.slice(0,7))} · ${ago(r.t)}</span></div><div class="md">${md(r.notes)}</div><div class="row"><button class="btn" onclick="dl(S.name+'-'+S.rel[${i}].tag+'.zip',zip(S.rel[${i}].files))">⬇ Source (zip)</button></div></div>`).join('')||'<p class="mu">Sem releases.</p>'}
function addRel(){if(!W())return;const tag=$('#rt').value.trim();if(!tag)return;let n=$('#rb').value;if(!n){const pv=(S.rel||[])[0],k=pv?S.commits.findIndex(c=>c.sha==pv.sha):-1;n='## Mudanças\n'+S.commits.slice(0,k<0?S.commits.length:k).map(c=>'- '+c.m).join('\n')}
(S.rel=S.rel||[]).unshift({tag,title:$('#rn2').value,notes:n,sha:S.commits[0].sha,t:Date.now(),files:{...S.files}});save();render()}
// projetos (kanban)
function projView(){const P=S.pj=S.pj||{cols:['A fazer','Em andamento','Feito'],cards:[]};
return`<div style="display:flex;gap:10px;overflow-x:auto">${P.cols.map((c,ci)=>`<div class="box" style="min-width:230px;flex:1"><div class="bh"><b>${esc(c)}</b><span class="ct">${P.cards.filter(k=>k.c==ci).length}</span></div>${P.cards.map((k,ki)=>k.c==ci?`<div class="row" style="flex-wrap:wrap"><span class="t">${esc(k.t)}</span>${ci>0?`<button class="btn" onclick="mvc(${ki},-1)">◀</button>`:''}${ci<2?`<button class="btn" onclick="mvc(${ki},1)">▶</button>`:''}<button class="btn" onclick="S.pj.cards.splice(${ki},1);save();render()">✕</button></div>`:'').join('')}<div class="row"><input style="width:100%" placeholder="+ Cartão" onchange="addCard(${ci},this.value)"></div></div>`).join('')}</div>`}
const mvc=(i,d)=>{S.pj.cards[i].c+=d;save();render()},addCard=(c,t)=>{if(!t.trim())return;S.pj.cards.push({c,t});save();render()};
function render(){if(V.home||!S)return homeView();const own=S.owner==UID,o=S.issues.filter(i=>i.o).length,po=S.prs.filter(p=>p.s=='open').length,
T=[['code','Code'],['issues','Issues',o],['prs','Pull requests',po],['actions','Actions'],['projects','Projects'],['releases','Releases'],['insights','Insights']];
const b={code:codeView,issues:issuesView,prs:prsView,actions:actionsView,insights:insView,releases:relView,projects:projView}[V.tab]();
$('#app').innerHTML=`<div class="rt"><a onclick="go({home:1})">${esc(UN[S.owner]||'usuário')}</a> / <b class="gt">${esc(S.name)}</b> <span class="pill">Public</span>${S.forkOf?' <span class="mu">fork</span>':''}</div><input style="width:100%" placeholder="Descrição" value="${esc(S.desc||'')}" ${own?'':'disabled'} onchange="S.desc=this.value;save()"><div style="display:flex;gap:6px;flex-wrap:wrap;margin:6px 0"><button class="btn ${S.watch.includes(UID)?'on':''}" onclick="tg('watch')">👁 Watch ${S.watch.length}</button><button class="btn" onclick="forkRepo()">⑂ Fork ${S.fork}</button><button class="btn ${S.star.includes(UID)?'on':''}" onclick="tg('star')">★ Star ${S.star.length}</button>${own&&S.forkOf&&R[S.forkOf]?'<button class="btn g" onclick="openPR()">Abrir PR</button>':''}${own?'<button class="btn" onclick="delRepo()">🗑</button>':''}</div>${own?'':'<p class="mu">🔒 Somente leitura: faça um fork para editar.</p>'}
<div class="tabs">${T.map(t=>`<a class="${V.tab==t[0]?'on':''}" onclick="go({tab:'${t[0]}',edit:0,cm:0})">${t[1]}${t[2]?`<span class="ct">${t[2]}</span>`:''}</a>`).join('')}</div>${tools()}${b}`}
// atalhos estilo GitHub: g c / g i / g p / g a / g r / g b e "t"
let gk=0;addEventListener('keydown',e=>{if(/INPUT|TEXTAREA|SELECT/.test(document.activeElement.tagName)||!S||V.home||e.ctrlKey||e.metaKey||e.altKey)return;
if(gk){gk=0;const m={c:'code',i:'issues',p:'prs',a:'actions',r:'releases',b:'projects'}[e.key];if(m)go({tab:m,edit:0,cm:0});return}
if(e.key=='g')gk=1;if(e.key=='t'){e.preventDefault();$('#sq').focus()}});
/* ============================================================
NEURAL RAPHAEL HUB
BLOCO 2 — CORE ENGINE (versão corrigida)
============================================================ */

// CORREÇÃO: render() não pode ser chamado se ainda não existir.
if (typeof render === "function") {
  render();
}

const NRH2 = (() => {
  const VERSION = "2.0.1";
  const PREFIX = "nrh-core";

  /* ---------------------------------------------------------
  UTILIDADES
  --------------------------------------------------------- */
  const now = () => Date.now();

  const uid = (prefix = "id") =>
    prefix + "_" +
    Date.now().toString(36) + "_" +
    Math.random().toString(36).slice(2, 10);

  const clone = value => {
    if (value === undefined) return undefined;
    return JSON.parse(JSON.stringify(value));
  };

  const isObject = value =>
    value !== null && typeof value === "object" && !Array.isArray(value);

  const isString = value => typeof value === "string";
  const isFunction = value => typeof value === "function";

  const clamp = (value, min, max) =>
    Math.max(min, Math.min(max, value));

  const sleep = ms =>
    new Promise(resolve => setTimeout(resolve, ms));

  const normalize = value =>
    String(value ?? "")
      .normalize("NFD")
      .replace(/[\u0300-\u036f]/g, "")
      .toLowerCase()
      .trim();

  const slugify = value =>
    normalize(value)
      .replace(/[^a-z0-9]+/g, "-")
      .replace(/^-+|-+$/g, "")
      .slice(0, 100);

  const timestamp = () => new Date().toISOString();

  const safeJSON = value => {
    try {
      return JSON.stringify(value);
    } catch {
      return null;
    }
  };

  const FORBIDDEN_KEYS = new Set(["__proto__", "prototype", "constructor"]);

  const isThenable = value =>
    value && isFunction(value.then);

  /* ---------------------------------------------------------
  EVENT BUS
  --------------------------------------------------------- */
  const events = new Map();

  function on(event, handler) {
    if (!isFunction(handler)) {
      throw new TypeError("Handler de evento precisa ser uma função.");
    }
    if (!events.has(event)) {
      events.set(event, new Set());
    }
    events.get(event).add(handler);
    return () => off(event, handler);
  }

  function once(event, handler) {
    // CORREÇÃO: guarda o handler original para que off(event, handler) funcione.
    const wrapper = payload => {
      off(event, wrapper);
      handler(payload);
    };
    wrapper.original = handler;
    return on(event, wrapper);
  }

  function off(event, handler) {
    const set = events.get(event);
    if (!set) return false;

    let removed = set.delete(handler);
    if (!removed) {
      for (const listener of set) {
        if (listener.original === handler) {
          set.delete(listener);
          removed = true;
          break;
        }
      }
    }
    if (!set.size) {
      events.delete(event);
    }
    return removed;
  }

  function emit(event, payload) {
    const listeners = events.get(event);
    if (!listeners) return;
    for (const listener of [...listeners]) {
      try {
        listener(payload);
      } catch (error) {
        console.error("[NRH EVENT ERROR]", event, error);
      }
    }
  }

  /* ---------------------------------------------------------
  STORE
  --------------------------------------------------------- */
  // CORREÇÃO: paths aceitam string "a.b" OU array ["a", "b"].
  // IDs com ponto ou barra (ex.: "joao.silva/repo") quebravam o split(".").
  const toPath = path =>
    Array.isArray(path) ? path.map(String) : String(path).split(".");

  const store = {
    state: {
      version: VERSION,
      initialized: false,
      user: null,
      route: { page: "home", params: {} },
      ui: {
        sidebar: true,
        commandPalette: false,
        notifications: false,
        modal: null,
        loading: false
      },
      preferences: {
        theme: "auto",
        density: "comfortable",
        animations: true
      },
      repositories: {},
      notifications: [],
      sessions: [],
      activity: [],
      extensions: {}
    },

    subscribers: new Set(),

    get(path) {
      if (path === undefined || path === null || path === "") {
        return this.state;
      }
      return toPath(path).reduce(
        (obj, key) => (obj == null ? undefined : obj[key]),
        this.state
      );
    },

    set(path, value) {
      const parts = toPath(path);

      if (!parts.length || parts.some(p => p === "" || FORBIDDEN_KEYS.has(p))) {
        throw new Error("Caminho de estado inválido.");
      }

      let target = this.state;
      for (let i = 0; i < parts.length - 1; i++) {
        const key = parts[i];
        if (target[key] === null || typeof target[key] !== "object") {
          target[key] = {};
        }
        target = target[key];
      }
      target[parts[parts.length - 1]] = value;
      this.notify(path, value);
      return value;
    },

    update(path, updater) {
      const current = this.get(path);
      const next = isFunction(updater) ? updater(current) : updater;
      return this.set(path, next);
    },

    subscribe(handler) {
      this.subscribers.add(handler);
      return () => {
        this.subscribers.delete(handler);
      };
    },

    notify(path, value) {
      for (const subscriber of [...this.subscribers]) {
        try {
          subscriber({ path, value, state: this.state });
        } catch (error) {
          console.error("[NRH STORE]", error);
        }
      }
      emit("store:update", { path, value });
    }
  };

  /* ---------------------------------------------------------
  STORAGE
  --------------------------------------------------------- */
  const storage = {
    memory: new Map(),

    key(key) {
      return `${PREFIX}:${key}`;
    },

    get(key, fallback = null) {
      const storageKey = this.key(key);
      try {
        const raw = localStorage.getItem(storageKey);
        if (raw !== null) {
          return JSON.parse(raw);
        }
      } catch (error) {
        console.warn("[NRH STORAGE GET]", error);
      }
      if (this.memory.has(storageKey)) {
        return clone(this.memory.get(storageKey));
      }
      return fallback;
    },

    set(key, value) {
      const storageKey = this.key(key);
      this.memory.set(storageKey, clone(value));
      try {
        // CORREÇÃO: JSON.stringify(undefined) gerava a string "undefined" corrompida.
        if (value === undefined) {
          localStorage.removeItem(storageKey);
        } else {
          localStorage.setItem(storageKey, JSON.stringify(value));
        }
      } catch (error) {
        console.warn("[NRH STORAGE SET]", error);
      }
      emit("storage:set", { key, value });
      return value;
    },

    remove(key) {
      const storageKey = this.key(key);
      this.memory.delete(storageKey);
      try {
        localStorage.removeItem(storageKey);
      } catch {}
      emit("storage:remove", { key });
    },

    clear() {
      try {
        Object.keys(localStorage)
          .filter(key => key.startsWith(PREFIX + ":"))
          .forEach(key => localStorage.removeItem(key));
      } catch {}
      this.memory.clear();
      emit("storage:clear");
    }
  };

  /* ---------------------------------------------------------
  ROUTER
  --------------------------------------------------------- */
  const router = {
    routes: new Map(),

    register(name, handler) {
      if (!isFunction(handler)) {
        throw new TypeError("Route handler precisa ser uma função.");
      }
      this.routes.set(name, handler);
      return this;
    },

    exists(name) {
      return this.routes.has(name);
    },

    navigate(name, params = {}) {
      const handler = this.routes.get(name);

      store.set("route", { page: name, params });
      emit("route:change", { name, params });

      if (!handler) {
        emit("route:notfound", { name, params });
        return;
      }

      const fail = error => {
        console.error("[NRH ROUTER]", error);
        emit("route:error", { name, params, error });
      };

      try {
        const result = handler(params);
        // CORREÇÃO: handlers assíncronos que falham não eram capturados.
        if (isThenable(result)) {
          return result.catch(fail);
        }
        return result;
      } catch (error) {
        fail(error);
      }
    },

    current() {
      return clone(store.get("route"));
    }
  };

  /* ---------------------------------------------------------
  PERMISSÕES
  --------------------------------------------------------- */
  const permissions = {
    levels: {
      none: 0,
      read: 10,
      triage: 20,
      write: 30,
      maintain: 40,
      admin: 50,
      owner: 60
    },

    compare(a, b) {
      const A = this.levels[a] ?? this.levels.none;
      const B = this.levels[b] ?? this.levels.none;
      return A - B;
    },

    allows(current, required) {
      return this.compare(current, required) >= 0;
    },

    repositoryRole(repository, userId) {
      if (!repository || !userId) return "none";
      if (repository.owner === userId) return "owner";
      const collaborators = repository.collaborators || {};
      return collaborators[userId] || "none";
    },

    can(repository, userId, required) {
      const role = this.repositoryRole(repository, userId);
      return this.allows(role, required);
    }
  };

  /* ---------------------------------------------------------
  NOTIFICAÇÕES
  --------------------------------------------------------- */
  const notifications = {
    push({
      title,
      message = "",
      type = "info",
      link = null,
      persistent = false
    }) {
      const item = {
        id: uid("notification"),
        title,
        message,
        type,
        link,
        persistent,
        read: false,
        createdAt: now()
      };
      store.update("notifications", list =>
        [item, ...(list || [])].slice(0, 200)
      );
      emit("notification:new", item);
      return item;
    },

    markRead(id) {
      store.update("notifications", list =>
        (list || []).map(item =>
          item.id === id ? { ...item, read: true } : item
        )
      );
    },

    markAllRead() {
      store.update("notifications", list =>
        (list || []).map(item => ({ ...item, read: true }))
      );
    },

    unread() {
      return (store.get("notifications") || []).filter(item => !item.read);
    },

    remove(id) {
      store.update("notifications", list =>
        (list || []).filter(item => item.id !== id)
      );
    },

    clear() {
      store.set("notifications", []);
    }
  };

  /* ---------------------------------------------------------
  ACTIVITY LOG
  --------------------------------------------------------- */
  const activity = {
    add(type, payload = {}) {
      const item = {
        id: uid("activity"),
        type,
        payload: clone(payload),
        user: store.get("user")?.id || "anonymous",
        createdAt: now()
      };
      store.update("activity", list =>
        [item, ...(list || [])].slice(0, 1000)
      );
      emit("activity:new", item);
      return item;
    },

    list(limit = 50) {
      return (store.get("activity") || []).slice(0, limit);
    }
  };

  /* ---------------------------------------------------------
  REPOSITORY SERVICE
  --------------------------------------------------------- */
  const VISIBILITIES = new Set(["public", "private"]);

  const repositories = {
    create({ owner, name, description = "", visibility = "public" }) {
      if (!owner) {
        throw new Error("Owner obrigatório.");
      }

      const cleanName = slugify(name);
      if (!cleanName) {
        throw new Error("Nome de repositório inválido.");
      }

      if (!VISIBILITIES.has(visibility)) {
        throw new Error("Visibilidade inválida.");
      }

      const id = `${owner}/${cleanName}`;

      // CORREÇÃO: path em array evita quebra quando owner contém ".".
      if (store.get(["repositories", id])) {
        throw new Error("Repositório já existe.");
      }

      const repository = {
        id,
        owner,
        name: cleanName,
        fullName: id,
        description,
        visibility,
        defaultBranch: "main",
        branches: {
          main: { name: "main", protected: false, head: null }
        },
        files: {},
        commits: [],
        issues: [],
        pullRequests: [],
        releases: [],
        projects: [],
        collaborators: {},
        stars: [],
        watchers: [],
        forks: [],
        createdAt: now(),
        updatedAt: now()
      };

      store.set(["repositories", id], repository);
      activity.add("repository.created", { repository: id });
      emit("repository:create", repository);
      return repository;
    },

    get(id) {
      return store.get(["repositories", id]);
    },

    update(id, updater) {
      const repository = this.get(id);
      if (!repository) {
        throw new Error("Repositório não encontrado.");
      }

      const updated = isFunction(updater)
        ? updater(clone(repository))
        : { ...repository, ...updater };

      // CORREÇÃO: updater que não retorna nada derrubava com TypeError.
      if (!isObject(updated)) {
        throw new TypeError("Updater precisa retornar o repositório.");
      }

      // CORREÇÃO: identidade do repositório não pode ser alterada.
      updated.id = repository.id;
      updated.owner = repository.owner;
      updated.fullName = repository.fullName;
      updated.updatedAt = now();

      store.set(["repositories", id], updated);
      emit("repository:update", updated);
      return updated;
    },

    remove(id) {
      const repository = this.get(id);
      if (!repository) return false;

      store.update("repositories", all => {
        const next = { ...(all || {}) };
        delete next[id];
        return next;
      });

      activity.add("repository.deleted", { repository: id });
      emit("repository:delete", repository);
      return true;
    },

    list(owner = null) {
      const all = Object.values(store.get("repositories") || {});
      if (!owner) return all;
      return all.filter(repository => repository.owner === owner);
    }
  };

  /* ---------------------------------------------------------
  FILE SERVICE
  --------------------------------------------------------- */
  const files = {
    normalizePath(path) {
      // CORREÇÃO: remove "." e ".." (path traversal) e chaves perigosas.
      return String(path || "")
        .replaceAll("\\", "/")
        .split("/")
        .filter(
          part =>
            part &&
            part !== "." &&
            part !== ".." &&
            !FORBIDDEN_KEYS.has(part)
        )
        .join("/");
    },

    exists(repository, path) {
      const p = this.normalizePath(path);
      return Object.prototype.hasOwnProperty.call(repository?.files || {}, p);
    },

    read(repository, path) {
      const p = this.normalizePath(path);
      if (!this.exists(repository, p)) return null;
      return repository.files[p];
    },

    write(repository, path, content) {
      const p = this.normalizePath(path);

      if (!p) {
        throw new Error("Caminho inválido.");
      }
      if (!isString(content)) {
        throw new TypeError("Conteúdo precisa ser texto.");
      }
      if (!isObject(repository.files)) {
        repository.files = {};
      }

      repository.files[p] = content;
      repository.updatedAt = now();
      return repository;
    },

    remove(repository, path) {
      const p = this.normalizePath(path);
      if (!this.exists(repository, p)) return false;
      delete repository.files[p];
      repository.updatedAt = now();
      return true;
    },

    list(repository, directory = "") {
      const prefix = this.normalizePath(directory);
      const base = prefix ? prefix + "/" : "";
      const result = new Map();

      for (const path of Object.keys(repository.files || {})) {
        if (!path.startsWith(base)) continue;

        const rest = path.slice(base.length);
        if (!rest) continue;

        const slash = rest.indexOf("/");
        const name = slash === -1 ? rest : rest.slice(0, slash);

        // Se já marcado como diretório, mantém.
        result.set(name, result.get(name) === true || slash !== -1);
      }

      return [...result]
        .map(([name, isDirectory]) => ({ name, directory: isDirectory }))
        .sort(
          (a, b) =>
            Number(b.directory) - Number(a.directory) ||
            a.name.localeCompare(b.name)
        );
    }
  };

  /* ---------------------------------------------------------
  COMMAND REGISTRY
  --------------------------------------------------------- */
  const commands = new Map();

  function registerCommand(
    id,
    { title, description = "", shortcut = "", handler, keywords = [] }
  ) {
    if (!id) {
      throw new Error("Command ID obrigatório.");
    }
    if (!isFunction(handler)) {
      throw new TypeError("Command handler inválido.");
    }
    commands.set(id, {
      id,
      title: title || id,
      description,
      shortcut,
      handler,
      keywords
    });
    return commands.get(id);
  }

  function reportCommandError(error) {
    notifications.push({
      title: "Erro ao executar comando",
      message: error?.message || String(error),
      type: "error"
    });
    console.error("[NRH COMMAND]", error);
    return false;
  }

  function executeCommand(id, ...args) {
    const command = commands.get(id);
    if (!command) return false;

    try {
      const result = command.handler(...args);
      // CORREÇÃO: comandos assíncronos com erro não eram tratados.
      if (isThenable(result)) {
        return result.catch(reportCommandError);
      }
      return result;
    } catch (error) {
      return reportCommandError(error);
    }
  }

  function searchCommands(query) {
    const q = normalize(query);
    if (!q) return [...commands.values()];

    return [...commands.values()]
      .map(command => {
        const title = normalize(command.title);
        const haystack = normalize(
          [command.title, command.description, ...command.keywords].join(" ")
        );

        let score = 0;
        if (haystack.includes(q)) score += 100;
        if (title.startsWith(q)) score += 50;
        if (title.includes(q)) score += 25;

        return { command, score };
      })
      .filter(item => item.score > 0)
      .sort((a, b) => b.score - a.score)
      .map(item => item.command);
  }

  /* ---------------------------------------------------------
  COMMANDS PADRÃO
  --------------------------------------------------------- */
  registerCommand("home", {
    title: "Ir para início",
    description: "Abrir página principal",
    shortcut: "G H",
    keywords: ["home", "inicio", "dashboard"],
    handler() {
      if (typeof go === "function") {
        go({ home: 1 });
      } else {
        router.navigate("home");
      }
    }
  });

  registerCommand("theme", {
    title: "Alternar tema",
    description: "Alternar entre tema claro e escuro",
    shortcut: "Ctrl+Shift+L",
    keywords: ["tema", "dark", "light"],
    handler() {
      if (typeof theme === "function") {
        theme();
        return;
      }
      // CORREÇÃO: fallback — antes o comando não fazia nada sem theme().
      const next = store.get("preferences.theme") === "dark" ? "light" : "dark";
      store.set("preferences.theme", next);
      if (typeof document !== "undefined") {
        document.documentElement.dataset.theme = next;
      }
    }
  });

  registerCommand("repository:refresh", {
    title: "Atualizar repositório",
    description: "Renderizar novamente a página atual",
    keywords: ["refresh", "reload", "atualizar"],
    handler() {
      if (typeof render === "function") {
        render();
      }
      emit("repository:refresh");
    }
  });

  registerCommand("notification:read-all", {
    title: "Marcar notificações como lidas",
    description: "Limpar contador de notificações não lidas",
    keywords: ["notifications", "read", "lidas"],
    handler() {
      notifications.markAllRead();
    }
  });

  /* ---------------------------------------------------------
  KEYBOARD ENGINE
  --------------------------------------------------------- */
  const keyboard = {
    bindings: new Map(),
    started: false,

    bind(key, handler, options = {}) {
      const id = uid("key");
      this.bindings.set(id, {
        key,
        handler,
        ctrl: !!options.ctrl,
        shift: !!options.shift,
        alt: !!options.alt,
        meta: !!options.meta,
        // CORREÇÃO: allowEditing nunca era gravado, então atalhos
        // não funcionavam dentro de inputs (ex.: fechar palette com Ctrl+K).
        allowEditing: !!options.allowEditing
      });
      return () => this.bindings.delete(id);
    },

    match(binding, event) {
      // CORREÇÃO: event.key pode ser undefined (autofill do navegador).
      if (typeof event.key !== "string") return false;
      return (
        event.key.toLowerCase() === binding.key.toLowerCase() &&
        !!event.ctrlKey === binding.ctrl &&
        !!event.shiftKey === binding.shift &&
        !!event.altKey === binding.alt &&
        !!event.metaKey === binding.meta
      );
    },

    init() {
      // CORREÇÃO: não quebra fora do navegador e não duplica listener.
      if (this.started || typeof window === "undefined") return;
      this.started = true;

      window.addEventListener("keydown", event => {
        const el = document.activeElement;
        const tag = el?.tagName;
        const editing =
          tag === "INPUT" ||
          tag === "TEXTAREA" ||
          tag === "SELECT" ||
          el?.isContentEditable;

        for (const binding of this.bindings.values()) {
          if (editing && !binding.allowEditing) continue;

          if (this.match(binding, event)) {
            event.preventDefault();
            try {
              binding.handler(event);
            } catch (error) {
              console.error("[NRH KEYBOARD]", error);
            }
            return;
          }
        }
      });
    }
  };

  keyboard.init();

  /* ---------------------------------------------------------
  COMMAND PALETTE
  --------------------------------------------------------- */
  const palette = {
    open() {
      store.set("ui.commandPalette", true);
      emit("palette:open");
    },

    close() {
      store.set("ui.commandPalette", false);
      emit("palette:close");
    },

    toggle() {
      store.update("ui.commandPalette", value => !value);
      emit(
        store.get("ui.commandPalette") ? "palette:open" : "palette:close"
      );
    },

    search(query) {
      return searchCommands(query);
    },

    execute(id, ...args) {
      this.close();
      return executeCommand(id, ...args);
    }
  };

  // Ctrl+K (Windows/Linux) e Cmd+K (Mac), inclusive digitando em inputs.
  keyboard.bind("k", () => palette.toggle(), { ctrl: true, allowEditing: true });
  keyboard.bind("k", () => palette.toggle(), { meta: true, allowEditing: true });

  // CORREÇÃO: o atalho do tema era anunciado mas nunca registrado.
  keyboard.bind("l", () => executeCommand("theme"), { ctrl: true, shift: true });

  /* ---------------------------------------------------------
  MODAL ENGINE
  --------------------------------------------------------- */
  const modal = {
    open(config = {}) {
      const data = {
        id: uid("modal"),
        title: config.title || "Neural Raphael Hub",
        content: config.content || "",
        actions: config.actions || [],
        closeable: config.closeable !== false
      };
      store.set("ui.modal", data);
      emit("modal:open", data);
      return data.id;
    },

    close() {
      const current = store.get("ui.modal");
      store.set("ui.modal", null);
      emit("modal:close", current);
    }
  };

  /* ---------------------------------------------------------
  USER SESSION
  --------------------------------------------------------- */
  const auth = {
    login(user) {
      if (!user) {
        throw new Error("Usuário inválido.");
      }

      const normalized = {
        id: user.id || uid("user"),
        name: user.name || "Usuário",
        username: user.username || slugify(user.name || "usuario"),
        avatar: user.avatar || "",
        createdAt: user.createdAt || now()
      };

      store.set("user", normalized);
      storage.set("session", normalized);
      activity.add("auth.login");
      emit("auth:login", normalized);
      return normalized;
    },

    logout() {
      const current = store.get("user");

      // CORREÇÃO: registra a atividade ANTES de limpar o usuário,
      // senão o log saía como "anonymous".
      activity.add("auth.logout");

      store.set("user", null);
      storage.remove("session");
      emit("auth:logout", current);
    },

    restore() {
      const session = storage.get("session");
      if (session) {
        store.set("user", session);
      }
      return session;
    },

    current() {
      return store.get("user");
    },

    isAuthenticated() {
      return !!this.current();
    }
  };

  /* ---------------------------------------------------------
  REPOSITORY GUARDS
  --------------------------------------------------------- */
  const guard = {
    authenticated() {
      if (!auth.isAuthenticated()) {
        notifications.push({
          title: "Autenticação necessária",
          message: "Entre na sua conta para continuar.",
          type: "warning"
        });
        return false;
      }
      return true;
    },

    repository(repository, level = "read") {
      if (!repository) return false;

      const isPublicRead =
        level === "read" && repository.visibility === "public";

      const user = auth.current();
      if (!user) return isPublicRead;

      return permissions.can(repository, user.id, level) || isPublicRead;
    }
  };

  /* ---------------------------------------------------------
  PERSISTÊNCIA DO CORE
  --------------------------------------------------------- */
  function persist() {
    storage.set("core-state", {
      preferences: store.get("preferences"),
      activity: store.get("activity"),
      notifications: store.get("notifications"),
      // CORREÇÃO: repositórios eram perdidos ao recarregar a página.
      repositories: store.get("repositories")
    });
  }

  function restore() {
    const saved = storage.get("core-state");
    if (!saved) return;

    if (isObject(saved.preferences)) {
      store.set("preferences", {
        ...store.get("preferences"),
        ...saved.preferences
      });
    }
    if (Array.isArray(saved.activity)) {
      store.set("activity", saved.activity);
    }
    if (Array.isArray(saved.notifications)) {
      store.set("notifications", saved.notifications);
    }
    if (isObject(saved.repositories)) {
      store.set("repositories", saved.repositories);
    }
  }

  /* ---------------------------------------------------------
  EXTENSIONS
  --------------------------------------------------------- */
  const extensions = {
    register(name, extension) {
      if (!name) {
        throw new Error("Nome da extensão obrigatório.");
      }
      // CORREÇÃO: path em array (nomes com "." não quebram).
      store.set(["extensions", name], {
        ...extension,
        registeredAt: now()
      });
      emit("extension:register", { name, extension });
    },

    get(name) {
      return store.get(["extensions", name]);
    },

    list() {
      return Object.keys(store.get("extensions") || {});
    }
  };

  /* ---------------------------------------------------------
  INICIALIZAÇÃO
  --------------------------------------------------------- */
  function init() {
    if (store.get("initialized")) return;

    restore();
    auth.restore();

    store.set("initialized", true);
    activity.add("core.initialized", { version: VERSION });
    persist();
    emit("core:ready", { version: VERSION });
  }

  /* ---------------------------------------------------------
  AUTOSAVE
  --------------------------------------------------------- */
  let autosaveTimer = null;

  function autosave() {
    // CORREÇÃO: antes do init(), um autosave sobrescrevia os dados salvos
    // com o estado vazio, antes de restore() conseguir lê-los.
    if (!store.get("initialized")) return;

    clearTimeout(autosaveTimer);
    autosaveTimer = setTimeout(persist, 500);
  }

  on("store:update", autosave);

  /* ---------------------------------------------------------
  API PÚBLICA
  --------------------------------------------------------- */
  return {
    VERSION,
    util: {
      now,
      uid,
      clone,
      isObject,
      isString,
      clamp,
      sleep,
      normalize,
      slugify,
      timestamp,
      safeJSON
    },
    events: { on, once, off, emit },
    store,
    storage,
    router,
    permissions,
    notifications,
    activity,
    repositories,
    files,
    commands: {
      register: registerCommand,
      execute: executeCommand,
      search: searchCommands
    },
    keyboard,
    palette,
    modal,
    auth,
    guard,
    extensions,
    init,
    persist,
    restore
  };
})();
<!-- ============================================================
     FINAL DO BLOCO 2 (corrigido)
     Este trecho estava solto, fora de <script>. Mantenha no Bloco 2.
     ============================================================ -->
<script>
NRH2.events.on("repository:create", function (repository) {
  console.log("[Neural Raphael Hub] Repositório criado:", repository.fullName);
});
NRH2.events.on("repository:update", function (repository) {
  console.log("[Neural Raphael Hub] Repositório atualizado:", repository.fullName);
});
NRH2.events.on("notification:new", function (notification) {
  console.log("[NRH Notification]", notification.title);
});

NRH2.commands.register("repository:create", {
  title: "Criar novo repositório",
  description: "Cria um novo projeto no Neural Raphael Hub",
  keywords: ["repo", "repository", "novo", "criar"],
  handler: function () {
    const name = prompt("Nome do repositório:");
    if (!name) return;
    const user = NRH2.auth.current();
    // CORREÇÃO: UID pode não existir -> ReferenceError
    const fallback = typeof UID !== "undefined" ? UID : "local";
    const owner = (user && (user.username || user.login)) || fallback;
    try {
      const repository = NRH2.repositories.create({
        owner: owner,
        name: name,
        description: "Novo projeto Neural Raphael Hub"
      });
      NRH2.notifications.push({
        title: "Repositório criado",
        message: repository.fullName,
        type: "success"
      });
    } catch (error) {
      NRH2.notifications.push({
        title: "Não foi possível criar",
        message: error && error.message ? error.message : String(error),
        type: "error"
      });
    }
  }
});

NRH2.commands.register("notifications", {
  title: "Abrir notificações",
  description: "Visualizar atividade e notificações",
  keywords: ["alertas", "atividade", "notifications"],
  handler: function () {
    NRH2.palette.close();
    NRH2.store.set("ui.notifications", true);
    NRH2.events.emit("notifications:open");
  }
});

NRH2.keyboard.bind("p", function () {
  if (NRH2.store.get("ui.commandPalette")) return;
  NRH2.palette.open();
}, { ctrl: true, shift: true });

NRH2.init();
console.log("%cNeural Raphael Hub Core " + NRH2.VERSION, "font-weight:bold");
console.log("Core Engine carregado.");
</script>

<script>
/* ============================================================
   NEURAL RAPHAEL HUB
   BLOCO 3 — USERS / PROFILES / ORGANIZATIONS / COLLABORATORS
   (versão corrigida)  |  Namespace: NRH3
   ============================================================ */
(function (global) {
  "use strict";

  if (!global.NRH2) {
    console.error("[NRH3] NRH2 não encontrado. Carregue o BLOCO 2 antes do BLOCO 3.");
    return;
  }
  if (global.NRH3) {
    console.warn("[NRH3] Já carregado; ignorando segunda carga.");
    return;
  }

  const NRH2 = global.NRH2;
  const VERSION = "3.0.1";

  /* =========================================================
     3.1 — UTILIDADES
     ========================================================= */
  const hasOwn = (o, k) => Object.prototype.hasOwnProperty.call(o, k);

  function clone(value) {
    if (typeof NRH2.clone === "function") return NRH2.clone(value);
    try { return JSON.parse(JSON.stringify(value)); } catch (e) { return value; }
  }
  function now() { return new Date().toISOString(); }
  function uid(prefix) {
    prefix = prefix || "id";
    let rnd;
    if (global.crypto && typeof global.crypto.randomUUID === "function") {
      rnd = global.crypto.randomUUID().replace(/-/g, "").slice(0, 12);
    } else {
      rnd = Math.random().toString(36).slice(2, 10);
    }
    return prefix + "_" + Date.now().toString(36) + "_" + rnd;
  }
  function normalize(value) { return String(value == null ? "" : value).trim().toLowerCase(); }
  function slugify(value) {
    return normalize(value)
      .normalize("NFD")
      .replace(/[\u0300-\u036f]/g, "")
      .replace(/[^a-z0-9]+/g, "-")
      .replace(/^-+|-+$/g, "")
      .slice(0, 80);
  }
  function validLogin(login) {
    return /^[a-zA-Z0-9][a-zA-Z0-9_-]{0,38}$/.test(String(login || ""));
  }
  function validEmail(email) {
    return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(String(email || ""));
  }
  function escapeHTML(value) {
    return String(value == null ? "" : value)
      .replace(/&/g, "&amp;").replace(/</g, "&lt;").replace(/>/g, "&gt;")
      .replace(/"/g, "&quot;").replace(/'/g, "&#039;");
  }
  function safeUrl(url) {
    url = String(url || "").trim();
    return /^(https?:\/\/|data:image\/|\/|\.\/)/i.test(url) ? url : "";
  }

  /* --- Ponte de eventos: o Bloco 2 usa NRH2.events.* --- */
  function emit(event, payload) {
    try {
      if (NRH2.events && typeof NRH2.events.emit === "function") NRH2.events.emit(event, payload);
      else if (typeof NRH2.emit === "function") NRH2.emit(event, payload);
    } catch (err) {
      console.warn("[NRH3] Listener falhou em", event, err);
    }
  }
  function on(event, fn) {
    if (NRH2.events && typeof NRH2.events.on === "function") NRH2.events.on(event, fn);
    else if (typeof NRH2.on === "function") NRH2.on(event, fn);
  }
  function save() {
    try {
      if (NRH2.persistence && typeof NRH2.persistence.save === "function") NRH2.persistence.save();
    } catch (err) {
      console.warn("[NRH3] Falha ao persistir:", err);
    }
  }

  /* --- Ponte de comandos: Bloco 2 usa register(id, {title, handler}) --- */
  function registerCommand(id, def) {
    const cmds = NRH2.commands;
    if (!cmds || typeof cmds.register !== "function") return;
    const full = {
      id: id, title: def.label, label: def.label,
      description: def.description, keywords: def.keywords,
      handler: def.run, run: def.run
    };
    try { cmds.register(id, full); }
    catch (e1) {
      try { cmds.register(full); }
      catch (e2) { console.warn("[NRH3] Não foi possível registrar comando", id, e2); }
    }
  }

  /* =========================================================
     3.2 — PAPÉIS E PERMISSÕES
     ========================================================= */
  const ROLES = {
    NONE: "none", READ: "read", TRIAGE: "triage", WRITE: "write",
    MAINTAIN: "maintain", ADMIN: "admin", OWNER: "owner"
  };
  const ROLE_WEIGHT = { none: 0, read: 1, triage: 2, write: 3, maintain: 4, admin: 5, owner: 6 };
  const ASSIGNABLE_ROLES = ["read", "triage", "write", "maintain", "admin"];

  const ROLE_PERMISSIONS = {
    none: [],
    read: ["repo.read", "issues.read", "pulls.read", "releases.read", "projects.read"],
    triage: ["repo.read", "issues.read", "issues.manage", "pulls.read", "pulls.triage",
      "releases.read", "projects.read"],
    write: ["repo.read", "repo.write", "issues.read", "issues.manage", "pulls.read",
      "pulls.triage", "pulls.write", "releases.read", "releases.write",
      "projects.read", "projects.write"],
    maintain: ["repo.read", "repo.write", "repo.maintain", "issues.read", "issues.manage",
      "pulls.read", "pulls.triage", "pulls.write", "pulls.merge", "releases.read",
      "releases.write", "projects.read", "projects.write", "settings.read"],
    admin: ["repo.read", "repo.write", "repo.maintain", "repo.admin", "issues.read",
      "issues.manage", "pulls.read", "pulls.triage", "pulls.write", "pulls.merge",
      "releases.read", "releases.write", "projects.read", "projects.write",
      "settings.read", "settings.write", "members.read", "members.write"],
    owner: ["*"]
  };

  function checkAssignable(role, label) {
    if (ASSIGNABLE_ROLES.indexOf(role) === -1) {
      throw new Error("Papel de " + label + " inválido. Use: " + ASSIGNABLE_ROLES.join(", ") + ".");
    }
  }

  /* =========================================================
     3.3 — ESTADO (acessado sempre pela raiz atual do NRH2)
     CORREÇÃO: se a persistência substituir store.state ao carregar,
     a referência antiga ficaria obsoleta. O Proxy resolve isso.
     ========================================================= */
  function rootState() { return NRH2.store && NRH2.store.state; }
  if (!rootState()) {
    console.error("[NRH3] Estado global do NRH2 não disponível.");
    return;
  }
  const COLLECTIONS = ["users", "organizations", "teams", "invitations",
    "collaborators", "followers", "sessions"];
  function ensureState() {
    const s = rootState();
    COLLECTIONS.forEach(k => {
      if (!s[k] || typeof s[k] !== "object") s[k] = {};
    });
    return s;
  }
  const state = new Proxy({}, {
    get: (_, key) => ensureState()[key],
    set: (_, key, value) => { ensureState()[key] = value; return true; }
  });
  ensureState();

  /* =========================================================
     3.4 — USERS
     CORREÇÃO: buscas usam hasOwn (logins como "constructor"
     retornavam funções do protótipo) e aceitam objetos
     (NRH2.auth.current() retorna objeto, não string).
     ========================================================= */
  const users = {
    create(data) {
      data = data || {};
      const login = String(data.login || "").trim();
      if (!validLogin(login)) {
        throw new Error("Login inválido. Use letras, números, '-' ou '_'.");
      }
      if (users.getRaw(login)) throw new Error("Este login já está em uso.");
      if (data.email && !validEmail(data.email)) throw new Error("E-mail inválido.");

      const user = {
        id: uid("usr"),
        login: login,
        username: login,
        name: data.name || login,
        email: data.email || "",
        bio: data.bio || "",
        company: data.company || "",
        location: data.location || "",
        website: data.website || "",
        avatar: data.avatar || "",
        avatar_url: data.avatar_url || "",
        status: data.status || "active",
        type: data.type || "User",
        hireable: data.hireable === true,
        public: data.public !== false,
        verified: data.verified === true,
        createdAt: now(),
        updatedAt: now(),
        followers: [],
        following: [],
        organizations: [],
        repositories: [],
        starred: [],
        preferences: {
          theme: "system", language: "pt-BR",
          emailNotifications: true, webNotifications: true
        },
        security: { twoFactorEnabled: false, sessions: [] },
        stats: { repositories: 0, contributions: 0, followers: 0, following: 0 }
      };
      state.users[normalize(login)] = user;
      emit("user:created", { user: clone(user) });
      save();
      return clone(user);
    },

    getRaw(ref) {
      if (ref && typeof ref === "object") ref = ref.id || ref.login || ref.username;
      if (!ref) return null;
      const value = String(ref);
      const key = normalize(value);
      if (hasOwn(state.users, key)) return state.users[key];
      return Object.values(state.users).find(u => u.id === value) || null;
    },

    get(ref) {
      const user = users.getRaw(ref);
      return user ? clone(user) : null;
    },

    list(options) {
      options = options || {};
      let result = Object.values(state.users);
      if (options.status) result = result.filter(u => u.status === options.status);
      if (options.search) {
        const q = normalize(options.search);
        result = result.filter(u =>
          normalize(u.login).includes(q) ||
          normalize(u.name).includes(q) ||
          normalize(u.bio).includes(q));
      }
      result.sort((a, b) => normalize(a.login).localeCompare(normalize(b.login)));
      if (options.limit) result = result.slice(0, options.limit);
      return clone(result);
    },

    update(ref, patch) {
      const user = users.getRaw(ref);
      if (!user) throw new Error("Usuário não encontrado.");
      patch = patch || {};
      if (patch.email !== undefined && patch.email && !validEmail(patch.email)) {
        throw new Error("E-mail inválido.");
      }
      ["name", "bio", "company", "location", "website", "avatar",
        "avatar_url", "email", "hireable", "public"].forEach(key => {
        if (hasOwn(patch, key)) user[key] = patch[key];
      });
      user.updatedAt = now();
      emit("user:updated", { user: clone(user) });
      save();
      return clone(user);
    },

    delete(ref) {
      const user = users.getRaw(ref);
      if (!user) return false;

      // Não deixa organização órfã de proprietário.
      Object.values(state.organizations).forEach(org => {
        if ((org.owners || []).includes(user.id) && org.owners.length === 1) {
          throw new Error(
            'Usuário é o único proprietário de "' + org.login +
            '". Transfira a propriedade antes de excluir.');
        }
      });

      // Limpeza completa de referências.
      Object.values(state.organizations).forEach(org => {
        org.owners = (org.owners || []).filter(id => id !== user.id);
        org.members = (org.members || []).filter(id => id !== user.id);
        if (org.memberRoles) delete org.memberRoles[user.id];
        org.stats.members = org.members.length;
      });
      Object.values(state.teams).forEach(team => {
        team.members = (team.members || []).filter(id => id !== user.id);
        team.maintainers = (team.maintainers || []).filter(id => id !== user.id);
      });
      Object.values(state.users).forEach(other => {
        other.followers = (other.followers || []).filter(id => id !== user.id);
        other.following = (other.following || []).filter(id => id !== user.id);
        other.stats.followers = other.followers.length;
        other.stats.following = other.following.length;
      });
      Object.keys(state.collaborators).forEach(k => {
        if (state.collaborators[k].userId === user.id) delete state.collaborators[k];
      });
      Object.keys(state.sessions).forEach(k => {
        if (state.sessions[k].userId === user.id) delete state.sessions[k];
      });
      Object.keys(state.invitations).forEach(k => {
        if (state.invitations[k].userId === user.id) delete state.invitations[k];
      });

      delete state.users[normalize(user.login)];
      emit("user:deleted", { userId: user.id, login: user.login });
      save();
      return true;
    }
  };

  /* =========================================================
     3.5 — PERFIL
     ========================================================= */
  const profiles = {
    get(ref) {
      const user = users.get(ref);
      if (!user) return null;
      return {
        id: user.id, login: user.login, name: user.name, bio: user.bio,
        company: user.company, location: user.location, website: user.website,
        avatar: user.avatar, avatar_url: user.avatar_url, type: user.type,
        createdAt: user.createdAt,
        repositories: user.repositories || [],
        organizations: user.organizations || [],
        stats: clone(user.stats || {}),
        followers: (user.followers || []).length,
        following: (user.following || []).length
      };
    },
    update(ref, patch) { return users.update(ref, patch); }
  };

  /* =========================================================
     3.6 — SOCIAL
     ========================================================= */
  const social = {
    follow(followerRef, targetRef) {
      const follower = users.getRaw(followerRef);
      const target = users.getRaw(targetRef);
      if (!follower || !target) throw new Error("Usuário não encontrado.");
      if (follower.id === target.id) throw new Error("Um usuário não pode seguir a si próprio.");

      follower.following = follower.following || [];
      target.followers = target.followers || [];
      if (!follower.following.includes(target.id)) follower.following.push(target.id);
      if (!target.followers.includes(follower.id)) target.followers.push(follower.id);

      follower.stats = follower.stats || {};
      target.stats = target.stats || {};
      follower.stats.following = follower.following.length;
      target.stats.followers = target.followers.length;

      emit("social:follow", { follower: follower.login, target: target.login });
      save();
      return true;
    },
    unfollow(followerRef, targetRef) {
      const follower = users.getRaw(followerRef);
      const target = users.getRaw(targetRef);
      if (!follower || !target) return false;

      follower.following = (follower.following || []).filter(id => id !== target.id);
      target.followers = (target.followers || []).filter(id => id !== follower.id);
      follower.stats = follower.stats || {};
      target.stats = target.stats || {};
      follower.stats.following = follower.following.length;
      target.stats.followers = target.followers.length;

      emit("social:unfollow", { follower: follower.login, target: target.login });
      save();
      return true;
    },
    followers(ref) {
      const user = users.getRaw(ref);
      return user ? (user.followers || []).map(id => users.get(id)).filter(Boolean) : [];
    },
    following(ref) {
      const user = users.getRaw(ref);
      return user ? (user.following || []).map(id => users.get(id)).filter(Boolean) : [];
    }
  };

  /* =========================================================
     3.7 — ORGANIZATIONS
     ========================================================= */
  const organizations = {
    create(data) {
      data = data || {};
      const login = String(data.login || data.name || "").trim();
      if (!validLogin(login)) throw new Error("Identificador da organização inválido.");
      if (organizations.getRaw(login)) throw new Error("Esta organização já existe.");

      // CORREÇÃO: auth.current() devolve objeto; getRaw agora aceita objeto.
      const ownerRef = data.owner ||
        (NRH2.auth && typeof NRH2.auth.current === "function" ? NRH2.auth.current() : null);
      const owner = users.getRaw(ownerRef);
      if (!owner) throw new Error("É necessário um proprietário válido.");

      const org = {
        id: uid("org"),
        login: login,
        name: data.name || login,
        description: data.description || "",
        avatar: data.avatar || "",
        website: data.website || "",
        email: data.email || "",
        location: data.location || "",
        public: data.public !== false,
        createdAt: now(),
        updatedAt: now(),
        owners: [owner.id],
        members: [owner.id],
        memberRoles: {},
        teams: [],
        repositories: [],
        invitations: [],
        settings: {
          defaultRepositoryRole: ROLES.READ,
          memberVisibility: "public",
          allowInvitations: true
        },
        stats: { members: 1, repositories: 0, teams: 0 }
      };
      org.memberRoles[owner.id] = ROLES.OWNER;
      state.organizations[normalize(login)] = org;

      owner.organizations = owner.organizations || [];
      if (!owner.organizations.includes(org.id)) owner.organizations.push(org.id);

      emit("organization:created", { organization: clone(org), owner: owner.login });
      save();
      return clone(org);
    },

    getRaw(ref) {
      if (ref && typeof ref === "object") ref = ref.id || ref.login;
      if (!ref) return null;
      const value = String(ref);
      const key = normalize(value);
      if (hasOwn(state.organizations, key)) return state.organizations[key];
      return Object.values(state.organizations).find(o => o.id === value) || null;
    },
    get(ref) {
      const org = organizations.getRaw(ref);
      return org ? clone(org) : null;
    },
    list() {
      return clone(Object.values(state.organizations)
        .sort((a, b) => normalize(a.login).localeCompare(normalize(b.login))));
    },

    update(ref, patch) {
      const org = organizations.getRaw(ref);
      if (!org) throw new Error("Organização não encontrada.");
      patch = patch || {};
      ["name", "description", "avatar", "website", "email", "location", "public"]
        .forEach(key => { if (hasOwn(patch, key)) org[key] = patch[key]; });
      org.updatedAt = now();
      emit("organization:updated", { organization: clone(org) });
      save();
      return clone(org);
    },

    addMember(ref, userRef, role) {
      const org = organizations.getRaw(ref);
      const user = users.getRaw(userRef);
      if (!org || !user) throw new Error("Organização ou usuário não encontrado.");

      role = role || ROLES.READ;
      checkAssignable(role, "organização"); // CORREÇÃO: impedia "owner" por esta via

      org.memberRoles = org.memberRoles || {};
      user.organizations = user.organizations || [];
      if (!org.members.includes(user.id)) org.members.push(user.id);
      if (!user.organizations.includes(org.id)) user.organizations.push(org.id);

      // Não rebaixa um proprietário.
      if (!org.owners.includes(user.id)) org.memberRoles[user.id] = role;
      org.stats.members = org.members.length;

      emit("organization:member_added", {
        organization: org.login, user: user.login,
        role: org.memberRoles[user.id] || role
      });
      save();
      return clone(org);
    },

    removeMember(ref, userRef) {
      const org = organizations.getRaw(ref);
      const user = users.getRaw(userRef);
      if (!org || !user) return false;
      if (org.owners.includes(user.id)) {
        throw new Error("O proprietário não pode ser removido diretamente.");
      }
      org.members = org.members.filter(id => id !== user.id);
      user.organizations = (user.organizations || []).filter(id => id !== org.id);
      if (org.memberRoles) delete org.memberRoles[user.id];

      // CORREÇÃO: remove também das equipes da organização.
      (org.teams || []).forEach(teamId => {
        const team = state.teams[teamId];
        if (!team) return;
        team.members = team.members.filter(id => id !== user.id);
        team.maintainers = team.maintainers.filter(id => id !== user.id);
      });

      org.stats.members = org.members.length;
      emit("organization:member_removed", { organization: org.login, user: user.login });
      save();
      return true;
    },

    members(ref) {
      const org = organizations.getRaw(ref);
      return org ? org.members.map(id => users.get(id)).filter(Boolean) : [];
    }
  };

  /* =========================================================
     3.8 — TEAMS
     ========================================================= */
  const teams = {
    create(orgRef, data) {
      const org = organizations.getRaw(orgRef);
      if (!org) throw new Error("Organização não encontrada.");
      data = data || {};
      const name = String(data.name || "").trim();
      if (!name) throw new Error("Nome da equipe é obrigatório.");
      const slug = slugify(name);
      if (!slug) throw new Error("Nome da equipe inválido.");
      if (Object.values(state.teams).some(t => t.organizationId === org.id && t.slug === slug)) {
        throw new Error("Esta equipe já existe.");
      }
      const team = {
        id: uid("team"),
        organizationId: org.id,
        name: name,
        slug: slug,
        description: data.description || "",
        privacy: data.privacy || "closed",
        members: [],
        maintainers: [],
        repositories: [], // [{ repositoryId, role }]
        createdAt: now(),
        updatedAt: now()
      };
      state.teams[team.id] = team;
      org.teams.push(team.id);
      org.stats.teams = org.teams.length;
      emit("team:created", { team: clone(team) });
      save();
      return clone(team);
    },
    getRaw(id) { return hasOwn(state.teams, id) ? state.teams[id] : null; },
    get(id) {
      const team = teams.getRaw(id);
      return team ? clone(team) : null;
    },
    list(orgRef) {
      const org = organizations.getRaw(orgRef);
      return org ? org.teams.map(id => teams.get(id)).filter(Boolean) : [];
    },
    addMember(teamId, userRef) {
      const team = teams.getRaw(teamId);
      const user = users.getRaw(userRef);
      if (!team || !user) throw new Error("Equipe ou usuário não encontrado.");
      const org = organizations.getRaw(team.organizationId);
      if (!org || !org.members.includes(user.id)) {
        throw new Error("O usuário precisa pertencer à organização.");
      }
      if (!team.members.includes(user.id)) team.members.push(user.id);
      team.updatedAt = now();
      emit("team:member_added", { team: team.slug, user: user.login });
      save();
      return clone(team);
    },
    removeMember(teamId, userRef) {
      const team = teams.getRaw(teamId);
      const user = users.getRaw(userRef);
      if (!team || !user) return false;
      team.members = team.members.filter(id => id !== user.id);
      team.maintainers = team.maintainers.filter(id => id !== user.id);
      team.updatedAt = now();
      emit("team:member_removed", { team: team.slug, user: user.login });
      save();
      return true;
    },
    members(teamId) {
      const team = teams.getRaw(teamId);
      return team ? team.members.map(id => users.get(id)).filter(Boolean) : [];
    },
    // NOVO: o campo "repositories" nunca era usado; agora equipes dão acesso.
    grantRepository(teamId, repoId, role) {
      const team = teams.getRaw(teamId);
      if (!team) throw new Error("Equipe não encontrada.");
      role = role || ROLES.READ;
      checkAssignable(role, "equipe");
      const entry = team.repositories.find(r => r.repositoryId === repoId);
      if (entry) entry.role = role;
      else team.repositories.push({ repositoryId: repoId, role: role });
      team.updatedAt = now();
      emit("team:repository_granted", { team: team.slug, repositoryId: repoId, role: role });
      save();
      return clone(team);
    }
  };

  /* =========================================================
     3.9 — COLABORADORES
     ========================================================= */
  const collaborators = {
    key(repoId, userId) { return String(repoId) + "::" + String(userId); },

    grant(repoId, userRef, role, actorLogin) {
      const user = users.getRaw(userRef);
      if (!user) throw new Error("Usuário não encontrado.");
      if (repoId == null || repoId === "") throw new Error("Repositório inválido.");
      role = role || ROLES.WRITE;
      checkAssignable(role, "colaborador"); // CORREÇÃO: bloqueia "owner" e "none"

      const key = collaborators.key(repoId, user.id);
      const previous = hasOwn(state.collaborators, key) ? state.collaborators[key] : null;
      const record = {
        id: key,
        repositoryId: repoId,
        userId: user.id,
        role: role,
        grantedBy: actorLogin || null,
        createdAt: previous ? previous.createdAt : now(), // preserva histórico
        updatedAt: now()
      };
      state.collaborators[key] = record;
      emit("repository:collaborator_granted", {
        repositoryId: repoId, user: user.login, role: role, grantedBy: actorLogin || null
      });
      save();
      return clone(record);
    },

    revoke(repoId, userRef) {
      const user = users.getRaw(userRef);
      if (!user) return false;
      const key = collaborators.key(repoId, user.id);
      if (!hasOwn(state.collaborators, key)) return false;
      delete state.collaborators[key];
      emit("repository:collaborator_revoked", { repositoryId: repoId, user: user.login });
      save();
      return true;
    },

    get(repoId, userRef) {
      const user = users.getRaw(userRef);
      if (!user) return null;
      const key = collaborators.key(repoId, user.id);
      return hasOwn(state.collaborators, key) ? clone(state.collaborators[key]) : null;
    },

    list(repoId) {
      return Object.values(state.collaborators)
        .filter(r => r.repositoryId === repoId)
        .map(r => Object.assign(clone(r), { user: users.get(r.userId) }));
    }
  };

  /* =========================================================
     3.10 — RESOLUÇÃO DE PERMISSÕES
     CORREÇÃO: agora considera organização (dono/membro) e equipes.
     ========================================================= */
  const access = {
    weight(role) { return hasOwn(ROLE_WEIGHT, role) ? ROLE_WEIGHT[role] : 0; },
    permissions(role) {
      return clone(hasOwn(ROLE_PERMISSIONS, role) ? ROLE_PERMISSIONS[role] : ROLE_PERMISSIONS.none);
    },
    hasRole(current, required) { return access.weight(current) >= access.weight(required); },
    canRole(role, permission) {
      const list = hasOwn(ROLE_PERMISSIONS, role) ? ROLE_PERMISSIONS[role] : [];
      return list.includes("*") || list.includes(permission);
    },

    repositoryRole(repoId, userRef) {
      const user = users.getRaw(userRef);
      if (!user) return ROLES.NONE;

      let best = ROLES.NONE;
      const consider = role => {
        if (access.weight(role) > access.weight(best)) best = role;
      };

      // 1) Colaborador explícito
      const collab = collaborators.get(repoId, user.id);
      if (collab) consider(collab.role);

      // 2) Equipes com acesso ao repositório
      Object.values(state.teams).forEach(team => {
        if (!team.members.includes(user.id)) return;
        const entry = (team.repositories || []).find(r => r.repositoryId === repoId);
        if (entry) consider(entry.role);
      });

      // 3) Dados do repositório (NRH2.repositories)
      let repo = null;
      if (NRH2.repositories && typeof NRH2.repositories.get === "function") {
        try { repo = NRH2.repositories.get(repoId); } catch (e) { repo = null; }
      }
      if (repo) {
        const ownerRef = repo.owner || repo.ownerLogin || repo.owner_id;
        if (ownerRef) {
          if (normalize(ownerRef) === normalize(user.login) || ownerRef === user.id) {
            consider(ROLES.OWNER);
          } else {
            const org = organizations.getRaw(ownerRef);
            if (org) {
              if (org.owners.includes(user.id)) consider(ROLES.OWNER);
              else if (org.members.includes(user.id)) {
                consider(org.settings.defaultRepositoryRole);
              }
            }
          }
        }
        if (repo.permissions && hasOwn(repo.permissions, user.id)) {
          consider(repo.permissions[user.id]);
        }
        if (repo.collaborators && hasOwn(repo.collaborators, user.login)) {
          consider(repo.collaborators[user.login]);
        }
      }
      return best;
    },

    canRepository(repoId, userRef, permission) {
      return access.canRole(access.repositoryRole(repoId, userRef), permission);
    }
  };

  /* =========================================================
     3.11 — CONVITES
     CORREÇÃO: convites de repositório não faziam nada ao aceitar;
     o estado "accepted" era gravado antes da ação (inconsistência
     se a ação falhasse).
     ========================================================= */
  const invitations = {
    create(data) {
      data = data || {};
      const target = users.getRaw(data.user || data.username);
      if (!target) throw new Error("Usuário convidado não encontrado.");

      const type = data.type || "repository";
      if (["repository", "organization", "team"].indexOf(type) === -1) {
        throw new Error("Tipo de convite inválido.");
      }
      const targetId = data.repositoryId || data.organizationId || data.teamId || null;
      if (targetId == null) throw new Error("Destino do convite não informado.");
      if (type === "organization" && !organizations.getRaw(targetId)) {
        throw new Error("Organização não encontrada.");
      }
      if (type === "team" && !teams.getRaw(targetId)) {
        throw new Error("Equipe não encontrada.");
      }
      const role = data.role || ROLES.READ;
      checkAssignable(role, "convite");

      const duplicate = Object.values(state.invitations).find(inv =>
        inv.state === "pending" && inv.type === type &&
        inv.targetId === targetId && inv.userId === target.id);
      if (duplicate) throw new Error("Já existe um convite pendente.");

      const invitation = {
        id: uid("inv"),
        type: type,
        targetId: targetId,
        userId: target.id,
        inviterId: data.inviterId || null,
        role: role,
        state: "pending",
        message: data.message || "",
        createdAt: now(),
        respondedAt: null
      };
      state.invitations[invitation.id] = invitation;
      emit("invitation:created", { invitation: clone(invitation) });
      save();
      return clone(invitation);
    },

    get(id) {
      return hasOwn(state.invitations, id) ? clone(state.invitations[id]) : null;
    },

    listForUser(userRef) {
      const user = users.getRaw(userRef);
      if (!user) return [];
      return Object.values(state.invitations)
        .filter(inv => inv.userId === user.id).map(clone);
    },

    accept(id) {
      const inv = hasOwn(state.invitations, id) ? state.invitations[id] : null;
      if (!inv) throw new Error("Convite não encontrado.");
      if (inv.state !== "pending") throw new Error("Este convite não está pendente.");

      // Executa a ação primeiro; só marca como aceito se der certo.
      if (inv.type === "organization") {
        organizations.addMember(inv.targetId, inv.userId, inv.role);
      } else if (inv.type === "team") {
        teams.addMember(inv.targetId, inv.userId);
      } else if (inv.type === "repository") {
        const inviter = inv.inviterId ? users.getRaw(inv.inviterId) : null;
        collaborators.grant(inv.targetId, inv.userId, inv.role, inviter ? inviter.login : null);
      }

      inv.state = "accepted";
      inv.respondedAt = now();
      emit("invitation:accepted", { invitation: clone(inv) });
      save();
      return clone(inv);
    },

    decline(id) {
      const inv = hasOwn(state.invitations, id) ? state.invitations[id] : null;
      if (!inv) throw new Error("Convite não encontrado.");
      if (inv.state !== "pending") throw new Error("Este convite não está pendente.");
      inv.state = "declined";
      inv.respondedAt = now();
      emit("invitation:declined", { invitation: clone(inv) });
      save();
      return clone(inv);
    }
  };

  /* =========================================================
     3.12 — IDENTIDADE (sessão LOCAL, sem senha)
     Atenção: isto NÃO é autenticação segura. Em produção a
     autenticação precisa ser feita no servidor.
     ========================================================= */
  function openSession(user) {
    const session = {
      id: uid("ses"), userId: user.id, login: user.login,
      createdAt: now(), lastSeenAt: now(), type: "local"
    };
    state.sessions[session.id] = session;
    if (NRH2.auth && typeof NRH2.auth.login === "function") {
      try { NRH2.auth.login(user.login); }
      catch (err) { console.warn("[NRH3] Login NRH2 não aplicado:", err); }
    }
    return session;
  }

  const identity = {
    register(data) {
      const user = users.create(data);
      const session = openSession(user);
      emit("identity:registered", { user: clone(user), session: clone(session) });
      save();
      return { user: user, session: clone(session) };
    },
    login(ref) {
      const user = users.get(ref);
      if (!user) throw new Error("Usuário não encontrado.");
      if (user.status !== "active") throw new Error("Conta não está ativa.");
      const session = openSession(user);
      emit("identity:login", { user: clone(user), session: clone(session) });
      save();
      return clone(session);
    },
    logout(sessionId) {
      if (!hasOwn(state.sessions, sessionId)) return false;
      const session = state.sessions[sessionId];
      delete state.sessions[sessionId];
      if (NRH2.auth && typeof NRH2.auth.logout === "function") {
        try { NRH2.auth.logout(); }
        catch (err) { console.warn("[NRH3] Logout NRH2 falhou:", err); }
      }
      emit("identity:logout", { session: clone(session) });
      save();
      return true;
    },
    session(sessionId) {
      return hasOwn(state.sessions, sessionId) ? clone(state.sessions[sessionId]) : null;
    }
  };

  /* =========================================================
     3.13 — AUDITORIA
     ========================================================= */
  const audit = {
    log(action, data) {
      data = data || {};
      const entry = {
        id: uid("audit"),
        action: action,
        timestamp: now(),
        actor: data.actor || null,
        resource: data.resource || null,
        metadata: data.metadata ? clone(data.metadata) : {}
      };
      if (NRH2.activity && typeof NRH2.activity.add === "function") {
        try { NRH2.activity.add(action, entry); }
        catch (err) { console.warn("[NRH3] Não foi possível registrar atividade.", err); }
      }
      emit("audit:event", entry);
      return entry;
    }
  };

  /* =========================================================
     3.14 — EVENTOS AUTOMÁTICOS
     CORREÇÃO: antes dependia de NRH2.on, que não existe no
     Bloco 2 (usa NRH2.events.on) -> a auditoria nunca ligava.
     ========================================================= */
  on("user:created", p => audit.log("user.created", {
    actor: p.user.login, resource: p.user.id, metadata: { login: p.user.login }
  }));
  on("organization:created", p => audit.log("organization.created", {
    actor: p.owner, resource: p.organization.id, metadata: { login: p.organization.login }
  }));
  on("organization:member_added", p => audit.log("organization.member_added", {
    actor: null, resource: p.organization, metadata: { user: p.user, role: p.role }
  }));
  on("repository:collaborator_granted", p => audit.log("repository.collaborator_granted", {
    actor: p.grantedBy, resource: p.repositoryId, metadata: { user: p.user, role: p.role }
  }));

  /* =========================================================
     3.15 — SEED DE DESENVOLVIMENTO
     ========================================================= */
  function seedDevelopmentUsers() {
    if (Object.keys(state.users).length > 0) return;

    let owner;
    try {
      owner = users.create({
        login: "raphael", name: "Raphael",
        bio: "Criador do Neural Raphael Hub",
        company: "Neural Raphael Hub", location: "Brasil", public: true
      });
    } catch (err) {
      console.warn("[NRH3] Seed do usuário principal:", err);
      return;
    }

    [
      { login: "developer", name: "Developer", bio: "Conta de desenvolvimento" },
      { login: "reviewer", name: "Code Reviewer", bio: "Revisão e qualidade de código" },
      { login: "designer", name: "Interface Designer", bio: "Design e experiência" }
    ].forEach(u => {
      try { users.create(Object.assign({ public: true }, u)); }
      catch (err) { console.warn("[NRH3] Seed de", u.login, err); }
    });

    try {
      organizations.create({
        login: "neural-raphael", name: "Neural Raphael",
        description: "Organização principal do Neural Raphael Hub.",
        owner: owner.login, public: true
      });
    } catch (err) {
      console.warn("[NRH3] Seed da organização:", err);
    }
  }

  /* =========================================================
     3.16 — COMPONENTES DE INTERFACE
     ========================================================= */
  const ui = {
    avatar(user, size) {
      user = user || {};
      size = Number(size) || 40;
      const source = safeUrl(user.avatar_url || user.avatar);
      if (source) {
        return '<img src="' + escapeHTML(source) + '" alt="' + escapeHTML(user.login || "") +
          '" width="' + size + '" height="' + size + '" style="width:' + size +
          'px;height:' + size + 'px;border-radius:50%;object-fit:cover;">';
      }
      const letter = escapeHTML((user.name || user.login || "?").charAt(0).toUpperCase());
      // CORREÇÃO: faltava espaço em "<div aria-label" (gerava <divaria-label>)
      return '<div aria-label="' + escapeHTML(user.login || "") + '" style="width:' + size +
        'px;height:' + size + 'px;border-radius:50%;display:flex;align-items:center;' +
        'justify-content:center;font-weight:700;background:linear-gradient(135deg,#6e40c9,#2f81f7);' +
        'color:#fff;">' + letter + '</div>';
    },

    profileCard(ref) {
      const user = users.get(ref);
      if (!user) return '<div class="nrh3-empty">Usuário não encontrado.</div>';
      const stats = user.stats || {};
      return '<article class="nrh3-profile-card" data-user="' + escapeHTML(user.login) + '">' +
        '<div class="nrh3-profile-avatar">' + ui.avatar(user, 72) + '</div>' +
        '<div class="nrh3-profile-body">' +
        '<h3>' + escapeHTML(user.name) + '</h3>' +
        '<div class="nrh3-profile-login">@' + escapeHTML(user.login) + '</div>' +
        (user.bio ? '<p>' + escapeHTML(user.bio) + '</p>' : '') +
        '<div class="nrh3-profile-meta">' +
        (user.location ? '<span>📍 ' + escapeHTML(user.location) + '</span>' : '') +
        (user.company ? '<span>🏢 ' + escapeHTML(user.company) + '</span>' : '') +
        '</div>' +
        '<div class="nrh3-profile-stats">' +
        '<span><strong>' + (stats.repositories || 0) + '</strong> repositórios</span> ' +
        '<span><strong>' + (stats.followers || 0) + '</strong> seguidores</span> ' +
        '<span><strong>' + (stats.following || 0) + '</strong> seguindo</span>' +
        '</div></div></article>';
    },

    organizationCard(ref) {
      const org = organizations.get(ref);
      if (!org) return '<div class="nrh3-empty">Organização não encontrada.</div>';
      const avatar = safeUrl(org.avatar);
      return '<article class="nrh3-organization-card">' +
        '<div class="nrh3-org-avatar">' +
        (avatar
          ? '<img src="' + escapeHTML(avatar) + '" alt="">'
          : '<div>' + escapeHTML(org.name.charAt(0).toUpperCase()) + '</div>') +
        '</div><div>' +
        '<h3>' + escapeHTML(org.name) + '</h3>' +
        '<div>@' + escapeHTML(org.login) + '</div>' +
        '<p>' + escapeHTML(org.description || "") + '</p>' +
        '<small>' + org.stats.members + ' membros · ' + org.stats.repositories +
        ' repositórios</small></div></article>';
    }
  };

  /* =========================================================
     3.17 — COMANDOS
     ========================================================= */
  function currentUserRef() {
    return NRH2.auth && typeof NRH2.auth.current === "function" ? NRH2.auth.current() : null;
  }

  registerCommand("user:profile", {
    label: "Abrir perfil do usuário",
    description: "Localiza e abre o perfil de um usuário.",
    keywords: ["user", "usuario", "perfil", "profile"],
    run(args) {
      const login = args && args[0] ? args[0] : null;
      const user = users.get(login);
      if (!user) throw new Error("Usuário não encontrado.");
      emit("navigation:user", { login: user.login });
      return user;
    }
  });

  registerCommand("organization:list", {
    label: "Listar organizações",
    description: "Lista as organizações disponíveis.",
    keywords: ["organization", "organizacao", "org"],
    run() { return organizations.list(); }
  });

  registerCommand("organization:create", {
    label: "Criar organização",
    description: "Cria uma nova organização.",
    keywords: ["organization", "create", "org"],
    run(args) {
      const login = args && args[0] ? args[0] : global.prompt("Identificador da organização:");
      if (!login) return null;
      // CORREÇÃO: sem fallback fixo "raphael"; usa o usuário autenticado.
      return organizations.create({ login: login, name: login, owner: currentUserRef() });
    }
  });

  /* =========================================================
     3.18 — API PÚBLICA
     ========================================================= */
  const NRH3 = {
    VERSION, ROLES, ROLE_WEIGHT, ROLE_PERMISSIONS,
    state, users, profiles, social, organizations, teams,
    collaborators, access, invitations, identity, audit, ui,
    escapeHTML,
    init() {
      seedDevelopmentUsers();
      emit("nrh3:ready", { version: VERSION });
      console.log("%c[NRH3] Users & Collaboration Engine " + VERSION + " carregado.",
        "color:#58a6ff;font-weight:bold");
      return NRH3;
    }
  };

  global.NRH3 = NRH3;
  NRH3.init();
})(window);
</script>
</script></body></html>
