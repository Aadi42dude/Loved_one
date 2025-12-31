<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy New Year Love Story</title>
<style>
*{margin:0;padding:0;box-sizing:border-box}
body{
  height:100vh;
  width:100vw;
  font-family:'Segoe UI',sans-serif;
  background:black;
  overflow:hidden;
  display:flex;
  justify-content:center;
  align-items:center;
}
.page{
  position:absolute;
  inset:0;
  display:none;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:20px;
  width:1080px;
  height:1920px;
  margin:auto;
}
.page.active{display:flex}
.card{
  background:rgba(0,0,0,.55);
  border-radius:20px;
  padding:30px;
  max-width:800px;
  animation:fade 1.8s ease;
}
button{
  margin-top:25px;
  padding:12px 26px;
  border:none;
  border-radius:30px;
  background:#ff5fa2;
  color:white;
  font-size:18px;
  cursor:pointer;
}
@keyframes fade{from{opacity:0;transform:translateY(25px)}to{opacity:1}}
.typing::after{content:'|';animation:blink 1s infinite}
@keyframes blink{50%{opacity:0}}
.float{animation:float 3s ease-in-out infinite}
@keyframes float{50%{transform:translateY(-15px)}}

/* Fireworks animation */
.firework{
  position:absolute;
  width:12px;
  height:12px;
  border-radius:50%;
  animation:fly 1s linear infinite;
}
@keyframes fly{
  0%{transform:translateY(0) scale(1);opacity:1;}
  100%{transform:translateY(-800px) scale(0.2);opacity:0;}
}

/* Dancing babies along border */
.baby{
  position:absolute;
  width:80px;
  height:80px;
  animation:dance 2s linear infinite;
}
@keyframes dance{
  0%,100%{transform:translateY(0);}
  50%{transform:translateY(-20px);}
}

/* Popup */
.popup{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,.8);
  display:none;
  align-items:center;
  justify-content:center;
  z-index:999;
}
.popup div{
  background:white;
  color:black;
  padding:40px;
  border-radius:20px;
  font-size:30px;
  text-align:center;
  animation:fade 1.5s ease;
}
</style>
</head>
<body>

<!-- MUSIC -->
<audio id="music" loop preload="auto">
  <source src="https://drive.google.com/uc?export=download&id=17nvYmoh8SPvdAiePfkOAYYyQhDPnzbqw" type="audio/mpeg">
</audio>

<!-- Fireworks container -->
<div id="fireworks"></div>

<!-- Dancing babies -->
<img src="https://i.imgur.com/8GQZ8YH.png" class="baby" style="top:10px;left:10px;">
<img src="https://i.imgur.com/8GQZ8YH.png" class="baby" style="top:10px;right:10px;">
<img src="https://i.imgur.com/8GQZ8YH.png" class="baby" style="bottom:10px;left:10px;">
<img src="https://i.imgur.com/8GQZ8YH.png" class="baby" style="bottom:10px;right:10px;">

<!-- Pages -->
<div class="page active" id="p1">
  <div class="card">
    <h2 class="typing" id="t1"></h2>
    <button onclick="startExperience()">Open slowly 💗</button>
  </div>
</div>

<div class="page" id="p2">
  <div class="card">
    <p class="typing" id="t2"></p>
    <button onclick="nextPage()">I remember… 🌸</button>
  </div>
</div>

<div class="page" id="p3">
  <div class="card">
    <img src="https://i.imgur.com/8GQZ8YH.png" width="250" class="float"><br><br>
    <p>A little panda brought something for you 🐼💖</p>
    <button onclick="nextPage()">Tap my belly 😄</button>
  </div>
</div>

<div class="page" id="p4">
  <div class="card">
    <div class="float">💌</div>
    <p class="typing" id="t4"></p>
    <button onclick="nextPage()">Open my heart 💞</button>
  </div>
</div>

<div class="page" id="p5" style="background:url('https://i.imgur.com/9sJYH0G.jpg') center/cover no-repeat;">
  <div class="card">
    <p class="typing" id="t5"></p>
    <img src="https://i.imgur.com/vibranthuggingcouple.png" style="width:400px; position:absolute; bottom:50px; left:50%; transform:translateX(-50%);">
  </div>
</div>

<div class="popup" id="popup">
  <div>✨ Happy New Year 💝 ✨</div>
</div>

<script>
// Text content
const text=[
"As the year ends… I have one question for you 💭",
"Do you remember how bright you once were? So happy, so healthy… and so full of love. You are still that person 🤍",
"",
"You may slowly forget me… but I never forgot us.",
"Happy New Year Kirabdhi Tanaya 💖\n\nAs the clock counts down, my mind drifts back to every quiet morning and the late-night laughs that made our stomachs hurt.\n\nLooking at our old photos reminded me — while years change, my heart for you only grows deeper.\n\nFrom our very first hello to this exact moment, you have been the best part of my life."
];

// Pages
const pages=['p1','p2','p3','p4','p5'];
let currentPage=0;

// Typing effect
function type(id,txt){
  let i=0;
  let el=document.getElementById(id);
  el.innerHTML="";
  let interval=setInterval(()=>{
    el.innerHTML+=txt[i++];
    if(i>=txt.length) clearInterval(interval);
  },45);
}

// Start experience
function startExperience(){
  const music=document.getElementById("music");
  music.play().catch(()=>{});
  showPage(1);
  type("t2", text[1]);
}

// Show page
function showPage(idx){
  document.getElementById(pages[currentPage]).classList.remove("active");
  document.getElementById(pages[idx]).classList.add("active");
  currentPage=idx;
  if(currentPage===3) type("t4", text[3]);
  if(currentPage===4){
    type("t5", text[4]);
    let typingDuration=text[4].length*45 + 2000;
    setTimeout(()=>document.getElementById("popup").style.display="flex", typingDuration);
  }
}

// Next page
function nextPage(){
  if(currentPage<pages.length-1){
    showPage(currentPage+1);
  }
}

// Initial typing page1
type("t1", text[0]);

// Fireworks
function createFirework(){
  const fw=document.createElement('div');
  fw.className='firework';
  fw.style.left=Math.random()*window.innerWidth+'px';
  fw.style.top=window.innerHeight+'px';
  fw.style.background='hsl('+Math.random()*360+',100%,50%)';
  document.body.appendChild(fw);
  setTimeout(()=>fw.remove(),1500);
}
setInterval(createFirework,50); // very fast for continuous big blasts
</script>

</body>
</html>
