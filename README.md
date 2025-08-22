<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>VNTX — الموقع الرسمي</title>
<link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700;900&display=swap" rel="stylesheet">
<style>
:root{
  --bg:#0a0012;
  --neon1:#8a2be2;
  --neon2:#d08cff;
  --muted:#cfc6dd;
}
*{margin:0;padding:0;box-sizing:border-box}
body{
  font-family:"Cairo",sans-serif;
  background:linear-gradient(135deg,var(--bg),#12021a 40%,#1a0326 100%);
  color:#fff;overflow-x:hidden;text-align:center;min-height:100vh;
}
header{padding:40px 20px;}
header h1{
  font-size:42px;font-weight:900;
  background:linear-gradient(90deg,var(--neon1),var(--neon2));
  -webkit-background-clip:text;-webkit-text-fill-color:transparent;
  text-shadow:0 0 30px var(--neon1),0 0 50px var(--neon2);
  animation:glowText 3s infinite alternate;
}
@keyframes glowText{
  from{text-shadow:0 0 20px var(--neon1);}
  to{text-shadow:0 0 40px var(--neon2),0 0 70px var(--neon1);}
}
header p{margin-top:10px;color:var(--muted);font-size:18px}

/* عدادات */
.counters{display:flex;justify-content:center;gap:20px;flex-wrap:wrap;margin:30px 0;}
.counter{
  background:rgba(255,255,255,0.05);border:2px solid var(--neon2);
  border-radius:18px;padding:20px 40px;box-shadow:0 0 20px var(--neon1);
}
.counter-number{font-size:36px;font-weight:900;color:var(--neon2);}
.counter-label{font-size:14px;color:var(--muted);margin-top:5px;}

/* عناوين */
.section-title{margin:40px 0 20px;color:var(--neon2);font-size:24px;font-weight:700;}

/* شبكة عامة */
.names-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:20px;justify-items:center;margin-bottom:20px;
}

/* شبكة خاصة للمصممين: صفين */
.designers-grid{
  display:grid;
  grid-template-columns:repeat(2,1fr); /* 2 جنب بعض */
  gap:20px;justify-items:center;margin-bottom:20px;
}
@media(max-width:700px){
  .designers-grid{grid-template-columns:1fr;} /* موبايل: واحد */
}

.name-card{
  background:linear-gradient(135deg,var(--neon1),var(--neon2));
  color:#fff;font-weight:900;font-size:22px;
  padding:30px 20px;border-radius:18px;
  text-decoration:none;display:flex;align-items:center;justify-content:center;
  box-shadow:0 0 20px var(--neon2),0 0 40px var(--neon1);
  transition:.3s;
}
.name-card:hover{transform:scale(1.08) rotate(-2deg);}

/* ألوان خاصة للسوشيال */
.tiktok{background:linear-gradient(135deg,#000,#fff);}
.twitter{background:linear-gradient(135deg,#1DA1F2,#0d47a1);}
.telegram{background:linear-gradient(135deg,#0088cc,#00bfff);}

/* Discord Section */
.discord-section{
  margin:60px auto;padding:40px 20px;border-radius:20px;
  background:rgba(255,255,255,0.05);border:2px dashed var(--neon2);
  max-width:600px;box-shadow:0 0 30px rgba(138,43,226,0.4);
}
.discord-section h2{font-size:26px;margin-bottom:20px;color:var(--neon2);}
.discord-btn{
  display:inline-block;padding:16px 32px;font-size:20px;font-weight:800;
  text-decoration:none;color:#fff;border-radius:14px;
  background:linear-gradient(90deg,var(--neon1),var(--neon2));
  box-shadow:0 0 20px var(--neon2),0 0 40px var(--neon1);
}
.discord-btn:hover{transform:scale(1.1);}

/* زر الموسيقى */
.music-control{position:fixed;bottom:20px;left:20px;z-index:999;}
.music-btn{
  background:linear-gradient(90deg,var(--neon1),var(--neon2));
  border:none;padding:12px 18px;border-radius:50%;color:#fff;
  font-weight:900;cursor:pointer;box-shadow:0 0 20px var(--neon2),0 0 40px var(--neon1);
}
.music-btn:hover{transform:scale(1.2);}
footer{margin:50px 0 20px;font-size:13px;color:var(--muted)}
</style>
</head>
<body>

<header>
  <h1>فريق VNTX</h1>
  <p>نحن فريق مصممين نقدم تصاميم احترافية ✨</p>
</header>

<!-- عدادات -->
<div class="counters">
  <div class="counter">
    <div class="counter-number" id="designersCount">0</div>
    <div class="counter-label">+100 مصمم</div>
  </div>
  <div class="counter">
    <div class="counter-number" id="membersCount">0</div>
    <div class="counter-label">+700 عضو</div>
  </div>
</div>

<!-- Discord Section -->
<div class="discord-section">
  <h2>✨ انضم إلينا على الديسكورد ✨</h2>
  <a class="discord-btn" href="https://discord.gg/vxtm" target="_blank">الانضمام الآن</a>
</div>

<!-- Owner -->
<h2 class="section-title">Owner</h2>
<div class="names-grid">
  <a href="https://www.tiktok.com/@2zdx_" target="_blank" class="name-card">ZDX</a>
</div>

<!-- Admins -->
<h2 class="section-title">أبرز المسؤولين</h2>
<div class="names-grid">
  <a href="https://www.tiktok.com/@a7ns2" target="_blank" class="name-card">A7N</a>
  <a href="https://www.tiktok.com/@.d7s6" target="_blank" class="name-card">D7S</a>
</div>

<!-- Designers -->
<h2 class="section-title">أبرز المصممين</h2>
<div class="designers-grid">
  <a href="https://www.tiktok.com/@k2.wolfer" target="_blank" class="name-card">WOLFER</a>
  <a href="https://www.tiktok.com/@238.l1" target="_blank" class="name-card">D7F</a>
  <a href="https://www.tiktok.com/@xxa1_1" target="_blank" class="name-card">XXA</a>
  <a href="https://www.tiktok.com/@zkrx18" target="_blank" class="name-card">LIOYD</a>
  <a href="https://www.tiktok.com/@ma13rt" target="_blank" class="name-card">MBR</a>
  <a href="https://www.tiktok.com/@vdrb77hv" target="_blank" class="name-card">TKZ</a>
  <a href="https://www.tiktok.com/@.nsj__" target="_blank" class="name-card">NSJ</a>
</div>

<!-- Social -->
<h2 class="section-title">حساباتنا</h2>
<div class="names-grid">
  <a href="https://www.tiktok.com/@teamvx1top" target="_blank" class="name-card tiktok">TikTok</a>
  <a href="https://x.com/VntxT36007" target="_blank" class="name-card twitter">Twitter</a>
  <a href="https://t.me/teamvx1" target="_blank" class="name-card telegram">Telegram</a>
</div>

<footer>© Team VNTX - فريق فنتكس</footer>

<!-- يوتيوب -->
<div id="ytplayer" style="display:none;"></div>
<div class="music-control">
  <button class="music-btn" onclick="toggleMusic()" id="musicBtn">▶</button>
</div>

<script>
// عدادات متصاعدة
function animateCounter(id,end){
  const el=document.getElementById(id);
  let start=0;
  const step=Math.ceil(end/200);
  const interval=setInterval(()=>{
    start+=step;
    if(start>=end){start=end;clearInterval(interval);}
    el.textContent=start;
  },20);
}
animateCounter('designersCount',100);
animateCounter('membersCount',700);

// YouTube API
let player;let isPlaying=false;
function onYouTubeIframeAPIReady(){
  player=new YT.Player('ytplayer',{
    height:'0',width:'0',
    videoId:'DOnFYgvD50M',
    playerVars:{'autoplay':0,'controls':0}
  });
}
function toggleMusic(){
  if(!player)return;
  const btn=document.getElementById("musicBtn");
  if(isPlaying){player.pauseVideo();isPlaying=false;btn.textContent="▶";}
  else{player.playVideo();isPlaying=true;btn.textContent="⏸";}
}
let tag=document.createElement('script');
tag.src="https://www.youtube.com/iframe_api";
document.body.appendChild(tag);
</script>

</body>
</html>
