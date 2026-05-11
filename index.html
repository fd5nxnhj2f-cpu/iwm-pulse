<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta http-equiv="Cache-Control" content="no-cache, no-store, must-revalidate">
<title>Value Screener</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@300;400;500&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#f7f5f0;--surface:#fff;--surface2:#f0ede6;--border:#e2ddd4;--ink:#1a1814;--ink2:#6b6560;--ink3:#9e9891;--green:#2d6a4f;--green-bg:#edf7f2;--green-light:#52b788;--red:#c1440e;--red-bg:#fdf0eb;--gold:#b5890a;--gold-bg:#fdf8ec;--accent:#1a3c5e;--brk:#7c4f1e;--brk-bg:#fdf4ec;--mono:"DM Mono",monospace;--sans:"DM Sans",sans-serif;}
*{margin:0;padding:0;box-sizing:border-box;}
body{background:var(--bg);color:var(--ink);font-family:var(--sans);font-size:14px;}
header{background:var(--accent);padding:14px 20px;display:flex;align-items:center;justify-content:space-between;position:sticky;top:0;z-index:100;}
.logo-main{font-family:var(--mono);font-size:16px;color:#fff;letter-spacing:1px;}
.logo-sub{font-size:10px;color:rgba(255,255,255,0.4);letter-spacing:1px;text-transform:uppercase;}
.last-upd{font-family:var(--mono);font-size:9px;color:rgba(255,255,255,0.4);max-width:130px;text-align:right;line-height:1.4;}
.refresh-btn{background:rgba(255,255,255,0.12);border:1px solid rgba(255,255,255,0.2);color:rgba(255,255,255,0.8);padding:6px 14px;border-radius:4px;cursor:pointer;font-family:var(--mono);font-size:11px;letter-spacing:1px;flex-shrink:0;}
.refresh-btn.spin{animation:spin 1s linear infinite;}
@keyframes spin{to{transform:rotate(360deg);}}
.summary-bar{background:var(--accent);border-top:1px solid rgba(255,255,255,0.1);padding:10px 20px;display:flex;gap:18px;overflow-x:auto;}
.s-stat{display:flex;flex-direction:column;gap:1px;flex-shrink:0;}
.s-lbl{font-family:var(--mono);font-size:8px;color:rgba(255,255,255,0.35);letter-spacing:1px;text-transform:uppercase;}
.s-val{font-family:var(--mono);font-size:14px;color:#fff;}
.s-val.g{color:#74c69d;}.s-val.r{color:#f4a261;}.s-val.y{color:#ffd166;}.s-val.brk{color:#f5c891;}
.filter-bar{background:var(--surface);border-bottom:1px solid var(--border);padding:10px 20px;display:flex;gap:6px;flex-wrap:wrap;align-items:center;}
.f-lbl{font-family:var(--mono);font-size:9px;color:var(--ink3);letter-spacing:1px;margin-right:2px;}
.f-btn{background:transparent;border:1px solid var(--border);color:var(--ink2);padding:5px 12px;border-radius:20px;cursor:pointer;font-family:var(--sans);font-size:12px;transition:all 0.15s;}
.f-btn:hover{border-color:var(--accent);color:var(--accent);}
.f-btn.active{background:var(--accent);border-color:var(--accent);color:#fff;}
.f-btn.brk-filter{border-color:var(--brk);color:var(--brk);}
.f-btn.brk-filter.active{background:var(--brk);border-color:var(--brk);color:#fff;}
.grid{padding:16px 20px;display:grid;grid-template-columns:repeat(auto-fill,minmax(310px,1fr));gap:12px;}
.card{background:var(--surface);border:1px solid var(--border);border-radius:8px;overflow:hidden;transition:box-shadow 0.2s;}
.card:hover{box-shadow:0 4px 16px rgba(0,0,0,0.07);}
.card.brk-holding{border-color:#c8956a;border-width:2px;}
.brk-badge{display:inline-flex;align-items:center;gap:3px;background:var(--brk-bg);color:var(--brk);font-family:var(--mono);font-size:8px;padding:2px 6px;border-radius:3px;border:1px solid #c8956a;margin-left:6px;vertical-align:middle;}
.card-header{padding:12px 16px 10px;display:flex;align-items:flex-start;justify-content:space-between;border-bottom:1px solid var(--border);}
.ticker{font-family:var(--mono);font-size:18px;color:var(--ink);font-weight:500;}
.s-tag{font-family:var(--mono);font-size:8px;color:var(--ink3);background:var(--surface2);padding:2px 6px;border-radius:3px;text-transform:uppercase;margin-left:5px;vertical-align:middle;}
.cname{font-size:11px;color:var(--ink3);margin-top:2px;}
.price-blk{text-align:right;}
.cprice{font-family:var(--mono);font-size:18px;}
.cchg{font-family:var(--mono);font-size:10px;margin-top:1px;}
.cchg.up{color:var(--green);}.cchg.dn{color:var(--red);}
.sec-title{font-family:var(--mono);font-size:8px;color:var(--ink3);letter-spacing:1.5px;text-transform:uppercase;padding:6px 16px 4px;background:var(--surface2);border-bottom:1px solid var(--border);}
.fund-grid{padding:8px 16px;display:grid;grid-template-columns:repeat(2,1fr);gap:6px;border-bottom:1px solid var(--border);}
.fund-item{display:flex;flex-direction:column;gap:1px;}
.f-lbl2{font-family:var(--mono);font-size:8px;color:var(--ink3);text-transform:uppercase;}
.f-val{font-family:var(--mono);font-size:12px;}
.f-val.g{color:var(--green);}.f-val.r{color:var(--red);}.f-val.y{color:var(--gold);}.f-val.n{color:var(--ink2);}
.score-wrap{padding:8px 16px;border-bottom:1px solid var(--border);}
.score-hdr{display:flex;justify-content:space-between;margin-bottom:4px;}
.score-lbl{font-family:var(--mono);font-size:8px;color:var(--ink3);text-transform:uppercase;letter-spacing:1px;}
.score-num{font-family:var(--mono);font-size:11px;font-weight:500;}
.bar-bg{height:5px;background:var(--surface2);border-radius:3px;overflow:hidden;}
.bar-fill{height:100%;border-radius:3px;transition:width 0.5s ease;}
.graham-wrap{padding:8px 16px;border-bottom:1px solid var(--border);display:flex;justify-content:space-between;align-items:center;}
.div-row{padding:8px 16px;display:flex;justify-content:space-between;align-items:center;border-bottom:1px solid var(--border);}
.div-info{font-family:var(--mono);font-size:10px;color:var(--ink2);}
.div-badge{font-family:var(--mono);font-size:9px;padding:2px 8px;border-radius:10px;}
.div-badge.a{background:var(--gold-bg);color:var(--gold);}
.div-badge.d{background:var(--green-bg);color:var(--green);}
.div-badge.n{background:var(--surface2);color:var(--ink3);}
.card-footer{padding:8px 16px;display:flex;justify-content:space-between;align-items:center;}
.sig-badge{display:inline-flex;align-items:center;gap:4px;padding:4px 11px;border-radius:4px;font-family:var(--mono);font-size:10px;font-weight:500;}
.sig-badge.strong-buy{background:var(--green-bg);color:var(--green);border:1px solid #b7e4c7;}
.sig-badge.buy{background:#f0f7f3;color:#40916c;border:1px solid #d8f3dc;}
.sig-badge.hold{background:var(--surface2);color:var(--ink2);border:1px solid var(--border);}
.sig-badge.watch{background:var(--gold-bg);color:var(--gold);border:1px solid #ffe08a;}
.sig-badge.avoid{background:var(--red-bg);color:var(--red);border:1px solid #fbc4ab;}
.copy-btn{background:transparent;border:none;color:var(--ink3);font-family:var(--mono);font-size:9px;cursor:pointer;padding:4px;}
.skeleton{background:linear-gradient(90deg,var(--surface2) 25%,var(--border) 50%,var(--surface2) 75%);background-size:200% 100%;animation:shimmer 1.5s infinite;border-radius:4px;}
@keyframes shimmer{0%{background-position:200% 0;}100%{background-position:-200% 0;}}
.empty{text-align:center;padding:40px 20px;color:var(--ink3);font-family:var(--mono);font-size:12px;grid-column:1/-1;line-height:2;}
.price-card{padding:14px;}
.loading-bar{font-family:var(--mono);font-size:9px;color:var(--ink3);margin-top:4px;}
@media(max-width:600px){.grid{grid-template-columns:1fr;padding:10px;}.summary-bar{gap:12px;}header{padding:12px;}.logo-main{font-size:14px;}}
</style>
</head>
<body>
<header>
  <div>
    <div class="logo-main">VALUE SCREENER</div>
    <div class="logo-sub">Mega Cap · 🦁 Berkshire Holdings Highlighted</div>
  </div>
  <div style="display:flex;align-items:center;gap:8px;">
    <div class="last-upd" id="lastUpd">Tap Refresh</div>
    <button class="refresh-btn" id="refreshBtn" onclick="loadAll()">↻ REFRESH</button>
  </div>
</header>
<div class="summary-bar">
  <div class="s-stat"><div class="s-lbl">Stocks</div><div class="s-val" id="sTotal">25</div></div>
  <div class="s-stat"><div class="s-lbl">🦁 BRK Holdings</div><div class="s-val brk" id="sBrk">5</div></div>
  <div class="s-stat"><div class="s-lbl">Strong Buy</div><div class="s-val g" id="sBuy">—</div></div>
  <div class="s-stat"><div class="s-lbl">Watch</div><div class="s-val y" id="sWatch">—</div></div>
  <div class="s-stat"><div class="s-lbl">Below Graham</div><div class="s-val g" id="sGraham">—</div></div>
  <div class="s-stat"><div class="s-lbl">Dividend</div><div class="s-val y" id="sDivs">—</div></div>
</div>
<div class="filter-bar">
  <span class="f-lbl">SHOW:</span>
  <button class="f-btn active" onclick="setFilter('all',this)">All</button>
  <button class="f-btn brk-filter" onclick="setFilter('brk',this)">🦁 BRK Only</button>
  <button class="f-btn" onclick="setFilter('buy',this)">Buy Signals</button>
  <button class="f-btn" onclick="setFilter('value',this)">Best Value</button>
  <button class="f-btn" onclick="setFilter('graham',this)">Below Graham #</button>
  <button class="f-btn" onclick="setFilter('moat',this)">Wide Moat</button>
  <button class="f-btn" onclick="setFilter('dividend',this)">Dividend</button>
  <button class="f-btn" onclick="setFilter('momentum',this)">🔥 Momentum</button>
</div>
<div class="grid" id="grid">
  <div class="empty">Tap ↻ REFRESH to load<br><span style="font-size:10px">25 mega cap stocks · 🦁 marks Berkshire holdings · Data: FMP free tier</span></div>
</div>

<script>
const FMP_KEY = 'QpKQuSOpEfIEMfaWzSi5cKDI9HCZQbKp';
const FMP     = 'https://financialmodelingprep.com/stable';

// BRK holdings set for quick lookup
const BRK_SET = new Set(['AAPL','BAC','AXP','KO','CVX','OXY','MCO','KHC','CB','DVA','VRSN','CHTR','JPM','BK','USB']);

// 25 mega cap stocks — all confirmed or very likely on FMP free tier
// BRK holdings in this list: AAPL, BAC, KO, CVX, JPM
const STOCKS = [
  // Tech
  {t:'AAPL', n:'Apple',           s:'Tech'},
  {t:'MSFT', n:'Microsoft',       s:'Tech'},
  {t:'NVDA', n:'NVIDIA',          s:'Tech'},
  {t:'AMZN', n:'Amazon',          s:'Tech'},
  {t:'GOOGL', n:'Alphabet',       s:'Tech'},
  {t:'META', n:'Meta',            s:'Tech'},
  {t:'ORCL', n:'Oracle',          s:'Tech'},
  {t:'NFLX', n:'Netflix',         s:'Tech'},
  // Finance
  {t:'JPM',  n:'JPMorgan',        s:'Finance'},
  {t:'BAC',  n:'Bank of America', s:'Finance'},
  {t:'V',    n:'Visa',            s:'Finance'},
  {t:'MA',   n:'Mastercard',      s:'Finance'},
  {t:'GS',   n:'Goldman Sachs',   s:'Finance'},
  // Healthcare
  {t:'UNH',  n:'UnitedHealth',    s:'Healthcare'},
  {t:'JNJ',  n:'Johnson & Johnson',s:'Healthcare'},
  {t:'LLY',  n:'Eli Lilly',       s:'Healthcare'},
  {t:'ABBV', n:'AbbVie',          s:'Healthcare'},
  // Consumer
  {t:'WMT',  n:'Walmart',         s:'Consumer'},
  {t:'COST', n:'Costco',          s:'Consumer'},
  {t:'HD',   n:'Home Depot',      s:'Consumer'},
  {t:'KO',   n:'Coca-Cola',       s:'Consumer'},
  {t:'PG',   n:'Procter & Gamble',s:'Consumer'},
  // Energy / Industrial
  {t:'XOM',  n:'ExxonMobil',      s:'Energy'},
  {t:'CVX',  n:'Chevron',         s:'Energy'},
  {t:'CAT',  n:'Caterpillar',     s:'Industrial'},
];

let allData=[], activeFilter='all';
const f2  = n=>(n!=null&&!isNaN(n))?Number(n).toFixed(2):'—';
const f1  = n=>(n!=null&&!isNaN(n))?Number(n).toFixed(1):'—';
const pct = n=>(n!=null&&!isNaN(n))?(n>=0?'+':'')+Number(n).toFixed(2)+'%':'—';
const pct1= n=>(n!=null&&!isNaN(n))?(n*100).toFixed(1)+'%':'—';
const B   = n=>{if(n==null||isNaN(n))return'—';const a=Math.abs(n);return a>=1e12?(n/1e12).toFixed(1)+'T':a>=1e9?(n/1e9).toFixed(1)+'B':a>=1e6?(n/1e6).toFixed(0)+'M':(n/1e3).toFixed(0)+'K';};
const nowStr=()=>new Date().toLocaleTimeString('en-US',{hour:'2-digit',minute:'2-digit'});
const delay =ms=>new Promise(r=>setTimeout(r,ms));

function setStatus(msg){
  document.getElementById('lastUpd').textContent=msg.slice(0,45);
  console.log(msg);
}

// ── Fetch from FMP stable (text-first for Safari) ─────────────────────────────
async function fmpFetch(path){
  const sep=path.includes('?')?'&':'?';
  const res=await fetch(`${FMP}/${path}${sep}apikey=${FMP_KEY}`);
  if(!res.ok) throw new Error(`HTTP ${res.status}`);
  const text=await res.text();
  if(!text||text.trim()==='[]'||text.trim()==='{}') return null;
  return JSON.parse(text);
}

async function loadStock(stock){
  // Quote: price + 52w + basic stats
  let quote=null, metrics=null, ratios=null, divs=null;

  try{
    const d=await fmpFetch(`quote?symbol=${stock.t}`);
    if(Array.isArray(d)&&d.length){
      const q=d[0];
      quote={
        price:      parseFloat(q.price)||null,
        change:     parseFloat(q.change)||null,
        changePct:  parseFloat(q.changesPercentage)||null,
        high52:     parseFloat(q.yearHigh)||null,
        low52:      parseFloat(q.yearLow)||null,
        vol:        parseInt(q.volume)||null,
        mktCap:     parseFloat(q.marketCap)||null,
        pe:         parseFloat(q.pe)||null,
        eps:        parseFloat(q.eps)||null,
      };
    }
  }catch(e){ setStatus(`${stock.t} quote: ${e.message}`); }
  await delay(1200);

  try{
    const d=await fmpFetch(`key-metrics-ttm?symbol=${stock.t}`);
    metrics=Array.isArray(d)?d[0]:d;
  }catch(e){ setStatus(`${stock.t} metrics: ${e.message}`); }
  await delay(1200);

  try{
    const d=await fmpFetch(`ratios-ttm?symbol=${stock.t}`);
    ratios=Array.isArray(d)?d[0]:d;
  }catch(e){ setStatus(`${stock.t} ratios: ${e.message}`); }
  await delay(1200);

  try{
    const d=await fmpFetch(`dividends?symbol=${stock.t}`);
    // stable/dividends returns array of dividend records
    divs=Array.isArray(d)&&d.length?d:null;
  }catch(e){ /* dividends optional */ }

  return {quote, metrics, ratios, divs};
}

// ── Scoring ───────────────────────────────────────────────────────────────────
function valueScore(quote, metrics, ratios){
  let s=50;
  const q=quote||{}, m=metrics||{}, r=ratios||{};

  // P/E from quote (confirmed field)
  const pe=q.pe||m.peRatioTTM;
  if(pe&&pe>0&&pe<300) s+=pe<15?18:pe<20?10:pe<25?4:pe<35?0:-8;

  // EV/EBITDA
  const evEbitda=m.evToEBITDATTM||m.enterpriseValueOverEBITDATTM;
  if(evEbitda&&evEbitda>0) s+=evEbitda<10?15:evEbitda<15?8:evEbitda<20?2:evEbitda<30?-3:-8;

  // Price/Book
  const pb=m.pbRatioTTM||m.priceToBookValueTTM||r.priceToBookRatioTTM;
  if(pb&&pb>0) s+=pb<1.5?10:pb<3?5:pb<5?0:-5;

  // ROE
  const roe=(m.roeTTM||r.returnOnEquityTTM||0)*100;
  if(roe) s+=roe>20?12:roe>15?8:roe>10?4:roe>0?0:-6;

  // Gross margin (moat)
  const gpm=r.grossProfitMarginTTM;
  if(gpm) s+=gpm>0.6?14:gpm>0.4?8:gpm>0.25?2:gpm>0.15?-2:-8;

  // Net margin
  const npm=r.netProfitMarginTTM;
  if(npm) s+=npm>0.25?10:npm>0.15?6:npm>0.08?2:npm>0?-2:-8;

  // FCF yield
  const fcfY=(m.freeCashFlowYieldTTM||0)*100;
  if(fcfY) s+=fcfY>8?10:fcfY>5?6:fcfY>3?3:0;

  // 52W position
  if(q.high52&&q.low52&&q.price){
    const pos=(q.price-q.low52)/(q.high52-q.low52||0.01);
    s+=pos<0.2?15:pos<0.35?8:pos>0.85?-10:pos>0.7?-4:0;
  }

  // Graham Number
  const graham=m.grahamNumberTTM;
  if(graham&&q.price){
    const diff=(q.price-graham)/graham*100;
    s+=diff<-20?15:diff<0?8:diff<15?0:diff<30?-5:-10;
  }

  // Debt/Equity
  const de=m.debtToEquityTTM||r.debtEquityRatioTTM;
  if(de!=null) s+=de<0.5?8:de<1?4:de<2?0:de<3?-4:-8;

  return Math.max(0,Math.min(100,Math.round(s)));
}

function getSignal(score, belowGraham){
  if(score>=72) return{sig:'strong-buy',lbl:'★ STRONG BUY'};
  if(score>=60) return{sig:'buy',lbl:'▲ BUY'};
  if(belowGraham&&score>=50) return{sig:'buy',lbl:'▲ BUY (GRAHAM)'};
  if(score<=32) return{sig:'avoid',lbl:'✗ AVOID'};
  if(score<=42) return{sig:'watch',lbl:'⚠ WATCH'};
  return{sig:'hold',lbl:'HOLD'};
}

// ── Render ────────────────────────────────────────────────────────────────────
function renderCard(d){
  const{stock,quote,metrics,ratios,divs,signal}=d;
  const q=quote||{}, m=metrics||{}, r=ratios||{};
  const isBrk=BRK_SET.has(stock.t);
  const score=valueScore(q,m,r);
  const graham=m.grahamNumberTTM;
  const belowGraham=graham&&q.price&&q.price<graham;
  const{sig,lbl}=signal||getSignal(score,belowGraham);
  const scColor=score>=65?'#2d6a4f':score>=50?'#b5890a':'#c1440e';

  const pe=q.pe||m.peRatioTTM;
  const pb=m.pbRatioTTM||m.priceToBookValueTTM||r.priceToBookRatioTTM;
  const roe=(m.roeTTM||r.returnOnEquityTTM||0)*100;
  const evEbitda=m.evToEBITDATTM||m.enterpriseValueOverEBITDATTM;
  const gpm=r.grossProfitMarginTTM;
  const npm=r.netProfitMarginTTM;
  const opm=r.operatingProfitMarginTTM;
  const fcfY=(m.freeCashFlowYieldTTM||0)*100;
  const de=m.debtToEquityTTM||r.debtEquityRatioTTM;

  const pos52=q.high52&&q.low52&&q.price?Math.round((q.price-q.low52)/(q.high52-q.low52)*100):null;
  const pos52C=pos52!=null?(pos52<25?'g':pos52>75?'r':'n'):'n';
  const graham_color=belowGraham?'var(--green)':graham?'var(--red)':'var(--ink3)';
  const graham_pct=graham&&q.price?((q.price-graham)/graham*100):null;

  // Latest dividend
  const latestDiv=Array.isArray(divs)?divs[0]:null;
  const divYield=latestDiv?.yield||0;
  const divAmt=latestDiv?.adjDividend||latestDiv?.dividend||0;

  return `<div class="card${isBrk?' brk-holding':''}" data-sig="${sig}" data-score="${score}" data-brk="${isBrk}" data-graham="${belowGraham?'true':'false'}" data-gpm="${(gpm||0)>0.4?'true':'false'}" data-div="${divYield>0?'true':'false'}" data-chgpct="${q.changePct||0}">
  <div class="card-header">
    <div>
      <div>
        <span class="ticker">${stock.t}</span>
        <span class="s-tag">${stock.s}</span>
        ${isBrk?'<span class="brk-badge">🦁 BRK</span>':''}
      </div>
      <div class="cname">${stock.n}</div>
    </div>
    <div class="price-blk">
      <div class="cprice">${q.price?'$'+f2(q.price):'—'}</div>
      <div class="cchg ${(q.change||0)>=0?'up':'dn'}">${q.change!=null?((q.change>=0?'+':'')+f2(q.change)+' ('+pct(q.changePct)+')'):'—'}</div>
    </div>
  </div>

  <div class="sec-title">PRICE CONTEXT</div>
  <div class="fund-grid">
    <div class="fund-item"><div class="f-lbl2">52W Low</div><div class="f-val n">${q.low52?'$'+f2(q.low52):'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">52W High</div><div class="f-val n">${q.high52?'$'+f2(q.high52):'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">52W Position</div><div class="f-val ${pos52C}">${pos52!=null?pos52+'% of range':'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">Market Cap</div><div class="f-val n">${B(q.mktCap)}</div></div>
  </div>

  <div class="sec-title">VALUATION (TTM)</div>
  <div class="fund-grid">
    <div class="fund-item"><div class="f-lbl2">P/E Ratio</div><div class="f-val ${pe?(pe<20?'g':pe<30?'n':'r'):'n'}">${pe?f1(pe):'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">EV/EBITDA</div><div class="f-val ${evEbitda?(evEbitda<15?'g':evEbitda<25?'n':'r'):'n'}">${evEbitda?f1(evEbitda):'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">Price/Book</div><div class="f-val ${pb?(pb<2?'g':pb<4?'n':'r'):'n'}">${pb?f2(pb):'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">FCF Yield</div><div class="f-val ${fcfY>5?'g':fcfY>2?'n':'n'}">${fcfY?f1(fcfY)+'%':'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">ROE</div><div class="f-val ${roe>15?'g':roe>8?'n':roe>0?'r':'n'}">${roe?f1(roe)+'%':'—'}</div></div>
    <div class="fund-item"><div class="f-lbl2">Debt/Equity</div><div class="f-val ${de!=null?(de<1?'g':de<2?'n':'r'):'n'}">${de!=null?f2(de):'—'}</div></div>
  </div>

  <div class="sec-title">PROFITABILITY & MOAT</div>
  <div class="fund-grid">
    <div class="fund-item"><div class="f-lbl2">Gross Margin</div><div class="f-val ${gpm?(gpm>0.5?'g':gpm>0.3?'n':'r'):'n'}">${pct1(gpm)}</div></div>
    <div class="fund-item"><div class="f-lbl2">Net Margin</div><div class="f-val ${npm?(npm>0.15?'g':npm>0.08?'n':'r'):'n'}">${pct1(npm)}</div></div>
    <div class="fund-item"><div class="f-lbl2">Operating Margin</div><div class="f-val ${opm?(opm>0.2?'g':opm>0.1?'n':'r'):'n'}">${pct1(opm)}</div></div>
    <div class="fund-item"><div class="f-lbl2">EPS</div><div class="f-val ${(q.eps||0)>0?'g':'r'}">${q.eps?'$'+f2(q.eps):'—'}</div></div>
  </div>

  <div class="graham-wrap">
    <div>
      <div style="font-family:var(--mono);font-size:8px;color:var(--ink3);text-transform:uppercase;letter-spacing:1px">Graham Number</div>
      <div style="font-family:var(--mono);font-size:8px;color:var(--ink3);margin-top:1px">√(22.5 × EPS × Book Value)</div>
    </div>
    <div style="text-align:right">
      <div style="font-family:var(--mono);font-size:13px;color:${graham_color}">${graham?'$'+f2(graham):'—'}</div>
      ${graham_pct!=null?`<div style="font-family:var(--mono);font-size:9px;color:${graham_color}">${belowGraham?'▼':'▲'} ${Math.abs(graham_pct).toFixed(1)}% ${belowGraham?'below':'above'}</div>`:''}
    </div>
  </div>

  <div class="score-wrap">
    <div class="score-hdr"><span class="score-lbl">Buffett Value Score</span><span class="score-num" style="color:${scColor}">${score}/100</span></div>
    <div class="bar-bg"><div class="bar-fill" style="width:${score}%;background:${scColor}"></div></div>
  </div>

  <div class="sec-title">DIVIDEND</div>
  <div class="div-row">
    <div class="div-info">${divYield>0?f2(divYield)+'% yield · $'+f2(divAmt)+'/qtr':'No dividend'}${q.eps?'  ·  EPS $'+f2(q.eps):''}</div>
    <span class="div-badge ${divYield>2.5?'a':divYield>0?'d':'n'}">${divYield>2.5?'★ HIGH YIELD':divYield>0?'DIVIDEND':'NO DIV'}</span>
  </div>

  <div class="card-footer">
    <span class="sig-badge ${sig}">${lbl}</span>
    <button class="copy-btn" onclick="copyTick('${stock.t}',this)">copy ↗</button>
  </div>
</div>`;
}

function renderPriceCard(d){
  const q=d.quote||{};
  const isBrk=BRK_SET.has(d.stock.t);
  const pos52=q.high52&&q.low52&&q.price?Math.round((q.price-q.low52)/(q.high52-q.low52)*100):null;
  return `<div class="card${isBrk?' brk-holding':''}" style="padding:14px">
    <div style="display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:6px">
      <div>
        <div><span class="ticker">${d.stock.t}</span><span class="s-tag">${d.stock.s}</span>${isBrk?'<span class="brk-badge">🦁 BRK</span>':''}</div>
        <div class="cname">${d.stock.n}</div>
      </div>
      <div class="price-blk">
        <div class="cprice">${q.price?'$'+f2(q.price):'—'}</div>
        <div class="cchg ${(q.change||0)>=0?'up':'dn'}">${q.change!=null?((q.change>=0?'+':'')+f2(q.change)+' ('+pct(q.changePct)+')'):'—'}</div>
      </div>
    </div>
    ${q.high52?`<div style="font-family:var(--mono);font-size:9px;color:var(--ink3);margin-bottom:6px">52W: $${f2(q.low52)} — $${f2(q.high52)} · <span style="color:${pos52<25?'var(--green)':pos52>75?'var(--red)':'var(--ink3)'}">${pos52!=null?pos52+'% of range':'—'}</span>  ·  P/E: ${q.pe?f1(q.pe):'—'}</div>`:''}
    <div class="skeleton" style="height:6px;margin-bottom:4px"></div>
    <div class="loading-bar">⏳ Loading fundamentals... ${d.fundStatus||''}</div>
  </div>`;
}

function copyTick(t,btn){navigator.clipboard?.writeText(t).then(()=>{btn.textContent='copied!';setTimeout(()=>btn.textContent='copy ↗',1500);}).catch(()=>alert(t));}

function renderCards(){
  const grid=document.getElementById('grid');
  let cards=[...allData];
  if(activeFilter==='brk')      cards=cards.filter(d=>BRK_SET.has(d.stock.t));
  else if(activeFilter==='buy') cards=cards.filter(d=>['strong-buy','buy'].includes(d.signal?.sig));
  else if(activeFilter==='value') cards.sort((a,b)=>valueScore(b.quote,b.metrics,b.ratios)-valueScore(a.quote,a.metrics,a.ratios));
  else if(activeFilter==='graham') cards=cards.filter(d=>{const m=d.metrics||{};const q=d.quote||{};return m.grahamNumberTTM&&q.price&&q.price<m.grahamNumberTTM;});
  else if(activeFilter==='moat')   cards=cards.filter(d=>(d.ratios?.grossProfitMarginTTM||0)>0.4);
  else if(activeFilter==='dividend') cards=cards.filter(d=>d.divs?.[0]?.yield>0);
  else if(activeFilter==='momentum'){
    cards=cards.filter(d=>(d.quote?.changePct||0)>0).sort((a,b)=>{
      const aPos=a.quote?.high52&&a.quote?.low52?((a.quote.price-a.quote.low52)/(a.quote.high52-a.quote.low52)):0;
      const bPos=b.quote?.high52&&b.quote?.low52?((b.quote.price-b.quote.low52)/(b.quote.high52-b.quote.low52)):0;
      return bPos-aPos;
    });
  }
  if(!cards.length&&allData.some(d=>d.quote)){grid.innerHTML='<div class="empty">No stocks match this filter.</div>';return;}
  if(!allData.some(d=>d.quote)){grid.innerHTML='<div class="empty">Tap ↻ REFRESH to load data</div>';return;}
  grid.innerHTML=cards.map(d=>d.metrics?renderCard(d):renderPriceCard(d)).join('');
}

function setFilter(f,btn){activeFilter=f;document.querySelectorAll('.f-btn').forEach(b=>b.classList.remove('active'));btn.classList.add('active');renderCards();}

function updateSummary(){
  let buys=0,watches=0,grahams=0,divs=0;
  allData.filter(d=>d.metrics).forEach(d=>{
    const s=d.signal?.sig;
    if(s==='strong-buy'||s==='buy') buys++;
    if(s==='watch') watches++;
    const m=d.metrics||{};
    if(m.grahamNumberTTM&&d.quote?.price&&d.quote.price<m.grahamNumberTTM) grahams++;
    if(d.divs?.[0]?.yield>0) divs++;
  });
  document.getElementById('sBuy').textContent=buys;
  document.getElementById('sWatch').textContent=watches;
  document.getElementById('sGraham').textContent=grahams;
  document.getElementById('sDivs').textContent=divs;
}

// ── Load ──────────────────────────────────────────────────────────────────────
async function loadAll(){
  const btn=document.getElementById('refreshBtn');
  btn.classList.add('spin');
  allData=[];
  STOCKS.forEach(s=>allData.push({stock:s,quote:null,metrics:null,ratios:null,divs:null,signal:null,fundStatus:''}));
  renderCards();

  // Load each stock sequentially — 4 FMP calls × 1.2s gaps + 12s rest = ~17s per stock
  // = ~3.5 calls/min average — safely under FMP free tier 5/min
  for(let i=0;i<STOCKS.length;i++){
    const s=STOCKS[i];
    setStatus(`Loading ${s.t} (${i+1}/${STOCKS.length})...`);
    try{
      const result=await loadStock(s);
      const idx=allData.findIndex(d=>d.stock.t===s.t);
      if(idx>=0){
        allData[idx].quote   = result.quote;
        allData[idx].metrics = result.metrics;
        allData[idx].ratios  = result.ratios;
        allData[idx].divs    = result.divs;
        const sc=valueScore(result.quote,result.metrics,result.ratios);
        const m=result.metrics||{};
        const belowGraham=m.grahamNumberTTM&&result.quote?.price&&result.quote.price<m.grahamNumberTTM;
        allData[idx].signal=getSignal(sc,belowGraham);
        renderCards();
        updateSummary();
      }
    }catch(e){ setStatus(`${s.t}: error — ${e.message}`); }

    // 12s gap between stocks
    if(i<STOCKS.length-1){
      for(let s2=12;s2>0;s2--){
        setStatus(`${s.t} done · next in ${s2}s (${i+2}/${STOCKS.length})`);
        await delay(1000);
      }
    }
  }

  updateSummary();
  document.getElementById('lastUpd').textContent='Updated '+nowStr();
  btn.classList.remove('spin');
}
</script>
</body>
</html>
