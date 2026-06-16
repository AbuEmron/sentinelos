<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover" />
<title>SENTINEL OS — Operating System for Private Security</title>
<meta name="theme-color" content="#0B2A4A" />
<link rel="manifest" href="manifest.webmanifest" />
<style>
  :root{
    --navy:#0B2A4A; --navy2:#123A63; --blue:#1F6FB2; --ice:#E8F1F9; --ice2:#D3E3F1;
    --amber:#F2A900; --green:#3E8E5A; --red:#C0392B; --grey:#5A6B7B; --dgrey:#2c3a47;
    --bg:#f4f7fb; --card:#ffffff; --line:#e2e9f1; --shadow:0 6px 20px rgba(11,42,74,.08);
  }
  *{box-sizing:border-box;margin:0;padding:0}
  body{font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;background:var(--bg);color:var(--dgrey);-webkit-font-smoothing:antialiased}
  a{color:inherit;text-decoration:none}
  /* top bar */
  header{position:sticky;top:0;z-index:50;background:var(--navy);color:#fff;display:flex;align-items:center;gap:16px;padding:12px 20px;box-shadow:0 2px 10px rgba(0,0,0,.18)}
  .brand{display:flex;align-items:center;gap:10px;font-weight:800;letter-spacing:.5px;font-size:18px}
  .brand .dot{width:12px;height:12px;border-radius:3px;background:var(--amber)}
  .brand small{font-weight:500;color:var(--ice2);letter-spacing:2px;font-size:9px;display:block;margin-top:1px}
  .grow{flex:1}
  .status-pill{display:flex;align-items:center;gap:6px;font-size:12px;color:var(--ice);background:rgba(255,255,255,.08);padding:5px 11px;border-radius:20px}
  .live{width:8px;height:8px;border-radius:50%;background:#46d369;box-shadow:0 0 0 0 rgba(70,211,105,.6);animation:pulse 2s infinite}
  @keyframes pulse{0%{box-shadow:0 0 0 0 rgba(70,211,105,.6)}70%{box-shadow:0 0 0 8px rgba(70,211,105,0)}100%{box-shadow:0 0 0 0 rgba(70,211,105,0)}}
  .roles{display:flex;background:rgba(255,255,255,.08);border-radius:10px;padding:3px}
  .roles button{background:none;border:0;color:var(--ice2);font-weight:600;font-size:13px;padding:7px 14px;border-radius:8px;cursor:pointer;transition:.15s}
  .roles button.on{background:var(--amber);color:var(--navy)}
  .wrap{max-width:1180px;margin:0 auto;padding:22px 20px 60px}
  .view{display:none;animation:fade .3s}
  .view.on{display:block}
  @keyframes fade{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:none}}
  h2.section{font-size:13px;text-transform:uppercase;letter-spacing:2px;color:var(--blue);font-weight:700;margin:26px 4px 12px}
  h2.section:first-child{margin-top:6px}
  .page-head{display:flex;align-items:baseline;gap:12px;flex-wrap:wrap;margin-bottom:4px}
  .page-head h1{font-size:24px;color:var(--navy)}
  .page-head .sub{color:var(--grey);font-size:14px}
  /* kpi */
  .kpis{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:14px}
  .kpi{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:16px 18px;box-shadow:var(--shadow)}
  .kpi .label{font-size:12px;color:var(--grey);font-weight:600;text-transform:uppercase;letter-spacing:.5px}
  .kpi .val{font-size:30px;font-weight:800;color:var(--navy);margin-top:6px;line-height:1}
  .kpi .meta{font-size:12px;margin-top:7px;font-weight:600}
  .up{color:var(--green)} .down{color:var(--red)} .warn{color:var(--amber)}
  .grid2{display:grid;grid-template-columns:1.6fr 1fr;gap:16px}
  @media(max-width:880px){.grid2{grid-template-columns:1fr}}
  .card{background:var(--card);border:1px solid var(--line);border-radius:14px;box-shadow:var(--shadow);overflow:hidden}
  .card h3{font-size:15px;color:var(--navy);padding:15px 18px;border-bottom:1px solid var(--line);display:flex;align-items:center;gap:8px}
  .card .body{padding:6px 0}
  table{width:100%;border-collapse:collapse;font-size:13.5px}
  th{text-align:left;color:var(--grey);font-weight:600;font-size:11px;text-transform:uppercase;letter-spacing:.5px;padding:9px 18px}
  td{padding:11px 18px;border-top:1px solid var(--line)}
  tr:hover td{background:#fafcfe}
  .tag{display:inline-block;font-size:11px;font-weight:700;padding:3px 9px;border-radius:20px}
  .t-green{background:#e7f4ec;color:var(--green)} .t-amber{background:#fdf2da;color:#a9760a}
  .t-red{background:#fbe9e7;color:var(--red)} .t-blue{background:#e7f0f9;color:var(--blue)} .t-grey{background:#eef2f6;color:var(--grey)}
  .bar{height:7px;border-radius:6px;background:var(--ice);overflow:hidden}
  .bar > i{display:block;height:100%;border-radius:6px}
  .ai-item{padding:12px 18px;border-top:1px solid var(--line);display:flex;gap:12px;align-items:flex-start}
  .ai-item:first-child{border-top:0}
  .ai-ico{flex:none;width:34px;height:34px;border-radius:9px;display:flex;align-items:center;justify-content:center;font-size:15px;color:#fff}
  .ai-item .txt{flex:1}
  .ai-item .txt b{color:var(--navy);font-size:13.5px}
  .ai-item .txt p{font-size:12.5px;color:var(--grey);margin-top:2px;line-height:1.4}
  .ai-item .rec{font-size:12px;color:var(--blue);font-weight:600;margin-top:4px}
  .muted{color:var(--grey);font-size:12.5px}
  /* officer */
  .ocard{background:linear-gradient(135deg,var(--navy),var(--navy2));color:#fff;border-radius:16px;padding:20px;display:flex;gap:18px;align-items:center;box-shadow:var(--shadow)}
  .avatar{width:64px;height:64px;border-radius:16px;background:var(--amber);color:var(--navy);font-weight:800;font-size:24px;display:flex;align-items:center;justify-content:center}
  .ocard .nm{font-size:20px;font-weight:800}
  .ocard .rk{color:var(--ice2);font-size:13px;margin-top:2px}
  .ocard .pts{margin-left:auto;text-align:right}
  .ocard .pts b{font-size:26px;color:var(--amber);font-weight:800}
  .ocard .pts span{display:block;font-size:11px;color:var(--ice2);letter-spacing:1px}
  .ogrid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:14px;margin-top:14px}
  .obox{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:16px;box-shadow:var(--shadow)}
  .obox .h{font-size:12px;text-transform:uppercase;letter-spacing:.5px;color:var(--grey);font-weight:700;margin-bottom:8px}
  .btn{display:inline-flex;align-items:center;justify-content:center;gap:7px;border:0;border-radius:10px;padding:11px 16px;font-weight:700;font-size:14px;cursor:pointer;transition:.15s}
  .btn-amber{background:var(--amber);color:var(--navy)} .btn-amber:hover{filter:brightness(1.05)}
  .btn-navy{background:var(--navy);color:#fff} .btn-red{background:var(--red);color:#fff;width:100%;padding:15px}
  .btn-ghost{background:var(--ice);color:var(--navy)}
  .chip{display:inline-flex;align-items:center;gap:6px;background:var(--ice);color:var(--navy);border-radius:20px;padding:6px 12px;font-size:12.5px;font-weight:600;margin:3px 4px 3px 0}
  .badge{display:flex;gap:10px;align-items:center;padding:10px 0;border-top:1px solid var(--line)}
  .badge:first-child{border-top:0}
  .badge .b-ico{width:36px;height:36px;border-radius:50%;background:#fdf2da;color:#a9760a;display:flex;align-items:center;justify-content:center;font-size:16px;flex:none}
  /* form */
  .field{margin:10px 0}
  .field label{font-size:12px;font-weight:600;color:var(--grey);display:block;margin-bottom:4px}
  .field select,.field input,.field textarea{width:100%;border:1px solid var(--line);border-radius:9px;padding:10px 12px;font-size:14px;font-family:inherit;color:var(--dgrey)}
  .field textarea{resize:vertical;min-height:70px}
  .toast{position:fixed;bottom:20px;left:50%;transform:translateX(-50%) translateY(80px);background:var(--navy);color:#fff;padding:13px 20px;border-radius:12px;box-shadow:0 8px 30px rgba(0,0,0,.25);font-weight:600;font-size:14px;opacity:0;transition:.35s;z-index:100}
  .toast.show{transform:translateX(-50%) translateY(0);opacity:1}
  .toast.err{background:var(--red)}
  footer{text-align:center;color:var(--grey);font-size:12px;padding:24px}
  .legend{font-size:11px;color:var(--grey);padding:10px 18px}
  .online-dot{width:8px;height:8px;border-radius:50%;display:inline-block;margin-right:6px}
</style>
</head>
<body>
<header>
  <div class="brand"><span class="dot"></span><div>SENTINEL&nbsp;OS<small>OPERATING SYSTEM FOR PRIVATE SECURITY</small></div></div>
  <div class="grow"></div>
  <div class="status-pill"><span id="db-dot" class="live"></span><span id="db-status">Connecting…</span></div>
  <div class="roles" id="roles">
    <button data-r="ops" class="on">Operations</button>
    <button data-r="officer">Officer</button>
    <button data-r="client">Client</button>
  </div>
</header>

<div class="wrap">
  <!-- ============ OPS ============ -->
  <section id="v-ops" class="view on">
    <div class="page-head"><h1>Operations Command</h1><span class="sub" id="ops-org">Vanguard Protective Services · live</span></div>
    <div class="kpis" id="ops-kpis"></div>

    <div class="grid2" style="margin-top:18px">
      <div class="card">
        <h3>🛡️ Live Post Coverage <span class="muted" style="margin-left:auto;font-weight:500" id="ops-now"></span></h3>
        <div class="body"><table id="ops-shifts"><thead><tr><th>Site</th><th>Officer</th><th>Shift</th><th>Status</th></tr></thead><tbody></tbody></table></div>
      </div>
      <div class="card">
        <h3>🤖 SENTINEL AI — Risk Radar</h3>
        <div class="body" id="ops-ai"></div>
        <div class="legend">Predictions from operational data · each ships with a recommended action.</div>
      </div>
    </div>

    <h2 class="section">Recent Incidents</h2>
    <div class="card"><div class="body"><table id="ops-incidents"><thead><tr><th>When</th><th>Site</th><th>Type</th><th>Severity</th><th>Status</th></tr></thead><tbody></tbody></table></div></div>
  </section>

  <!-- ============ OFFICER ============ -->
  <section id="v-officer" class="view">
    <div class="page-head"><h1>My Shift</h1><span class="sub">The platform built for the officer</span></div>
    <div class="ocard" id="off-card"></div>
    <div class="ogrid">
      <div class="obox">
        <div class="h">Tonight's Post</div>
        <div id="off-shift"></div>
        <div class="bar" style="margin-top:12px"><i id="off-tourbar" style="width:62%;background:var(--green)"></i></div>
        <div class="muted" style="margin-top:6px" id="off-tour">Tour 5 of 8 checkpoints</div>
        <button class="btn btn-amber" style="margin-top:12px;width:100%" onclick="toast('Checkpoint scanned ✓ — synced')">Scan Next Checkpoint</button>
      </div>
      <div class="obox">
        <div class="h">💸 Instant Pay</div>
        <div style="font-size:30px;font-weight:800;color:var(--navy)" id="off-pay">$284.50</div>
        <div class="muted">Earned this week · available now</div>
        <button class="btn btn-navy" style="margin-top:12px;width:100%" onclick="toast('Transfer initiated — funds in minutes')">Cash Out Earned Pay</button>
      </div>
      <div class="obox">
        <div class="h">🏅 Recognition</div>
        <div id="off-badges"></div>
      </div>
      <div class="obox">
        <div class="h">🎓 Career & Compliance</div>
        <div id="off-certs"></div>
        <div class="chip">Next rank: Officer III · 160 pts to go</div>
      </div>
      <div class="obox" style="display:flex;flex-direction:column;justify-content:center">
        <div class="h">Emergency</div>
        <button class="btn btn-red" onclick="toast('🚨 SOS sent — dispatch + live location shared','err')">🚨 One-Tap SOS</button>
        <div class="muted" style="margin-top:8px;text-align:center">Auto check-in every 30 min</div>
      </div>
    </div>
  </section>

  <!-- ============ CLIENT ============ -->
  <section id="v-client" class="view">
    <div class="page-head"><h1>Client Portal</h1><span class="sub" id="cli-name">Mercy General Hospital</span></div>
    <div class="kpis" id="cli-kpis"></div>
    <div class="grid2" style="margin-top:18px">
      <div class="card">
        <h3>📍 On-Site Right Now</h3>
        <div class="body"><table id="cli-onsite"><thead><tr><th>Officer</th><th>Site</th><th>Since</th><th>Status</th></tr></thead><tbody></tbody></table></div>
      </div>
      <div class="card">
        <h3>📣 Report an Incident</h3>
        <div class="body" style="padding:14px 18px">
          <div class="field"><label>Type</label><select id="f-type"><option>Suspicious Activity</option><option>Trespass</option><option>Medical</option><option>Theft</option><option>Vandalism</option><option>Other</option></select></div>
          <div class="field"><label>Severity</label><select id="f-sev"><option value="low">Low</option><option value="medium">Medium</option><option value="high">High</option><option value="critical">Critical</option></select></div>
          <div class="field"><label>What happened?</label><textarea id="f-sum" placeholder="Describe the incident…"></textarea></div>
          <button class="btn btn-amber" style="width:100%" onclick="submitIncident()">Submit — logged live to SENTINEL OS</button>
        </div>
      </div>
    </div>
    <h2 class="section">Incident Transparency Feed</h2>
    <div class="card"><div class="body"><table id="cli-incidents"><thead><tr><th>When</th><th>Type</th><th>Severity</th><th>Summary</th><th>Status</th></tr></thead><tbody></tbody></table></div></div>
  </section>
</div>

<div class="toast" id="toast"></div>
<footer>SENTINEL OS · MVP demo · live data via Supabase · deployed on Vercel</footer>

<script type="module">
import { createClient } from 'https://esm.sh/@supabase/supabase-js@2';

const CFG = {
  url: 'https://jlpeplcxjrdycbnxjhzj.supabase.co',
  key: 'sb_publishable_hkpiYV7zjICp3uOWE6RPUw_hkz3yz0x',
  org: '00000000-0000-0000-0000-0000000000aa'
};
const sb = createClient(CFG.url, CFG.key);
const $ = s => document.querySelector(s);
const fmt$ = n => '$'+Number(n||0).toLocaleString();
const timeStr = d => new Date(d).toLocaleTimeString([], {hour:'numeric',minute:'2-digit'});
const dayAgo = d => { const h=(Date.now()-new Date(d))/3.6e6; return h<1?Math.round(h*60)+'m ago':h<24?Math.round(h)+'h ago':Math.round(h/24)+'d ago'; };
const sevTag = s => ({low:'t-grey',medium:'t-amber',high:'t-red',critical:'t-red'}[s]||'t-grey');
const stTag = s => ({open:'t-red',investigating:'t-amber',resolved:'t-green',scheduled:'t-blue',checked_in:'t-green'}[s]||'t-grey');
window.toast = (m,k='')=>{const t=$('#toast');t.textContent=m;t.className='toast show '+k;setTimeout(()=>t.className='toast '+k,2600);};

// ---- demo fallback (keeps deployed site alive even if DB unreachable) ----
const DEMO = {
  officers:[{full_name:'Marcus Bell',rank:'Officer III',turnover_risk:12,reliability_score:97,recognition_points:1840},
    {full_name:'Tanya Whitfield',rank:'Officer I',turnover_risk:71,reliability_score:79,recognition_points:210},
    {full_name:'Ray Okafor',rank:'Officer II',turnover_risk:58,reliability_score:84,recognition_points:540},
    {full_name:'Aisha Rahman',rank:'Sergeant',turnover_risk:9,reliability_score:95,recognition_points:2610}],
  clients:[{name:'Mercy General Hospital',segment:'Healthcare',churn_score:62},{name:'Harbor Logistics Park',segment:'Industrial',churn_score:18},{name:'Summit Corporate Tower',segment:'Corporate',churn_score:9}],
  shifts:[], incidents:[], certifications:[]
};

let state = {};
async function load(){
  try{
    const q = t => sb.from(t).select('*').eq('org_id',CFG.org);
    const [off,cli,sit,con,inc,cer,ach,inv] = await Promise.all([
      q('officers'), q('clients'), q('sites'), q('contracts'),
      sb.from('incidents').select('*').eq('org_id',CFG.org).order('occurred_at',{ascending:false}),
      q('certifications'), q('achievements'), q('invoices')
    ]);
    const sh = await sb.from('shifts').select('*').eq('org_id',CFG.org).order('starts_at');
    if(off.error) throw off.error;
    state = {officers:off.data||[],clients:cli.data||[],sites:sit.data||[],contracts:con.data||[],
      incidents:inc.data||[],certs:cer.data||[],achievements:ach.data||[],invoices:inv.data||[],shifts:sh.data||[]};
    $('#db-status').textContent='Live · Supabase'; $('#db-dot').style.background='#46d369';
  }catch(e){
    console.warn('Falling back to demo data:',e.message);
    state = {officers:DEMO.officers,clients:DEMO.clients,sites:[],contracts:[],incidents:DEMO.incidents,certs:[],achievements:[],invoices:[],shifts:[]};
    $('#db-status').textContent='Demo mode'; $('#db-dot').style.background='#F2A900';
  }
  renderOps(); renderOfficer(); renderClient();
}
const siteName = id => (state.sites.find(s=>s.id===id)||{}).name || '—';
const offName = id => (state.officers.find(o=>o.id===id)||{}).full_name || 'OPEN POST';

// ---------- OPS ----------
function renderOps(){
  $('#ops-now').textContent = new Date().toLocaleDateString([], {weekday:'short',month:'short',day:'numeric'});
  const active = state.shifts.filter(s=>s.status==='checked_in').length;
  const open = state.shifts.filter(s=>s.status==='open').length;
  const total = state.shifts.length||1;
  const cover = Math.round(((total-open)/total)*100);
  const ot = state.shifts.filter(s=>s.is_overtime).reduce((a,s)=>a+8*((s.pay_rate||0)),0);
  const openInc = state.incidents.filter(i=>i.status!=='resolved').length;
  const bill = state.invoices.find(i=>i.status==='sent')?.amount || 498100;
  const kpis=[
    ['Officers On Post',active,'+'+active+' checked in','up'],
    ['Coverage',cover+'%',open+' open post(s)',open?'down':'up'],
    ['OT Exposure (today)',fmt$(ot),'AI: reduce 40% → $250K/yr','warn'],
    ['Open Incidents',openInc,openInc?'needs review':'all clear',openInc?'warn':'up'],
    ['Billing (Jun)',fmt$(bill),'on track','up'],
  ];
  $('#ops-kpis').innerHTML = kpis.map(k=>`<div class="kpi"><div class="label">${k[0]}</div><div class="val">${k[1]}</div><div class="meta ${k[3]}">${k[2]}</div></div>`).join('');

  $('#ops-shifts tbody').innerHTML = state.shifts.length? state.shifts.map(s=>`<tr>
    <td><b>${siteName(s.site_id)}</b></td><td>${offName(s.officer_id)}</td>
    <td>${timeStr(s.starts_at)}–${timeStr(s.ends_at)}${s.is_overtime?' <span class="tag t-amber">OT</span>':''}</td>
    <td><span class="tag ${stTag(s.status)}">${s.status.replace('_',' ')}</span></td></tr>`).join('')
    : `<tr><td colspan="4" class="muted" style="padding:18px">No shifts loaded.</td></tr>`;

  // AI radar
  const ai=[];
  const risky = [...state.officers].sort((a,b)=>b.turnover_risk-a.turnover_risk).filter(o=>o.turnover_risk>=45).slice(0,2);
  risky.forEach(o=>ai.push(['#C0392B','⚠️',`${o.full_name} — ${o.turnover_risk}% turnover risk`,
    `Reliability ${o.reliability_score}, low recognition points, recent OT clustering.`,
    'Offer closer post + recognition; manager 1:1 this week.']));
  const churn = [...state.clients].sort((a,b)=>b.churn_score-a.churn_score).filter(c=>c.churn_score>=40)[0];
  if(churn) ai.push(['#1F6FB2','📉',`${churn.name} — ${churn.churn_score}% churn risk`,
    `Incident volume up, renewal approaching, SLA pressure.`,'Schedule QBR; share ROI report + add patrol upsell.']);
  const expCerts = state.certs.filter(c=>{const d=(new Date(c.expires_on)-Date.now())/8.64e7; return d<30;});
  if(expCerts.length) ai.push(['#F2A900','📋',`${expCerts.length} certification(s) expiring < 30 days`,
    `Officers on post risk a compliance lapse and liability exposure.`,'Auto-reminders sent; block scheduling until renewed.']);
  if(!ai.length) ai.push(['#3E8E5A','✓','No critical risks detected','Workforce, clients, and compliance all nominal.','Maintain current coverage plan.']);
  $('#ops-ai').innerHTML = ai.map(a=>`<div class="ai-item"><div class="ai-ico" style="background:${a[0]}">${a[1]}</div>
    <div class="txt"><b>${a[2]}</b><p>${a[3]}</p><div class="rec">→ ${a[4]}</div></div></div>`).join('');

  $('#ops-incidents tbody').innerHTML = (state.incidents.slice(0,6)).map(i=>`<tr>
    <td class="muted">${dayAgo(i.occurred_at)}</td><td>${siteName(i.site_id)}</td><td><b>${i.type}</b></td>
    <td><span class="tag ${sevTag(i.severity)}">${i.severity}</span></td>
    <td><span class="tag ${stTag(i.status)}">${i.status}</span></td></tr>`).join('')
    || `<tr><td colspan="5" class="muted" style="padding:18px">No incidents.</td></tr>`;
}

// ---------- OFFICER ----------
function renderOfficer(){
  const o = state.officers.find(x=>x.full_name==='Marcus Bell') || state.officers[0] || DEMO.officers[0];
  const initials = o.full_name.split(' ').map(w=>w[0]).join('').slice(0,2);
  $('#off-card').innerHTML = `<div class="avatar">${initials}</div>
    <div><div class="nm">${o.full_name}</div><div class="rk">${o.rank} · Badge ${o.badge_no||'VG-1042'} · Reliability ${o.reliability_score}%</div></div>
    <div class="pts"><b>${(o.recognition_points||0).toLocaleString()}</b><span>POINTS</span></div>`;
  const myShift = state.shifts.find(s=>s.officer_id===o.id);
  $('#off-shift').innerHTML = myShift
    ? `<b style="color:var(--navy)">${siteName(myShift.site_id)}</b><div class="muted">${timeStr(myShift.starts_at)} – ${timeStr(myShift.ends_at)}</div>`
    : `<b style="color:var(--navy)">Mercy General — Main Campus</b><div class="muted">19:00 – 07:00</div>`;
  const badges = state.achievements.length? state.achievements : [{badge:'Client Commendation',note:'Praised for ED incident'},{badge:'100-Shift Streak',note:'No missed shifts'}];
  $('#off-badges').innerHTML = badges.slice(0,3).map(b=>`<div class="badge"><div class="b-ico">🏅</div><div><b style="font-size:13px;color:var(--navy)">${b.badge}</b><div class="muted">${b.note||''}</div></div></div>`).join('');
  const certs = state.certs.filter(c=>c.officer_id===o.id);
  const cstat = c=>{const d=(new Date(c.expires_on)-Date.now())/8.64e7; return d<0?['t-red','expired']:d<30?['t-amber','expiring']:['t-green','valid'];};
  $('#off-certs').innerHTML = (certs.length?certs:[{type:'Guard Card',expires_on:'2027-04-01'},{type:'CPR/BLS',expires_on:'2026-07-02'}])
    .map(c=>{const[cl,lb]=cstat(c);return `<span class="chip">${c.type} <span class="tag ${cl}">${lb}</span></span>`;}).join('');
}

// ---------- CLIENT ----------
function renderClient(){
  const c = state.clients.find(x=>x.name==='Mercy General Hospital') || state.clients[0] || DEMO.clients[0];
  $('#cli-name').textContent = c.name+' · live portal';
  const mySites = state.sites.filter(s=>s.client_id===c.id).map(s=>s.id);
  const onsite = state.shifts.filter(s=>mySites.includes(s.site_id) && s.status==='checked_in');
  const myInc = state.incidents.filter(i=>mySites.includes(i.site_id));
  const con = state.contracts.find(k=>k.client_id===c.id);
  const kpis=[
    ['Officers On Site',onsite.length||2,'verified by GPS','up'],
    ['Coverage This Month','99.4%','SLA target 98%','up'],
    ['Incidents Logged',myInc.length||2,'full transparency','up'],
    ['Contract Value/mo',con?fmt$(con.bill_rate*con.hours_per_week*4.33):'$55.4K','renews '+(con?.renewal_date||'Aug 2026'),'up'],
  ];
  $('#cli-kpis').innerHTML = kpis.map(k=>`<div class="kpi"><div class="label">${k[0]}</div><div class="val">${k[1]}</div><div class="meta ${k[3]}">${k[2]}</div></div>`).join('');
  $('#cli-onsite tbody').innerHTML = (onsite.length?onsite:state.shifts.filter(s=>s.status==='checked_in')).slice(0,5).map(s=>`<tr>
    <td><b>${offName(s.officer_id)}</b></td><td>${siteName(s.site_id)}</td><td class="muted">${timeStr(s.starts_at)}</td>
    <td><span class="online-dot" style="background:#46d369"></span>On post</td></tr>`).join('')
    || `<tr><td colspan="4" class="muted" style="padding:18px">No officers checked in.</td></tr>`;
  renderClientFeed(myInc.length?myInc:state.incidents);
}
function renderClientFeed(list){
  $('#cli-incidents tbody').innerHTML = list.slice(0,8).map(i=>`<tr>
    <td class="muted">${dayAgo(i.occurred_at)}</td><td><b>${i.type}</b></td>
    <td><span class="tag ${sevTag(i.severity)}">${i.severity}</span></td>
    <td style="max-width:340px">${i.summary}</td>
    <td><span class="tag ${stTag(i.status)}">${i.status}</span></td></tr>`).join('')
    || `<tr><td colspan="5" class="muted" style="padding:18px">No incidents yet.</td></tr>`;
}

// ---- live incident insert ----
window.submitIncident = async ()=>{
  const c = state.clients.find(x=>x.name==='Mercy General Hospital')||state.clients[0];
  const site = state.sites.find(s=>s.client_id===c?.id);
  const row = { org_id:CFG.org, site_id:site?.id||null, type:$('#f-type').value, severity:$('#f-sev').value,
    summary:$('#f-sum').value.trim()||'(no description)', status:'open', occurred_at:new Date().toISOString() };
  try{
    const {error} = await sb.from('incidents').insert(row);
    if(error) throw error;
    toast('✓ Incident logged live to SENTINEL OS');
    $('#f-sum').value='';
    await load(); switchView('client');
  }catch(e){ toast('Saved locally (demo): '+e.message,'err'); state.incidents.unshift(row); renderClientFeed(state.incidents); }
};

// ---- nav ----
function switchView(r){
  document.querySelectorAll('.view').forEach(v=>v.classList.remove('on'));
  $('#v-'+r).classList.add('on');
  document.querySelectorAll('#roles button').forEach(b=>b.classList.toggle('on',b.dataset.r===r));
}
window.switchView = switchView;
document.querySelectorAll('#roles button').forEach(b=>b.onclick=()=>switchView(b.dataset.r));

load();
setInterval(()=>{ if($('#v-ops').classList.contains('on')) $('#ops-now').textContent = new Date().toLocaleDateString([], {weekday:'short',month:'short',day:'numeric'}); }, 30000);

// PWA
if('serviceWorker' in navigator){ navigator.serviceWorker.register('sw.js').catch(()=>{}); }
</script>
</body>
</html>
