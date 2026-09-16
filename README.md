# safevn.
<!DOCTYPE html>
<html lang="vi">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SafeVN | Phòng chống thiên tai & Giải pháp địa phương</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Be+Vietnam+Pro:ital,wght@0,400;0,500;0,600;0,700;0,800;0,900;1,500&family=Montserrat:wght@700;800;900&display=swap" rel="stylesheet">
<style>
:root{--navy:#031f33;--blue:#0a7ab8;--cyan:#0ea5c9;--sky:#e6f5fb;--green:#0f8a4c;--yellow:#f0b429;--orange:#e07a1b;--red:#d12b2b;--ink:#152836;--muted:#5a7080;--bg:#f3f7fa;--white:#fff;--line:#d0e3ef;--shadow:0 8px 28px rgba(3,31,51,.07);--shadow-lg:0 18px 48px rgba(3,31,51,.12);--radius:18px}
*{box-sizing:border-box;margin:0;padding:0}html{scroll-behavior:smooth}
body{font-family:'Be Vietnam Pro',system-ui,sans-serif;color:var(--ink);background:var(--bg);line-height:1.75;font-size:16px}
h1,h2,h3,h4,.brand,.stat b,.em b{font-family:'Montserrat','Be Vietnam Pro',sans-serif}
a{text-decoration:none;color:inherit;transition:.25s}img{max-width:100%;height:auto;display:block}
.top{background:linear-gradient(90deg,#021624,#031f33);color:#b8dceb;font-size:12.5px;font-weight:600;letter-spacing:.3px}
.topin,.navin,.wrap{max-width:1160px;margin:0 auto;padding:0 22px}
.topin{height:36px;display:flex;justify-content:space-between;align-items:center}
header{position:sticky;top:0;z-index:100;background:rgba(255,255,255,.96);backdrop-filter:blur(14px);box-shadow:0 3px 18px rgba(3,31,51,.06)}
.navin{height:72px;display:flex;align-items:center;justify-content:space-between}
.brand{font-weight:900;color:var(--navy);font-size:21px;display:flex;align-items:center;gap:10px;letter-spacing:-.3px}
.brand span{display:flex;flex-direction:column;line-height:1.12}
.brand em{font-style:normal;color:var(--blue);font-size:10px;letter-spacing:.8px;font-weight:800;font-family:'Be Vietnam Pro',sans-serif}
nav{display:flex;gap:18px;align-items:center}
nav a{font-size:13.5px;font-weight:700;color:#2f4a5c;position:relative;padding:4px 0}
nav a:hover{color:var(--blue)}
nav a::after{content:'';position:absolute;bottom:0;left:0;width:0;height:2.5px;background:var(--blue);border-radius:2px;transition:.3s}
nav a:hover::after{width:100%}
.menu{display:none;border:0;background:none;font-size:26px;cursor:pointer;color:var(--navy)}
.hero{position:relative;color:#fff;background:linear-gradient(145deg,#021624 0%,#064a6e 45%,#0c8fb8 100%);overflow:hidden}
.hero-bg{position:absolute;inset:0;background:url('https://images.unsplash.com/photo-1504608524841-42fe6f032b4b?w=1600&q=80') center/cover no-repeat;opacity:.22}
.hero .wrap{position:relative;padding:78px 22px 88px;display:grid;grid-template-columns:1.2fr .8fr;gap:42px;align-items:center}
.badge{display:inline-flex;align-items:center;gap:6px;padding:6px 14px;border:1px solid rgba(255,255,255,.3);background:rgba(255,255,255,.1);border-radius:40px;font-size:11.5px;font-weight:800;letter-spacing:.4px}
.hero h1{font-size:clamp(34px,5vw,54px);line-height:1.1;margin:16px 0 14px;font-weight:900;letter-spacing:-.5px}
.hero p{font-size:16.5px;color:#d4eef9;max-width:520px;margin-bottom:24px;font-weight:500}
.btn{display:inline-flex;align-items:center;gap:8px;padding:13px 20px;border-radius:12px;font-weight:800;font-size:14.5px;margin:5px 8px 0 0;transition:.25s;font-family:'Be Vietnam Pro',sans-serif}
.gold{background:linear-gradient(135deg,#fbbf24,#f59e0b);color:#1a2a38;box-shadow:0 8px 22px rgba(245,158,11,.4)}
.gold:hover{transform:translateY(-2px);box-shadow:0 12px 28px rgba(245,158,11,.5)}
.outline{border:1.5px solid rgba(255,255,255,.45);color:#fff;background:rgba(255,255,255,.08)}
.outline:hover{background:rgba(255,255,255,.16)}
.panel{background:#fff;color:var(--ink);border-radius:20px;padding:26px 28px;box-shadow:var(--shadow-lg)}
.panel h2{font-size:18px;margin-bottom:14px;color:var(--navy);display:flex;align-items:center;gap:8px}
.panel ul{list-style:none}
.panel li{padding:9px 0;border-bottom:1px solid #eef3f7;font-size:14.5px}
.panel li:last-child{border-bottom:0}
.panel strong{color:var(--red);font-weight:800}
.note{background:#fff8e6;border-left:4px solid var(--yellow);padding:12px 14px;border-radius:8px;margin-top:14px;font-size:13.5px;color:#5a4a1e;font-weight:500}
.stats-wrap{margin-top:-34px;position:relative;z-index:5}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
.stat{background:#fff;border:1px solid var(--line);padding:20px 14px;border-radius:14px;text-align:center;box-shadow:var(--shadow);transition:.3s}
.stat:hover{transform:translateY(-4px);box-shadow:var(--shadow-lg)}
.stat b{font-size:28px;color:var(--blue);display:block;font-weight:900}
.stat span{font-size:12.5px;color:var(--muted);font-weight:700}
section{padding:72px 0}
.sec-label{display:inline-block;font-size:12px;font-weight:800;letter-spacing:1.2px;color:var(--blue);background:var(--sky);padding:5px 12px;border-radius:6px;margin-bottom:10px;text-transform:uppercase}
.title{text-align:center;max-width:780px;margin:0 auto 42px}
.title h2{font-size:30px;color:var(--navy);margin-bottom:10px;font-weight:900;letter-spacing:-.4px;line-height:1.2}
.title p{color:var(--muted);font-size:15.5px;font-weight:500}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
.card{background:#fff;border:1px solid var(--line);border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow);transition:.3s;display:flex;flex-direction:column}
.card:hover{transform:translateY(-5px);box-shadow:var(--shadow-lg)}
.card-img{height:140px;background-size:cover;background-position:center;position:relative}
.card-img::after{content:'';position:absolute;inset:0;background:linear-gradient(to top,rgba(0,0,0,.2),transparent)}
.card-body{padding:18px 20px 22px;flex:1;display:flex;flex-direction:column}
.ico{font-size:26px;margin-bottom:4px}
.card h3{margin:2px 0 10px;color:var(--navy);font-size:17px;font-weight:800}
.card p{font-size:13.8px;color:#51697a;margin-bottom:7px;line-height:1.65}
.card p b{color:var(--ink);font-weight:700}
.tag{display:inline-block;margin-top:10px;background:var(--sky);color:var(--blue);border-radius:6px;padding:3px 9px;font-size:10.5px;font-weight:800;align-self:flex-start}
.band{background:linear-gradient(180deg,#e8f4fa 0%,#f0f8fc 100%);border-top:1px solid #d2eaf5;border-bottom:1px solid #d2eaf5}
.timeline{display:grid;grid-template-columns:repeat(4,1fr);gap:16px}
.time{background:#fff;border:1px solid var(--line);border-radius:14px;padding:22px 18px;box-shadow:var(--shadow);transition:.3s;position:relative}
.time:hover{transform:translateY(-3px)}
.time .num{position:absolute;top:-12px;left:18px;background:var(--blue);color:#fff;font-size:12px;font-weight:800;width:26px;height:26px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-family:'Montserrat',sans-serif}
.time b{color:var(--blue);font-size:11.5px;font-weight:800;letter-spacing:.6px;display:block;margin-top:6px}
.time h3{margin:6px 0 8px;font-size:16px;color:var(--navy);font-weight:800}
.time p{font-size:13.5px;color:var(--muted);line-height:1.6}
.localnav{display:flex;justify-content:center;gap:8px;flex-wrap:wrap;margin-bottom:28px}
.localnav button{border:1.5px solid #b8d4e6;background:#fff;color:var(--navy);padding:10px 16px;border-radius:40px;font-weight:800;font-size:13.5px;cursor:pointer;transition:.25s;font-family:'Be Vietnam Pro',sans-serif}
.localnav button.active,.localnav button:hover{background:var(--blue);color:#fff;border-color:var(--blue);box-shadow:0 6px 16px rgba(10,122,184,.28)}
.local{display:none;animation:fadeIn .35s ease}.local.active{display:block}
@keyframes fadeIn{from{opacity:0;transform:translateY(6px)}to{opacity:1;transform:translateY(0)}}
.localhead{background:#fff;border:1px solid var(--line);border-radius:16px;padding:24px;margin-bottom:18px;box-shadow:var(--shadow);display:flex;gap:18px;align-items:flex-start}
.localhead-img{width:110px;height:82px;border-radius:12px;object-fit:cover;flex-shrink:0}
.localhead h3{font-size:20px;color:var(--navy);margin-bottom:5px;font-weight:800}
.localhead p{color:var(--muted);font-size:14.5px}
.solutions{display:grid;grid-template-columns:1fr 1fr;gap:16px}
.solution{background:#fff;border:1px solid var(--line);border-radius:14px;padding:20px;box-shadow:var(--shadow)}
.solution h4{margin:0 0 11px;color:var(--navy);font-size:15.5px;font-weight:800}
.solution ul{margin:0;padding-left:18px}
.solution li{margin:6px 0;font-size:13.8px;color:#456070;line-height:1.55}
.video-grid{display:grid;grid-template-columns:1.25fr .75fr;gap:22px;align-items:start}
.video-main{background:#fff;border-radius:var(--radius);overflow:hidden;box-shadow:var(--shadow-lg);border:1px solid var(--line)}
.video-main iframe{width:100%;aspect-ratio:16/9;border:0;display:block}
.video-side{display:flex;flex-direction:column;gap:12px}
.video-card{background:#fff;border:1.5px solid var(--line);border-radius:12px;padding:12px;display:flex;gap:12px;align-items:center;box-shadow:var(--shadow);cursor:pointer;transition:.25s}
.video-card:hover,.video-card.active{border-color:var(--blue);transform:translateX(3px)}
.video-thumb{width:86px;height:52px;border-radius:8px;background:#ccc center/cover;flex-shrink:0;position:relative}
.video-thumb::after{content:'▶';position:absolute;inset:0;display:flex;align-items:center;justify-content:center;background:rgba(0,0,0,.32);color:#fff;font-size:16px;border-radius:8px}
.video-card h4{font-size:13.5px;color:var(--navy);margin-bottom:2px;font-weight:700;line-height:1.3}
.video-card span{font-size:11.5px;color:var(--muted)}
.check{background:#fff;border:1px solid var(--line);border-radius:18px;padding:26px 28px;box-shadow:var(--shadow);max-width:720px;margin:0 auto}
.check-intro{text-align:center;margin-bottom:16px;font-size:14px;color:var(--muted)}
.check label{display:flex;gap:12px;padding:11px 6px;border-bottom:1px solid #edf2f5;cursor:pointer;align-items:center;font-size:14.5px;transition:.2s;font-weight:500}
.check label:hover{background:#f7fbfd}.check label:last-of-type{border-bottom:0}
.check input{width:19px;height:19px;accent-color:var(--blue);flex-shrink:0}
.progress{height:11px;background:#e4eef4;border-radius:20px;overflow:hidden;margin:20px 0 8px}
.bar{height:100%;width:0;background:linear-gradient(90deg,var(--blue),var(--cyan));transition:width .4s ease;border-radius:20px}
#txt{font-weight:800;color:var(--navy);font-size:14.5px;font-family:'Montserrat',sans-serif}
.tablewrap{overflow:auto;background:#fff;border:1px solid var(--line);border-radius:14px;box-shadow:var(--shadow)}
table{width:100%;min-width:680px;border-collapse:collapse}
th,td{padding:13px 16px;text-align:left;border-bottom:1px solid var(--line);font-size:14px}
th{background:#e8f5fb;color:var(--navy);font-weight:800;font-size:13.5px}
tr:last-child td{border-bottom:0}tr:hover td{background:#f7fbfd}
.emergency{display:grid;grid-template-columns:repeat(4,1fr);gap:14px}
.em{background:#fff;border:1px solid var(--line);border-radius:14px;text-align:center;padding:22px 12px;box-shadow:var(--shadow);transition:.3s}
.em:hover{transform:translateY(-3px);box-shadow:var(--shadow-lg)}
.em b{font-size:30px;color:var(--red);display:block;font-weight:900;margin-bottom:3px}
.em span{font-size:13.5px;color:var(--muted);font-weight:700}
.success{background:#eaf7f0;border-left:5px solid var(--green);padding:15px 18px;border-radius:10px;margin-top:22px;font-size:14.5px;font-weight:500}
.after-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:16px}
.after-card{background:#fff;border:1px solid var(--line);border-radius:14px;padding:22px;box-shadow:var(--shadow)}
.after-card h4{font-size:16px;color:var(--navy);margin-bottom:10px;font-weight:800}
.after-card ul{padding-left:18px;margin:0}
.after-card li{font-size:13.8px;color:#456070;margin:6px 0;line-height:1.55}
.faq{background:#fff;border:1px solid var(--line);border-radius:12px;margin:10px 0;box-shadow:var(--shadow);overflow:hidden}
.faq summary{padding:15px 18px;font-weight:800;cursor:pointer;color:var(--navy);list-style:none;display:flex;justify-content:space-between;align-items:center;font-size:15px}
.faq summary::-webkit-details-marker{display:none}
.faq summary::after{content:'+';font-size:20px;color:var(--blue);font-weight:500;font-family:'Montserrat',sans-serif}
.faq[open] summary::after{content:'−'}
.faq p{padding:0 18px 16px;margin:0;color:var(--muted);font-size:14.2px;line-height:1.65}
.tips-strip{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:28px}
.tip{background:#fff;border-radius:12px;padding:16px 18px;border:1px solid var(--line);box-shadow:var(--shadow);font-size:13.8px;color:#3d5566}
.tip strong{display:block;color:var(--navy);font-weight:800;margin-bottom:4px;font-size:14px}
.rich-box{background:#fff;border:1px solid var(--line);border-radius:16px;padding:24px 26px;box-shadow:var(--shadow);margin-bottom:20px}
.rich-box h3{font-size:18px;color:var(--navy);margin-bottom:12px;font-weight:800}
.rich-box p,.rich-box li{font-size:14.5px;color:#456070;line-height:1.7}
.rich-box ul{padding-left:20px;margin:10px 0}
.rich-box li{margin:7px 0}
.two-col{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.highlight{background:linear-gradient(135deg,#e8f5fb,#f0f9fc);border-radius:14px;padding:20px 22px;border:1px solid #c5e4f3}
.highlight h4{color:var(--navy);font-size:15px;font-weight:800;margin-bottom:8px}
.highlight p{font-size:14px;color:#3d5566;margin:0}
footer{background:linear-gradient(180deg,#021624,#031f33);color:#a8cfe0;padding:48px 0 0}
.foot{display:grid;grid-template-columns:1.5fr 1fr 1fr;gap:32px}
.foot h3{color:#fff;margin-bottom:12px;font-size:16px;font-weight:800}
.foot p,.foot li{font-size:13.5px;line-height:1.65}
.foot ul{list-style:none;padding:0}.foot li{margin:5px 0}
.copy{text-align:center;border-top:1px solid rgba(255,255,255,.1);padding:20px 22px;margin-top:32px;font-size:12.5px;color:#7aa8bc}
@media(max-width:960px){.hero .wrap,.video-grid,.solutions,.foot,.after-grid,.two-col{grid-template-columns:1fr}.grid{grid-template-columns:1fr 1fr}.stats{grid-template-columns:1fr 1fr}.timeline{grid-template-columns:1fr 1fr}.emergency{grid-template-columns:1fr 1fr}.tips-strip{grid-template-columns:1fr}.localhead{flex-direction:column}.localhead-img{width:100%;height:130px}}
@media(max-width:640px){nav{display:none;position:absolute;top:72px;left:0;right:0;background:#fff;flex-direction:column;padding:14px 18px;box-shadow:0 12px 30px rgba(0,0,0,.1);gap:10px}nav.open{display:flex}.menu{display:block}.grid,.timeline,.stats,.emergency{grid-template-columns:1fr}.hero .wrap{padding-top:48px;padding-bottom:58px}.hero h1{font-size:30px}.topin span:last-child{display:none}.title h2{font-size:24px}}

/* === NÂNG CẤP GIAO DIỆN === */
body{ -webkit-font-smoothing: antialiased; }
.hero h1{ text-shadow: 0 2px 20px rgba(0,0,0,.25); }
.stat{ border-top: 3px solid var(--blue); }
.sec-label{ box-shadow: 0 2px 8px rgba(10,122,184,.12); }
.card{ transition: transform .28s ease, box-shadow .28s ease; }
.card:hover{ border-color: #b8d4e8; }
.localnav button{ box-shadow: 0 2px 8px rgba(0,0,0,.04); }
.time{ border-top: 3px solid transparent; }
.time:hover{ border-top-color: var(--blue); }
.check label{ border-radius: 8px; margin: 2px 0; }
.check label:has(input:checked){ background: #eef8f3; }
.faq summary{ transition: background .2s; }
.faq summary:hover{ background: #f5fafd; }
.em{ border-bottom: 3px solid transparent; }
.em:hover{ border-bottom-color: var(--red); }
.btn{ letter-spacing: .2px; }
.gold:active, .outline:active{ transform: scale(.98); }

/* Quick access strip */
.quick{ display:flex; flex-wrap:wrap; gap:10px; justify-content:center; margin:28px 0 8px; }
.quick a{
  display:inline-flex; align-items:center; gap:6px;
  padding:10px 16px; background:#fff; border:1.5px solid var(--line);
  border-radius:40px; font-size:13px; font-weight:700; color:var(--navy);
  box-shadow: var(--shadow); transition:.25s;
}
.quick a:hover{ background:var(--blue); color:#fff; border-color:var(--blue); transform:translateY(-2px); }

/* Back to top */
#topBtn{
  position:fixed; bottom:24px; right:24px; z-index:90;
  width:48px; height:48px; border-radius:50%; border:0;
  background:var(--blue); color:#fff; font-size:20px; cursor:pointer;
  box-shadow:0 8px 24px rgba(10,122,184,.35); opacity:0; pointer-events:none;
  transition: opacity .3s, transform .25s;
}
#topBtn.show{ opacity:1; pointer-events:auto; }
#topBtn:hover{ transform:translateY(-3px); background:#086a9e; }

/* Section fade-in feel */
section{ scroll-margin-top: 80px; }

/* Stronger table */
th{ letter-spacing: .3px; }
td:first-child{ font-weight:700; color:var(--blue); }

/* App highlight box */
.app-badge{
  display:inline-block; background:linear-gradient(135deg,#0a7ab8,#0ea5c9);
  color:#fff; font-size:11px; font-weight:800; padding:4px 10px;
  border-radius:6px; letter-spacing:.4px; margin-bottom:8px;
}

@media(max-width:640px){
  #topBtn{ bottom:16px; right:16px; width:44px; height:44px; }
  .quick a{ font-size:12px; padding:8px 12px; }
}


/* ========== GIAO DIỆN ĐẸP HƠN ========== */
:root{
  --navy:#021a2e;
  --blue:#0b7ec4;
  --cyan:#12b0d8;
  --sky:#e8f6fc;
  --green:#0d9a58;
  --yellow:#f5b820;
  --orange:#ee8530;
  --red:#e03a3a;
  --ink:#132838;
  --muted:#5a7385;
  --bg:#f0f6fa;
  --white:#ffffff;
  --line:#cfe3f0;
  --shadow:0 4px 20px rgba(2,26,46,.06);
  --shadow-lg:0 16px 48px rgba(2,26,46,.12);
  --radius:20px;
}
body{
  background:
    radial-gradient(ellipse 80% 50% at 50% -20%, #d4eef9 0%, transparent 55%),
    var(--bg);
}
header{
  background:rgba(255,255,255,.92);
  border-bottom:1px solid rgba(207,227,240,.6);
}
.brand{ font-size:22px; letter-spacing:-.4px; }
.brand em{ color:var(--cyan); }
nav a{ font-size:13px; font-weight:700; padding:6px 2px; }
.hero{
  background:linear-gradient(145deg, #011525 0%, #053d5c 40%, #0a8bb8 100%);
  position:relative;
}
.hero::before{
  content:'';
  position:absolute; inset:0;
  background:
    radial-gradient(circle at 20% 80%, rgba(18,176,216,.25) 0%, transparent 40%),
    radial-gradient(circle at 80% 20%, rgba(245,184,32,.12) 0%, transparent 35%);
  pointer-events:none;
}
.hero .wrap{ position:relative; z-index:1; }
.hero h1{
  background:linear-gradient(180deg, #fff 30%, #b8e8f8 100%);
  -webkit-background-clip:text; -webkit-text-fill-color:transparent;
  background-clip:text;
  filter:drop-shadow(0 2px 8px rgba(0,0,0,.2));
}
.badge{
  background:rgba(255,255,255,.15);
  backdrop-filter:blur(8px);
  border-color:rgba(255,255,255,.4);
}
.panel{
  border:1px solid rgba(255,255,255,.5);
  box-shadow:0 24px 60px rgba(0,0,0,.2);
}
.gold{
  background:linear-gradient(135deg, #ffd54f 0%, #f5a623 100%);
  box-shadow:0 8px 28px rgba(245,166,35,.45);
}
.gold:hover{ box-shadow:0 12px 36px rgba(245,166,35,.55); }
.stat{
  border:none;
  box-shadow:var(--shadow-lg);
  border-radius:16px;
  position:relative;
  overflow:hidden;
}
.stat::before{
  content:'';
  position:absolute; top:0; left:0; right:0; height:3px;
  background:linear-gradient(90deg, var(--blue), var(--cyan));
}
.stat b{
  background:linear-gradient(135deg, var(--blue), var(--cyan));
  -webkit-background-clip:text; -webkit-text-fill-color:transparent;
  background-clip:text;
  font-size:30px;
}
.title h2{
  font-size:32px;
  letter-spacing:-.5px;
}
.sec-label{
  background:linear-gradient(135deg, #e0f2fa, #d0ebf7);
  color:var(--blue);
  border:1px solid #b8dcec;
  box-shadow:0 2px 10px rgba(11,126,196,.1);
}
.card{
  border:none;
  box-shadow:var(--shadow);
  border-radius:var(--radius);
  overflow:hidden;
}
.card:hover{
  box-shadow:var(--shadow-lg);
  transform:translateY(-6px);
}
.card-img{ height:148px; }
.card-body{ padding:20px 22px 24px; }
.card h3{ font-size:17.5px; }
.tag{
  background:linear-gradient(135deg, #e8f6fc, #d8eef8);
  border:1px solid #b8dcec;
}
.time{
  border:none;
  box-shadow:var(--shadow);
  border-radius:16px;
  overflow:hidden;
}
.time .num{
  background:linear-gradient(135deg, var(--blue), var(--cyan));
  box-shadow:0 4px 12px rgba(11,126,196,.35);
}
.localnav button{
  border:1.5px solid #c5dde9;
  box-shadow:0 2px 10px rgba(0,0,0,.04);
}
.localnav button.active,
.localnav button:hover{
  background:linear-gradient(135deg, var(--blue), #0a9bc8);
  border-color:transparent;
  box-shadow:0 6px 20px rgba(11,126,196,.35);
}
.localhead{
  border:none;
  box-shadow:var(--shadow-lg);
  border-radius:18px;
}
.solution{
  border:none;
  box-shadow:var(--shadow);
  border-radius:16px;
  transition:transform .25s, box-shadow .25s;
}
.solution:hover{
  transform:translateY(-3px);
  box-shadow:var(--shadow-lg);
}
.video-main{
  border:none;
  box-shadow:var(--shadow-lg);
  border-radius:18px;
}
.video-card{
  border:1.5px solid var(--line);
  border-radius:14px;
}
.video-card.active{
  border-color:var(--blue);
  box-shadow:0 4px 16px rgba(11,126,196,.15);
}
.check{
  border:none;
  box-shadow:var(--shadow-lg);
  border-radius:20px;
}
.progress{
  height:12px;
  background:#e0eef5;
}
.bar{
  background:linear-gradient(90deg, var(--blue), var(--cyan), #2dd4bf);
}
.tablewrap{
  border:none;
  box-shadow:var(--shadow-lg);
  border-radius:16px;
}
th{
  background:linear-gradient(180deg, #e8f5fb, #dceff8);
}
.em{
  border:none;
  box-shadow:var(--shadow);
  border-radius:16px;
}
.em b{
  background:linear-gradient(135deg, #e03a3a, #f06060);
  -webkit-background-clip:text; -webkit-text-fill-color:transparent;
  background-clip:text;
}
.after-card{
  border:none;
  box-shadow:var(--shadow);
  border-radius:16px;
  transition:transform .25s;
}
.after-card:hover{ transform:translateY(-3px); box-shadow:var(--shadow-lg); }
.faq{
  border:none;
  box-shadow:var(--shadow);
  border-radius:14px;
}
.faq summary:hover{ background:#f0f8fc; }
.rich-box{
  border:none;
  box-shadow:var(--shadow);
  border-radius:18px;
  background:linear-gradient(180deg, #fff 0%, #f8fcfe 100%);
}
.highlight{
  background:linear-gradient(135deg, #e4f3fa, #eef8fc);
  border:1px solid #b8dcec;
  border-radius:16px;
  box-shadow:0 2px 12px rgba(11,126,196,.06);
}
.tip{
  border:none;
  box-shadow:var(--shadow);
  border-radius:14px;
  transition:transform .25s;
}
.tip:hover{ transform:translateY(-2px); }
.quick a{
  border:none;
  box-shadow:var(--shadow);
  background:#fff;
}
.quick a:hover{
  background:linear-gradient(135deg, var(--blue), var(--cyan));
  box-shadow:0 8px 24px rgba(11,126,196,.3);
}
#topBtn{
  background:linear-gradient(135deg, var(--blue), var(--cyan));
  box-shadow:0 8px 28px rgba(11,126,196,.4);
}
.app-badge{
  background:linear-gradient(135deg, #0b7ec4, #12b0d8);
  box-shadow:0 2px 10px rgba(11,126,196,.3);
}
.band{
  background:linear-gradient(180deg, #e4f2f9 0%, #eef7fb 50%, #f0f6fa 100%);
  border-top:1px solid #c5e0ee;
  border-bottom:1px solid #c5e0ee;
}
footer{
  background:linear-gradient(180deg, #011525, #021a2e 40%, #032438);
}
.note{
  border-radius:10px;
  box-shadow:0 2px 8px rgba(245,184,32,.15);
}
.success{
  border-radius:12px;
  box-shadow:0 2px 12px rgba(13,154,88,.1);
}
/* Soft section separators */
section + section{ position:relative; }


/* ========== ANIMATION MƯỢT ========== */
@media (prefers-reduced-motion: no-preference) {
  html{ scroll-behavior: smooth; }

  /* Hero entrance */
  .hero .badge{
    animation: fadeDown .7s ease both;
  }
  .hero h1{
    animation: fadeUp .8s .1s ease both;
  }
  .hero p{
    animation: fadeUp .8s .2s ease both;
  }
  .hero .btn{
    animation: fadeUp .7s .35s ease both;
  }
  .hero .panel{
    animation: fadeLeft .9s .2s ease both;
  }

  /* Stats pop */
  .stat{
    animation: fadeUp .6s ease both;
  }
  .stats .stat:nth-child(1){ animation-delay: .05s; }
  .stats .stat:nth-child(2){ animation-delay: .12s; }
  .stats .stat:nth-child(3){ animation-delay: .19s; }
  .stats .stat:nth-child(4){ animation-delay: .26s; }

  /* Reveal on scroll */
  .reveal{
    opacity: 0;
    transform: translateY(28px);
    transition: opacity .7s ease, transform .7s ease;
  }
  .reveal.in{
    opacity: 1;
    transform: translateY(0);
  }
  .reveal-delay-1{ transition-delay: .08s; }
  .reveal-delay-2{ transition-delay: .16s; }
  .reveal-delay-3{ transition-delay: .24s; }

  /* Cards stagger feel when revealed */
  .card, .time, .solution, .after-card, .tip, .em, .faq{
    transition: transform .35s cubic-bezier(.22,.68,0,1.2), box-shadow .35s ease, opacity .5s ease, border-color .25s ease;
  }
  .card:hover, .time:hover, .solution:hover, .after-card:hover, .tip:hover, .em:hover{
    transition-duration: .3s;
  }

  /* Buttons */
  .btn, .localnav button, .quick a, #topBtn{
    transition: transform .25s cubic-bezier(.22,.68,0,1.2), box-shadow .25s ease, background .25s ease, color .2s ease, border-color .2s ease;
  }
  .btn:active, .localnav button:active, .quick a:active{
    transform: scale(.97);
  }

  /* Checklist */
  .check label{
    transition: background .25s ease, transform .2s ease;
  }
  .check label:hover{ transform: translateX(4px); }
  .bar{
    transition: width .5s cubic-bezier(.22,1,.36,1);
  }
  .check input{
    transition: transform .2s ease;
  }
  .check input:checked{
    transform: scale(1.1);
  }

  /* Progress pulse when complete */
  @keyframes pulseSoft{
    0%,100%{ box-shadow: 0 0 0 0 rgba(11,126,196,.35); }
    50%{ box-shadow: 0 0 0 8px rgba(11,126,196,0); }
  }
  .bar.done{
    animation: pulseSoft 1.2s ease 1;
  }

  /* Nav underline smooth already exists; enhance */
  nav a::after{
    transition: width .35s cubic-bezier(.22,1,.36,1);
  }

  /* Local switch */
  .local{
    animation: none;
  }
  .local.active{
    animation: fadeInUp .45s ease both;
  }

  /* Video cards */
  .video-card{
    transition: transform .3s ease, border-color .25s ease, box-shadow .3s ease;
  }
  .video-card:hover{ transform: translateX(6px); }

  /* FAQ open */
  .faq p{
    animation: fadeIn .35s ease;
  }

  /* Top button */
  #topBtn{
    transition: opacity .35s ease, transform .3s cubic-bezier(.22,.68,0,1.2), background .25s ease;
  }
  #topBtn.show:hover{ transform: translateY(-4px) scale(1.05); }

  /* Keyframes */
  @keyframes fadeUp{
    from{ opacity:0; transform: translateY(24px); }
    to{ opacity:1; transform: translateY(0); }
  }
  @keyframes fadeDown{
    from{ opacity:0; transform: translateY(-16px); }
    to{ opacity:1; transform: translateY(0); }
  }
  @keyframes fadeLeft{
    from{ opacity:0; transform: translateX(32px); }
    to{ opacity:1; transform: translateX(0); }
  }
  @keyframes fadeInUp{
    from{ opacity:0; transform: translateY(12px); }
    to{ opacity:1; transform: translateY(0); }
  }
  @keyframes fadeIn{
    from{ opacity:0; }
    to{ opacity:1; }
  }
}

@media (prefers-reduced-motion: reduce){
  *, *::before, *::after{
    animation-duration: .01ms !important;
    transition-duration: .01ms !important;
  }
}


/* ========== TÍNH NĂNG ĐỘT PHÁ ========== */
.sos-bar{
  position:fixed; left:0; right:0; bottom:0; z-index:95;
  background:linear-gradient(90deg,#8b1a1a,#c62828 40%,#8b1a1a);
  color:#fff; padding:8px 12px;
  display:flex; align-items:center; justify-content:center; gap:10px; flex-wrap:wrap;
  box-shadow:0 -4px 24px rgba(0,0,0,.25);
  font-size:13px; font-weight:700;
  transform:translateY(110%);
  transition:transform .4s cubic-bezier(.22,1,.36,1);
}
.sos-bar.show{ transform:translateY(0); }
.sos-bar a{
  display:inline-flex; align-items:center; gap:4px;
  background:rgba(255,255,255,.18); color:#fff;
  padding:6px 12px; border-radius:20px; font-weight:800;
  border:1px solid rgba(255,255,255,.3);
  transition:.2s;
}
.sos-bar a:hover{ background:#fff; color:#c62828; }
.sos-close{
  background:transparent; border:0; color:#fff; font-size:18px;
  cursor:pointer; opacity:.8; margin-left:4px;
}
.sos-toggle{
  position:fixed; bottom:80px; left:16px; z-index:94;
  background:linear-gradient(135deg,#e03a3a,#c62828);
  color:#fff; border:0; border-radius:50%;
  width:52px; height:52px; font-size:22px; cursor:pointer;
  box-shadow:0 8px 28px rgba(198,40,40,.45);
  transition:transform .25s;
}
.sos-toggle:hover{ transform:scale(1.08); }
body.has-sos{ padding-bottom:56px; }
#topBtn{ bottom:72px; }

.quiz-box{
  background:#fff; border-radius:20px; padding:28px;
  box-shadow:var(--shadow-lg); max-width:720px; margin:0 auto;
}
.quiz-q{ font-size:16px; font-weight:700; color:var(--navy); margin-bottom:14px; }
.quiz-opts{ display:flex; flex-direction:column; gap:8px; margin-bottom:18px; }
.quiz-opts label{
  display:flex; gap:10px; align-items:center;
  padding:12px 14px; border:1.5px solid var(--line); border-radius:12px;
  cursor:pointer; font-size:14.5px; transition:.2s; font-weight:500;
}
.quiz-opts label:hover, .quiz-opts label.active{
  border-color:var(--blue); background:#f0f8fc;
}
.quiz-nav{ display:flex; gap:10px; justify-content:space-between; align-items:center; }
.quiz-nav button{
  padding:11px 20px; border-radius:12px; font-weight:800; font-size:14px;
  border:0; cursor:pointer; font-family:inherit; transition:.25s;
}
.quiz-prev{ background:#e8eef3; color:var(--navy); }
.quiz-next, .quiz-submit{
  background:linear-gradient(135deg,var(--blue),var(--cyan)); color:#fff;
  box-shadow:0 4px 16px rgba(11,126,196,.3);
}
.quiz-next:hover, .quiz-submit:hover{ transform:translateY(-2px); }
.quiz-progress{ height:6px; background:#e4eef4; border-radius:10px; margin-bottom:20px; overflow:hidden; }
.quiz-progress div{
  height:100%; width:0; background:linear-gradient(90deg,var(--blue),var(--cyan));
  transition:width .4s ease; border-radius:10px;
}
.quiz-result{
  text-align:center; padding:20px 10px;
}
.quiz-result .score{
  font-size:48px; font-weight:900; font-family:'Montserrat',sans-serif;
  background:linear-gradient(135deg,var(--blue),var(--cyan));
  -webkit-background-clip:text; -webkit-text-fill-color:transparent; background-clip:text;
}
.quiz-result .level{
  display:inline-block; margin:10px 0 16px; padding:6px 16px;
  border-radius:20px; font-weight:800; font-size:14px;
}
.level-low{ background:#fde8e8; color:#c62828; }
.level-mid{ background:#fff3e0; color:#e65100; }
.level-high{ background:#e8f5e9; color:#2e7d32; }
.quiz-tips{ text-align:left; margin-top:16px; padding:16px; background:#f7fbfd; border-radius:12px; font-size:14px; }

.plan-form{
  background:#fff; border-radius:20px; padding:28px;
  box-shadow:var(--shadow-lg); max-width:720px; margin:0 auto;
}
.plan-form label{ display:block; font-weight:700; font-size:13.5px; color:var(--navy); margin:12px 0 6px; }
.plan-form input, .plan-form select, .plan-form textarea{
  width:100%; padding:11px 14px; border:1.5px solid var(--line);
  border-radius:10px; font-size:14.5px; font-family:inherit;
  transition:border-color .2s; background:#fafcfd;
}
.plan-form input:focus, .plan-form select:focus, .plan-form textarea:focus{
  outline:0; border-color:var(--blue); background:#fff;
}
.plan-form textarea{ min-height:70px; resize:vertical; }
.plan-out{
  margin-top:20px; padding:20px; background:linear-gradient(180deg,#f0f9fc,#fff);
  border:1.5px dashed var(--blue); border-radius:14px; display:none;
}
.plan-out h4{ color:var(--navy); margin-bottom:10px; }
.plan-out pre{
  white-space:pre-wrap; font-family:'Be Vietnam Pro',sans-serif;
  font-size:14px; line-height:1.7; color:#2a4050; margin:0;
}
.plan-actions{ display:flex; gap:10px; margin-top:14px; flex-wrap:wrap; }
.plan-actions button{
  padding:10px 18px; border-radius:10px; font-weight:800; font-size:13.5px;
  border:0; cursor:pointer; font-family:inherit;
}
.btn-copy{ background:var(--blue); color:#fff; }
.btn-print{ background:#e8eef3; color:var(--navy); }

.filter-bar{
  display:flex; flex-wrap:wrap; gap:8px; justify-content:center; margin-bottom:24px;
}
.filter-bar button{
  padding:8px 14px; border-radius:20px; border:1.5px solid var(--line);
  background:#fff; font-weight:700; font-size:13px; cursor:pointer;
  font-family:inherit; color:var(--navy); transition:.25s;
}
.filter-bar button.active, .filter-bar button:hover{
  background:linear-gradient(135deg,var(--blue),var(--cyan));
  color:#fff; border-color:transparent;
}
.card.dimmed{ opacity:.35; transform:scale(.97); pointer-events:none; }

@media(max-width:640px){
  .sos-toggle{ bottom:70px; left:12px; width:48px; height:48px; }
  .sos-bar{ font-size:12px; gap:6px; }
  .sos-bar a{ padding:5px 10px; }
}


/* ========== GIÁO DỤC ========== */
.edu-tabs{ display:flex; flex-wrap:wrap; gap:8px; justify-content:center; margin-bottom:24px; }
.edu-tabs button{
  padding:10px 18px; border-radius:24px; border:1.5px solid var(--line);
  background:#fff; font-weight:800; font-size:13.5px; cursor:pointer;
  font-family:inherit; color:var(--navy); transition:.25s;
}
.edu-tabs button.active, .edu-tabs button:hover{
  background:linear-gradient(135deg,var(--blue),var(--cyan));
  color:#fff; border-color:transparent;
  box-shadow:0 6px 18px rgba(11,126,196,.28);
}
.edu-panel{ display:none; animation:fadeInUp .4s ease both; }
.edu-panel.active{ display:block; }
.should-grid{ display:grid; grid-template-columns:1fr 1fr; gap:12px; margin-top:12px; }
.should-card{
  border-radius:14px; padding:14px 16px; font-size:14px; line-height:1.55;
  font-weight:500;
}
.should-yes{ background:#e8f7ef; border:1px solid #a8dfc0; color:#1b5e3a; }
.should-no{ background:#fdeeee; border:1px solid #f0b0b0; color:#8b1a1a; }
.should-card b{ display:block; margin-bottom:4px; font-size:13px; }
.lesson-box{
  background:#fff; border-radius:16px; padding:22px; box-shadow:var(--shadow);
  margin-bottom:14px; border-left:4px solid var(--blue);
}
.lesson-box h4{ color:var(--navy); margin-bottom:8px; font-size:15.5px; }
.lesson-box ol, .lesson-box ul{ padding-left:20px; margin:8px 0; }
.lesson-box li{ margin:5px 0; font-size:14px; color:#3d5566; }
.age-tag{
  display:inline-block; font-size:11px; font-weight:800; padding:3px 10px;
  border-radius:6px; background:var(--sky); color:var(--blue); margin-bottom:8px;
}
@media(max-width:640px){ .should-grid{ grid-template-columns:1fr; } }

</style>
</head>
<body>
<div class="top"><div class="topin"><span>🇻🇳 SAFEVIETNAM • GIÁO DỤC CỘNG ĐỒNG</span><span>Phòng ngừa tốt — Giảm thiệt hại — Phục hồi an toàn</span></div></div>
<header>
<div class="navin">
<a class="brand" href="#">🛡️<span>SafeVN<em>PHÒNG CHỐNG THIÊN TAI</em></span></a>
<nav id="mainNav">
<a href="#thientai">Rủi ro</a>
<a href="#dia-phuong">Địa phương</a>
<a href="#chuan-bi">Chuẩn bị</a>
<a href="#cong-cu">Công cụ</a>
<a href="#ung-dung">Ứng dụng</a>
<a href="#khancap">Khẩn cấp</a>
<a href="#sau-thien-tai">Phục hồi</a>
<a href="#giao-duc">Giáo dục</a>
</nav>
<button class="menu" onclick="document.getElementById('mainNav').classList.toggle('open')">☰</button>
</div>
</header>

<section class="hero">
<div class="hero-bg"></div>
<div class="wrap">
<div>
<span class="badge">🛡️ PHÒNG CHỐNG THIÊN TAI • CỘNG ĐỒNG</span>
<h1>Hiểu thiên tai.<br>Chuẩn bị đúng.<br>Hành động an toàn.</h1>
<p>SafeVN giúp bạn nắm rõ các loại thiên tai thường gặp ở Việt Nam, cách chuẩn bị theo từng vùng, và những việc cần làm khi có tình huống. Nội dung ngắn gọn, dễ hiểu, dành cho mọi nhà.</p>
<a class="btn gold" href="#dia-phuong">📍 Xem giải pháp địa phương</a>
<a class="btn outline" href="#thientai">🌪️ Tìm hiểu thiên tai</a>
</div>
<div class="panel">
<h2>🚨 Bốn nguyên tắc cần nhớ</h2>
<ul>
<li><strong>Giữ bình tĩnh:</strong> kiểm tra thông tin chính thức rồi mới hành động.</li>
<li><strong>Đừng chủ quan:</strong> có cảnh báo là làm ngay, dù trời còn yên.</li>
<li><strong>Đừng mạo hiểm:</strong> tránh vùng nguy hiểm, đừng tự ý cứu hộ khi chưa an toàn.</li>
<li><strong>Ưu tiên con người:</strong> bảo vệ trẻ em, người già và người cần hỗ trợ trước.</li>
</ul>
<div class="note">⚠️ Luôn làm theo hướng dẫn và lệnh sơ tán của chính quyền địa phương. Tin trên mạng cần đối chiếu với nguồn chính thống.</div>
</div>
</div>
</section>

<div class="wrap stats-wrap">
<div class="stats">
<div class="stat"><b>01</b><span>Phòng ngừa</span></div>
<div class="stat"><b>02</b><span>Chuẩn bị</span></div>
<div class="stat"><b>03</b><span>Ứng phó</span></div>
<div class="stat"><b>04</b><span>Phục hồi</span></div>
</div>
</div>

<div class="wrap">

<div class="wrap" style="margin-top:8px;margin-bottom:8px">
<p style="text-align:center;font-size:13.5px;color:var(--muted);font-weight:600;line-height:1.8">
Lộ trình trên trang: <span style="color:var(--blue)">① Nhận biết rủi ro</span> → <span style="color:var(--blue)">② Giải pháp theo vùng</span> → <span style="color:var(--blue)">③ Chuẩn bị</span> → <span style="color:var(--blue)">④ Ứng phó & phục hồi</span>
</p>
</div>

<div class="quick">
<a href="#thientai">🌪️ Rủi ro</a>
<a href="#dia-phuong">📍 Địa phương</a>
<a href="#chuan-bi">🎒 Chuẩn bị</a>
<a href="#cong-cu">🛠️ Công cụ</a>
<a href="#khancap">📞 Khẩn cấp</a>
<a href="#sau-thien-tai">♻️ Phục hồi</a>
<a href="#giao-duc">📚 Giáo dục</a>
</div>
</div>

<section id="thientai">
<div class="wrap">
<div class="title">
<span class="sec-label">Phần 1</span>
<h2>Các loại thiên tai và cách ứng phó</h2>
<p>Việt Nam thường xuyên gặp bão, lũ, sạt lở, hạn… Mỗi loại có đặc điểm riêng. Biết rõ giúp bạn không chủ quan và chọn đúng việc cần làm.</p>
</div>
<div class="rich-box">
<h3>📌 Vì sao cần biết rõ từng loại?</h3>
<p>Hiểu đúng thì đỡ hoảng loạn và hành động đúng lúc. Lũ quét đến rất nhanh nên phải sơ tán sớm. Bão thường được báo trước vài ngày nên còn thời gian gia cố nhà cửa. Sạt lở thường có dấu hiệu (vết nứt, cây nghiêng) nếu để ý sẽ phát hiện kịp.</p>
</div>
<div class="grid">
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1504608524841-42fe6f032b4b?w=600&q=80')"></div><div class="card-body"><div class="ico">🌀</div><h3>Bão và áp thấp nhiệt đới</h3><p><b>Nguy cơ:</b> gió mạnh, mưa lớn kéo dài, nước dâng ven biển, ngập, cây đổ, nhà hư, mất điện.</p><p><b>Dấu hiệu:</b> bản tin cảnh báo từ đài khí tượng, gió bắt đầu mạnh, mây dày.</p><p><b>Nên làm:</b> gia cố mái cửa, cất đồ dễ bay, neo đậu tàu thuyền, dự trữ nước và đồ ăn 3–5 ngày, sạc đầy điện thoại, sẵn sàng sơ tán.</p><p><b>Không nên:</b> ra ngoài khi gió mạnh, đứng gần cây hay cột điện, cố ra khơi.</p><span class="tag">Ven biển • Đồng bằng • Miền Trung</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1547683905-f686c993aae5?w=600&q=80')"></div><div class="card-body"><div class="ico">🌊</div><h3>Lũ, lũ quét, ngập lụt</h3><p><b>Nguy cơ:</b> nước lên nhanh (đặc biệt lũ quét), dòng chảy xiết, đường bị cắt, mất điện, nước bị ô nhiễm, nguy cơ đuối nước.</p><p><b>Dấu hiệu:</b> mưa lớn lâu, nước sông suối dâng đột ngột, nước đổi màu đục.</p><p><b>Nên làm:</b> theo dõi cảnh báo, chuyển lên chỗ cao, kê cao đồ điện, bảo vệ nguồn nước sạch.</p><p><b>Không nên:</b> lội qua nước sâu hay chảy xiết, vào hầm ngập, để trẻ gần bờ sông.</p><span class="tag">Sông • Suối • Đô thị • Miền núi</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1506905925346-21bda4d32df4?w=600&q=80')"></div><div class="card-body"><div class="ico">⛰️</div><h3>Sạt lở đất</h3><p><b>Nguy cơ:</b> đất đá trượt sau mưa lớn, nhất là sườn dốc, taluy đường, nhà ven đồi.</p><p><b>Dấu hiệu:</b> vết nứt trên đất hay tường, cây nghiêng lạ, tiếng động từ lòng đất, nước suối đột ngột đục.</p><p><b>Nên làm:</b> theo dõi khi mưa lớn, di dời ngay khi thấy dấu hiệu lạ, báo chính quyền.</p><p><b>Không nên:</b> ở lại chỗ đã có nguy cơ, xây sát taluy chưa gia cố.</p><span class="tag">Miền núi • Trung du</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1605727216801-e27ce1d0cc28?w=600&q=80')"></div><div class="card-body"><div class="ico">⚡</div><h3>Dông, lốc, sét</h3><p><b>Nguy cơ:</b> gió giật đột ngột, sét đánh, cây đổ, mái tôn bay, nguy hiểm khi đứng chỗ trống.</p><p><b>Dấu hiệu:</b> mây đen dày, gió đổi hướng nhanh, sấm sét gần.</p><p><b>Nên làm:</b> trú trong nhà chắc, rút phích điện, tránh cây cao, cột điện và mặt nước.</p><p><b>Không nên:</b> đứng dưới tán cây, dùng điện thoại ngoài trời khi đang sấm sét.</p><span class="tag">Toàn quốc</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=600&q=80')"></div><div class="card-body"><div class="ico">☀️</div><h3>Nắng nóng và hạn hán</h3><p><b>Nguy cơ:</b> thiếu nước, cháy rừng, mùa màng kém, say nắng, ảnh hưởng sức khỏe.</p><p><b>Dấu hiệu:</b> nóng kéo dài, ít mưa, mực nước giảm, đất nứt nẻ.</p><p><b>Nên làm:</b> tiết kiệm và trữ nước, điều chỉnh mùa vụ, uống đủ nước, hạn chế ra ngoài lúc 10–15h.</p><p><b>Không nên:</b> đốt ngoài trời tùy tiện, để trẻ nhỏ hay người già ở ngoài nắng lâu.</p><span class="tag">Nam Trung Bộ • Tây Nguyên</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1564494469690-4f4e0b4a5f5e?w=600&q=80')"></div><div class="card-body"><div class="ico">🌎</div><h3>Động đất và rung chấn</h3><p><b>Nguy cơ:</b> đồ đạc rơi, nhà hư, mất điện nước, dư chấn sau đó.</p><p><b>Dấu hiệu:</b> rung lắc đột ngột, tiếng động lớn từ dưới đất.</p><p><b>Nên làm:</b> nằm thấp, che đầu, giữ chặt dưới bàn chắc (Drop–Cover–Hold); kiểm tra nhà sau khi hết rung.</p><p><b>Không nên:</b> chạy ra ngoài ngay, dùng thang máy, đứng gần cửa kính.</p><span class="tag">Khu vực có nguy cơ</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05?w=600&q=80')"></div><div class="card-body"><div class="ico">🔥</div><h3>Cháy rừng</h3><p><b>Nguy cơ:</b> lửa lan nhanh khi khô nóng có gió; khói ảnh hưởng sức khỏe và đường đi.</p><p><b>Dấu hiệu:</b> mùi khói, cột khói từ xa, cảnh báo cấp độ cháy rừng.</p><p><b>Nên làm:</b> không đốt tùy tiện, tạo đường băng cản lửa nếu được, báo cháy sớm qua 114.</p><p><b>Không nên:</b> tự lao vào đám cháy lớn, đốt rẫy trong mùa khô.</p><span class="tag">Rừng • Vùng khô hạn</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=600&q=80')"></div><div class="card-body"><div class="ico">🌾</div><h3>Xâm nhập mặn</h3><p><b>Nguy cơ:</b> nước ngọt và đất bị mặn, nhất là mùa khô ở Đồng bằng sông Cửu Long.</p><p><b>Dấu hiệu:</b> nước giếng hay kênh có vị mặn, độ mặn tăng theo bản tin.</p><p><b>Nên làm:</b> trữ nước ngọt trước mùa mặn, kiểm tra nước trước khi dùng, chuyển cây trồng phù hợp nếu cần.</p><p><b>Không nên:</b> dùng nước mặn để uống hay tưới khi chưa kiểm tra.</p><span class="tag">Ven biển • Đồng bằng sông Cửu Long</span></div></div>
<div class="card"><div class="card-img" style="background-image:url('https://images.unsplash.com/photo-1514565131-fce0801e5785?w=600&q=80')"></div><div class="card-body"><div class="ico">🏙️</div><h3>Ngập đô thị</h3><p><b>Nguy cơ:</b> mưa lớn vượt hệ thống thoát nước, đường kẹt, hầm ngập, mất điện cục bộ.</p><p><b>Dấu hiệu:</b> mưa to lâu, nước tràn lề đường, cảnh báo điểm ngập từ thành phố.</p><p><b>Nên làm:</b> khơi thông cống trước mùa mưa, không đi đường hay hầm ngập sâu, bảo vệ đồ điện.</p><p><b>Không nên:</b> lái xe vào chỗ ngập không rõ độ sâu, để trẻ chơi gần cống.</p><span class="tag">Đô thị lớn</span></div></div>
</div>
</div>
</section>

<section id="dia-phuong">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 2</span><h2>Giải pháp theo từng vùng</h2><p>Mỗi vùng có rủi ro khác nhau. Chọn vùng gần nơi bạn sống để xem gợi ý phù hợp. Đây chỉ là khung tham khảo — việc thực tế vẫn theo hướng dẫn địa phương.</p></div>
<div class="localnav">
<button class="active" onclick="showLocal('bacbo',this)">Miền Bắc</button>
<button onclick="showLocal('mientrung',this)">Miền Trung</button>
<button onclick="showLocal('taynguyen',this)">Tây Nguyên</button>
<button onclick="showLocal('nambo',this)">Nam Bộ</button>
<button onclick="showLocal('venbien',this)">Ven biển</button>
<button onclick="showLocal('dothi',this)">Đô thị</button>
</div>

<div id="bacbo" class="local active">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1528127269322-539801943592?w=400&q=80" alt="Miền Bắc"><div><h3>🌿 Miền Bắc — đồng bằng, trung du và miền núi</h3><p>Bão từ Biển Đông, mưa lớn mùa hè–thu, ngập đồng bằng sông Hồng, lũ quét và sạt lở ở trung du – miền núi phía Bắc là những rủi ro chính.</p></div></div>
<div class="solutions">
<div class="solution"><h4>🏘️ Khu dân cư đồng bằng</h4><ul><li>Rà soát chỗ hay ngập sâu và đường dễ bị chia cắt.</li><li>Vệ sinh, khơi thông cống rãnh trước mùa mưa.</li><li>Bảo vệ trạm điện, trường học, bệnh viện.</li><li>Chọn điểm tập kết sơ tán, ưu tiên người già và trẻ nhỏ.</li><li>Theo dõi bản tin thời tiết và loa thôn/xã.</li><li>Có phương án làm việc hay học linh hoạt khi đường ngập.</li></ul></div>
<div class="solution"><h4>⛰️ Vùng trung du, miền núi</h4><ul><li>Khoanh vùng sườn dốc, taluy và chỗ từng sạt lở.</li><li>Cảnh báo khi mưa lớn kéo dài (thường trên 100–150mm/ngày).</li><li>Chuẩn bị đường đi thay thế nếu đường chính bị cắt.</li><li>Sơ tán sớm người ở chỗ nguy cơ cao trước mưa lớn.</li><li>Dự trữ lương thực, nước, thuốc cho trường hợp bị cô lập vài ngày.</li><li>Để ý vết nứt, cây nghiêng, tiếng lạ và báo ngay.</li></ul></div>
</div></div>

<div id="mientrung" class="local">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=400&q=80" alt="Miền Trung"><div><h3>🌊 Miền Trung — bão, lũ và sạt lở</h3><p>Địa hình dốc, sông ngắn nên lũ lên rất nhanh. Bão đổ bộ trực tiếp mang theo gió mạnh, mưa lớn và nước dâng. Đây là vùng thường chịu thiệt hại nặng.</p></div></div>
<div class="solutions">
<div class="solution"><h4>🌧️ Lưu vực sông và vùng trũng</h4><ul><li>Rà soát nhà ven sông, chỗ trũng và điểm hay ngập.</li><li>Cảnh báo phải đến nhanh từng thôn, từng hộ.</li><li>Chọn nơi trú và đường sơ tán không đi qua chỗ ngập.</li><li>Bảo vệ nguồn nước sạch sau lũ, xử lý vệ sinh sớm.</li><li>Không để trẻ gần bờ sông khi nước đang lên.</li><li>Chuẩn bị xuồng, phao, dây nếu nhà ở vùng thấp.</li></ul></div>
<div class="solution"><h4>⛰️ Vùng núi và trung du</h4><ul><li>Theo dõi mưa lớn, lũ quét và sạt lở sát sao.</li><li>Không để người ở lâu tại chỗ đã được cảnh báo nguy cơ cao.</li><li>Dự trữ đồ cần thiết cho khu vực dễ bị cô lập.</li><li>Kiểm tra cầu, đường, taluy sau mỗi đợt mưa lớn.</li><li>Lập nhóm giúp nhau trong thôn bản.</li><li>Tham gia tập huấn sơ tán do địa phương tổ chức.</li></ul></div>
</div></div>

<div id="taynguyen" class="local">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1441974231531-c6227db76b6e?w=400&q=80" alt="Tây Nguyên"><div><h3>🌳 Tây Nguyên — hạn, cháy rừng, mưa lớn và sạt lở</h3><p>Mùa khô dài, dễ cháy rừng; mùa mưa có mưa lớn gây sạt lở. Nông nghiệp phụ thuộc nguồn nước nên cần kết hợp quản lý nước và phòng cháy.</p></div></div>
<div class="solutions">
<div class="solution"><h4>💧 Quản lý nước và hạn</h4><ul><li>Trữ nước sinh hoạt và sản xuất (bể, hồ, giếng).</li><li>Ưu tiên nước sinh hoạt khi thiếu; tưới tiết kiệm.</li><li>Điều chỉnh mùa vụ cho phù hợp.</li><li>Bảo vệ nguồn nước khỏi ô nhiễm.</li><li>Theo dõi dự báo hạn từ cơ quan khí tượng.</li><li>Chia sẻ nguồn nước công bằng trong cộng đồng khi khan hiếm.</li></ul></div>
<div class="solution"><h4>🔥 Phòng cháy rừng</h4><ul><li>Kiểm soát việc dùng lửa trong mùa khô.</li><li>Rà soát nhà gần rừng và đường tiếp cận chữa cháy.</li><li>Phát hiện cháy sớm và báo ngay (114).</li><li>Không tự lao vào đám cháy lớn.</li><li>Tham gia tập huấn phòng cháy nếu địa phương tổ chức.</li><li>Tạo đường băng cản lửa quanh nhà, nương nếu được.</li></ul></div>
</div></div>

<div id="nambo" class="local">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1500382017468-9049fed747ef?w=400&q=80" alt="Nam Bộ"><div><h3>🌾 Nam Bộ — ngập, triều cường, hạn và xâm nhập mặn</h3><p>Đồng bằng sông Cửu Long và Đông Nam Bộ thấp, chịu triều cường, ngập mưa, hạn và mặn. Cần kết hợp thoát nước, trữ nước ngọt và thích ứng sản xuất.</p></div></div>
<div class="solutions">
<div class="solution"><h4>🌊 Ngập và triều cường</h4><ul><li>Rà soát chỗ hay ngập và đường đi thay thế.</li><li>Vệ sinh cống, kênh trước mùa mưa.</li><li>Kê cao đồ điện và tài sản ở chỗ dễ ngập.</li><li>Cảnh báo rõ điểm ngập sâu, hầm chui.</li><li>Chuẩn bị cách di chuyển khi nước lên cao.</li><li>Theo dõi lịch triều và bản tin ngập của địa phương.</li></ul></div>
<div class="solution"><h4>🧂 Xâm nhập mặn và hạn</h4><ul><li>Trữ nước ngọt trước khi mặn vào.</li><li>Kiểm tra độ mặn trước khi dùng nước.</li><li>Điều chỉnh cây trồng, vật nuôi theo nguồn nước.</li><li>Phối hợp địa phương phân phối nước công bằng.</li><li>Theo dõi lịch xả nước và bản tin mặn.</li><li>Dùng nước ngọt đã trữ tiết kiệm.</li></ul></div>
</div></div>

<div id="venbien" class="local">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=400&q=80" alt="Ven biển"><div><h3>⚓ Ven biển và hải đảo</h3><p>Ưu tiên an toàn người, tàu thuyền và nhà cửa trước bão, nước dâng và sóng lớn. Nghề biển cần tuân thủ nghiêm cảnh báo.</p></div></div>
<div class="solutions">
<div class="solution"><h4>🚤 Tàu thuyền và nghề biển</h4><ul><li>Tuân thủ thông báo về khu vực và thời gian ra khơi.</li><li>Neo đậu, tránh trú đúng theo hướng dẫn.</li><li>Giữ máy liên lạc và thiết bị an toàn trên tàu.</li><li>Không cố ra khơi khi có cảnh báo bão hay sóng lớn.</li><li>Đăng ký tàu đầy đủ và cập nhật số liên lạc.</li><li>Tham gia bảo hiểm và tập huấn an toàn nếu có.</li></ul></div>
<div class="solution"><h4>🏠 Khu dân cư ven biển</h4><ul><li>Gia cố mái, cửa và đồ dễ bị gió cuốn trước mùa bão.</li><li>Chọn nhà chắc (trường, nhà văn hóa) làm nơi tránh trú.</li><li>Chuẩn bị phương án sơ tán khi nước dâng.</li><li>Bảo vệ nước ngọt và thực phẩm dự trữ.</li><li>Theo dõi bản tin bão và nước dâng sát giờ.</li><li>Không ở lại nhà tạm, nhà yếu khi bão mạnh.</li></ul></div>
</div></div>

<div id="dothi" class="local">
<div class="localhead"><img class="localhead-img" src="https://images.unsplash.com/photo-1514565131-fce0801e5785?w=400&q=80" alt="Đô thị"><div><h3>🏙️ Khu vực đô thị</h3><p>Rủi ro chính: mưa lớn gây ngập, cây đổ, mất điện, đường kẹt. Hệ thống thoát nước và cây xanh cần được quan tâm trước mùa mưa.</p></div></div>
<div class="solutions">
<div class="solution"><h4>🚧 Hạ tầng đô thị</h4><ul><li>Khơi thông cống, cửa thu nước trước mùa mưa.</li><li>Rà soát cây xanh, biển quảng cáo dễ đổ khi gió mạnh.</li><li>Cảnh báo điểm ngập và phân luồng giao thông kịp thời.</li><li>Bảo vệ trạm điện, trường học, bệnh viện.</li><li>Chuẩn bị phương án làm việc, học từ xa khi cần.</li><li>Công khai bản đồ điểm ngập và đường dây nóng.</li></ul></div>
<div class="solution"><h4>👨‍👩‍👧 Người dân đô thị</h4><ul><li>Không đi vào đường hay hầm ngập sâu.</li><li>Hạn chế ra đường khi mưa bão lớn.</li><li>Sạc điện thoại và chuẩn bị đèn phòng mất điện.</li><li>Theo dõi cảnh báo của thành phố, quận, huyện.</li><li>Giữ liên lạc với người thân và tổ dân phố.</li><li>Không đổ rác, đất xuống cống làm tắc nước.</li></ul></div>
</div></div>
</div>
</section>

<section class="band" id="giai-phap">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 3</span><h2>Giải pháp theo 4 cấp độ</h2><p>Phòng chống thiên tai không chỉ là việc của chính quyền. Mỗi cấp — từ nhà mình đến cả vùng — đều có vai trò quan trọng.</p></div>
<div class="timeline">
<div class="time"><span class="num">1</span><b>CẤP GIA ĐÌNH</b><h3>Chuẩn bị đồ và kế hoạch</h3><p>Chuẩn bị túi khẩn cấp, thống nhất trong nhà cách sơ tán, biết số điện thoại khẩn cấp và theo dõi cảnh báo chính thức. Đây là lớp bảo vệ đầu tiên, gần gũi nhất.</p></div>
<div class="time"><span class="num">2</span><b>CẤP CỘNG ĐỒNG</b><h3>Cảnh báo và giúp nhau</h3><p>Tổ dân phố hay thôn lập nhóm liên lạc nhanh, hỗ trợ người già – trẻ nhỏ – người cần giúp, chọn điểm tập kết an toàn và chia sẻ thông tin kịp thời trong xóm.</p></div>
<div class="time"><span class="num">3</span><b>CẤP ĐỊA PHƯƠNG</b><h3>Sơ tán và bảo vệ hạ tầng</h3><p>Rà soát chỗ yếu, cảnh báo sớm qua nhiều kênh, lập tuyến sơ tán và nơi tránh trú, giữ giao thông cùng điện nước thiết yếu hoạt động.</p></div>
<div class="time"><span class="num">4</span><b>CẤP LIÊN VÙNG</b><h3>Phối hợp nguồn lực lớn</h3><p>Chia sẻ thông tin giữa các tỉnh, điều phối cứu hộ, thuốc men, lương thực và khôi phục hạ tầng khi thiên tai vượt sức một địa bàn.</p></div>
</div>
</div>
</section>

<section id="chuan-bi" class="band">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 4</span><h2>Checklist gia đình 15 mục</h2><p>Đánh dấu những gì nhà bạn đã sẵn sàng. Mục tiêu là chuẩn bị trước — không phải lúc đang hoảng loạn mới tìm.</p></div>
<div class="check">
<p class="check-intro">Tích vào các mục đã có. Tiến độ sẽ tự cập nhật. Nên kiểm tra lại túi khẩn cấp khoảng 6 tháng một lần.</p>
<div id="items"></div>
<div class="progress"><div class="bar" id="bar"></div></div>
<b id="txt">0/15 mục đã chuẩn bị</b>
</div>
<div class="tips-strip">
<div class="tip"><strong>💡 Mẹo 1 — Để túi ở đâu</strong>Để túi khẩn cấp chỗ dễ lấy, gần cửa ra vào hoặc nơi cả nhà đều biết. Đừng cất quá sâu trong tủ.</div>
<div class="tip"><strong>💡 Mẹo 2 — Giấy tờ</strong>Chụp ảnh giấy tờ quan trọng (CMND, sổ đỏ, bảo hiểm…) rồi lưu trong điện thoại hoặc cloud phòng khi mất bản gốc.</div>
<div class="tip"><strong>💡 Mẹo 3 — Điểm hẹn</strong>Thống nhất trước điểm gặp lại nếu gia đình bị tách (trường học, nhà văn hóa, nhà người thân tin cậy).</div>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="title"><span class="sec-label">Phần 5</span><h2>Kế hoạch gia đình 5 bước</h2><p>Thống nhất trước trong nhà để khi có việc thì làm nhanh, đúng và an toàn. Nên viết ra và dán chỗ dễ thấy.</p></div>
<div class="tablewrap">
<table>
<tr><th style="width:60px">Bước</th><th>Nội dung</th><th>Cần thống nhất trong nhà</th></tr>
<tr><td><strong>1</strong></td><td>Nhận cảnh báo</td><td>Theo dõi kênh nào: loa, tin nhắn, app Thời tiết KTTV, truyền hình, Zalo tổ dân phố.</td></tr>
<tr><td><strong>2</strong></td><td>Liên lạc</td><td>Ai là người liên hệ chính, số dự phòng (họ hàng, tổ dân phố, hàng xóm). Lưu sẵn 112, 113, 114, 115.</td></tr>
<tr><td><strong>3</strong></td><td>Di chuyển</td><td>Đi đâu, đường nào an toàn. Có phương án khác nếu đường chính bị chặn.</td></tr>
<tr><td><strong>4</strong></td><td>Đồ dùng</td><td>Túi khẩn cấp gồm nước, đồ ăn, thuốc, đèn, giấy tờ, quần áo, tiền mặt nhỏ, sạc dự phòng.</td></tr>
<tr><td><strong>5</strong></td><td>Kiểm tra</td><td>Ai cần hỗ trợ đặc biệt (trẻ nhỏ, người già, người bệnh) và ai phụ trách giúp từng người.</td></tr>
</table>
</div>
<div class="two-col" style="margin-top:24px">
<div class="highlight"><h4>👨‍👩‍👧 Nhà có trẻ nhỏ</h4><p>Giải thích đơn giản, không làm trẻ sợ. Dạy số điện thoại khẩn cấp và điểm hẹn. Cho trẻ cùng đóng túi khẩn cấp để quen và bớt lo.</p></div>
<div class="highlight"><h4>🧓 Người già / người khuyết tật</h4><p>Chuẩn bị thuốc đủ dùng, dụng cụ hỗ trợ di chuyển. Báo trước với tổ dân phố để được ưu tiên khi sơ tán. Phân công người thân rõ ràng.</p></div>
</div>
</div>
</section>

<section id="cong-cu" class="band">
<div class="wrap">
<div class="title">
<span class="sec-label">Phần 6</span>
<h2>Công cụ tương tác</h2>
<p>Tự kiểm tra mức độ sẵn sàng, lập kế hoạch gia đình và lọc nhanh loại thiên tai bạn quan tâm.</p>
</div>

<!-- QUIZ -->
<div class="rich-box" style="margin-bottom:28px">
<h3>🎯 Kiểm tra mức độ sẵn sàng của gia đình</h3>
<p style="margin-bottom:16px;color:var(--muted);font-size:14.5px">Trả lời 6 câu hỏi ngắn. Hệ thống sẽ chấm điểm và gợi ý việc cần làm tiếp.</p>
<div class="quiz-box" id="quizBox">
  <div class="quiz-progress"><div id="quizBar"></div></div>
  <div id="quizStep"></div>
  <div class="quiz-nav">
    <button type="button" class="quiz-prev" id="quizPrev" style="visibility:hidden">← Trước</button>
    <span id="quizNum" style="font-size:13px;color:var(--muted);font-weight:600"></span>
    <button type="button" class="quiz-next" id="quizNext">Tiếp →</button>
  </div>
</div>
</div>

<!-- PLAN GENERATOR -->
<div class="rich-box" style="margin-bottom:28px">
<h3>📋 Tạo kế hoạch sơ tán gia đình</h3>
<p style="margin-bottom:12px;color:var(--muted);font-size:14.5px">Điền nhanh vài thông tin. Hệ thống tạo bản kế hoạch để lưu hoặc in.</p>
<div class="plan-form" id="planForm">
  <div class="two-col">
    <div>
      <label>Họ tên người liên hệ chính</label>
      <input type="text" id="pName" placeholder="VD: Nguyễn Văn A">
    </div>
    <div>
      <label>Số điện thoại</label>
      <input type="tel" id="pPhone" placeholder="VD: 09xx xxx xxx">
    </div>
  </div>
  <div class="two-col">
    <div>
      <label>Địa chỉ / khu vực</label>
      <input type="text" id="pAddr" placeholder="Thôn/xã, huyện, tỉnh">
    </div>
    <div>
      <label>Loại rủi ro chính</label>
      <select id="pRisk">
        <option value="Bão, mưa lớn">Bão, mưa lớn</option>
        <option value="Lũ, ngập lụt">Lũ, ngập lụt</option>
        <option value="Sạt lở đất">Sạt lở đất</option>
        <option value="Hạn, cháy rừng">Hạn, cháy rừng</option>
        <option value="Ngập đô thị">Ngập đô thị</option>
        <option value="Nhiều loại">Nhiều loại</option>
      </select>
    </div>
  </div>
  <label>Điểm sơ tán / nơi trú an toàn</label>
  <input type="text" id="pMeet" placeholder="VD: Trường học xã, nhà văn hóa thôn…">
  <label>Người cần hỗ trợ đặc biệt (trẻ nhỏ, người già…)</label>
  <input type="text" id="pCare" placeholder="VD: Ông 78 tuổi, bé 3 tuổi">
  <label>Ghi chú thêm</label>
  <textarea id="pNote" placeholder="Đường đi an toàn, hàng xóm hỗ trợ…"></textarea>
  <div style="margin-top:16px">
    <button type="button" class="quiz-submit" id="planGen" style="padding:12px 22px;border-radius:12px;border:0;font-weight:800;cursor:pointer;font-family:inherit;background:linear-gradient(135deg,var(--blue),var(--cyan));color:#fff">Tạo kế hoạch</button>
  </div>
  <div class="plan-out" id="planOut">
    <h4>📄 Kế hoạch sơ tán gia đình</h4>
    <pre id="planText"></pre>
    <div class="plan-actions">
      <button type="button" class="btn-copy" id="planCopy">📋 Sao chép</button>
      <button type="button" class="btn-print" id="planPrint">🖨️ In kế hoạch</button>
    </div>
  </div>
</div>
</div>

<!-- DISASTER FILTER (works with #thientai cards) -->
<div class="rich-box">
<h3>🔍 Lọc nhanh loại thiên tai</h3>
<p style="margin-bottom:12px;color:var(--muted);font-size:14.5px">Chọn loại bạn quan tâm — các thẻ ở phần Thiên tai sẽ được làm nổi bật. (Cuộn lên phần 1 để xem.)</p>
<div class="filter-bar" id="filterBar">
  <button type="button" class="active" data-f="all">Tất cả</button>
  <button type="button" data-f="bao">Bão</button>
  <button type="button" data-f="lu">Lũ / ngập</button>
  <button type="button" data-f="sat">Sạt lở</button>
  <button type="button" data-f="han">Hạn / cháy</button>
  <button type="button" data-f="khac">Khác</button>
</div>
</div>
</div>
</section>

<section id="ung-dung">
<div class="wrap">
<div class="title">
<span class="sec-label">Phần 7</span>
<h2>Ứng dụng cảnh báo nên tải</h2>
<p>Ưu tiên nguồn chính thống để nhận cảnh báo sớm. Cài sẵn trước mùa mưa bão, bật thông báo và cho phép định vị khi dùng.</p>
</div>

<div class="rich-box">
<span class="app-badge">CHÍNH THỐNG</span>
<h3>📱 Ứng dụng chính thức nên dùng trước</h3>
<p><b>Thời tiết Việt Nam KTTV</b> — do Cục Khí tượng Thủy văn phát hành, miễn phí trên Android và iOS. Đây là nguồn chính thống đáng tin nhất hiện nay.</p>
<ul>
<li>Cập nhật thời tiết theo vị trí khoảng <b>10 phút/lần</b></li>
<li>Dự báo chi tiết đến <b>10 ngày</b></li>
<li>Cảnh báo <b>dông sét thời gian thực</b></li>
<li>Cảnh báo <b>lũ quét, sạt lở</b> theo vị trí (3 mức: trung bình – cao – rất cao)</li>
<li>Cảnh báo bão, áp thấp, mưa lớn, gió mạnh trên biển</li>
<li>Dữ liệu từ hơn <b>2.600 trạm</b> quan trắc và radar trong nước</li>
</ul>
<p style="margin-top:12px"><b>Cách tải:</b> Mở CH Play (Android) hoặc App Store (iOS) → tìm <b>“Thời tiết Việt Nam KTTV”</b> hoặc <b>“Vietnam Weather KTTV”</b> → Cài đặt → Bật thông báo.</p>
</div>

<div class="grid" style="margin-top:8px">
<div class="card"><div class="card-body">
<div class="ico">⛰️</div>
<h3>Sạt lở Việt Nam</h3>
<p>Ứng dụng hỗ trợ cảnh báo <b>sạt lở đất và lũ quét</b>, hữu ích với miền núi và trung du. Cập nhật khoảng 20 phút/lần, chi tiết đến cấp thôn/bản. Miễn phí trên Android và iOS.</p>
<p style="margin-top:8px"><b>Nên dùng kèm</b> app Thời tiết Việt Nam KTTV, không thay thế nguồn chính thống.</p>
</div></div>
<div class="card"><div class="card-body">
<div class="ico">📢</div>
<h3>Kênh cảnh báo khác cần giữ</h3>
<p><b>Loa phát thanh thôn/xã</b> — vẫn rất quan trọng ở nông thôn.</p>
<p><b>Tin nhắn / Zalo tổ dân phố</b> — cảnh báo địa phương nhanh.</p>
<p><b>Truyền hình, phát thanh địa phương</b> — bản tin chính thức.</p>
<p><b>112 – 114 – 115</b> — khi cần trợ giúp khẩn.</p>
</div></div>
<div class="card"><div class="card-body">
<div class="ico">✅</div>
<h3>Lưu ý khi dùng app</h3>
<p>• Bật <b>thông báo</b> và cho phép <b>định vị</b> để nhận cảnh báo đúng chỗ.</p>
<p>• Không chỉ dựa vào app — vẫn theo dõi loa, tin chính quyền địa phương.</p>
<p>• Đối chiếu khi tin trên mạng xã hội khác với app chính thống.</p>
<p>• Sạc pin và giữ sạc dự phòng trong mùa mưa bão.</p>
</div></div>
</div>

<div class="two-col" style="margin-top:22px">
<div class="highlight">
<h4>🔎 Tìm app trên cửa hàng</h4>
<p><b>Android:</b> CH Play → tìm “Thời tiết Việt Nam KTTV”<br>
<b>iOS:</b> App Store → tìm “Vietnam Weather KTTV” hoặc “Thời tiết Việt Nam KTTV”</p>
</div>
<div class="highlight">
<h4>⚠️ Nhớ</h4>
<p>App giúp cảnh báo sớm, nhưng quyết định sơ tán vẫn theo <b>lệnh chính quyền địa phương</b>. Khi có lệnh sơ tán, ưu tiên làm theo lệnh đó.</p>
</div>
</div>
</div>
</section>

<section id="mau-tin" class="band">
<div class="wrap">
<div class="title">
<span class="sec-label">Phần 8</span>
<h2>Mẫu thông báo khẩn cấp</h2>
<p>Dùng khi cần viết tin cảnh báo hoặc lệnh sơ tán nhanh. Copy rồi điền địa phương, giờ và mức độ cho phù hợp. Luôn ghi rõ nguồn phát hành.</p>
</div>

<div class="rich-box">
<h3>📌 Cách viết tin khẩn cấp hiệu quả</h3>
<ul>
<li><b>Ngắn – rõ – đúng:</b> người đọc đang căng thẳng, không có thời gian đọc dài.</li>
<li><b>Ưu tiên hành động:</b> nói ngay họ cần làm gì, trước khi giải thích dài.</li>
<li><b>Một thông điệp chính:</b> mỗi tin chỉ tập trung 1–2 việc quan trọng nhất.</li>
<li><b>Ghi nguồn và giờ:</b> ai phát hành, lúc mấy giờ — để người dân biết tin mới nhất.</li>
</ul>
</div>

<div class="grid" style="margin-top:8px">
<div class="card"><div class="card-body">
<div class="ico">🌀</div>
<h3>Mẫu cảnh báo bão</h3>
<p style="background:#f7fbfd;padding:12px;border-radius:8px;font-size:13px;line-height:1.6;white-space:pre-wrap;color:#2a4050"><b>CẢNH BÁO BÃO SỐ … – CẬP NHẬT … GIỜ …/…/…</b>

Theo Trung tâm Dự báo KTTV, bão số … đang tiến gần, dự kiến ảnh hưởng khu vực từ … đến … từ chiều … đến sáng ….

<b>Mức độ:</b> Gió mạnh cấp …–…, mưa lớn, nguy cơ ngập và cây đổ.

<b>Người dân cần làm ngay:</b>
• Gia cố mái, cửa, cất đồ dễ bay
• Dự trữ nước, đồ ăn, thuốc 3–5 ngày
• Theo dõi lệnh sơ tán của chính quyền
• Không ra ngoài khi gió mạnh

<b>Không nên:</b> Ra khơi, đứng gần cây/cột điện, chủ quan vì trời còn yên.

<b>Liên hệ:</b> 112 / UBND xã … / Tổ dân phố

Tin sẽ được cập nhật khi có diễn biến mới.</p>
</div></div>

<div class="card"><div class="card-body">
<div class="ico">🌊</div>
<h3>Mẫu cảnh báo lũ / lũ quét</h3>
<p style="background:#f7fbfd;padding:12px;border-radius:8px;font-size:13px;line-height:1.6;white-space:pre-wrap;color:#2a4050"><b>CẢNH BÁO LŨ – … GIỜ …/…/…</b>

Mưa lớn kéo dài khiến nước sông … dâng nhanh. Khu vực …, … có nguy cơ ngập sâu và bị chia cắt.

<b>Người dân cần:</b>
• Di chuyển lên chỗ cao an toàn
• Không lội qua dòng nước chảy xiết
• Mang theo túi khẩn cấp và giấy tờ
• Giúp người già, trẻ em sơ tán trước

<b>Liên hệ khẩn:</b> 112 – 114 – UBND xã …

Nguồn: Ban Chỉ huy PCTT …</p>
</div></div>

<div class="card"><div class="card-body">
<div class="ico">⛰️</div>
<h3>Mẫu cảnh báo sạt lở</h3>
<p style="background:#f7fbfd;padding:12px;border-radius:8px;font-size:13px;line-height:1.6;white-space:pre-wrap;color:#2a4050"><b>CẢNH BÁO SẠT LỞ – … GIỜ …/…/…</b>

Mưa lớn kéo dài làm tăng nguy cơ sạt lở tại các sườn dốc, taluy đường khu vực ….

<b>Dấu hiệu cần chú ý:</b> vết nứt đất/tường, cây nghiêng, tiếng động lạ.

<b>Người dân cần:</b>
• Rời ngay khỏi chỗ có dấu hiệu nguy hiểm
• Không ở lại nhà sát taluy chưa gia cố
• Báo chính quyền khi phát hiện dấu hiệu lạ

<b>Liên hệ:</b> 112 / UBND xã … / Tổ dân phố

Nguồn: Ban Chỉ huy PCTT …</p>
</div></div>

<div class="card"><div class="card-body">
<div class="ico">📢</div>
<h3>Mẫu lệnh sơ tán</h3>
<p style="background:#f7fbfd;padding:12px;border-radius:8px;font-size:13px;line-height:1.6;white-space:pre-wrap;color:#2a4050"><b>LỆNH SƠ TÁN KHẨN – … GIỜ …/…/…</b>

Ban Chỉ huy PCTT … yêu cầu toàn bộ hộ dân tại … sơ tán ngay đến điểm tập kết: …

<b>Mang theo:</b> nước, đồ ăn, thuốc, giấy tờ, điện thoại đã sạc.

<b>Không quay lại</b> vùng nguy hiểm khi chưa có thông báo cho phép.

<b>Hỗ trợ sơ tán:</b> gọi … (tổ dân phố / lực lượng tại chỗ)

Nguồn: Ban Chỉ huy PCTT … – … giờ …/…/…</p>
</div></div>

<div class="card"><div class="card-body">
<div class="ico">🔥</div>
<h3>Mẫu cảnh báo cháy rừng</h3>
<p style="background:#f7fbfd;padding:12px;border-radius:8px;font-size:13px;line-height:1.6;white-space:pre-wrap;color:#2a4050"><b>CẢNH BÁO CHÁY RỪNG – … GIỜ …/…/…</b>

Thời tiết khô nóng, cấp độ cảnh báo cháy rừng khu vực … đang ở mức cao.

<b>Người dân cần:</b>
• Không đốt ngoài trời, không đốt rẫy
• Theo dõi khói, lửa và báo ngay 114 khi phát hiện
• Không tự lao vào đám cháy lớn

<b>Liên hệ:</b> 114 – Kiểm lâm / UBND xã …

Nguồn: Ban Chỉ huy PCTT …</p>
</div></div>

<div class="card"><div class="card-body">
<div class="ico">✍️</div>
<h3>Lời văn nên dùng / nên tránh</h3>
<p><b>Nên dùng:</b> Cần làm ngay • Di chuyển lên chỗ cao • Nguy cơ cao • Theo dõi lệnh chính quyền • Không ra ngoài khi gió mạnh</p>
<p style="margin-top:8px"><b>Tránh dùng:</b> Có thể xem xét • Tùy tình hình • Tương đối nguy hiểm • Hạn chế ra ngoài nếu không cần thiết • Sẽ thông báo sau</p>
<p style="margin-top:8px">Viết câu ngắn, đưa hành động lên đầu, ghi rõ địa danh và giờ, lặp lại số điện thoại ở cuối tin.</p>
</div></div>
</div>
</div>
</section>

<section id="khancap">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 9</span><h2>Số điện thoại khẩn cấp</h2><p>Khi cần giúp, nói rõ vị trí và tình hình ngắn gọn, chính xác. Giữ bình tĩnh để bên tiếp nhận hiểu đúng.</p></div>
<div class="emergency">
<div class="em"><b>112</b><span>Trợ giúp khẩn cấp</span></div>
<div class="em"><b>113</b><span>Công an</span></div>
<div class="em"><b>114</b><span>Cứu hỏa và cứu nạn</span></div>
<div class="em"><b>115</b><span>Cấp cứu y tế</span></div>
</div>
<div class="success">✅ Khi gọi: nói rõ <b>ở đâu — chuyện gì xảy ra — có bao nhiêu người cần giúp — nguy hiểm hiện tại là gì</b>. Làm theo hướng dẫn của bên tiếp nhận. Đừng gác máy khi chưa được phép.</div>
<div class="two-col" style="margin-top:24px">
<div class="highlight"><h4>📱 Nên lưu sẵn trong máy</h4><p>Ngoài 112–115, lưu số tổ trưởng dân phố, công an xã/phường và người thân tin cậy. Đặt tên rõ để dễ tìm khi cần.</p></div>
<div class="highlight"><h4>🔋 Khi mất điện hoặc hết pin</h4><p>Ưu tiên sạc dự phòng cho điện thoại. Nếu có radio dùng pin thì bật nghe tin. Báo vị trí cho hàng xóm nếu không liên lạc được bên ngoài.</p></div>
</div>
</div>
</section>

<section id="sau-thien-tai" class="band">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 10</span><h2>Sau thiên tai cần làm gì?</h2><p>Phục hồi an toàn cũng quan trọng như phòng ngừa. Làm đúng giúp tránh bệnh và thiệt hại thêm.</p></div>
<div class="after-grid">
<div class="after-card"><h4>💧 Nước và thực phẩm</h4><ul><li>Không dùng nước giếng, ao hồ chưa kiểm tra.</li><li>Đun sôi nước ít nhất 1 phút hoặc dùng viên khử trùng.</li><li>Bỏ đồ ăn đã ngâm nước lũ hoặc hết hạn.</li><li>Rửa tay thường xuyên bằng xà phòng.</li><li>Những ngày đầu chỉ ăn đồ đã nấu chín kỹ.</li></ul></div>
<div class="after-card"><h4>🏠 Nhà cửa và điện</h4><ul><li>Kiểm tra tường, mái, cột trước khi vào ở lại.</li><li>Không bật điện nếu nhà còn ướt hoặc có mùi lạ.</li><li>Gọi thợ điện kiểm tra nếu nghi hỏng.</li><li>Dọn bùn, rác đúng theo hướng dẫn địa phương.</li><li>Chụp ảnh thiệt hại để làm thủ tục hỗ trợ hoặc bảo hiểm.</li></ul></div>
<div class="after-card"><h4>❤️ Sức khỏe và tinh thần</h4><ul><li>Để ý sốt, tiêu chảy, nhiễm trùng da.</li><li>Đến cơ sở y tế nếu thấy bất thường.</li><li>Chia sẻ cảm xúc với người thân, hàng xóm — đừng giữ một mình.</li><li>Giúp trẻ và người già lấy lại tinh thần (nói chuyện, nghỉ ngơi).</li><li>Tham gia hoạt động cộng đồng để gắn kết và giảm lo.</li></ul></div>
</div>
<div class="rich-box" style="margin-top:24px">
<h3>📋 Việc nên làm trong 48 giờ đầu</h3>
<ul>
<li>Đảm bảo an toàn tính mạng và chỗ ở tạm cho cả nhà.</li>
<li>Liên lạc người thân để báo tin an toàn.</li>
<li>Theo dõi thông tin chính thức về cứu trợ và hỗ trợ.</li>
<li>Không lan tin đồn; chỉ chia sẻ thông tin đã được xác minh.</li>
<li>Giúp hàng xóm nếu sức khỏe và điều kiện cho phép, nhưng không mạo hiểm.</li>
</ul>
</div>
</div>
</section>

<section>
<div class="wrap">
<div class="title"><span class="sec-label">Phần 11</span><h2>Chính quyền địa phương có thể làm gì?</h2><p>Những việc quản lý có thể làm rõ theo từng tỉnh, huyện, xã. Người dân biết để phối hợp và theo dõi.</p></div>
<div class="grid">
<div class="card"><div class="card-body"><div class="ico">📢</div><h3>Cảnh báo sớm</h3><p>Truyền tin qua nhiều kênh: loa, tin nhắn, mạng xã hội, tổ dân phố. Nói rõ chỗ nào, lúc nào, mức độ thế nào và cần làm gì. Cảnh báo phải đến được từng hộ, nhất là hộ già yếu và vùng sâu.</p></div></div>
<div class="card"><div class="card-body"><div class="ico">🗺️</div><h3>Bản đồ rủi ro</h3><p>Rà soát chỗ ngập, sạt lở, lũ quét, nhà xung yếu và đường dễ bị cắt. Cập nhật thường xuyên và công khai. Bản đồ giúp ưu tiên đầu tư và sơ tán đúng chỗ.</p></div></div>
<div class="card"><div class="card-body"><div class="ico">🏫</div><h3>Nơi sơ tán</h3><p>Chọn công trình an toàn, đủ chỗ, có nước sạch, vệ sinh, y tế và đường tiếp cận rõ. Tập huấn định kỳ cho lực lượng tại chỗ và diễn tập với người dân.</p></div></div>
<div class="card"><div class="card-body"><div class="ico">🚑</div><h3>Cứu hộ và y tế</h3><p>Chuẩn bị lực lượng, phương tiện, điểm sơ cứu và cách phối hợp khi nhiều nơi cùng bị. Ưu tiên người yếu thế. Có phương án hỗ trợ y tế lưu động nếu cần.</p></div></div>
<div class="card"><div class="card-body"><div class="ico">🌉</div><h3>Bảo vệ hạ tầng</h3><p>Kiểm tra đê, hồ, cầu, đường, điện, nước, trường học và cơ sở y tế ở chỗ xung yếu trước mùa mưa bão. Sửa kịp những chỗ xuống cấp.</p></div></div>
<div class="card"><div class="card-body"><div class="ico">♻️</div><h3>Phục hồi sau thiên tai</h3><p>Đánh giá thiệt hại nhanh, xử lý môi trường, khôi phục nước – điện – đường, hỗ trợ sinh kế và chỗ ở tạm. Công khai thông tin hỗ trợ cho minh bạch.</p></div></div>
</div>
</div>
</section>

<section class="band" id="video">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 12</span><h2>Video hướng dẫn</h2><p>Xem các video ngắn để nắm kỹ năng thực tế. Ưu tiên nguồn chính thống từ truyền hình và cơ quan chức năng.</p></div>
<div class="video-grid">
<div class="video-main"><iframe id="mainVideo" src="https://www.youtube.com/embed/FH8Cht_KklM" title="Hướng dẫn cách phòng tránh thiên tai" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
<div class="video-side">
<div class="video-card active" onclick="changeVideo('FH8Cht_KklM', this)"><div class="video-thumb" style="background-image:url('https://img.youtube.com/vi/FH8Cht_KklM/mqdefault.jpg')"></div><div><h4>Hướng dẫn cách phòng tránh thiên tai</h4><span>VTV1 • Kỹ năng cơ bản</span></div></div>
<div class="video-card" onclick="changeVideo('DP1pbho14kA', this)"><div class="video-thumb" style="background-image:url('https://img.youtube.com/vi/DP1pbho14kA/mqdefault.jpg')"></div><div><h4>Kỹ năng an toàn trước bão</h4><span>Hướng dẫn chi tiết</span></div></div>
<div class="video-card" onclick="changeVideo('B2yuJMnLGHA', this)"><div class="video-thumb" style="background-image:url('https://img.youtube.com/vi/B2yuJMnLGHA/mqdefault.jpg')"></div><div><h4>Chủ động phòng chống thiên tai</h4><span>Truyền hình địa phương</span></div></div>
<div class="video-card" onclick="changeVideo('WRCaO__DTCY', this)"><div class="video-thumb" style="background-image:url('https://img.youtube.com/vi/WRCaO__DTCY/mqdefault.jpg')"></div><div><h4>Chủ động phòng chống tại địa phương</h4><span>NTV • Thực tế</span></div></div>
</div>
</div>
</div>
</section>

<section class="band">
<div class="wrap">
<div class="title"><span class="sec-label">Phần 13</span><h2>Câu hỏi thường gặp</h2><p>Những thắc mắc phổ biến. Còn câu nào khác, hãy hỏi chính quyền địa phương hoặc cơ quan chuyên môn.</p></div>
<details class="faq"><summary>Giải pháp trên có áp dụng giống nhau mọi tỉnh không?</summary><p>Không. Mỗi nơi có địa hình, dân cư và nhóm thiên tai khác nhau. Nội dung website chỉ là khung tham khảo. Việc thực tế cần theo hướng dẫn của Ban Chỉ huy phòng chống thiên tai và chính quyền nơi bạn sống.</p></details>
<details class="faq"><summary>Khi có lệnh sơ tán, nên ưu tiên gì?</summary><p>Ưu tiên an toàn con người. Mang túi khẩn cấp và giấy tờ cần thiết, đi theo tuyến được hướng dẫn, không quay lại vùng nguy hiểm khi chưa được phép. Giúp người già, trẻ em, người bệnh đi trước.</p></details>
<details class="faq"><summary>Sau lũ có dùng ngay nước và đồ ăn được không?</summary><p>Không nên mặc định an toàn. Nước và đồ ăn có thể bị ô nhiễm. Đun sôi nước hoặc dùng viên khử trùng; bỏ đồ đã ngâm nước lũ hoặc có dấu hiệu hỏng.</p></details>
<details class="faq"><summary>Có nên tự đi cứu hộ trong vùng nguy hiểm?</summary><p>Không nên tự đặt mình vào nguy hiểm nếu chưa được đào tạo. Báo vị trí và nhu cầu hỗ trợ cho lực lượng chuyên trách (114, công an). Chỉ giúp khi điều kiện an toàn và phù hợp khả năng của mình.</p></details>
<details class="faq"><summary>Làm sao biết thông tin cảnh báo là chính thức?</summary><p>Ưu tiên đài truyền hình/phát thanh địa phương, app Thời tiết KTTV, tin nhắn từ chính quyền, loa thôn/xã, trang thông tin chính thức của Ban Chỉ huy phòng chống thiên tai. Đối chiếu vài nguồn trước khi chia sẻ.</p></details>
<details class="faq"><summary>Trẻ em cần chuẩn bị thế nào?</summary><p>Giải thích đơn giản, không làm trẻ sợ. Dạy số điện thoại khẩn cấp và điểm hẹn. Cho trẻ cùng đóng túi khẩn cấp và diễn tập nhẹ. Người lớn giữ bình tĩnh vì trẻ học theo.</p></details>
<details class="faq"><summary>Người già hoặc người khuyết tật cần lưu ý gì?</summary><p>Chuẩn bị thuốc đủ dùng (ít nhất 7 ngày), dụng cụ hỗ trợ di chuyển. Báo trước với tổ dân phố để được ưu tiên. Giữ liên lạc thường xuyên trong mùa mưa bão.</p></details>
<details class="faq"><summary>Túi khẩn cấp nên chuẩn bị bao nhiêu ngày?</summary><p>Ít nhất 3 ngày, tốt hơn là 5–7 ngày (nước khoảng 2–3 lít/người/ngày, đồ ăn khô, thuốc, đèn, pin). Vùng núi dễ bị cô lập nên chuẩn bị nhiều hơn.</p></details>
<details class="faq"><summary>Có nên tin hết thông tin trên mạng xã hội?</summary><p>Không. Mạng lan tin nhanh nhưng dễ có tin đồn. Chỉ tham khảo ban đầu, rồi đối chiếu nguồn chính thống. Không chia sẻ thông tin chưa được xác minh.</p></details>
</div>
</section>


<section id="giao-duc" class="band">
<div class="wrap">
<div class="title">
<span class="sec-label">Phần 14</span>
<h2>Dành cho giáo dục</h2>
<p>Tài liệu ngắn gọn cho học sinh, giáo viên và nhà trường. Có thể dùng trong 1 tiết học hoặc hoạt động ngoại khóa về phòng chống thiên tai.</p>
</div>

<div class="edu-tabs" id="eduTabs">
  <button type="button" class="active" data-edu="hs">👨‍🎓 Học sinh</button>
  <button type="button" data-edu="gv">👩‍🏫 Giáo viên</button>
  <button type="button" data-edu="truong">🏫 Nhà trường</button>
  <button type="button" data-edu="nen">✅ Nên / Không nên</button>
</div>

<!-- HỌC SINH -->
<div class="edu-panel active" id="edu-hs">
  <div class="rich-box">
    <span class="age-tag">TIỂU HỌC · THCS</span>
    <h3>🎯 Quiz 5 câu cho học sinh</h3>
    <p style="color:var(--muted);font-size:14px;margin-bottom:14px">Chọn đáp án đúng. Xong sẽ hiện điểm và lời giải thích ngắn.</p>
    <div class="quiz-box" id="eduQuizBox">
      <div class="quiz-progress"><div id="eduQuizBar"></div></div>
      <div id="eduQuizStep"></div>
      <div class="quiz-nav">
        <button type="button" class="quiz-prev" id="eduQuizPrev" style="visibility:hidden">← Trước</button>
        <span id="eduQuizNum" style="font-size:13px;color:var(--muted);font-weight:600"></span>
        <button type="button" class="quiz-next" id="eduQuizNext">Tiếp →</button>
      </div>
    </div>
  </div>
  <div class="rich-box" style="margin-top:18px">
    <h3>📝 5 điều học sinh cần nhớ</h3>
    <ul>
      <li><b>1.</b> Theo dõi lời thầy cô và loa trường khi có cảnh báo.</li>
      <li><b>2.</b> Không lội nước lũ, không chơi gần sông suối khi mưa lớn.</li>
      <li><b>3.</b> Nhớ số <b>112</b> (trợ giúp) và số điện thoại bố mẹ.</li>
      <li><b>4.</b> Khi sơ tán: đi cùng người lớn, không tách nhóm.</li>
      <li><b>5.</b> Sau mưa bão: không đụng dây điện, không ăn đồ chưa sạch.</li>
    </ul>
  </div>
</div>

<!-- GIÁO VIÊN -->
<div class="edu-panel" id="edu-gv">
  <div class="lesson-box">
    <span class="age-tag">GIÁO ÁN MẪU · 40–45 PHÚT</span>
    <h4>Tiết học: Phòng chống thiên tai — Biết để an toàn</h4>
    <p style="font-size:14px;color:#3d5566"><b>Mục tiêu:</b> Học sinh nêu được 2–3 rủi ro tại địa phương; nhớ việc nên/không nên; biết số 112–115; hoàn thành checklist nhóm.</p>
    <p style="font-size:14px;color:#3d5566;margin-top:8px"><b>Chuẩn bị:</b> Máy chiếu / điện thoại mở SafeVN; phiếu checklist in sẵn (hoặc chép bảng).</p>
  </div>
  <div class="lesson-box">
    <h4>Tiến trình gợi ý</h4>
    <ol>
      <li><b>(5 phút) Mở đầu:</b> Hỏi “Em đã từng gặp mưa lớn / ngập chưa?” — chia sẻ 1–2 ý.</li>
      <li><b>(8 phút) Video / giới thiệu:</b> Xem 1 video ngắn trên SafeVN hoặc đọc 4 nguyên tắc vàng.</li>
      <li><b>(10 phút) Theo vùng:</b> Học sinh chọn đúng vùng mình ở (Phần Địa phương) → ghi 3 việc cần làm.</li>
      <li><b>(12 phút) Hoạt động nhóm:</b> Làm quiz học sinh hoặc thẻ Nên / Không nên; đại diện trình bày.</li>
      <li><b>(5 phút) Củng cố:</b> Đồng thanh số 112–115 + một nguyên tắc “Không mạo hiểm”.</li>
      <li><b>(5 phút) Về nhà:</b> Cùng bố mẹ xem checklist gia đình trên SafeVN (hoặc phiếu in).</li>
    </ol>
  </div>
  <div class="lesson-box">
    <h4>Câu hỏi thảo luận nhanh</h4>
    <ul>
      <li>Vì sao không nên lội qua nước lũ dù trông có vẻ nông?</li>
      <li>Khi nào cần sơ tán? Em nghe lệnh từ ai?</li>
      <li>Tin trên mạng và tin loa xã — nên tin nguồn nào trước?</li>
      <li>Em có thể giúp người già / em nhỏ trong nhà như thế nào cho an toàn?</li>
    </ul>
  </div>
  <div class="two-col">
    <div class="highlight">
      <h4>📎 Gợi ý đánh giá</h4>
      <p>Hoàn thành quiz ≥ 3/5 đúng; nêu được 2 hành động an toàn; nhớ ít nhất 2 số khẩn cấp.</p>
    </div>
    <div class="highlight">
      <h4>📚 Liên hệ môn học</h4>
      <p>Địa lý (thời tiết, địa hình), GDCD / HĐTN, An toàn trường học, Sinh hoạt dưới cờ.</p>
    </div>
  </div>
</div>

<!-- NHÀ TRƯỜNG -->
<div class="edu-panel" id="edu-truong">
  <div class="rich-box">
    <h3>🏫 Checklist trường an toàn trước mùa mưa bão</h3>
    <div class="check" id="schoolCheck" style="max-width:100%;box-shadow:none;border:1px solid var(--line)">
      <div id="schoolItems"></div>
      <div class="progress"><div class="bar" id="schoolBar"></div></div>
      <b id="schoolTxt">0/10 mục đã sẵn sàng</b>
    </div>
  </div>
  <div class="rich-box" style="margin-top:18px">
    <h3>📢 Mẫu thông báo gửi phụ huynh (rút gọn)</h3>
    <p style="background:#f7fbfd;padding:14px;border-radius:12px;font-size:14px;line-height:1.7;color:#2a4050">
      Kính gửi quý phụ huynh,<br><br>
      Nhà trường thông báo: theo dự báo, khu vực có thể chịu ảnh hưởng mưa lớn / bão trong thời gian tới. Đề nghị phụ huynh:
      (1) Theo dõi thông báo của nhà trường và chính quyền địa phương;
      (2) Nhắc con không ra đường khi mưa lớn, không lội nước ngập;
      (3) Cập nhật số điện thoại liên hệ khẩn với giáo viên chủ nhiệm.<br><br>
      Khi có thay đổi lịch học / cho học sinh về sớm, nhà trường sẽ thông báo kịp thời.<br>
      Trân trọng.
    </p>
  </div>
  <div class="lesson-box" style="margin-top:18px">
    <h4>⏱️ Kịch bản diễn tập sơ tán 15–20 phút</h4>
    <ol>
      <li>Phát tín hiệu cảnh báo (loa / còi) — học sinh dừng hoạt động.</li>
      <li>Giáo viên hướng dẫn xếp hàng, điểm số nhanh.</li>
      <li>Di chuyển theo lối thoát hiểm đã quy định (không chạy hỗn loạn).</li>
      <li>Tập kết điểm an toàn — điểm danh đủ người.</li>
      <li>Nhắc 1–2 quy tắc an toàn — kết thúc, rút kinh nghiệm 3 phút.</li>
    </ol>
  </div>
</div>

<!-- NÊN / KHÔNG NÊN -->
<div class="edu-panel" id="edu-nen">
  <div class="rich-box">
    <h3>🌀 Bão</h3>
    <div class="should-grid">
      <div class="should-card should-yes"><b>✅ NÊN</b>Ở trong nhà chắc, đóng cửa sổ; cất đồ dễ bay; theo dõi cảnh báo.</div>
      <div class="should-card should-no"><b>❌ KHÔNG NÊN</b>Ra ngoài xem bão; đứng gần cây, cột điện; tự ý ra sông / biển.</div>
    </div>
  </div>
  <div class="rich-box" style="margin-top:14px">
    <h3>🌊 Lũ / ngập</h3>
    <div class="should-grid">
      <div class="should-card should-yes"><b>✅ NÊN</b>Lên chỗ cao; nghe lệnh sơ tán; mang theo nước, đồ ăn, thuốc nếu được giao.</div>
      <div class="should-card should-no"><b>❌ KHÔNG NÊN</b>Lội nước lũ; bơi chơi trên đường ngập; chạm dây điện xuống nước.</div>
    </div>
  </div>
  <div class="rich-box" style="margin-top:14px">
    <h3>⛰️ Sạt lở</h3>
    <div class="should-grid">
      <div class="should-card should-yes"><b>✅ NÊN</b>Báo người lớn khi thấy đất nứt, cây nghiêng; rời khỏi chỗ nguy hiểm khi được yêu cầu.</div>
      <div class="should-card should-no"><b>❌ KHÔNG NÊN</b>Đứng xem chỗ vừa sạt; ở lại nhà sát taluy khi đã có cảnh báo.</div>
    </div>
  </div>
  <p style="text-align:center;margin-top:16px;font-size:13.5px;color:var(--muted)">Giáo viên có thể in phần này hoặc chiếu lên lớp để học sinh giơ tay “Nên / Không nên”.</p>
</div>

</div>
</section>

<footer>
<div class="wrap foot">
<div><h3>🛡️ SafeVN</h3><p>Website học tập và truyền thông cộng đồng về phòng chống thiên tai tại Việt Nam. Nội dung dễ hiểu, thực tế — từ nhận biết rủi ro đến giải pháp theo vùng, checklist gia đình, kỹ năng ứng phó và phục hồi sau thiên tai.</p></div>
<div><h3>Chủ đề chính</h3><ul><li>9 loại thiên tai phổ biến</li><li>Giải pháp theo 6 vùng</li><li>Checklist và kế hoạch 5 bước</li><li>Video hướng dẫn thực tế</li><li>Việc cần làm sau thiên tai</li><li>Câu hỏi thường gặp</li>
<li>Mẫu thông báo khẩn cấp</li></ul></div>
<div><h3>Ghi nhớ</h3><p>Phòng ngừa sớm • Cảnh báo nhanh • Sơ tán đúng lúc • Không mạo hiểm • Phục hồi an toàn</p><p style="margin-top:12px;font-size:12.5px">Nguồn tham khảo: Cục Quản lý đê điều và Phòng chống thiên tai, Trung tâm Dự báo KTTV Quốc gia, UNICEF Việt Nam.</p></div>
</div>
<div class="wrap copy">© 2026 SafeVN — Nội dung mang tính giáo dục và tham khảo. Khi có thiên tai, ưu tiên hướng dẫn chính thức của cơ quan chức năng.</div>
</footer>

<script>
function showLocal(id,btn){document.querySelectorAll('.local').forEach(x=>x.classList.remove('active'));document.getElementById(id).classList.add('active');document.querySelectorAll('.localnav button').forEach(x=>x.classList.remove('active'));btn.classList.add('active')}
function changeVideo(id,el){document.getElementById('mainVideo').src='https://www.youtube.com/embed/'+id;document.querySelectorAll('.video-card').forEach(c=>c.classList.remove('active'));el.classList.add('active')}
const items=["💧 Nước uống (đủ 3–5 ngày / người)","🥫 Thực phẩm khô / đồ hộp dễ chế biến","🔦 Đèn pin + bóng dự phòng","🔋 Pin / sạc dự phòng đầy pin","🩹 Bộ sơ cứu cơ bản","📻 Radio / app nhận cảnh báo","😷 Khẩu trang & đồ vệ sinh cá nhân","📄 Bản sao giấy tờ quan trọng (CMND, sổ đỏ…)","👕 Quần áo phù hợp (kín, ấm, dễ di chuyển)","👟 Giày dép chắc chắn","💊 Thuốc cần thiết (theo đơn bác sĩ)","📱 Danh sách liên lạc khẩn cấp (giấy + điện thoại)","🧴 Nước sát khuẩn / xà phòng","🧰 Dụng cụ cơ bản (kéo, băng keo, dao nhỏ…)","🗺️ Kế hoạch sơ tán gia đình đã thống nhất"];
const box=document.getElementById("items");items.forEach(x=>box.insertAdjacentHTML("beforeend",`<label><input type="checkbox" onchange="update()"> ${x}</label>`));
function update(){let n=document.querySelectorAll("#items input:checked").length;document.getElementById("bar").style.width=(n/items.length*100)+"%";document.getElementById("txt").textContent=n+"/"+items.length+" mục đã chuẩn bị"}
document.querySelectorAll('#mainNav a').forEach(a=>a.addEventListener('click',()=>document.getElementById('mainNav').classList.remove('open')));

window.addEventListener('scroll', function(){
  var b = document.getElementById('topBtn');
  if(!b) return;
  if(window.scrollY > 400) b.classList.add('show');
  else b.classList.remove('show');
});


/* Scroll reveal */
(function(){
  var els = document.querySelectorAll('.title, .grid, .timeline, .localhead, .solutions, .video-grid, .check, .tablewrap, .emergency, .after-grid, .rich-box, .tips-strip, .two-col, .faq, .quick');
  els.forEach(function(el, i){
    el.classList.add('reveal');
    if(i % 3 === 1) el.classList.add('reveal-delay-1');
    if(i % 3 === 2) el.classList.add('reveal-delay-2');
  });
  if(!('IntersectionObserver' in window)){
    els.forEach(function(el){ el.classList.add('in'); });
    return;
  }
  var io = new IntersectionObserver(function(entries){
    entries.forEach(function(e){
      if(e.isIntersecting){
        e.target.classList.add('in');
        io.unobserve(e.target);
      }
    });
  }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });
  els.forEach(function(el){ io.observe(el); });
})();

/* Checklist bar pulse when full */
(function(){
  var orig = window.update;
  if(typeof orig !== 'function') return;
  window.update = function(){
    orig();
    var n = document.querySelectorAll('#items input:checked').length;
    var total = document.querySelectorAll('#items input').length;
    var bar = document.getElementById('bar');
    if(!bar) return;
    if(n === total && total > 0){
      bar.classList.add('done');
      setTimeout(function(){ bar.classList.remove('done'); }, 1300);
    }
  };
})();


/* === SOS bar === */
(function(){
  var bar = document.getElementById('sosBar');
  var tog = document.getElementById('sosToggle');
  var cls = document.getElementById('sosClose');
  if(!bar||!tog) return;
  function open(){ bar.classList.add('show'); document.body.classList.add('has-sos'); }
  function close(){ bar.classList.remove('show'); document.body.classList.remove('has-sos'); }
  tog.addEventListener('click', function(){
    if(bar.classList.contains('show')) close(); else open();
  });
  if(cls) cls.addEventListener('click', close);
})();

/* === Preparedness Quiz === */
(function(){
  var qs = [
    { q:'Gia đình bạn đã có túi khẩn cấp (nước, đồ ăn, đèn, thuốc) chưa?', opts:['Chưa có','Đang chuẩn bị','Đã có đủ 3–5 ngày'], pts:[0,1,2] },
    { q:'Mọi người trong nhà có biết số 112, 113, 114, 115 không?', opts:['Chưa ai nhớ','Một số người biết','Cả nhà đều biết / đã lưu máy'], pts:[0,1,2] },
    { q:'Đã thống nhất điểm sơ tán / nơi trú an toàn chưa?', opts:['Chưa','Đã bàn nhưng chưa rõ','Đã thống nhất rõ ràng'], pts:[0,1,2] },
    { q:'Bạn theo dõi cảnh báo bằng kênh nào?', opts:['Hầu như không','Mạng xã hội là chính','App KTTV + loa / chính quyền'], pts:[0,1,2] },
    { q:'Nhà có người cần hỗ trợ đặc biệt (già, trẻ nhỏ, bệnh) và đã phân công người giúp chưa?', opts:['Có nhưng chưa phân công','Không có người đặc biệt','Đã phân công rõ'], pts:[0,2,2] },
    { q:'Khi có lệnh sơ tán, phản ứng của nhà bạn thường là?', opts:['Chờ xem đã','Chuẩn bị rồi mới đi','Đi ngay theo hướng dẫn'], pts:[0,1,2] }
  ];
  var step = 0, answers = [];
  var stepEl = document.getElementById('quizStep');
  var bar = document.getElementById('quizBar');
  var num = document.getElementById('quizNum');
  var prev = document.getElementById('quizPrev');
  var next = document.getElementById('quizNext');
  if(!stepEl) return;

  function render(){
    if(step >= qs.length){ showResult(); return; }
    var item = qs[step];
    var html = '<div class="quiz-q">' + (step+1) + '. ' + item.q + '</div><div class="quiz-opts">';
    item.opts.forEach(function(o,i){
      var act = answers[step] === i ? ' active' : '';
      html += '<label class="'+act+'" data-i="'+i+'"><input type="radio" name="qz" '+(answers[step]===i?'checked':'')+'> '+o+'</label>';
    });
    html += '</div>';
    stepEl.innerHTML = html;
    bar.style.width = ((step)/qs.length*100) + '%';
    num.textContent = (step+1) + ' / ' + qs.length;
    prev.style.visibility = step === 0 ? 'hidden' : 'visible';
    next.textContent = step === qs.length-1 ? 'Xem kết quả' : 'Tiếp →';
    next.className = step === qs.length-1 ? 'quiz-submit' : 'quiz-next';
    stepEl.querySelectorAll('label').forEach(function(lb){
      lb.addEventListener('click', function(){
        answers[step] = parseInt(lb.getAttribute('data-i'),10);
        stepEl.querySelectorAll('label').forEach(function(x){ x.classList.remove('active'); });
        lb.classList.add('active');
        lb.querySelector('input').checked = true;
      });
    });
  }
  function showResult(){
    var total = 0;
    answers.forEach(function(a,i){ if(a!=null) total += qs[i].pts[a]; });
    var max = qs.length * 2;
    var pct = Math.round(total/max*100);
    var level, cls, tip;
    if(pct < 40){ level='Cần chuẩn bị gấp'; cls='level-low'; tip='Ưu tiên: lập túi khẩn cấp, lưu số 112–115, thống nhất điểm sơ tán và theo dõi app Thời tiết Việt Nam KTTV.'; }
    else if(pct < 75){ level='Khá sẵn sàng'; cls='level-mid'; tip='Bạn đã có nền tảng. Hãy hoàn thiện checklist 15 mục, diễn tập nhẹ với cả nhà và cập nhật kế hoạch mỗi mùa mưa bão.'; }
    else{ level='Sẵn sàng tốt'; cls='level-high'; tip='Rất tốt! Duy trì kiểm tra túi khẩn cấp 6 tháng/lần, chia sẻ kinh nghiệm với hàng xóm và luôn theo dõi cảnh báo chính thống.'; }
    bar.style.width = '100%';
    stepEl.innerHTML = '<div class="quiz-result"><div class="score">'+pct+'%</div><div class="level '+cls+'">'+level+'</div><p style="color:var(--muted);font-size:14px">Điểm: '+total+'/'+max+'</p><div class="quiz-tips"><b>Gợi ý:</b> '+tip+'</div><button type="button" class="quiz-next" id="quizRetry" style="margin-top:16px">Làm lại</button></div>';
    num.textContent = 'Hoàn thành';
    prev.style.visibility = 'hidden';
    next.style.visibility = 'hidden';
    var retry = document.getElementById('quizRetry');
    if(retry) retry.addEventListener('click', function(){
      step=0; answers=[]; next.style.visibility='visible'; render();
    });
  }
  next.addEventListener('click', function(){
    if(answers[step]==null && step < qs.length){ alert('Hãy chọn một đáp án trước khi tiếp tục.'); return; }
    if(step < qs.length){ step++; render(); }
  });
  prev.addEventListener('click', function(){ if(step>0){ step--; render(); next.style.visibility='visible'; }});
  render();
})();

/* === Plan generator === */
(function(){
  var btn = document.getElementById('planGen');
  if(!btn) return;
  btn.addEventListener('click', function(){
    var name = document.getElementById('pName').value.trim() || '………………';
    var phone = document.getElementById('pPhone').value.trim() || '………………';
    var addr = document.getElementById('pAddr').value.trim() || '………………';
    var risk = document.getElementById('pRisk').value;
    var meet = document.getElementById('pMeet').value.trim() || '………………';
    var care = document.getElementById('pCare').value.trim() || 'Không có / chưa ghi';
    var note = document.getElementById('pNote').value.trim() || 'Không';
    var text = 'KẾ HOẠCH SƠ TÁN GIA ĐÌNH\\n' +
      '================================\\n' +
      'Người liên hệ: ' + name + '\\n' +
      'Điện thoại: ' + phone + '\\n' +
      'Địa chỉ: ' + addr + '\\n' +
      'Rủi ro chính: ' + risk + '\\n' +
      'Điểm sơ tán: ' + meet + '\\n' +
      'Người cần hỗ trợ: ' + care + '\\n' +
      'Ghi chú: ' + note + '\\n' +
      '--------------------------------\\n' +
      'Số khẩn cấp: 112 | 113 | 114 | 115\\n' +
      'Khi có lệnh sơ tán:\\n' +
      '1. Mang túi khẩn cấp + giấy tờ\\n' +
      '2. Đi theo tuyến an toàn đã chọn\\n' +
      '3. Báo tin cho người thân\\n' +
      '4. Không quay lại vùng nguy hiểm khi chưa được phép\\n' +
      '================================\\n' +
      'SafeVN — In và dán chỗ dễ thấy trong nhà';
    document.getElementById('planText').textContent = text;
    document.getElementById('planOut').style.display = 'block';
    document.getElementById('planOut').scrollIntoView({behavior:'smooth', block:'nearest'});
  });
  var copy = document.getElementById('planCopy');
  if(copy) copy.addEventListener('click', function(){
    var t = document.getElementById('planText').textContent;
    if(navigator.clipboard) navigator.clipboard.writeText(t).then(function(){ copy.textContent='✓ Đã sao chép'; setTimeout(function(){ copy.textContent='📋 Sao chép'; },1500); });
    else{ alert('Hãy chọn và sao chép thủ công.'); }
  });
  var pr = document.getElementById('planPrint');
  if(pr) pr.addEventListener('click', function(){
    var t = document.getElementById('planText').textContent;
    var w = window.open('','_blank');
    w.document.write('<pre style="font-family:sans-serif;font-size:14px;padding:24px;line-height:1.7">'+t.replace(/</g,'&lt;')+'</pre>');
    w.document.close(); w.print();
  });
})();

/* === Disaster filter === */
(function(){
  var map = {
    all: [],
    bao: ['Bão', 'bão'],
    lu: ['Lũ', 'Ngập', 'lũ', 'ngập'],
    sat: ['Sạt lở', 'sạt'],
    han: ['Nắng nóng', 'Hạn', 'Cháy', 'cháy', 'hạn'],
    khac: ['Dông', 'Động đất', 'Xâm nhập', 'sét', 'mặn']
  };
  var bar = document.getElementById('filterBar');
  if(!bar) return;
  var cards = document.querySelectorAll('#thientai .card');
  bar.querySelectorAll('button').forEach(function(btn){
    btn.addEventListener('click', function(){
      bar.querySelectorAll('button').forEach(function(b){ b.classList.remove('active'); });
      btn.classList.add('active');
      var key = btn.getAttribute('data-f');
      cards.forEach(function(c){
        if(key === 'all'){ c.classList.remove('dimmed'); return; }
        var text = c.textContent || '';
        var keys = map[key] || [];
        var ok = keys.some(function(k){ return text.indexOf(k) !== -1; });
        if(ok) c.classList.remove('dimmed'); else c.classList.add('dimmed');
      });
      var target = document.getElementById('thientai');
      if(target) target.scrollIntoView({behavior:'smooth', block:'start'});
    });
  });
})();


/* === Education tabs === */
(function(){
  var tabs = document.getElementById('eduTabs');
  if(!tabs) return;
  tabs.querySelectorAll('button').forEach(function(btn){
    btn.addEventListener('click', function(){
      tabs.querySelectorAll('button').forEach(function(b){ b.classList.remove('active'); });
      btn.classList.add('active');
      var id = btn.getAttribute('data-edu');
      document.querySelectorAll('.edu-panel').forEach(function(p){ p.classList.remove('active'); });
      var panel = document.getElementById('edu-' + id);
      if(panel) panel.classList.add('active');
    });
  });
})();

/* === Student quiz (5 questions) === */
(function(){
  var qs = [
    { q:'Khi có bão lớn, em nên làm gì?', opts:['Ra ngoài xem gió mạnh','Ở trong nhà chắc, đóng cửa','Đứng dưới gốc cây'], ok:1 },
    { q:'Số điện thoại trợ giúp khẩn cấp là số nào?', opts:['113','114','112'], ok:2 },
    { q:'Có nên lội qua nước lũ trên đường không?', opts:['Có, nếu trông nông','Không, rất nguy hiểm','Chỉ cần đi nhanh'], ok:1 },
    { q:'Khi trường báo sơ tán, em nên?', opts:['Chạy một mình về nhà','Đi theo thầy cô, không tách nhóm','Ở lại lớp chờ hết bão'], ok:1 },
    { q:'Tin cảnh báo nên ưu tiên từ đâu?', opts:['Tin đồn trên mạng','Loa trường / thầy cô / chính quyền','Chỉ hỏi bạn bè'], ok:1 }
  ];
  var step = 0, answers = [];
  var stepEl = document.getElementById('eduQuizStep');
  var bar = document.getElementById('eduQuizBar');
  var num = document.getElementById('eduQuizNum');
  var prev = document.getElementById('eduQuizPrev');
  var next = document.getElementById('eduQuizNext');
  if(!stepEl) return;

  function render(){
    if(step >= qs.length){ showResult(); return; }
    var item = qs[step];
    var h = '<div class="quiz-q">'+(step+1)+'. '+item.q+'</div><div class="quiz-opts">';
    item.opts.forEach(function(o,i){
      var act = answers[step]===i ? ' active' : '';
      h += '<label class="'+act+'" data-i="'+i+'"><input type="radio" name="eqz" '+(answers[step]===i?'checked':'')+'> '+o+'</label>';
    });
    h += '</div>';
    stepEl.innerHTML = h;
    bar.style.width = (step/qs.length*100)+'%';
    num.textContent = (step+1)+' / '+qs.length;
    prev.style.visibility = step===0 ? 'hidden' : 'visible';
    next.textContent = step===qs.length-1 ? 'Xem điểm' : 'Tiếp →';
    stepEl.querySelectorAll('label').forEach(function(lb){
      lb.addEventListener('click', function(){
        answers[step] = parseInt(lb.getAttribute('data-i'),10);
        stepEl.querySelectorAll('label').forEach(function(x){ x.classList.remove('active'); });
        lb.classList.add('active');
      });
    });
  }
  function showResult(){
    var correct = 0;
    answers.forEach(function(a,i){ if(a===qs[i].ok) correct++; });
    var tips = [
      'Đúng: Ở trong nhà chắc khi bão.',
      'Đúng: 112 là số trợ giúp khẩn cấp chung.',
      'Đúng: Không lội nước lũ — có thể sâu, chảy xiết, có điện.',
      'Đúng: Sơ tán theo thầy cô, không tách nhóm.',
      'Đúng: Ưu tiên loa trường, thầy cô và chính quyền.'
    ];
    var explain = '<ul style="text-align:left;margin-top:12px">';
    tips.forEach(function(t,i){
      var mark = answers[i]===qs[i].ok ? '✅' : '❌';
      explain += '<li style="margin:6px 0">'+mark+' '+t+'</li>';
    });
    explain += '</ul>';
    bar.style.width = '100%';
    var msg = correct>=4 ? 'Giỏi lắm! Em đã nắm được kiến thức an toàn.' : (correct>=3 ? 'Khá tốt! Xem lại vài ý chưa đúng.' : 'Cần ôn lại các nguyên tắc an toàn nhé.');
    stepEl.innerHTML = '<div class="quiz-result"><div class="score">'+correct+'/5</div><p style="font-weight:700;color:var(--navy)">'+msg+'</p>'+explain+'<button type="button" class="quiz-next" id="eduQuizRetry" style="margin-top:14px">Làm lại</button></div>';
    num.textContent = 'Xong';
    prev.style.visibility = 'hidden';
    next.style.visibility = 'hidden';
    var r = document.getElementById('eduQuizRetry');
    if(r) r.addEventListener('click', function(){ step=0; answers=[]; next.style.visibility='visible'; render(); });
  }
  next.addEventListener('click', function(){
    if(answers[step]==null && step<qs.length){ alert('Em hãy chọn một đáp án nhé!'); return; }
    if(step<qs.length){ step++; render(); }
  });
  prev.addEventListener('click', function(){ if(step>0){ step--; next.style.visibility='visible'; render(); }});
  render();
})();

/* === School checklist === */
(function(){
  var items = [
    'Đã kiểm tra mái, cửa sổ, cổng trường',
    'Đã thông thoát nước sân, cống trong khuôn viên',
    'Đã rà cây xanh, biển hiệu dễ đổ',
    'Đã cập nhật danh sách HS và SĐT phụ huynh',
    'Đã phân công ban chỉ huy PCTT nhà trường',
    'Đã xác định lối thoát hiểm và điểm tập kết',
    'Đã diễn tập sơ tán ít nhất 1 lần trong năm',
    'Đã chuẩn bị loa, đèn pin, túi sơ cứu tại văn phòng',
    'Đã có phương án thông báo phụ huynh (Zalo/nhóm lớp)',
    'Đã theo dõi app Thời tiết Việt Nam KTTV / bản tin chính thức'
  ];
  var box = document.getElementById('schoolItems');
  if(!box) return;
  items.forEach(function(x){
    box.insertAdjacentHTML('beforeend', '<label><input type="checkbox" class="sch-cb"> '+x+'</label>');
  });
  function upd(){
    var n = document.querySelectorAll('.sch-cb:checked').length;
    var bar = document.getElementById('schoolBar');
    var txt = document.getElementById('schoolTxt');
    if(bar) bar.style.width = (n/items.length*100)+'%';
    if(txt) txt.textContent = n+'/'+items.length+' mục đã sẵn sàng';
  }
  box.querySelectorAll('.sch-cb').forEach(function(c){ c.addEventListener('change', upd); });
})();

</script>


<button class="sos-toggle" id="sosToggle" title="Số khẩn cấp">🆘</button>
<div class="sos-bar" id="sosBar">
  <span>Gọi khẩn:</span>
  <a href="tel:112">112 Trợ giúp</a>
  <a href="tel:113">113 Công an</a>
  <a href="tel:114">114 Cứu hỏa</a>
  <a href="tel:115">115 Cấp cứu</a>
  <button class="sos-close" id="sosClose" title="Đóng">×</button>
</div>

<button id="topBtn" onclick="window.scrollTo({top:0,behavior:'smooth'})" title="Lên đầu trang">↑</button>

</body>
</html>
