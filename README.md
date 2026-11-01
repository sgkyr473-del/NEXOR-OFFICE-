






<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NEXOR OFFICIAL | مرجع تخصصی گیمینگ</title>
<meta name="description" content="NEXOR، مرجع اختصاصی معرفی پنل‌ها، ابزارها و محتوای گیمینگ.">
<link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;600;700;800;900&display=swap" rel="stylesheet">

<style>
*{margin:0;padding:0;box-sizing:border-box}
:root{
 --red:#ff153d;
 --dark:#07070a;
 --blue:#168cff;
}
html{scroll-behavior:smooth}
body{
 background:var(--dark);
 color:white;
 font-family:Vazirmatn,sans-serif;
 overflow-x:hidden;
}
body:before{
 content:"";
 position:fixed;
 width:400px;height:400px;
 background:var(--red);
 filter:blur(170px);
 opacity:.17;
 top:5%;left:-180px;
 pointer-events:none;
}
body:after{
 content:"";
 position:fixed;
 width:350px;height:350px;
 background:#a500ff;
 filter:blur(170px);
 opacity:.12;
 bottom:0;right:-150px;
 pointer-events:none;
}
a{text-decoration:none;color:inherit}
header{
 position:sticky;top:0;z-index:10;
 background:#08080bdc;
 backdrop-filter:blur(20px);
 border-bottom:1px solid #ffffff12;
}
.nav{
 max-width:1150px;margin:auto;
 padding:17px 22px;
 display:flex;align-items:center;
 justify-content:space-between;
}
.logo{
 font-size:24px;font-weight:900;
 letter-spacing:3px;color:white;
}
.tick{
 display:inline-flex;
 width:19px;height:19px;
 align-items:center;justify-content:center;
 border-radius:50%;
 background:var(--blue);
 color:white;
 font-size:13px;
 vertical-align:middle;
 box-shadow:0 0 15px #168cff77;
}
.navtag{
 font-size:11px;color:#aaa;
 border:1px solid #ffffff20;
 padding:8px 13px;border-radius:30px;
}
.hero{
 min-height:720px;
 display:flex;flex-direction:column;
 align-items:center;justify-content:center;
 text-align:center;padding:80px 20px;
 position:relative;
}
.hero:before{
 content:"NEXOR";
 position:absolute;
 font-size:clamp(100px,23vw,260px);
 font-weight:900;color:#ffffff04;
 z-index:-1;
}
.pill{
 background:#ff153d12;
 border:1px solid #ff153d55;
 color:#ff657d;
 padding:9px 20px;
 border-radius:40px;
 font-size:12px;
 margin-bottom:27px;
 animation:pulse 2s infinite;
}
h1{
 font-size:clamp(65px,14vw,125px);
 font-weight:900;
 letter-spacing:7px;
 line-height:1.2;
 background:linear-gradient(120deg,#fff 15%,#ff526c 50%,#b50028);
 -webkit-background-clip:text;
 color:transparent;
 filter:drop-shadow(0 0 30px #ff153d33);
}
.official{
 color:#168cff;
 font-weight:800;
 font-size:15px;
 margin-top:13px;
}
.official .tick{margin-left:5px}
.subtitle{
 max-width:680px;
 color:#a4a4ad;
 line-height:2.5;
 font-size:14px;
 margin:25px auto 30px;
}
.subtitle strong{color:white}
.actions{
 display:flex;gap:14px;
 justify-content:center;flex-wrap:wrap;
}
.btn{
 padding:15px 26px;
 border-radius:13px;
 font-weight:800;font-size:13px;
 display:inline-flex;align-items:center;
 justify-content:center;gap:9px;
 transition:.3s;
}
.btn:hover{transform:translateY(-5px);filter:brightness(1.2)}
.primary{
 background:linear-gradient(110deg,#ff153d,#a60029);
 box-shadow:0 8px 30px #ff153d35;
}
.secondary{
 background:#168cff;
 box-shadow:0 8px 30px #168cff35;
}
.outline{
 border:1px solid #ffffff25;
 background:#ffffff08;
}
.trust{
 margin-top:55px;
 display:flex;gap:30px;
 flex-wrap:wrap;justify-content:center;
 color:#777;font-size:11px;
}
.trust span{color:#ddd}
section{
 width:min(1100px,90%);
 margin:90px auto;
}
.heading{text-align:center;margin-bottom:40px}
.heading small{
 color:var(--red);font-size:11px;
 letter-spacing:3px;font-weight:800;
}
.heading h2{
 font-size:30px;font-weight:900;
 margin-top:10px;
}
.heading h2 span{color:var(--red)}
.heading p{
 color:#888;font-size:12px;
 margin-top:12px;line-height:2;
}
.features{
 display:grid;
 grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
 gap:17px;
}
.feature{
 position:relative;
 overflow:hidden;
 background:linear-gradient(145deg,#191217,#0d0c10);
 border:1px solid #ffffff13;
 border-radius:20px;
 padding:28px 22px;
 transition:.35s;
}
.feature:hover{
 transform:translateY(-8px);
 border-color:#ff153d88;
 box-shadow:0 15px 40px #ff153d12;
}
.feature:after{
 content:"";
 position:absolute;
 width:100px;height:100px;
 background:#ff153d;
 filter:blur(80px);
 opacity:.18;top:-40px;left:-30px;
}
.ico{font-size:32px;margin-bottom:20px}
.feature h3{font-size:17px;margin-bottom:12px}
.feature p{font-size:12px;color:#888;line-height:2.3}
.banner{
 padding:50px 25px;
 text-align:center;
 border:1px solid #ff153d55;
 border-radius:25px;
 background:linear-gradient(120deg,#200b12,#100d12,#1a0b12);
 box-shadow:inset 0 0 50px #ff153d0c;
}
.banner h2{font-size:clamp(23px,5vw,38px);font-weight:900}
.banner p{
 color:#aaa;font-size:13px;
 line-height:2.5;margin:15px auto 25px;
 max-width:600px;
}
.channel-grid{
 display:grid;
 grid-template-columns:1fr 1fr;
 gap:16px;margin-top:30px;
}
.channel{
 padding:25px;
 border:1px solid #ffffff17;
 background:#ffffff06;
 border-radius:18px;
 text-align:center;
}
.channel h3{font-size:18px;margin-bottom:9px}
.channel p{color:#888;font-size:11px;margin-bottom:18px}
.channel a{
 display:inline-block;
 padding:11px 22px;
 border-radius:10px;
 font-size:12px;font-weight:800;
}
.channel.tg a{background:#168cff}
.channel.rb a{background:#e62949}
.final{
 text-align:center;
 padding:45px 15px;
 border-top:1px solid #ffffff12;
 color:#666;font-size:11px;line-height:2.5;
}
.final strong{color:#ff304d}
@keyframes pulse{
 50%{box-shadow:0 0 25px #ff153d25}
}
@media(max-width:550px){
 .hero{min-height:650px}
 .nav{padding:14px}
 .channel-grid{grid-template-columns:1fr}
 .trust{gap:15px}
 section{margin:70px auto}
}
</style>
</head>

<body>

<header>
 <div class="nav">
  <div class="logo">NEXOR <span class="tick">✓</span></div>
  <div class="navtag">✦ OFFICIAL BRAND</div>
 </div>
</header>

<main>

<div class="hero">

 <div class="pill">✦ WELCOME TO THE NEXT LEVEL ✦</div>

 <h1>NEXOR</h1>

 <div class="official">
  <span class="tick">✓</span>
  OFFICIAL GAMING BRAND
 </div>

 <p class="subtitle">
  به <strong>مرجع اختصاصی و رسمی NEXOR</strong> خوش آمدید.
  <br>
  دنیایی متفاوت از پنل‌های گیمینگ، ابزارهای اختصاصی،
  ایموجی‌های خاص و جدیدترین محتوای دنیای بازی.
  <br>
  <strong>قدرت، کیفیت و تفاوت؛ با امضای NEXOR.</strong>
 </p>

 <div class="actions">
  <a class="btn primary" href="https://t.me/NEXOR_PANEL" target="_blank">
   ✈ عضویت در تلگرام
  </a>
  <a class="btn secondary" href="https://rubika.ir/PANEL_NEXOR" target="_blank">
   ✦ عضویت در روبیکا
  </a>
 </div>

 <div class="trust">
  <div>✓ <span>برند اختصاصی NEXOR</span></div>
  <div>✦ <span>محتوای تخصصی گیمینگ</span></div>
  <div>♛ <span>تجربه متفاوت</span></div>
 </div>

</div>

<section>
 <div class="heading">
  <small>WHY NEXOR?</small>
  <h2>دنیای <span>NEXOR</span> چه دارد؟</h2>
  <p>همه چیز در یک مجموعه اختصاصی برای علاقه‌مندان گیمینگ</p>
 </div>

 <div class="features">

  <div class="feature">
   <div class="ico">⚡</div>
   <h3>پنل‌های اختصاصی</h3>
   <p>معرفی مجموعه‌ای از پنل‌ها و ابزارهای متنوع گیمینگ.</p>
  </div>

  <div class="feature">
   <div class="ico">🎯</div>
   <h3>بخش ابزار و چیت</h3>
   <p>معرفی محتوای تخصصی و ابزارهای مرتبط با بازی‌ها.</p>
  </div>

  <div class="feature">
   <div class="ico">💎</div>
   <h3>ایموجی‌های خاص</h3>
   <p>دسترسی به استایل‌ها و مجموعه‌های جذاب ایموجی.</p>
  </div>

  <div class="feature">
   <div class="ico">🔥</div>
   <h3>آپدیت و اخبار</h3>
   <p>اطلاع‌رسانی درباره مطالب و محصولات جدید مجموعه.</p>
  </div>

 </div>
</section>

<section>
 <div class="banner">
  <div class="pill">NEXOR COMMUNITY</div>
  <h2>فقط تماشا نکن؛ عضو خانواده NEXOR شو!</h2>
  <p>
   برای دسترسی به آخرین مطالب، معرفی‌ها و اطلاعیه‌های مجموعه،
   همین حالا به کانال‌های ما بپیوند.
  </p>
  <div class="actions">
   <a class="btn primary" href="https://t.me/NEXOR_PANEL" target="_blank">
    JOIN TELEGRAM ↗
   </a>
   <a class="btn secondary" href="https://rubika.ir/PANEL_NEXOR" target="_blank">
    JOIN RUBIKA ↗
   </a>
  </div>
 </div>
</section>

<section>
 <div class="heading">
  <small>CONNECT WITH US</small>
  <h2>کانال‌های <span>اصلی NEXOR</span></h2>
  <p>از طریق لینک‌های زیر به صفحات مجموعه وارد شوید.</p>
 </div>

 <div class="channel-grid">
  <div class="channel tg">
   <h3>✈ TELEGRAM</h3>
   <p>کانال تلگرام NEXOR</p>
   <a href="https://t.me/NEXOR_PANEL" target="_blank">ورود به تلگرام ↗</a>
  </div>

  <div class="channel rb">
   <h3>✦ RUBIKA</h3>
   <p>کانال روبیکا NEXOR</p>
   <a href="https://rubika.ir/PANEL_NEXOR" target="_blank">ورود به روبیکا ↗</a>
  </div>
 </div>
</section>

</main>

<footer class="final">
 <strong>♛ NEXOR OFFICIAL ♛</strong>
 <br>
 THE NEXT LEVEL OF GAMING
 <br>
 © 2026 NEXOR. ALL RIGHTS RESERVED.
</footer>

</body>
</html>
