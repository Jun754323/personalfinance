<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent" />
<meta name="theme-color" content="#0d0d10" />
<title>Fintrack</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Fraunces:ital,wght@0,300;0,500;1,300&display=swap" rel="stylesheet" />
<style>
*, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; -webkit-tap-highlight-color: transparent; }

:root {
  --bg: #0d0d10;
  --surface: #17171c;
  --surface2: #1f1f26;
  --surface3: #27272f;
  --border: rgba(255,255,255,0.06);
  --border2: rgba(255,255,255,0.11);
  --text: #f0ede8;
  --muted: #777;
  --faint: #3a3a42;
  --green: #4dffa0;
  --green-bg: rgba(77,255,160,0.1);
  --red: #ff5f5f;
  --red-bg: rgba(255,95,95,0.1);
  --amber: #ffbe4d;
  --blue: #6eaeff;
  --purple: #b08fff;
  --mono: 'DM Mono', monospace;
  --serif: 'Fraunces', Georgia, serif;
  --safe-bottom: env(safe-area-inset-bottom, 20px);
}

html, body {
  height: 100%;
  overflow: hidden;
  background: var(--bg);
  color: var(--text);
  font-family: var(--mono);
  font-size: 14px;
}

/* ─── App shell ─── */
.app {
  display: flex;
  flex-direction: column;
  height: 100vh;
  height: 100dvh;
  max-width: 430px;
  margin: 0 auto;
  background: var(--bg);
  position: relative;
  overflow: hidden;
}

/* ─── Status bar ─── */
.status-bar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 14px 20px 6px;
  font-size: 12px;
  font-weight: 500;
  color: var(--text);
  flex-shrink: 0;
}
.status-time { font-size: 15px; font-weight: 500; }
.status-icons { display: flex; gap: 6px; align-items: center; }
.status-icons svg { width: 16px; height: 16px; fill: var(--text); }

/* ─── Screens ─── */
.screen {
  flex: 1;
  display: none;
  flex-direction: column;
  overflow: hidden;
}
.screen.active { display: flex; }

/* ─── Tab bar ─── */
.tab-bar {
  display: flex;
  background: var(--surface);
  border-top: 0.5px solid var(--border2);
  padding-bottom: var(--safe-bottom);
  flex-shrink: 0;
}
.tab-btn {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 3px;
  padding: 10px 0 8px;
  background: none;
  border: none;
  color: var(--muted);
  font-family: var(--mono);
  font-size: 10px;
  letter-spacing: 0.05em;
  cursor: pointer;
  transition: color 0.15s;
}
.tab-btn svg { width: 22px; height: 22px; stroke: currentColor; fill: none; stroke-width: 1.5; stroke-linecap: round; stroke-linejoin: round; }
.tab-btn.active { color: var(--green); }

/* ─── HOME screen ─── */
.home-scroll {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  padding: 4px 0 0;
}

.home-header {
  padding: 6px 20px 20px;
}
.home-greeting {
  font-family: var(--serif);
  font-weight: 300;
  font-size: 22px;
  color: var(--text);
  margin-bottom: 2px;
}
.home-greeting em { font-style: italic; color: var(--green); }
.home-date { font-size: 11px; color: var(--muted); letter-spacing: 0.08em; }

/* Balance card */
.balance-card {
  margin: 0 16px 16px;
  background: var(--surface);
  border-radius: 20px;
  padding: 24px;
  border: 0.5px solid var(--border2);
  position: relative;
  overflow: hidden;
}
.balance-card::before {
  content: '';
  position: absolute;
  top: -40px; right: -40px;
  width: 140px; height: 140px;
  border-radius: 50%;
  background: var(--green);
  opacity: 0.04;
}
.balance-label { font-size: 11px; color: var(--muted); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 6px; }
.balance-amount {
  font-family: var(--serif);
  font-size: 42px;
  font-weight: 300;
  letter-spacing: -0.02em;
  line-height: 1;
  margin-bottom: 20px;
}
.balance-amount.pos { color: var(--green); }
.balance-amount.neg { color: var(--red); }
.balance-amount.neu { color: var(--text); }

.balance-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 12px;
}
.balance-pill {
  background: var(--surface2);
  border-radius: 12px;
  padding: 10px 14px;
  display: flex;
  align-items: center;
  gap: 8px;
}
.balance-pill-dot { width: 6px; height: 6px; border-radius: 50%; flex-shrink: 0; }
.balance-pill-info {}
.balance-pill-label { font-size: 10px; color: var(--muted); letter-spacing: 0.06em; text-transform: uppercase; }
.balance-pill-val { font-size: 14px; font-weight: 500; margin-top: 1px; }

/* Section */
.section { padding: 0 16px 16px; }
.section-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 10px;
}
.section-title { font-size: 11px; color: var(--muted); letter-spacing: 0.1em; text-transform: uppercase; }
.section-action { font-size: 11px; color: var(--green); cursor: pointer; }

/* Recent tx */
.tx-list { display: flex; flex-direction: column; gap: 3px; }
.tx-item {
  display: flex;
  align-items: center;
  gap: 12px;
  padding: 12px 14px;
  background: var(--surface);
  border-radius: 14px;
  border: 0.5px solid var(--border);
  animation: slideUp 0.2s ease;
}
@keyframes slideUp { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: none; } }
.tx-icon {
  width: 38px; height: 38px;
  border-radius: 12px;
  display: flex; align-items: center; justify-content: center;
  font-size: 17px;
  flex-shrink: 0;
}
.tx-info { flex: 1; overflow: hidden; }
.tx-name { font-size: 13px; color: var(--text); white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
.tx-cat { font-size: 10px; color: var(--muted); letter-spacing: 0.05em; margin-top: 2px; }
.tx-right { text-align: right; flex-shrink: 0; }
.tx-amt { font-size: 14px; font-weight: 500; }
.tx-amt.pos { color: var(--green); }
.tx-amt.neg { color: var(--red); }
.tx-date { font-size: 10px; color: var(--muted); margin-top: 2px; }
.tx-del-btn { background: none; border: none; color: var(--faint); cursor: pointer; font-size: 18px; padding: 0 0 0 8px; line-height: 1; }
.tx-del-btn:active { color: var(--red); }

.tx-empty { text-align: center; color: var(--muted); font-size: 12px; padding: 2rem 0; }

/* ─── ANALYTICS screen ─── */
.analytics-scroll {
  flex: 1;
  overflow-y: auto;
  -webkit-overflow-scrolling: touch;
  padding: 12px 16px;
}

.analytics-title {
  font-family: var(--serif);
  font-size: 22px;
  font-weight: 300;
  color: var(--text);
  margin-bottom: 20px;
  padding: 0 4px;
}
.analytics-title em { font-style: italic; color: var(--amber); }

.donut-card {
  background: var(--surface);
  border-radius: 20px;
  border: 0.5px solid var(--border2);
  padding: 20px;
  margin-bottom: 14px;
  display: flex;
  align-items: center;
  gap: 20px;
}
.donut-wrap { position: relative; width: 120px; height: 120px; flex-shrink: 0; }
.donut-center {
  position: absolute; inset: 0;
  display: flex; flex-direction: column;
  align-items: center; justify-content: center;
  pointer-events: none;
}
.donut-center-lbl { font-size: 9px; color: var(--muted); letter-spacing: 0.08em; text-transform: uppercase; }
.donut-center-val { font-size: 15px; font-weight: 500; color: var(--text); margin-top: 1px; }

.donut-legend { flex: 1; display: flex; flex-direction: column; gap: 8px; }
.dl-row { display: flex; align-items: center; gap: 8px; }
.dl-dot { width: 7px; height: 7px; border-radius: 50%; flex-shrink: 0; }
.dl-name { flex: 1; font-size: 12px; color: var(--muted); }
.dl-pct { font-size: 12px; color: var(--text); font-weight: 500; }

.cat-bars-card {
  background: var(--surface);
  border-radius: 20px;
  border: 0.5px solid var(--border2);
  padding: 20px;
  margin-bottom: 14px;
}
.cat-bars-title { font-size: 11px; color: var(--muted); letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 16px; }
.cat-bar-row { margin-bottom: 14px; }
.cat-bar-row:last-child { margin-bottom: 0; }
.cat-bar-top { display: flex; justify-content: space-between; margin-bottom: 6px; }
.cat-bar-name { font-size: 12px; color: var(--text); }
.cat-bar-val { font-size: 12px; color: var(--muted); }
.cat-track { height: 5px; background: var(--surface3); border-radius: 3px; overflow: hidden; }
.cat-fill { height: 100%; border-radius: 3px; transition: width 0.5s ease; }

/* ─── ADD screen ─── */
.add-screen { padding: 12px 20px; }
.add-screen-title {
  font-family: var(--serif);
  font-size: 22px;
  font-weight: 300;
  color: var(--text);
  margin-bottom: 24px;
}
.add-screen-title em { font-style: italic; color: var(--purple); }

.type-seg {
  display: grid;
  grid-template-columns: 1fr 1fr;
  background: var(--surface);
  border-radius: 14px;
  padding: 4px;
  margin-bottom: 16px;
  border: 0.5px solid var(--border2);
}
.seg-btn {
  padding: 11px;
  border-radius: 11px;
  border: none;
  background: transparent;
  color: var(--muted);
  font-family: var(--mono);
  font-size: 13px;
  cursor: pointer;
  transition: all 0.15s;
  letter-spacing: 0.03em;
}
.seg-btn.active-exp { background: var(--red-bg); color: var(--red); }
.seg-btn.active-inc { background: var(--green-bg); color: var(--green); }

.field-group { margin-bottom: 14px; }
.field-lbl { font-size: 10px; color: var(--muted); letter-spacing: 0.1em; text-transform: uppercase; margin-bottom: 6px; padding: 0 2px; }

.field-input, .field-select {
  width: 100%;
  background: var(--surface);
  border: 0.5px solid var(--border2);
  border-radius: 14px;
  color: var(--text);
  font-family: var(--mono);
  font-size: 15px;
  padding: 14px 16px;
  outline: none;
  -webkit-appearance: none;
  appearance: none;
  transition: border-color 0.15s, box-shadow 0.15s;
}
.field-input::placeholder { color: var(--faint); }
.field-input:focus, .field-select:focus {
  border-color: rgba(77,255,160,0.3);
  box-shadow: 0 0 0 3px rgba(77,255,160,0.07);
}
.field-select {
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' width='10' height='6'%3E%3Cpath d='M0 0l5 6 5-6z' fill='%23555'/%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-position: right 16px center;
  padding-right: 36px;
  cursor: pointer;
}

.amount-wrap { position: relative; }
.amount-prefix {
  position: absolute;
  left: 16px;
  top: 50%;
  transform: translateY(-50%);
  font-size: 18px;
  color: var(--muted);
  pointer-events: none;
}
.amount-input {
  padding-left: 30px !important;
  font-size: 22px !important;
  font-family: var(--serif) !important;
  font-weight: 300 !important;
}

.cat-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 8px;
}
.cat-chip {
  display: flex;
  flex-direction: column;
  align-items: center;
  gap: 5px;
  padding: 10px 4px 8px;
  background: var(--surface);
  border: 0.5px solid var(--border);
  border-radius: 14px;
  cursor: pointer;
  transition: all 0.15s;
  font-size: 9px;
  color: var(--muted);
  letter-spacing: 0.05em;
  text-transform: uppercase;
}
.cat-chip-icon { font-size: 20px; }
.cat-chip.selected { border-color: var(--green); background: var(--green-bg); color: var(--green); }

.submit-btn {
  width: 100%;
  padding: 17px;
  background: var(--green-bg);
  border: 0.5px solid rgba(77,255,160,0.25);
  border-radius: 16px;
  color: var(--green);
  font-family: var(--mono);
  font-size: 15px;
  font-weight: 500;
  letter-spacing: 0.05em;
  cursor: pointer;
  margin-top: 8px;
  transition: all 0.15s;
}
.submit-btn:active { transform: scale(0.98); background: rgba(77,255,160,0.18); }

/* scrollbar */
::-webkit-scrollbar { width: 0; }
</style>
</head>
<body>

<div class="app">

  <!-- Status bar -->
  <div class="status-bar">
    <div class="status-time" id="statusTime">9:41</div>
    <div class="status-icons">
      <svg viewBox="0 0 24 24"><path d="M1 6l5.5 5.5L12 6l5.5 5.5L23 6" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round"/></svg>
      <svg viewBox="0 0 24 24"><rect x="2" y="8" width="16" height="8" rx="2" stroke="currentColor" fill="none"/><path d="M18 11h2a1 1 0 011 1v0a1 1 0 01-1 1h-2" stroke="currentColor" fill="none"/><rect x="3" y="9" width="10" height="6" rx="1" fill="currentColor"/></svg>
    </div>
  </div>

  <!-- HOME screen -->
  <div class="screen active" id="screen-home">
    <div class="home-scroll">

      <div class="home-header">
        <div class="home-greeting">Good <em id="timeOfDay">morning</em></div>
        <div class="home-date" id="homeDate"></div>
      </div>

      <div class="balance-card">
        <div class="balance-label">Net balance</div>
        <div class="balance-amount neu" id="balAmt">$0</div>
        <div class="balance-row">
          <div class="balance-pill">
            <div class="balance-pill-dot" style="background:var(--green)"></div>
            <div class="balance-pill-info">
              <div class="balance-pill-label">Income</div>
              <div class="balance-pill-val" id="incAmt" style="color:var(--green)">$0</div>
            </div>
          </div>
          <div class="balance-pill">
            <div class="balance-pill-dot" style="background:var(--red)"></div>
            <div class="balance-pill-info">
              <div class="balance-pill-label">Expenses</div>
              <div class="balance-pill-val" id="expAmt" style="color:var(--red)">$0</div>
            </div>
          </div>
        </div>
      </div>

      <div class="section">
        <div class="section-header">
          <div class="section-title">Recent transactions</div>
          <div class="section-action" onclick="switchTab('analytics')">See all →</div>
        </div>
        <div class="tx-list" id="txList">
          <div class="tx-empty">No transactions yet.<br/>Tap + to add one.</div>
        </div>
      </div>

    </div>
  </div>

  <!-- ANALYTICS screen -->
  <div class="screen" id="screen-analytics">
    <div class="analytics-scroll">
      <div class="analytics-title">Spending<br/><em>overview</em></div>

      <div class="donut-card">
        <div class="donut-wrap">
          <canvas id="donutCanvas" width="120" height="120" role="img" aria-label="Donut chart of expenses by category">Expenses by category</canvas>
          <div class="donut-center">
            <div class="donut-center-lbl">spent</div>
            <div class="donut-center-val" id="donutTotal">$0</div>
          </div>
        </div>
        <div class="donut-legend" id="donutLegend">
          <div style="font-size:12px;color:var(--muted)">Add expenses to see breakdown</div>
        </div>
      </div>

      <div class="cat-bars-card">
        <div class="cat-bars-title">By category</div>
        <div id="catBarsGrid">
          <div style="font-size:12px;color:var(--muted)">No expense data yet.</div>
        </div>
      </div>
    </div>
  </div>

  <!-- ADD screen -->
  <div class="screen" id="screen-add">
    <div style="flex:1;overflow-y:auto;-webkit-overflow-scrolling:touch;padding:12px 20px 24px;">
      <div class="add-screen-title">New<br/><em>transaction</em></div>

      <div class="type-seg">
        <button class="seg-btn active-exp" id="segExp" onclick="setTxType('expense')">Expense</button>
        <button class="seg-btn" id="segInc" onclick="setTxType('income')">Income</button>
      </div>

      <div class="field-group">
        <div class="field-lbl">Amount</div>
        <div class="amount-wrap">
          <span class="amount-prefix">$</span>
          <input type="number" id="txAmount" class="field-input amount-input" placeholder="0.00" min="0" step="0.01" inputmode="decimal" />
        </div>
      </div>

      <div class="field-group">
        <div class="field-lbl">Description</div>
        <input type="text" id="txName" class="field-input" placeholder="What was this for?" />
      </div>

      <div class="field-group">
        <div class="field-lbl">Category</div>
        <div class="cat-grid" id="catGrid"></div>
      </div>

      <button class="submit-btn" onclick="addTx()">Add transaction</button>
    </div>
  </div>

  <!-- Tab bar -->
  <nav class="tab-bar">
    <button class="tab-btn active" id="tab-home" onclick="switchTab('home')">
      <svg viewBox="0 0 24 24"><path d="M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z"/><polyline points="9 22 9 12 15 12 15 22"/></svg>
      Home
    </button>
    <button class="tab-btn" id="tab-analytics" onclick="switchTab('analytics')">
      <svg viewBox="0 0 24 24"><line x1="18" y1="20" x2="18" y2="10"/><line x1="12" y1="20" x2="12" y2="4"/><line x1="6" y1="20" x2="6" y2="14"/></svg>
      Analytics
    </button>
    <button class="tab-btn" id="tab-add" onclick="switchTab('add')">
      <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><line x1="12" y1="8" x2="12" y2="16"/><line x1="8" y1="12" x2="16" y2="12"/></svg>
      Add
    </button>
  </nav>

</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<script>
// ─── Data ───
const CATS = [
  { key: 'Housing', icon: '🏠' },
  { key: 'Food', icon: '🍔' },
  { key: 'Transport', icon: '🚗' },
  { key: 'Health', icon: '💊' },
  { key: 'Entertainment', icon: '🎬' },
  { key: 'Shopping', icon: '🛍️' },
  { key: 'Salary', icon: '💰' },
  { key: 'Other', icon: '📦' },
];
const CAT_COLORS = {
  Housing:'#6eaeff', Food:'#4dffa0', Transport:'#ffbe4d',
  Health:'#ff8fdb', Entertainment:'#b08fff', Shopping:'#ff8f6e',
  Salary:'#4dffa0', Other:'#777'
};

let txType = 'expense';
let selCat = 'Food';
let nextId = 6;
let donutInst = null;

let transactions = [
  { id:1, name:'Monthly rent', amount:1500, type:'expense', cat:'Housing', ts: Date.now()-5*86400000 },
  { id:2, name:'Groceries', amount:220, type:'expense', cat:'Food', ts: Date.now()-3*86400000 },
  { id:3, name:'Paycheck', amount:3200, type:'income', cat:'Salary', ts: Date.now()-2*86400000 },
  { id:4, name:'Netflix', amount:18, type:'expense', cat:'Entertainment', ts: Date.now()-86400000 },
  { id:5, name:'Bus pass', amount:65, type:'expense', cat:'Transport', ts: Date.now()-43200000 },
];

// ─── Utils ───
function fmt(n) { return '$' + Math.round(Math.abs(n)).toLocaleString('en-US'); }
function relDate(ts) {
  const diff = Date.now() - ts;
  if (diff < 60000) return 'just now';
  if (diff < 3600000) return Math.floor(diff/60000) + 'm ago';
  if (diff < 86400000) return Math.floor(diff/3600000) + 'h ago';
  return Math.floor(diff/86400000) + 'd ago';
}

// ─── Clock ───
function updateClock() {
  const now = new Date();
  const h = now.getHours(), m = now.getMinutes();
  document.getElementById('statusTime').textContent = h + ':' + String(m).padStart(2,'0');
  const hour = now.getHours();
  document.getElementById('timeOfDay').textContent = hour < 12 ? 'morning' : hour < 17 ? 'afternoon' : 'evening';
  const days = ['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday'];
  const months = ['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];
  document.getElementById('homeDate').textContent = days[now.getDay()] + ', ' + months[now.getMonth()] + ' ' + now.getDate();
}
updateClock();
setInterval(updateClock, 30000);

// ─── Cat grid ───
function buildCatGrid() {
  document.getElementById('catGrid').innerHTML = CATS.map(c => `
    <div class="cat-chip ${c.key === selCat ? 'selected' : ''}" onclick="selectCat('${c.key}')">
      <span class="cat-chip-icon">${c.icon}</span>
      ${c.key}
    </div>
  `).join('');
}
buildCatGrid();

function selectCat(k) { selCat = k; buildCatGrid(); }

// ─── Type toggle ───
function setTxType(t) {
  txType = t;
  document.getElementById('segExp').className = 'seg-btn' + (t==='expense' ? ' active-exp' : '');
  document.getElementById('segInc').className = 'seg-btn' + (t==='income' ? ' active-inc' : '');
}

// ─── Tab switching ───
function switchTab(tab) {
  ['home','analytics','add'].forEach(t => {
    document.getElementById('screen-'+t).classList.toggle('active', t===tab);
    document.getElementById('tab-'+t).classList.toggle('active', t===tab);
  });
  if (tab === 'analytics') renderAnalytics();
}

// ─── Add tx ───
function addTx() {
  const name = document.getElementById('txName').value.trim();
  const amount = parseFloat(document.getElementById('txAmount').value);
  if (!name || isNaN(amount) || amount <= 0) {
    document.getElementById('txAmount').focus();
    return;
  }
  transactions.push({ id: nextId++, name, amount, type: txType, cat: selCat, ts: Date.now() });
  document.getElementById('txName').value = '';
  document.getElementById('txAmount').value = '';
  renderHome();
  switchTab('home');
}

function deleteTx(id) {
  transactions = transactions.filter(t => t.id !== id);
  renderHome();
}

// ─── Render home ───
function renderHome() {
  const income = transactions.filter(t=>t.type==='income').reduce((s,t)=>s+t.amount,0);
  const expenses = transactions.filter(t=>t.type==='expense').reduce((s,t)=>s+t.amount,0);
  const bal = income - expenses;

  document.getElementById('incAmt').textContent = fmt(income);
  document.getElementById('expAmt').textContent = fmt(expenses);
  const balEl = document.getElementById('balAmt');
  balEl.textContent = (bal < 0 ? '-' : '') + fmt(bal);
  balEl.className = 'balance-amount ' + (bal > 0 ? 'pos' : bal < 0 ? 'neg' : 'neu');

  const list = document.getElementById('txList');
  if (!transactions.length) {
    list.innerHTML = '<div class="tx-empty">No transactions yet.<br/>Tap + to add one.</div>';
    return;
  }
  const sorted = transactions.slice().sort((a,b) => b.ts - a.ts).slice(0, 10);
  list.innerHTML = sorted.map(t => {
    const cat = CATS.find(c=>c.key===t.cat)||{icon:'📦'};
    const col = t.type==='income' ? 'var(--green)' : (CAT_COLORS[t.cat]||'#777');
    return `
      <div class="tx-item">
        <div class="tx-icon" style="background:${col}18">${cat.icon}</div>
        <div class="tx-info">
          <div class="tx-name">${t.name}</div>
          <div class="tx-cat">${t.cat.toUpperCase()}</div>
        </div>
        <div class="tx-right">
          <div class="tx-amt ${t.type==='income'?'pos':'neg'}">${t.type==='income'?'+':'-'}${fmt(t.amount)}</div>
          <div class="tx-date">${relDate(t.ts)}</div>
        </div>
        <button class="tx-del-btn" onclick="deleteTx(${t.id})">×</button>
      </div>
    `;
  }).join('');
}

// ─── Render analytics ───
function renderAnalytics() {
  const expTx = transactions.filter(t=>t.type==='expense');
  const bycat = {};
  expTx.forEach(t => { bycat[t.cat] = (bycat[t.cat]||0) + t.amount; });
  const cats = Object.keys(bycat);
  const vals = cats.map(c=>bycat[c]);
  const colors = cats.map(c=>CAT_COLORS[c]||'#777');
  const total = vals.reduce((a,b)=>a+b,0);

  document.getElementById('donutTotal').textContent = fmt(total);

  const canvas = document.getElementById('donutCanvas');
  if (donutInst) { donutInst.destroy(); donutInst = null; }
  if (cats.length) {
    donutInst = new Chart(canvas, {
      type: 'doughnut',
      data: { labels: cats, datasets: [{ data: vals, backgroundColor: colors, borderWidth: 0 }] },
      options: {
        responsive: false, maintainAspectRatio: false,
        plugins: { legend: { display: false }, tooltip: { callbacks: { label: ctx=>' '+ctx.label+': '+fmt(ctx.raw) } } },
        cutout: '70%'
      }
    });
    document.getElementById('donutLegend').innerHTML = cats.map((c,i) => `
      <div class="dl-row">
        <div class="dl-dot" style="background:${colors[i]}"></div>
        <div class="dl-name">${c}</div>
        <div class="dl-pct">${total?Math.round(vals[i]/total*100):0}%</div>
      </div>
    `).join('');
  } else {
    document.getElementById('donutLegend').innerHTML = '<div style="font-size:12px;color:var(--muted)">Add expenses to see breakdown</div>';
  }

  const barsEl = document.getElementById('catBarsGrid');
  if (!cats.length) {
    barsEl.innerHTML = '<div style="font-size:12px;color:var(--muted)">No expense data yet.</div>';
    return;
  }
  const sorted = cats.map((c,i)=>({c,v:vals[i],col:colors[i]})).sort((a,b)=>b.v-a.v);
  barsEl.innerHTML = sorted.map(({c,v,col}) => `
    <div class="cat-bar-row">
      <div class="cat-bar-top">
        <div class="cat-bar-name">${c}</div>
        <div class="cat-bar-val">${fmt(v)}</div>
      </div>
      <div class="cat-track">
        <div class="cat-fill" style="width:${total?Math.round(v/total*100):0}%;background:${col}"></div>
      </div>
    </div>
  `).join('');
}

renderHome();
</script>
</body>
</html>
