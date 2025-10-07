<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>Inspection QA - HD785</title>
<style>
  :root{
    --bg1:#f0f6ff; --bg2:#e8fff4; --card:#ffffff;
    --accent:#2c8c6a; --muted:#666;
  }
  body{
    margin:0; font-family: system-ui, -apple-system, "Segoe UI", Roboto, Arial;
    background: linear-gradient(135deg,var(--bg1),var(--bg2));
    padding:18px;
  }
  .card{
    background:var(--card);
    border-radius:14px;
    box-shadow: 0 8px 24px rgba(30,60,80,0.12);
    padding:18px; max-width:980px; margin:0 auto 18px;
  }
  h1{margin:0 0 8px; font-size:20px; color:var(--accent); text-align:center}
  label{display:block; font-weight:700; color:#234; margin-top:10px}
  input[type=text], input[type=date], textarea, select{
    width:100%; padding:10px; border-radius:8px; border:1px solid #d2d8dd; box-sizing:border-box;
    margin-top:6px; background:#fff;
  }
  textarea{min-height:80px; resize:vertical}
  .grid{
    display:grid; grid-template-columns: repeat(auto-fit,minmax(220px,1fr)); gap:10px; margin-top:8px;
  }
  .checkbox-item{
    display:flex; align-items:center; justify-content:space-between;
    gap:12px; padding:8px 10px; border-radius:8px; background:linear-gradient(180deg,#fff,#fbfbfb);
    border:1px solid #e6e6e6; box-shadow: 0 3px 8px rgba(20,30,40,0.04);
  }
  .checkbox-item label{margin:0; font-weight:600; color:#1f2b2a}
  .checkbox-item input[type=checkbox]{transform:scale(1.18)}
  .inline-row{display:flex; gap:8px; align-items:center; flex-wrap:wrap}
  .inline-row input[type=text]{flex:1; min-width:90px}
  .actions{display:flex; gap:10px; margin-top:14px; flex-wrap:wrap}
  .btn{padding:12px 14px; border-radius:10px; border:none; cursor:pointer; font-weight:800}
  .btn-preview{background:#f6c84c;color:#082; box-shadow:0 4px 10px rgba(246,200,76,0.18)}
  .btn-wa{background:#25d366;color:#fff}
  .btn-copy{background:#3498db;color:#fff}
  .output{white-space:pre-wrap; font-family:Menlo,monospace; background:#0f1720; color:#f8fafc; padding:14px; border-radius:10px; margin-top:14px; min-height:120px}
  .small{font-size:13px; color:var(--muted)}
  .tyre-find{margin-top:8px}
  @media (max-width:520px){
    .inline-row{flex-direction:column; align-items:stretch}
  }
</style>
</head>
<body>

<div class="card">
  <h1>Inspection Report — HD Series</h1>

  <label>Jenis Inspection</label>
  <select id="qaType">
    <option value="QA-1 Pre Inspection">QA-1 Pre Inspection</option>
    <option value="QA-7 Final Inspection">QA-7 Final Inspection</option>
  </select>

  <div style="display:flex; gap:10px; margin-top:10px; flex-wrap:wrap">
    <div style="flex:1; min-width:180px">
      <label>📅 Tgl</label>
      <input type="date" id="tanggal">
    </div>
    <div style="flex:2; min-width:180px">
      <label>👷 Mekanik</label>
      <input type="text" id="mekanik" placeholder="contoh: Mario, Jovan">
    </div>
  </div>

  <div style="display:flex; gap:10px; margin-top:10px; flex-wrap:wrap">
    <div style="flex:1; min-width:140px">
      <label>🚗 CN</label>
      <input type="text" id="cn" placeholder="DT4947">
    </div>
    <div style="flex:1; min-width:140px">
      <label>⌛ HM</label>
      <input type="text" id="hm" placeholder="35026">
    </div>
  </div>

  <label style="margin-top:14px">🩸 Oil Level</label>
  <div class="grid">
    <div class="checkbox-item"><label>Engine oil level</label><input type="checkbox" id="engineOil"></div>
    <div class="checkbox-item"><label>Transmission oil level</label><input type="checkbox" id="transOil"></div>
    <div class="checkbox-item"><label>Hydraulic oil level</label><input type="checkbox" id="hydOil"></div>
  </div>

  <label style="margin-top:12px">⚙ Engine Area</label>
  <div class="grid">
    <div class="checkbox-item"><label>Belt tension</label><input type="checkbox" id="belt"></div>
    <div class="checkbox-item"><label>Engine oil leakage</label><input type="checkbox" id="oilLeak"></div>
    <div class="checkbox-item"><label>Common Rail Connector</label><input type="checkbox" id="crc"></div>
    <div class="checkbox-item"><label>Injector Tube</label><input type="checkbox" id="injector"></div>
  </div>

  <label style="margin-top:12px">🚗 Cabin Area</label>
  <div class="grid">
    <div class="checkbox-item"><label>FM Radio</label><input type="checkbox" id="radio"></div>
    <div class="checkbox-item"><label>Fatigue Warning</label><input type="checkbox" id="fatigue"></div>
    <div class="checkbox-item"><label>Power Window</label><input type="checkbox" id="pw"></div>
  </div>

  <div class="inline-row" style="margin-top:10px">
    <div style="flex:1">
      <label>⚡ Power Supply</label>
      <input type="text" id="powerSupply" placeholder="contoh: 25.7 V">
    </div>
    <div style="flex:1">
      <label>💧 Common Rail Pressure (ON)</label>
      <input type="text" id="crp" placeholder="contoh: 0 MPa">
    </div>
  </div>

  <label style="margin-top:12px">🚗 Frame Area</label>
  <div class="grid">
    <div class="checkbox-item"><label>Operator seat</label><input type="checkbox" id="seat"></div>
    <div class="checkbox-item"><label>Hand Rail</label><input type="checkbox" id="rail"></div>
  </div>

  <label style="margin-top:12px">💧 Pressure Suspension (Panel) — (satu baris)</label>
  <div class="inline-row">
    <input type="text" id="fl" placeholder="FL (mis. 3.80 MPa)">
    <input type="text" id="fr" placeholder="FR (mis. 3.50 MPa)">
    <input type="text" id="rl" placeholder="RL (mis. 2.00 MPa)">
    <input type="text" id="rr" placeholder="RR (mis. 2.09 MPa)">
  </div>

  <label style="margin-top:12px">🛞 Tyre Condition</label>
  <div style="display:flex; gap:12px; align-items:center; margin-top:6px">
    <label style="font-weight:700">Tyre :</label>
    <label style="display:flex; align-items:center; gap:6px"><input type="radio" name="tyre" value="Good" checked id="tyreGood"> ✅ Good</label>
    <label style="display:flex; align-items:center; gap:6px"><input type="radio" name="tyre" value="Bad" id="tyreBad"> ❌ Bad</label>
  </div>
  <div id="tyreFindDiv" class="tyre-find" style="display:none; margin-top:8px">
    <label>Temuan Tyre (jika Bad)</label>
    <input type="text" id="tyreFinding" placeholder="Tulis temuan ban...">
  </div>

  <label style="margin-top:12px">📝 Validasi & Kelengkapan Service</label>
  <div class="grid">
    <div class="checkbox-item"><label>Job Card & Cover Checklist</label><input type="checkbox" id="jobCard"></div>
    <div class="checkbox-item"><label>Form Observasi Redo PS</label><input type="checkbox" id="redo"></div>
    <div class="checkbox-item"><label>Form QA 1 & QA 7</label><input type="checkbox" id="qaForm"></div>
    <div class="checkbox-item"><label>Form PPM</label><input type="checkbox" id="ppm"></div>
    <div class="checkbox-item"><label>Form Check List A</label><input type="checkbox" id="a"></div>
    <div class="checkbox-item"><label>Form Check List B</label><input type="checkbox" id="b"></div>
    <div class="checkbox-item"><label>Form Check List C</label><input type="checkbox" id="c"></div>
    <div class="checkbox-item"><label>Form Backlog</label><input type="checkbox" id="backlog"></div>
    <div class="checkbox-item"><label>Form FUI</label><input type="checkbox" id="fui"></div>
    <div class="checkbox-item"><label>Form Repair Order</label><input type="checkbox" id="ro"></div>
    <div class="checkbox-item"><label>Form Combine Maintenance</label><input type="checkbox" id="combine"></div>
    <div class="checkbox-item"><label>Form Service Activity Report</label><input type="checkbox" id="sar"></div>
  </div>

  <label style="margin-top:12px">*Deviation* (masukkan tiap baris baru untuk tiap temuan)</label>
  <textarea id="deviation" placeholder="contoh: canopy atas cabin crack 200mm&#10;gasket coupling oil cooler transmission leak"></textarea>

  <div class="actions">
    <button class="btn btn-preview" onclick="previewText()">🔎 Preview</button>
    <button class="btn btn-wa" onclick="sendWA()">📤 Send to WhatsApp</button>
    <button class="btn btn-copy" onclick="copyText()">📋 Copy</button>
  </div>

  <div class="output" id="output">Preview akan muncul di sini — klik Preview.</div>
  <div class="small" style="margin-top:8px">Catatan: "Send to WhatsApp" membuka WhatsApp dengan teks sudah terisi; tekan Send di aplikasi WhatsApp untuk kirim.</div>
</div>

<script>
  // set default date to today
  (function(){ const d = new Date(); const iso = d.toISOString().split('T')[0]; document.getElementById('tanggal').value = iso; })();

  // tyre radio handling
  document.getElementById('tyreGood').addEventListener('change', ()=> document.getElementById('tyreFindDiv').style.display='none');
  document.getElementById('tyreBad').addEventListener('change', ()=> document.getElementById('tyreFindDiv').style.display='block');

  function getCheck(id){ return document.getElementById(id).checked ? '✅' : '❌'; }

  function formatDeviationLines(raw){
    if(!raw) return 'None';
    const lines = raw.split(/\r?\n/).map(l=>l.trim()).filter(l=>l.length>0);
    if(lines.length===0) return 'None';
    return lines.map(l=>`⚠️ ${l}`).join('\\n');
  }

  function generateText(){
    const qa = document.getElementById('qaType').value;
    const date = document.getElementById('tanggal').value;
    const mekanik = document.getElementById('mekanik').value || '-';
    const cn = document.getElementById('cn').value || '-';
    const hm = document.getElementById('hm').value || '-';

    const engineOil = getCheck('engineOil');
    const transOil = getCheck('transOil');
    const hydOil = getCheck('hydOil');

    const belt = getCheck('belt');
    const oilLeak = getCheck('oilLeak');
    const crc = getCheck('crc');
    const injector = getCheck('injector');

    const radio = getCheck('radio');
    const fatigue = getCheck('fatigue');
    const pw = getCheck('pw');
    const power = document.getElementById('powerSupply').value || '-';
    const crp = document.getElementById('crp').value || '-';

    const seat = getCheck('seat');
    const rail = getCheck('rail');

    const fl = document.getElementById('fl').value || '-';
    const fr = document.getElementById('fr').value || '-';
    const rl = document.getElementById('rl').value || '-';
    const rr = document.getElementById('rr').value || '-';

    const tyre = document.querySelector('input[name="tyre"]:checked')?.value || 'Good';
    const tyreFinding = document.getElementById('tyreFinding').value || '';

    const jobCard = getCheck('jobCard'); const redo = getCheck('redo'); const qaForm = getCheck('qaForm');
    const ppm = getCheck('ppm'); const a = getCheck('a'); const b = getCheck('b'); const c = getCheck('c');
    const backlog = getCheck('backlog'); const fui = getCheck('fui'); const ro = getCheck('ro');
    const combine = getCheck('combine'); const sar = getCheck('sar');

    const deviationRaw = document.getElementById('deviation').value;
    const deviation = formatDeviationLines(deviationRaw);

    // pressure suspension inline format
    const suspensionLine = `FL : ${fl}   FR : ${fr}   RL : ${rl}   RR : ${rr}`;

    const text =
`*${qa}*

📅 Tgl : ${date}
👷 Mekanik : ${mekanik}

🚗 CN : ${cn}
⌛ HM : ${hm}

🩸 *Oil Level* 🩸
Engine oil level : ${engineOil}
Transmission oil level : ${transOil}
Hydraulic oil level : ${hydOil}

⚙ *Engine Area* ⚙
Belt tension : ${belt}
Engine oil leakage : ${oilLeak}
Common Rail Connector : ${crc}
Injector Tube : ${injector}

🚗 *Cabin Area* 🚗
📸 FM Radio : ${radio}
⛔ Fatigue Warning : ${fatigue}
⚡ Power Supply : ${power}
💧 Common Rail Pressure (ON) : ${crp}
🖼️ Power Window : ${pw}

🚗 *Frame Area* 🚗
Operator seat : ${seat}
Hand Rail : ${rail}

💧 *Pressure Suspension (Panel)* 💧
${suspensionLine}

🛞 *Tyre condition :*
Tyre : ${tyre}${tyre==='Bad' && tyreFinding ? ' - ' + tyreFinding : ''}

📝 Validasi & Kelengkapan Check list Service :
- Job Card & Cover Checklist ${jobCard}
- Form Observasi Redo PS ${redo}
- Form QA 1 & QA 7 ${qaForm}
- Form PPM ${ppm}
- Form Check List A ${a}
- Form Check List B ${b}
- Form Check List C ${c}
- Form Backlog ${backlog}
- Form FUI ${fui}
- Form Repair Order ${ro}
- Form Combine Maintenance ${combine}
- Form Service Activity Report ${sar}

*Deviation :*
${deviation}`;

    return text;
  }

  function previewText(){
    const txt = generateText();
    document.getElementById('output').innerText = txt;
    // scroll to preview
    document.getElementById('output').scrollIntoView({behavior:'smooth'});
  }

  function sendWA(){
    const txt = generateText();
    const url = 'https://wa.me/?text=' + encodeURIComponent(txt);
    window.open(url, '_blank');
  }

  function copyText(){
    const txt = generateText();
    navigator.clipboard.writeText(txt).then(()=>{
      alert('✅ Teks berhasil disalin, siap ditempel di WhatsApp.');
    }).catch(err=>{
      alert('Gagal salin ke clipboard: '+err);
    });
  }
</script>

</body>
</html>
