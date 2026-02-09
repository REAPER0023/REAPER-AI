<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>GHAYAL PADHAI CALCULATOR 👾</title>
  <style>
    :root{
      --bg:#070a12;
      --muted:#9ca3af;
      --text:#e5e7eb;
      --accent:#7c3aed;
      --accent2:#06b6d4;
      --ring: rgba(124,58,237,.35);
      --border: rgba(255,255,255,.10);
      --shadow: 0 18px 60px rgba(0,0,0,.55);

      --good:#22c55e;
      --bad:#ef4444;
      --warn:#f59e0b;
      --mid:#60a5fa;
    }

    *{box-sizing:border-box;font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial}
    body{
      margin:0;
      min-height:100vh;
      display:flex;
      align-items:center;
      justify-content:center;
      padding:24px;
      color:var(--text);

      background:
        radial-gradient(1100px 700px at 15% 10%, rgba(124,58,237,.40), transparent 60%),
        radial-gradient(900px 600px at 80% 20%, rgba(6,182,212,.18), transparent 60%),
        radial-gradient(700px 500px at 70% 85%, rgba(34,197,94,.10), transparent 60%),
        var(--bg);
    }

    .wrap{
      width:min(1040px, 100%);
      display:grid;
      gap:16px;
    }

    .header{
      display:flex;
      align-items:flex-start;
      justify-content:space-between;
      gap:14px;
    }

    .title h1{
      margin:0;
      font-size:clamp(22px, 3.2vw, 38px);
      letter-spacing:.3px;
    }

    .title p{
      margin:8px 0 0;
      color:var(--muted);
      font-size:14px;
      line-height:1.45;
      max-width: 70ch;
    }

    .pill{
      display:inline-flex;
      align-items:center;
      gap:10px;
      padding:10px 12px;
      border-radius:999px;
      border:1px solid var(--border);
      background: rgba(255,255,255,.03);
      color:rgba(255,255,255,.75);
      font-size:13px;
      white-space:nowrap;
      backdrop-filter: blur(8px);
    }

    .card{
      background: linear-gradient(180deg, rgba(255,255,255,.05), rgba(255,255,255,.02));
      border:1px solid var(--border);
      border-radius:20px;
      padding:18px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(10px);
      animation: popIn .45s ease both;
    }

    @keyframes popIn{
      from{ opacity:0; transform: translateY(10px) scale(.99); }
      to{ opacity:1; transform: translateY(0) scale(1); }
    }

    .grid{
      display:grid;
      grid-template-columns: repeat(12, 1fr);
      gap:14px;
    }

    .field{grid-column: span 4;}
    @media (max-width: 860px){ .field{grid-column: span 6;} }
    @media (max-width: 520px){ .field{grid-column: span 12;} }

    label{
      display:flex;
      align-items:center;
      justify-content:space-between;
      gap:10px;
      font-size:13px;
      color:rgba(255,255,255,.70);
      margin-bottom:7px;
    }

    .cap{
      font-size:12px;
      color:rgba(255,255,255,.35);
    }

    input{
      width:100%;
      padding:12px 12px;
      border-radius:14px;
      border:1px solid rgba(255,255,255,.12);
      background: rgba(15,23,42,.65);
      color:var(--text);
      outline:none;
      font-size:15px;
      transition: .15s ease;
    }

    input:focus{
      border-color: rgba(124,58,237,.8);
      box-shadow: 0 0 0 4px var(--ring);
      transform: translateY(-1px);
    }

    .actions{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
      align-items:center;
      margin-top:14px;
    }

    button{
      cursor:pointer;
      border:0;
      border-radius:14px;
      padding:12px 14px;
      font-size:15px;
      font-weight:900;
      color:white;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      box-shadow: 0 10px 25px rgba(124,58,237,.25);
      transition: transform .15s ease, filter .15s ease;
      position:relative;
      overflow:hidden;
    }

    button:hover{ transform: translateY(-1px); }
    button:active{ transform: translateY(0px) scale(.99); }
    button:disabled{ opacity:.55; cursor:not-allowed; }

    button::after{
      content:"";
      position:absolute;
      top:-40%;
      left:-40%;
      width:80%;
      height:180%;
      background: linear-gradient(90deg, transparent, rgba(255,255,255,.25), transparent);
      transform: rotate(20deg);
      opacity:0;
    }
    button:hover::after{
      opacity:1;
      animation: shine .9s ease;
    }
    @keyframes shine{
      from{ transform: translateX(-120%) rotate(20deg); }
      to{ transform: translateX(220%) rotate(20deg); }
    }

    button.secondary{
      background: rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.14);
      color:rgba(255,255,255,.85);
      font-weight:800;
      box-shadow:none;
    }

    .live{
      display:flex;
      gap:10px;
      flex-wrap:wrap;
      margin-left:auto;
    }

    .tag{
      display:inline-flex;
      align-items:center;
      gap:8px;
      padding:8px 10px;
      border-radius:999px;
      border:1px solid rgba(255,255,255,.12);
      background: rgba(255,255,255,.03);
      font-size:13px;
      color:rgba(255,255,255,.75);
      white-space:nowrap;
      transition: transform .15s ease;
    }

    .tag.bump{ animation: bump .25s ease; }
    @keyframes bump{
      0%{ transform: scale(1); }
      55%{ transform: scale(1.03); }
      100%{ transform: scale(1); }
    }

    .result{
      display:grid;
      grid-template-columns: repeat(12, 1fr);
      gap:14px;
      align-items:stretch;
    }

    .panel{
      border-radius:18px;
      border:1px solid rgba(255,255,255,.10);
      background: rgba(0,0,0,.16);
      padding:18px;
    }

    .main{ grid-column: span 7; }
    .side{ grid-column: span 5; }

    @media (max-width: 900px){
      .main,.side{ grid-column: span 12; }
      .live{ width:100%; margin-left:0; }
    }

    .kpi{
      font-size:52px;
      font-weight:1000;
      letter-spacing:.4px;
      margin:8px 0 0;
      line-height:1;
      min-height: 56px;
    }

    .status{
      margin:10px 0 0;
      font-size:18px;
      font-weight:900;
      min-height: 24px;
    }

    .hint{
      margin:10px 0 0;
      color:rgba(255,255,255,.60);
      font-size:13px;
      line-height:1.6;
      min-height: 20px;
    }

    .barWrap{
      margin-top:16px;
      height:14px;
      border-radius:999px;
      background: rgba(255,255,255,.06);
      border:1px solid rgba(255,255,255,.10);
      overflow:hidden;
    }

    .bar{
      height:100%;
      width:0%;
      background: linear-gradient(90deg, var(--bad), var(--warn), var(--good));
      transition: width .55s cubic-bezier(.2,.8,.2,1);
    }

    .reveal{
      opacity:0;
      transform: translateY(8px);
      transition: opacity .35s ease, transform .35s ease;
    }
    .reveal.show{
      opacity:1;
      transform: translateY(0px);
    }

    .good{ color: var(--good); }
    .bad{ color: var(--bad); }
    .warn{ color: var(--warn); }
    .mid{ color: var(--mid); }

    ul{ margin:10px 0 0; padding-left:18px; line-height:1.75; color:rgba(255,255,255,.70); }
    b{ color: rgba(255,255,255,.92); }

    .footer{
      color:rgba(255,255,255,.35);
      font-size:12px;
      text-align:center;
      padding:6px 0 0;
    }

    @media (prefers-reduced-motion: reduce){
      *{ animation:none !important; transition:none !important; }
    }
  </style>
</head>
<body>
  <div class="wrap">

    <div class="header">
      <div class="title">
        <h1>GHAYAL PADHAI CALCULATOR 👾</h1>
        <p>
          Enter marks for 6 subjects. Then click <b>Calculate</b>.
          The percentage + status will appear with animations, because humans need drama to accept math.
        </p>
      </div>
      <div class="pill">Total = s1+s2+s3+s4+s5+s6 + <b>120</b> &nbsp;|&nbsp; Out of <b>600</b></div>
    </div>

    <div class="card">
      <div class="grid">
        <div class="field">
          <label>Subject 1 <span class="cap">0 - 100</span></label>
          <input id="s1" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
        <div class="field">
          <label>Subject 2 <span class="cap">0 - 100</span></label>
          <input id="s2" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
        <div class="field">
          <label>Subject 3 <span class="cap">0 - 100</span></label>
          <input id="s3" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
        <div class="field">
          <label>Subject 4 <span class="cap">0 - 100</span></label>
          <input id="s4" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
        <div class="field">
          <label>Subject 5 <span class="cap">0 - 100</span></label>
          <input id="s5" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
        <div class="field">
          <label>Subject 6 <span class="cap">0 - 100</span></label>
          <input id="s6" type="number" min="0" max="100" placeholder="Enter marks" />
        </div>
      </div>

      <div class="actions">
        <button id="calcBtn">Calculate %</button>
        <button class="secondary" id="resetBtn">Reset</button>

        <div class="live">
          <span class="tag" id="liveTotal">Total: —</span>
          <span class="tag" id="livePer">Percentage: —</span>
        </div>
      </div>
    </div>

    <div class="card">
      <div class="result">
        <div class="panel main">
          <div style="color:rgba(255,255,255,.55);font-size:13px">Your percentage</div>

          <div class="kpi reveal" id="perOut">—</div>
          <div class="status reveal" id="statusOut"></div>
          <div class="hint reveal" id="logicOut"></div>

          <div class="barWrap reveal" id="barWrap" aria-label="percentage bar">
            <div class="bar" id="bar"></div>
          </div>
        </div>

        <div class="panel side">
          <div style="color:rgba(255,255,255,.55);font-size:13px">Logic (fixed version)</div>
          <ul>
            <li><b>total</b> = s1+s2+s3+s4+s5+s6 + <b>120</b></li>
            <li><b>percentage</b> = (total * 100) / 600</li>
            <li>Status is based on proper ranges</li>
          </ul>

          <div class="hint" style="margin-top:12px">
            Note: I kept your original status names and emojis.
            I only fixed the <b>if-else</b> ordering so it behaves logically.
          </div>
        </div>
      </div>
    </div>

    <div class="footer">Made from your C program. The +120 is still here, because tradition.</div>
  </div>

<script>
  const ids = ["s1","s2","s3","s4","s5","s6"];
  const el = (id)=>document.getElementById(id);

  let hasCalculated = false;

  function num(v){
    if(v === "" || v === null || v === undefined) return 0;
    const n = Number(v);
    return Number.isFinite(n) ? n : 0;
  }

  function clamp(n, a, b){ return Math.max(a, Math.min(b, n)); }

  function compute(){
    const s = ids.map(id => num(el(id).value));
    const total = s.reduce((a,b)=>a+b,0) + 120;
    const per = (total * 100) / 600;
    return { s, total, per };
  }

  function statusFor(per){
    if(per < 35){
      return {text:"Fail 😭", cls:"bad"};
    }else if(per >= 35 && per <= 45){
      return {text:"status:- Manthan level 🤓", cls:"warn"};
    }else if(per >= 46 && per <= 55){
      return {text:"status:- urvashi level 🤠", cls:"mid"};
    }else if(per >= 56 && per <= 65){
      return {text:"status:- Dhawle or diksha 😁", cls:"mid"};
    }else if(per >= 66 && per <= 75){
      return {text:"status:- kavya 👾", cls:"good"};
    }else if(per >= 76 && per <= 80){
      return {text:"status:- Dilip 😑🖕", cls:"good"};
    }else if(per >= 81 && per <= 90){
      return {text:"status: vedika 🥸", cls:"good"};
    }else{
      return {text:"🙂 hag dia 👍", cls:"good"};
    }
  }

  function validate(){
    ids.forEach(id=>{
      const v = el(id).value;
      if(v === "") return;
      const n = clamp(Number(v), 0, 100);
      if(Number.isFinite(n)) el(id).value = n;
    });
  }

  function bumpTag(node){
    node.classList.remove("bump");
    void node.offsetWidth;
    node.classList.add("bump");
  }

  function updateLive(){
    validate();
    const {total, per} = compute();

    el("liveTotal").textContent = "Total: " + total.toFixed(0);
    el("livePer").textContent = "Percentage: " + per.toFixed(2) + "%";

    bumpTag(el("liveTotal"));
    bumpTag(el("livePer"));

    if(hasCalculated){
      render(false);
    }
  }

  function showResults(){
    ["perOut","statusOut","logicOut","barWrap"].forEach(id=>{
      el(id).classList.add("show");
    });
  }

  function hideResults(){
    ["perOut","statusOut","logicOut","barWrap"].forEach(id=>{
      el(id).classList.remove("show");
    });
  }

  function animateNumber(node, from, to, duration=650){
    const start = performance.now();
    function tick(now){
      const t = clamp((now - start) / duration, 0, 1);
      const e = 1 - Math.pow(1 - t, 3);
      const val = from + (to - from) * e;
      node.textContent = val.toFixed(2) + "%";
      if(t < 1) requestAnimationFrame(tick);
    }
    requestAnimationFrame(tick);
  }

  function render(withNumberAnim=true){
    validate();
    const {total, per} = compute();
    const st = statusFor(per);

    el("statusOut").className = "status reveal show " + st.cls;

    el("statusOut").textContent = st.text;
    el("logicOut").textContent = `Total = ${total.toFixed(0)} (including +120 bonus)`;

    const w = clamp(per, 0, 100);
    el("bar").style.width = w.toFixed(1) + "%";

    if(withNumberAnim){
      const currentText = el("perOut").textContent.replace("%","");
      const current = Number(currentText);
      const from = Number.isFinite(current) ? current : 0;
      animateNumber(el("perOut"), from, per, 700);
    }else{
      el("perOut").textContent = per.toFixed(2) + "%";
    }

    showResults();
  }

  el("calcBtn").addEventListener("click", ()=>{
    hasCalculated = true;
    render(true);
  });

  el("resetBtn").addEventListener("click", ()=>{
    hasCalculated = false;
    ids.forEach(id => el(id).value = "");
    el("liveTotal").textContent = "Total: —";
    el("livePer").textContent = "Percentage: —";
    el("bar").style.width = "0%";
    el("perOut").textContent = "—";
    el("statusOut").textContent = "";
    el("logicOut").textContent = "";
    hideResults();
  });

  ids.forEach(id => el(id).addEventListener("input", updateLive));

  hideResults();
</script>
</body>
</html>
