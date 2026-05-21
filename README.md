# pengumuman_kelulusan1
<html lang="id">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0"/>
<title>Pengumuman Kelulusan – SD Negeri 1 Musuk 2025/2026</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet"/>
<script src="https://cdn.tailwindcss.com"></script>
<style>
/* ════════════════════════════════
   ROOT & RESET
════════════════════════════════ */
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:'Poppins',sans-serif;
  background:#080418;
  color:#e9e4ff;
  min-height:100vh;
  overflow-x:hidden;
}

/* ── Ambient gradient backdrop ── */
.bg-ambient{
  position:fixed;inset:0;pointer-events:none;z-index:0;
  background:
    radial-gradient(ellipse 90% 60% at 10%   0%, rgba(88,28,220,.38)  0%,transparent 55%),
    radial-gradient(ellipse 70% 55% at 90%  90%, rgba(124,58,237,.28) 0%,transparent 50%),
    radial-gradient(ellipse 50% 45% at 55%  45%, rgba(167,139,250,.10)0%,transparent 50%),
    radial-gradient(ellipse 40% 35% at 80%  10%, rgba(59,7,100,.35)   0%,transparent 50%);
}

/* ── Stars ── */
.stars-wrap{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.star{
  position:absolute;border-radius:50%;background:#fff;
  animation:twinkle var(--d,3s) ease-in-out var(--dl,0s) infinite;
}
@keyframes twinkle{0%,100%{opacity:.1;transform:scale(1)}50%{opacity:.9;transform:scale(1.5)}}

/* ════════════════════════════════
   HEADER
════════════════════════════════ */
header{
  position:fixed;top:0;left:0;right:0;z-index:200;
  background:linear-gradient(135deg,
    #0c0330 0%,#1e0660 18%,#3b0f8c 38%,#5b21b6 62%,#7c3aed 82%,#8b5cf6 100%);
  box-shadow:0 2px 0 rgba(167,139,250,.2),0 6px 40px rgba(91,33,182,.55);
  padding:.5rem 1rem;
}
.hdr-inner{
  max-width:880px;margin:0 auto;
  display:flex;align-items:center;gap:.85rem;
}

/* Logo slot — invisible, no border/ring/text */
.logo-slot{
  flex-shrink:0;width:68px;height:68px;
  overflow:hidden;cursor:pointer;
  display:flex;align-items:center;justify-content:center;
}
.logo-slot img{width:100%;height:100%;object-fit:contain;display:none}
.logo-label{display:block;width:100%;height:100%;cursor:pointer}
#logoFile{display:none}

.hdr-text{flex:1;text-align:center;min-width:0}
.hdr-title{
  font-size:clamp(.92rem,3.4vw,1.38rem);
  font-weight:800;color:#fff;letter-spacing:.055em;
  text-shadow:0 2px 18px rgba(167,139,250,.7);line-height:1.2;
}
.hdr-school{
  font-size:clamp(.78rem,2.5vw,1.05rem);
  font-weight:700;letter-spacing:.15em;
  background:linear-gradient(90deg,#fde68a 0%,#fff 40%,#fbbf24 60%,#fde68a 100%);
  background-size:200% auto;
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  animation:shimmer 3.5s linear infinite;
}
.hdr-year{
  font-size:clamp(.62rem,1.8vw,.78rem);
  color:rgba(255,255,255,.65);font-weight:400;margin-top:.04rem;
}
@keyframes shimmer{to{background-position:200% center}}

/* balance spacer mirrors logo slot */
.hdr-spacer{width:68px;flex-shrink:0}

/* ════════════════════════════════
   LAYOUT
════════════════════════════════ */
main{position:relative;z-index:1;padding-top:106px;padding-bottom:4rem}
.wrap{max-width:800px;margin:0 auto;padding:0 1rem}

/* ── Glass card ── */
.card{
  background:rgba(18,7,52,.72);
  backdrop-filter:blur(20px);-webkit-backdrop-filter:blur(20px);
  border:1px solid rgba(167,139,250,.16);
  border-radius:1.4rem;
  padding:2rem;
  margin-bottom:1.5rem;
  box-shadow:0 8px 48px rgba(76,29,149,.28);
}

/* ════════════════════════════════
   FORM SECTION
════════════════════════════════ */
#formSection{display:block;text-align:center}
.opened-badge{
  display:inline-flex;align-items:center;gap:.4rem;
  background:linear-gradient(135deg,#064e3b,#059669);
  color:#fff;font-weight:700;
  font-size:clamp(.82rem,2.5vw,.98rem);
  padding:.48rem 1.4rem;border-radius:999px;
  margin-bottom:1.15rem;
  box-shadow:0 4px 22px rgba(5,150,105,.4);
  animation:popIn .5s cubic-bezier(.34,1.56,.64,1);
}
@keyframes popIn{from{transform:scale(.6);opacity:0}to{transform:scale(1);opacity:1}}
.form-hint{font-size:.83rem;color:rgba(200,185,255,.65);margin-bottom:1.2rem;line-height:1.6}
.input-row{display:flex;gap:.65rem;flex-wrap:wrap;justify-content:center;align-items:stretch}
#namaInput{
  flex:1;min-width:200px;max-width:375px;
  padding:.75rem 1.1rem;border-radius:.82rem;
  border:1.5px solid rgba(167,139,250,.35);
  background:rgba(255,255,255,.065);
  color:#fff;font-family:'Poppins',sans-serif;font-size:.9rem;
  outline:none;transition:border-color .2s,box-shadow .2s;
}
#namaInput:focus{border-color:#a78bfa;box-shadow:0 0 0 3px rgba(167,139,250,.2)}
#namaInput::placeholder{color:rgba(200,180,255,.36)}
#cekBtn{
  padding:.75rem 1.75rem;border-radius:.82rem;
  background:linear-gradient(135deg,#7c3aed 0%,#4c1d95 100%);
  color:#fff;font-family:'Poppins',sans-serif;
  font-size:.9rem;font-weight:600;
  border:none;cursor:pointer;white-space:nowrap;
  box-shadow:0 4px 18px rgba(124,58,237,.44);
  transition:transform .14s,box-shadow .14s,filter .14s;
}
#cekBtn:hover{transform:translateY(-2px);box-shadow:0 8px 26px rgba(124,58,237,.6);filter:brightness(1.1)}
#cekBtn:active{transform:translateY(0)}

/* ════════════════════════════════
   RESULT
════════════════════════════════ */
#resultSection{display:none}
.anim-in{animation:slideUp .42s cubic-bezier(.22,1,.36,1)}
@keyframes slideUp{from{opacity:0;transform:translateY(26px)}to{opacity:1;transform:translateY(0)}}

/* ── Certificate base ── */
.cert{
  border-radius:1.3rem;padding:2rem 1.8rem;
  position:relative;overflow:hidden;text-align:center;
}
/* Decorative orbs */
.cert::before,.cert::after{
  content:'';position:absolute;border-radius:50%;pointer-events:none;
}
/* top-right orb */
.cert::before{width:220px;height:220px;top:-90px;right:-70px;opacity:.14}
/* bottom-left orb */
.cert::after{width:160px;height:160px;bottom:-60px;left:-55px;opacity:.11}

/* LULUS — green */
.cert-lulus{
  background:linear-gradient(145deg,#022c22 0%,#064e3b 40%,#065f46 70%,#047857 100%);
  border:2px solid rgba(16,185,129,.5);
  box-shadow:0 10px 50px rgba(16,185,129,.25);
}
.cert-lulus::before{background:#10b981}
.cert-lulus::after{background:#34d399}

/* TIDAK LULUS — red */
.cert-tidak{
  background:linear-gradient(145deg,#3b0000 0%,#7f1d1d 40%,#991b1b 70%,#b91c1c 100%);
  border:2px solid rgba(239,68,68,.45);
  box-shadow:0 10px 50px rgba(239,68,68,.22);
}
.cert-tidak::before{background:#ef4444}
.cert-tidak::after{background:#f87171}

/* Watermark text */
.cert-watermark{
  position:absolute;top:50%;left:50%;
  transform:translate(-50%,-50%) rotate(-30deg);
  font-size:clamp(3rem,12vw,6rem);font-weight:900;
  white-space:nowrap;pointer-events:none;z-index:0;
  letter-spacing:.1em;opacity:.04;user-select:none;
}
.cert-lulus .cert-watermark{color:#10b981}
.cert-tidak .cert-watermark{color:#ef4444}

/* Content z-index fix */
.cert > *:not(.cert-watermark){position:relative;z-index:1}

.cert-icon-wrap{
  width:76px;height:76px;border-radius:50%;
  display:flex;align-items:center;justify-content:center;
  font-size:2.1rem;margin:0 auto .9rem;
}
.cert-lulus .cert-icon-wrap{background:rgba(16,185,129,.2);border:2px solid rgba(16,185,129,.55)}
.cert-tidak .cert-icon-wrap{background:rgba(239,68,68,.18);border:2px solid rgba(239,68,68,.5)}

.cert-title{
  font-size:clamp(1rem,3.8vw,1.5rem);font-weight:800;
  letter-spacing:.07em;margin-bottom:.25rem;
}
.cert-lulus .cert-title{color:#6ee7b7}
.cert-tidak .cert-title{color:#fca5a5}

.cert-meta{
  font-size:clamp(.65rem,2vw,.78rem);
  letter-spacing:.07em;margin-bottom:.1rem;opacity:.65;
}
.cert-lulus .cert-meta{color:#6ee7b7}
.cert-tidak .cert-meta{color:#fca5a5}

.cert-hr{
  height:1px;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,.25),transparent);
  margin:1rem 0;
}
.cert-table{
  width:100%;border-collapse:collapse;
  font-size:clamp(.72rem,2.1vw,.88rem);text-align:left;
}
.cert-table td{padding:.4rem .45rem;vertical-align:top}
.cert-table td:first-child{color:rgba(255,255,255,.52);width:42%}
.cert-table td:last-child{font-weight:600;color:#fff}

.status-tag{
  display:inline-block;padding:.28rem .9rem;
  border-radius:999px;font-weight:700;font-size:.82rem;letter-spacing:.04em;
}
.tag-lulus{background:#10b981;color:#fff}
.tag-tidak{background:#ef4444;color:#fff}

.cert-body{
  font-size:clamp(.7rem,2vw,.8rem);line-height:1.65;margin:.65rem 0;
}
.cert-lulus .cert-body{color:rgba(167,243,208,.72)}
.cert-tidak .cert-body{color:rgba(255,180,180,.7)}

/* Seal ring */
.cert-seal{
  width:70px;height:70px;border-radius:50%;
  border:2.5px dashed rgba(255,255,255,.3);
  margin:1rem auto 0;
  display:flex;align-items:center;justify-content:center;
  font-size:.46rem;color:rgba(255,255,255,.4);
  text-align:center;line-height:1.55;letter-spacing:.04em;
}
.cert-date{font-size:.68rem;color:rgba(255,255,255,.35);margin-top:.55rem}

/* Print button */
.btn-print{
  display:inline-flex;align-items:center;gap:.4rem;
  margin-top:1rem;padding:.52rem 1.2rem;border-radius:.7rem;
  background:rgba(255,255,255,.09);border:1px solid rgba(255,255,255,.22);
  color:#fff;font-family:'Poppins',sans-serif;
  font-size:.78rem;font-weight:500;cursor:pointer;
  transition:background .18s,transform .14s;
}
.btn-print:hover{background:rgba(255,255,255,.17);transform:translateY(-1px)}

/* ── Error box ── */
.err-box{
  text-align:center;padding:2rem 1.5rem;
  background:rgba(120,53,15,.25);
  border:1px solid rgba(245,158,11,.55);
  border-radius:1.1rem;color:#fde68a;
}
.err-icon{font-size:2.6rem;margin-bottom:.6rem}
.err-box h3{font-weight:700;font-size:.98rem;margin-bottom:.4rem}
.err-box p{font-size:.8rem;opacity:.78;line-height:1.65}

/* ════════════════════════════════
   CANVAS OVERLAYS
════════════════════════════════ */
#fwCanvas,#rnCanvas{
  position:fixed;inset:0;
  pointer-events:none;z-index:500;
  display:none;
}

/* ════════════════════════════════
   TOAST
════════════════════════════════ */
#toast{
  position:fixed;bottom:1.5rem;left:50%;transform:translateX(-50%);
  background:#4c1d95;color:#fff;
  padding:.58rem 1.4rem;border-radius:.8rem;
  font-size:.83rem;font-family:'Poppins',sans-serif;
  z-index:999;box-shadow:0 4px 24px rgba(0,0,0,.45);
  transition:opacity .3s;opacity:0;pointer-events:none;
  white-space:nowrap;
}

/* ════════════════════════════════
   FOOTER
════════════════════════════════ */
footer{
  position:relative;z-index:1;text-align:center;
  padding:1.4rem 1rem;
  border-top:1px solid rgba(167,139,250,.1);
  color:rgba(167,139,250,.42);font-size:.74rem;
}

/* ════════════════════════════════
   RESPONSIVE
════════════════════════════════ */
@media(max-width:480px){
  header{padding:.4rem .7rem}
  .logo-slot{width:52px;height:52px}
  .hdr-spacer{width:52px}
  .card{padding:1.3rem 1rem}
  .cert{padding:1.4rem 1rem}
  .input-row{flex-direction:column;align-items:stretch}
  #namaInput,#cekBtn{max-width:100%;width:100%}
}

/* ════════════════════════════════
   PRINT
════════════════════════════════ */
@media print{
  header,footer,#formSection,.btn-print,
  .stars-wrap,.bg-ambient,#fwCanvas,#rnCanvas{display:none!important}
  body{background:#fff;color:#000}
  main{padding-top:0}
  .card{background:#fff;border:none;box-shadow:none;backdrop-filter:none}
  .cert-lulus{background:#f0fdf4!important;border:2px solid #6ee7b7!important}
  .cert-tidak{background:#fef2f2!important;border:2px solid #fca5a5!important}
  .cert-title,.cert-table td,.cert-body{color:#000!important}
}
</style>
</head>
<body>

<div class="bg-ambient"></div>
<div class="stars-wrap" id="starsWrap"></div>
<canvas id="fwCanvas"></canvas>
<canvas id="rnCanvas"></canvas>
<div id="toast"></div>

<!-- ═══════════════ HEADER ═══════════════ -->
<header>
  <div class="hdr-inner">

    <!-- Logo upload area: invisible, no border/text/circle -->
    <div class="logo-slot" id="logoSlot">
      <label class="logo-label" for="logoFile"></label>
      <img id="logoImg" alt="Logo Sekolah"/>
      <input type="file" id="logoFile" accept="image/*"/>
    </div>

    <div class="hdr-text">
      <div class="hdr-title">PENGUMUMAN KELULUSAN</div>
      <div class="hdr-school">SD NEGERI 1 MUSUK</div>
      <div class="hdr-year">Tahun Ajaran 2025/2026</div>
    </div>

    <div class="hdr-spacer"></div>
  </div>
</header>

<!-- ═══════════════ MAIN ═══════════════ -->
<main>
  <div class="wrap">

    <!-- FORM CEK KELULUSAN -->
    <div class="card" id="formSection">
      <div class="opened-badge">🎉 Pengumuman Sudah Dibuka!</div>
      <p class="form-hint">Masukkan nama lengkap siswa sesuai data terdaftar untuk melihat hasil kelulusan.</p>
      <div class="input-row">
        <input type="text" id="namaInput" placeholder="Ketik nama lengkap siswa…"
               autocomplete="off" autocorrect="off" spellcheck="false"/>
        <button id="cekBtn">🔍 Cek Hasil</button>
      </div>
    </div>

    <!-- RESULT -->
    <div id="resultSection">
      <div id="resultInner"></div>
    </div>

  </div>
</main>

<!-- ═══════════════ FOOTER ═══════════════ -->
<footer>
  &copy; 2026 SD Negeri 1 Musuk &mdash; Hak Cipta Dilindungi
</footer>

<script>
/* ════════════════════════════════
   DATA SISWA
════════════════════════════════ */
const DB = [
  {nama:"ADAM MUHAMMAD NIZAM",            kelas:"6",nisn:"3142864504",tempat:"Boyolali, 7 Maret 2014",      status:"LULUS"},
  {nama:"ADZKIA SAUFA NAILA PUTRI",       kelas:"6",nisn:"0148792359",tempat:"Boyolali, 23 Mei 2014",       status:"LULUS"},
  {nama:"AFFAN NAFI MUHAMMAD",            kelas:"6",nisn:"3149680064",tempat:"Boyolali, 13 Januari 2014",   status:"LULUS"},
  {nama:"AKMAL RAMADHANNY",               kelas:"6",nisn:"3133340926",tempat:"Boyolali, 26 Desember 2013",  status:"LULUS"},
  {nama:"ALDEN ZAIDANSYAH SUWARJO",       kelas:"6",nisn:"3137265059",tempat:"Boyolali, 29 Agustus 2013",  status:"LULUS"},
  {nama:"ALMEERA ZAHRA PURNAMA",          kelas:"6",nisn:"3131810822",tempat:"Boyolali, 17 Oktober 2013",  status:"LULUS"},
  {nama:"ARIF WICAKSONO",                 kelas:"6",nisn:"3140525718",tempat:"Boyolali, 3 Maret 2014",      status:"LULUS"},
  {nama:"BRIAN PRABASWARA PRATAMA",       kelas:"6",nisn:"0137415041",tempat:"Boyolali, 8 Oktober 2013",   status:"LULUS"},
  {nama:"DHIFA RASYDAN ARIEF",            kelas:"6",nisn:"0131790767",tempat:"Boyolali, 20 Oktober 2013",  status:"LULUS"},
  {nama:"DIMAS WAHYU SAPUTRO",            kelas:"6",nisn:"3138538832",tempat:"Boyolali, 16 Desember 2013", status:"LULUS"},
  {nama:"FAUZIYAH ALISHA NASTARI",        kelas:"6",nisn:"3135003210",tempat:"Boyolali, 26 April 2013",    status:"LULUS"},
  {nama:"HAFIZ ARFA ROSYAD",              kelas:"6",nisn:"0148192155",tempat:"Boyolali, 25 Januari 2014",  status:"LULUS"},
  {nama:"MAULIDA PUTRI ASKANA SALSABILA", kelas:"6",nisn:"0142534889",tempat:"Boyolali, 17 Januari 2014",  status:"LULUS"},
  {nama:"MUHAMMAD TITO",                  kelas:"6",nisn:"3124234745",tempat:"Boyolali, 6 Agustus 2012",   status:"LULUS"},
  {nama:"NABILA AZZAHRA",                 kelas:"6",nisn:"0133280284",tempat:"Bogor, 22 Juni 2013",         status:"LULUS"},
  {nama:"NAUFAL ADIRA AVRILLIO",          kelas:"6",nisn:"0146172987",tempat:"Pemalang, 15 April 2014",    status:"LULUS"},
  {nama:"PRADIPTA WAHYU MAHARANI",        kelas:"6",nisn:"0143033729",tempat:"Boyolali, 5 Agustus 2014",   status:"LULUS"},
  {nama:"RAFFA DENTA PRADIVTA",           kelas:"6",nisn:"0132275711",tempat:"Boyolali, 26 Juni 2013",     status:"LULUS"},
  {nama:"RAFIF SANIN SARAWI",             kelas:"6",nisn:"3143233030",tempat:"Klaten, 26 April 2014",      status:"LULUS"},
  {nama:"RAZIEF ASLAMA ZIDAN",            kelas:"6",nisn:"0141128913",tempat:"Boyolali, 30 Januari 2014",  status:"LULUS"},
  {nama:"RIDWAN DAVA SAPUTRA",            kelas:"6",nisn:"0131566383",tempat:"Boyolali, 28 Desember 2013", status:"LULUS"},
  {nama:"RINA SULISTYONINGRUM",           kelas:"6",nisn:"3138017800",tempat:"Boyolali, 1 Juli 2013",      status:"LULUS"},
  {nama:"RISKY TIRTA AJI PAMUNGKAS",      kelas:"6",nisn:"0139914719",tempat:"Boyolali, 10 September 2013",status:"LULUS"},
  {nama:"SALSABILA NADHIFA GUMILANG",     kelas:"6",nisn:"0137372252",tempat:"Boyolali, 12 Juni 2013",     status:"LULUS"},
  {nama:"SHEVA PRASETYA ALFATAH",         kelas:"6",nisn:"0131090708",tempat:"Boyolali, 29 Agustus 2013",  status:"LULUS"},
  {nama:"SYIFANA AYU FITRIA",             kelas:"6",nisn:"0125740907",tempat:"Boyolali, 2 September 2012", status:"LULUS"},
  {nama:"YUANITA KIRANA MUKTI",           kelas:"6",nisn:"3143867311",tempat:"Sukoharjo, 6 Maret 2014",   status:"LULUS"},
  {nama:"YUSUF RAHMAT FIRDAUS",           kelas:"6",nisn:"3134423796",tempat:"Boyolali, 2 Mei 2013",       status:"LULUS"},
  {nama:"ZHAVIRA AINUN NISA",             kelas:"6",nisn:"3146902875",tempat:"Boyolali, 5 Maret 2014",     status:"LULUS"},
  {nama:"KAIRA SHABIRA PUTRI",            kelas:"6",nisn:"3132922946",tempat:"Jakarta, 22 Februari 2013",  status:"LULUS"},
  {nama:"EARLYTA RIZKY NUR CAHYANI",      kelas:"6",nisn:"0142621415",tempat:"Boyolali, 10 Januari 2014",  status:"LULUS"},
  {nama:"LARAS SULISTYOWATI",             kelas:"6",nisn:"0137168250",tempat:"Boyolali, 10 Mei 2013",      status:"LULUS"},
];

/* ════════════════════════════════
   STARS
════════════════════════════════ */
(function(){
  const wrap = document.getElementById('starsWrap');
  for(let i=0;i<110;i++){
    const s=document.createElement('div');
    s.className='star';
    const sz=(Math.random()*2.5+.4).toFixed(1);
    s.style.cssText=
      `width:${sz}px;height:${sz}px;`+
      `top:${(Math.random()*100).toFixed(2)}%;`+
      `left:${(Math.random()*100).toFixed(2)}%;`+
      `--d:${(Math.random()*4+2).toFixed(1)}s;`+
      `--dl:${(Math.random()*7).toFixed(1)}s`;
    wrap.appendChild(s);
  }
})();

/* ════════════════════════════════
   LOGO UPLOAD
════════════════════════════════ */
document.getElementById('logoSlot').addEventListener('click',()=>
  document.getElementById('logoFile').click());
document.getElementById('logoFile').addEventListener('change',function(){
  const f=this.files[0];if(!f)return;
  const r=new FileReader();
  r.onload=ev=>{
    const img=document.getElementById('logoImg');
    img.src=ev.target.result;img.style.display='block';
    document.querySelector('.logo-label').style.display='none';
  };
  r.readAsDataURL(f);
});

/* ════════════════════════════════
   CEK KELULUSAN
════════════════════════════════ */
const norm=s=>s.trim().toLowerCase().replace(/\s+/g,' ');
const esc=s=>s.replace(/&/g,'&amp;').replace(/</g,'&lt;').replace(/>/g,'&gt;');
function dateStr(){
  const d=new Date();
  const DY=['Minggu','Senin','Selasa','Rabu','Kamis','Jumat','Sabtu'];
  const MO=['Januari','Februari','Maret','April','Mei','Juni',
            'Juli','Agustus','September','Oktober','November','Desember'];
  return `${DY[d.getDay()]}, ${d.getDate()} ${MO[d.getMonth()]} ${d.getFullYear()}`;
}

document.getElementById('cekBtn').addEventListener('click',cek);
document.getElementById('namaInput').addEventListener('keydown',e=>{if(e.key==='Enter')cek()});

function cek(){
  const q=norm(document.getElementById('namaInput').value);
  if(!q){toast('Silakan masukkan nama siswa terlebih dahulu.');return;}
  stopAnim();
  const rs=document.getElementById('resultSection');
  rs.style.display='none';
  document.getElementById('resultInner').innerHTML='';
  const found=DB.find(s=>norm(s.nama)===q);
  rs.style.display='block';
  if(!found){
    document.getElementById('resultInner').innerHTML=htmlError(
      document.getElementById('namaInput').value.trim());
  } else if(found.status==='LULUS'){
    document.getElementById('resultInner').innerHTML=htmlLulus(found);
    startFireworks();
  } else {
    document.getElementById('resultInner').innerHTML=htmlTidak(found);
    startRain();
  }
  setTimeout(()=>rs.scrollIntoView({behavior:'smooth',block:'nearest'}),100);
}

/* ════════════════════════════════
   HTML TEMPLATES
════════════════════════════════ */
function htmlLulus(s){return`
<div class="cert cert-lulus anim-in">
  <div class="cert-watermark">LULUS</div>
  <div class="cert-icon-wrap">🎓</div>
  <div class="cert-title">SERTIFIKAT KELULUSAN</div>
  <div class="cert-meta">SD NEGERI 1 MUSUK &bull; TAHUN AJARAN 2025/2026</div>
  <div class="cert-hr"></div>
  <table class="cert-table">
    <tr><td>Nama Lengkap</td><td>${esc(s.nama)}</td></tr>
    <tr><td>Kelas</td><td>${esc(s.kelas)}</td></tr>
    <tr><td>NISN</td><td>${esc(s.nisn)}</td></tr>
    <tr><td>Tempat, Tgl Lahir</td><td>${esc(s.tempat)}</td></tr>
    <tr><td>Status Kelulusan</td><td><span class="status-tag tag-lulus">✓ LULUS</span></td></tr>
  </table>
  <div class="cert-hr"></div>
  <p class="cert-body">
    Yang bertanda tangan di bawah ini menerangkan bahwa siswa tersebut telah menyelesaikan
    seluruh program pendidikan dan dinyatakan <strong>LULUS</strong> dari SD Negeri 1 Musuk
    Tahun Ajaran 2025/2026.
  </p>
  <div class="cert-seal">SD N 1<br/>MUSUK<br/>2025/2026</div>
  <p class="cert-date">Dikeluarkan pada: ${dateStr()}</p>
  <button class="btn-print" onclick="window.print()">🖨️ Cetak Sertifikat</button>
</div>`;}

function htmlTidak(s){return`
<div class="cert cert-tidak anim-in">
  <div class="cert-watermark">BELUM LULUS</div>
  <div class="cert-icon-wrap">📋</div>
  <div class="cert-title">SURAT KETERANGAN BELUM LULUS</div>
  <div class="cert-meta">SD NEGERI 1 MUSUK &bull; TAHUN AJARAN 2025/2026</div>
  <div class="cert-hr"></div>
  <table class="cert-table">
    <tr><td>Nama Lengkap</td><td>${esc(s.nama)}</td></tr>
    <tr><td>Kelas</td><td>${esc(s.kelas)}</td></tr>
    <tr><td>NISN</td><td>${esc(s.nisn)}</td></tr>
    <tr><td>Tempat, Tgl Lahir</td><td>${esc(s.tempat)}</td></tr>
    <tr><td>Status Kelulusan</td><td><span class="status-tag tag-tidak">✗ BELUM LULUS</span></td></tr>
  </table>
  <div class="cert-hr"></div>
  <p class="cert-body">
    Siswa yang bersangkutan belum memenuhi persyaratan kelulusan Tahun Ajaran 2025/2026.
    Silakan menghubungi pihak sekolah untuk keterangan dan tindak lanjut lebih lanjut.
  </p>
  <div class="cert-seal">SD N 1<br/>MUSUK<br/>2025/2026</div>
  <p class="cert-date">Dikeluarkan pada: ${dateStr()}</p>
</div>`;}

function htmlError(q){return`
<div class="err-box anim-in">
  <div class="err-icon">🔍</div>
  <h3>Data Tidak Ditemukan</h3>
  <p>Nama "<strong>${esc(q)}</strong>" tidak ditemukan dalam database.<br/>
  Pastikan penulisan nama sesuai dengan data yang terdaftar.</p>
</div>`;}

/* ════════════════════════════════
   TOAST
════════════════════════════════ */
let toastTimer;
function toast(msg){
  const el=document.getElementById('toast');
  el.textContent=msg;el.style.opacity='1';
  clearTimeout(toastTimer);
  toastTimer=setTimeout(()=>{el.style.opacity='0'},2600);
}

/* ════════════════════════════════
   FIREWORKS
════════════════════════════════ */
let fwRAF=null,fwParts=[];
function startFireworks(){
  const cv=document.getElementById('fwCanvas');
  cv.style.display='block';cv.width=innerWidth;cv.height=innerHeight;
  const ctx=cv.getContext('2d');
  fwParts=[];
  const CLR=['#fbbf24','#f87171','#34d399','#60a5fa','#a78bfa','#f9a8d4','#fff','#fb923c','#fde68a'];

  function burst(){
    const x=.15*cv.width+Math.random()*.7*cv.width;
    const y=.05*cv.height+Math.random()*.5*cv.height;
    const c=CLR[Math.floor(Math.random()*CLR.length)];
    const n=50+Math.floor(Math.random()*20);
    for(let i=0;i<n;i++){
      const a=(Math.PI*2/n)*i,sp=Math.random()*7+2;
      fwParts.push({x,y,vx:Math.cos(a)*sp,vy:Math.sin(a)*sp,
        al:1,c,sz:Math.random()*3+.8,star:Math.random()<.3,slow:false});
    }
    for(let i=0;i<7;i++)
      fwParts.push({x:Math.random()*cv.width,y:Math.random()*cv.height*.6,
        vx:(Math.random()-.5)*.5,vy:(Math.random()-.5)*.5,
        al:1,c:'#fde68a',sz:8,star:true,slow:true});
  }

  function drawStar(ctx,x,y,r,c){
    ctx.save();ctx.fillStyle=c;ctx.translate(x,y);ctx.beginPath();
    for(let i=0;i<5;i++){
      ctx.lineTo(Math.cos((18+i*72)*Math.PI/180)*r,-Math.sin((18+i*72)*Math.PI/180)*r);
      ctx.lineTo(Math.cos((54+i*72)*Math.PI/180)*r*.4,-Math.sin((54+i*72)*Math.PI/180)*r*.4);
    }
    ctx.closePath();ctx.fill();ctx.restore();
  }

  let fr=0;
  function loop(){
    ctx.clearRect(0,0,cv.width,cv.height);
    if(++fr%40===0)burst();
    fwParts=fwParts.filter(p=>p.al>.02);
    fwParts.forEach(p=>{
      p.x+=p.vx;p.y+=p.vy;if(!p.slow)p.vy+=.065;
      p.al-=p.slow?.006:.017;
      ctx.globalAlpha=Math.max(0,p.al);
      if(p.star)drawStar(ctx,p.x,p.y,p.sz,p.c);
      else{ctx.beginPath();ctx.arc(p.x,p.y,p.sz,0,Math.PI*2);ctx.fillStyle=p.c;ctx.fill();}
    });
    fwRAF=requestAnimationFrame(loop);
  }
  burst();burst();loop();
  setTimeout(stopAnim,9000);
}

/* ════════════════════════════════
   RAIN
════════════════════════════════ */
let rnRAF=null,drops=[];
function startRain(){
  const cv=document.getElementById('rnCanvas');
  cv.style.display='block';cv.style.opacity='.5';
  cv.width=innerWidth;cv.height=innerHeight;
  const ctx=cv.getContext('2d');
  drops=[];
  for(let i=0;i<140;i++)
    drops.push({x:Math.random()*cv.width,y:Math.random()*cv.height,
      len:Math.random()*18+7,sp:Math.random()*6.5+3,
      al:Math.random()*.5+.2,w:Math.random()*1.2+.3});
  function loop(){
    ctx.clearRect(0,0,cv.width,cv.height);
    drops.forEach(d=>{
      ctx.beginPath();
      ctx.strokeStyle=`rgba(147,197,253,${d.al})`;
      ctx.lineWidth=d.w;
      ctx.moveTo(d.x,d.y);ctx.lineTo(d.x-2,d.y+d.len);ctx.stroke();
      d.y+=d.sp;if(d.y>cv.height){d.y=-d.len;d.x=Math.random()*cv.width;}
    });
    rnRAF=requestAnimationFrame(loop);
  }
  loop();
  setTimeout(stopAnim,7500);
}

function stopAnim(){
  if(fwRAF){cancelAnimationFrame(fwRAF);fwRAF=null;}
  if(rnRAF){cancelAnimationFrame(rnRAF);rnRAF=null;}
  document.getElementById('fwCanvas').style.display='none';
  document.getElementById('rnCanvas').style.display='none';
}

window.addEventListener('resize',()=>{
  ['fwCanvas','rnCanvas'].forEach(id=>{
    const c=document.getElementById(id);
    if(c.style.display!=='none'){c.width=innerWidth;c.height=innerHeight;}
  });
});
</script>
</body>
</html>
