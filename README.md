
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday Tiddy 💗</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;400;500;600;700&display=swap');

:root {
  --pink: #ff75ad;
  --light: #fff0f6;
  --dark: #71334e;
  --white: #fffafd;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  scroll-behavior: smooth;
}

body {
  font-family: 'Poppins', sans-serif;
  color: var(--dark);
  background: linear-gradient(135deg,#fff0f6,#ffe0ed,#fff7fa);
  overflow-x: hidden;
}

button {
  border: none;
  cursor: pointer;
  font-family: inherit;
}

section {
  padding: 75px 20px;
  text-align: center;
}

h1,h2 {
  font-family: 'Pacifico', cursive;
  color: #ed5796;
}

h2 {
  font-size: clamp(2rem,5vw,3rem);
  margin-bottom: 25px;
}

p {
  line-height: 1.8;
}

.card {
  background: rgba(255,255,255,.82);
  border: 1px solid white;
  border-radius: 25px;
  padding: 25px;
  box-shadow: 0 10px 30px #e879a51c;
}

.pink-btn {
  background: linear-gradient(135deg,#ff6da9,#ff9bc4);
  color: white;
  padding: 13px 25px;
  border-radius: 30px;
  margin: 10px;
  font-weight: 600;
  box-shadow: 0 5px 15px #f78bbd55;
  transition: .3s;
}

.pink-btn:hover {
  transform: translateY(-4px) scale(1.04);
}

#intro {
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  padding: 25px;
}

#intro h1 {
  font-size: clamp(3rem,9vw,6rem);
}

#intro p {
  margin: 15px 0;
}

.hero {
  min-height: 85vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background: radial-gradient(circle,#fff,#ffe0ed);
}

.hero h1 {
  font-size: clamp(3rem,10vw,6rem);
}

.subtitle {
  font-size: 1.1rem;
  margin: 15px;
}

.countdown {
  display: flex;
  justify-content: center;
  gap: 12px;
  flex-wrap: wrap;
  margin: 25px;
}

.time-box {
  background: white;
  border-radius: 18px;
  padding: 15px;
  min-width: 75px;
  box-shadow: 0 5px 20px #e879a522;
}

.time-box strong {
  display: block;
  color: #ed5796;
  font-size: 1.5rem;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
  gap: 20px;
  max-width: 1000px;
  margin: auto;
}

.gallery img {
  width: 100%;
  height: 230px;
  object-fit: cover;
  border-radius: 18px;
  background: #ffe0ed;
}

.gallery input {
  width: 100%;
  margin-top: 10px;
}

.letter {
  max-width: 750px;
  margin: auto;
  text-align: left;
  line-height: 2;
  font-size: 1rem;
}

.reason {
  transition: .3s;
}

.reason:hover {
  transform: translateY(-7px) rotate(-1deg);
}

#cake {
  font-size: 100px;
  cursor: pointer;
  display: inline-block;
  transition: .3s;
}

#cake:hover {
  transform: scale(1.15);
}

#gift {
  font-size: 100px;
  cursor: pointer;
  transition: .3s;
}

#gift:hover {
  transform: rotate(10deg) scale(1.1);
}

#gameArea {
  position: relative;
  height: 350px;
  max-width: 600px;
  margin: 20px auto;
  overflow: hidden;
  background: #fff;
  border: 3px dashed #ff9bc4;
  border-radius: 25px;
}

.heart {
  position: absolute;
  font-size: 30px;
  cursor: pointer;
  user-select: none;
}

input[type="password"] {
  padding: 13px;
  border: 2px solid #ffacd0;
  border-radius: 20px;
  outline: none;
  width: min(280px,90%);
  margin: 10px;
  text-align: center;
}

#secretMessage {
  display: none;
  margin: 25px auto;
  max-width: 600px;
  font-family: 'Pacifico',cursive;
  color: #ed5796;
  font-size: 2rem;
  animation: pop .6s ease;
}

#music {
  position: fixed;
  right: 15px;
  bottom: 15px;
  z-index: 10;
  background: white;
  padding: 12px;
  border-radius: 30px;
  box-shadow: 0 5px 20px #0002;
}

#music input {
  max-width: 150px;
}

#topBtn {
  position: fixed;
  left: 15px;
  bottom: 15px;
  border-radius: 50%;
  background: #ff75ad;
  color: white;
  width: 45px;
  height: 45px;
  font-size: 20px;
  z-index: 10;
}

footer {
  padding: 35px;
  text-align: center;
  background: #ffe0ed;
}

.float {
  position: fixed;
  pointer-events: none;
  z-index: 20;
  animation: floatUp 4s linear forwards;
}

@keyframes floatUp {
  to {
    transform: translateY(-110vh) rotate(360deg);
    opacity: 0;
  }
}

@keyframes pop {
  from {transform:scale(.5);opacity:0}
  to {transform:scale(1);opacity:1}
}

@media(max-width:600px) {
  section {padding:55px 15px}
  .letter {font-size:.95rem}
  #music {max-width: calc(100% - 20px)}
}
</style>
</head>

<body>

<!-- INTRO -->
<div id="intro">
  <div style="font-size:70px">🎀💗</div>
  <h1>Hey Tiddy!</h1>
  <p>I made something special for you...</p>
  <p>Are you ready, birthday girl?</p>
  <button class="pink-btn" onclick="enterSite()">OPEN YOUR SURPRISE 💌</button>
</div>

<!-- MAIN WEBSITE -->
<main id="main" style="display:none">

<!-- HERO -->
<div class="hero">
  <div style="font-size:65px">🎂🌷</div>
  <h1>Happy Birthday Tiddy!</h1>
  <p class="subtitle">To my favourite human, my boni, my forever headache 💗</p>
  <p>मंसिर २२ — Your special day!</p>

  <div class="countdown">
    <div class="time-box"><strong id="days">--</strong>Days</div>
    <div class="time-box"><strong id="hours">--</strong>Hours</div>
    <div class="time-box"><strong id="minutes">--</strong>Minutes</div>
    <div class="time-box"><strong id="seconds">--</strong>Seconds</div>
  </div>

  <button class="pink-btn" onclick="document.getElementById('letter').scrollIntoView()">READ YOUR LETTER 💌</button>
</div>

<!-- LETTER -->
<section id="letter">
  <h2>A Little Letter For You 💗</h2>
  <div class="card letter">
    Dear Tiddy,

    <br><br>
    Happy birthday to one of the most precious people in my life.
    I genuinely don't know how to explain how much you mean to me.
    You're not just my best friend, you're my comfort person,
    my personal comedian, my favourite troublemaker and my
    forever partner in crime.

    <br><br>
    Thank you for all the laughs, the random conversations,
    the stupid jokes, the memories and even the arguments.
    Every little moment with you means more than you know.

    <br><br>
    I hope this new year of your life brings you happiness,
    success, peace, love and everything your heart wishes for.

    <br><br>
    Never stop being your chaotic, adorable and dramatic self.
    The world is lucky to have you, and I'm even luckier to have you.

    <br><br>
    Love you loads, boni. 💗

    <br><br>
    Forever your annoying best friend.
  </div>
</section>

<!-- GALLERY -->
<section>
  <h2>Our Little Memory Corner 📸</h2>
  <p>Upload your favourite pictures together!</p>
  <div class="grid gallery" id="gallery">
    <div class="card">
      <img src="https://placehold.co/400x300/ffe0ed/ed5796?text=Our+Memory+1" alt="Memory 1">
      <input type="file" accept="image/*" onchange="changePhoto(this)">
    </div>
    <div class="card">
      <img src="https://placehold.co/400x300/ffe0ed/ed5796?text=Our+Memory+2" alt="Memory 2">
      <input type="file" accept="image/*" onchange="changePhoto(this)">
    </div>
    <div class="card">
      <img src="https://placehold.co/400x300/ffe0ed/ed5796?text=Our+Memory+3" alt="Memory 3">
      <input type="file" accept="image/*" onchange="changePhoto(this)">
    </div>
  </div>
</section>

<!-- REASONS -->
<section>
  <h2>Reasons Why You're Special 🌸</h2>
  <div class="grid">
    <div class="card reason">💗 You make ordinary days special.</div>
    <div class="card reason">😂 You make me laugh like an idiot.</div>
    <div class="card reason">🫶 You're always there when I need you.</div>
    <div class="card reason">🌷 You have the sweetest heart.</div>
    <div class="card reason">✨ You're completely irreplaceable.</div>
    <div class="card reason">🎀 You're simply YOU. And that's enough.</div>
  </div>
</section>

<!-- ROAST -->
<section>
  <h2>A Very Serious Birthday Report 💀</h2>
  <div class="card" style="max-width:650px;margin:auto">
    <p>📋 OFFICIAL TIDDY REPORT</p>
    <br>
    <p>📏 Height: Still buffering...</p>
    <p>👑 Attitude: 7 feet tall</p>
    <p>🎭 Drama level: Unlimited</p>
    <p>🧠 Common sense: Sometimes unavailable</p>
    <p>💗 Cuteness: Unfortunately, maximum</p>
    <p>😂 Annoying level: Professional</p>
    <br>
    <h2 style="font-size:25px">Small package, unlimited drama. 😭</h2>
    <p>Don't worry, boni. I love you anyway. 💗</p>
  </div>
</section>

<!-- QUIZ -->
<section>
  <h2>Best Friend Test 🧠</h2>
  <div class="card" style="max-width:500px;margin:auto">
    <p><strong>Who is the most annoying person in this friendship?</strong></p>
    <button class="pink-btn" onclick="quizAnswer('Correct. Obviously you. 😭')">You</button>
    <button class="pink-btn" onclick="quizAnswer('Wrong. It's still you. 💀')">Me</button>
    <button class="pink-btn" onclick="quizAnswer('Nice try. Still you. 😂')">Both</button>
    <h3 id="quizResult" style="margin-top:20px"></h3>
  </div>
</section>

<!-- CAKE -->
<section>
  <h2>Make A Birthday Wish 🎂</h2>
  <p>Tap the cake to blow out the candles!</p>
  <div id="cake" onclick="cutCake()">🎂</div>
  <h3 id="cakeMessage">Make a wish, birthday girl! 💗</h3>
</section>

<!-- GIFT -->
<section>
  <h2>A Little Gift For You 🎁</h2>
  <p>There's something waiting inside...</p>
  <div id="gift" onclick="openGift()">🎁</div>
  <h3 id="giftMessage"></h3>
</section>

<!-- MINI GAME -->
<section>
  <h2>Catch The Hearts 💗</h2>
  <p>Catch 10 hearts in 30 seconds to become the official birthday champion!</p>
  <p>Score: <strong id="score">0</strong>/10</p>
  <p>Time: <strong id="timer">30</strong>s</p>
  <button class="pink-btn" onclick="startGame()">START GAME 🎮</button>
  <div id="gameArea"></div>
  <h3 id="gameResult"></h3>
</section>

<!-- SECRET MESSAGE -->
<section>
  <h2>A Secret Surprise 🔐</h2>
  <p>Only the birthday girl knows the password...</p>
  <input type="password" id="password" placeholder="Enter the secret password">
  <br>
  <button class="pink-btn" onclick="unlockSecret()">UNLOCK 💌</button>
  <div id="secretMessage">arrey boni happy birthday 💗🎀</div>
</section>

<!-- MUSIC -->
<section>
  <h2>Our Birthday Soundtrack 🎶</h2>
  <p>Choose a song from your device to play in the background.</p>
  <input type="file" id="musicFile" accept="audio/*">
  <br><br>
  <audio id="audio" controls loop></audio>
</section>

<!-- FINAL -->
<section>
  <h2>One Last Thing... 💗</h2>
  <div class="card" style="max-width:650px;margin:auto">
    <p>
      No matter how old you get, how much life changes,
      or how far apart we end up, you'll always have a special
      place in my heart.
    </p>
    <br>
    <h2 style="font-size:30px">HAPPY BIRTHDAY, TIDDY! 🎀</h2>
    <p>Stay happy. Stay crazy. Stay YOU. 💗</p>
    <button class="pink-btn" onclick="celebrate()">ONE MORE CELEBRATION 🎉</button>
  </div>
</section>

<footer>
  Made with endless love, for Tiddy. 💗
  <br>
  © Your favourite annoying human
</footer>

</main>

<button id="music" onclick="toggleMusic()">🎵 Music</button>
<button id="topBtn" onclick="window.scrollTo({top:0,behavior:'smooth'})">↑</button>

<script>
/* INTRO */
function enterSite() {
  document.getElementById("intro").style.display = "none";
  document.getElementById("main").style.display = "block";
  celebrate();
}

/* COUNTDOWN: Set the correct Nepali birthday year below.
   This example uses the Gregorian date 2026-12-08.
   Update it to the correct Gregorian birthday date/year. */
const birthday = new Date("2026-12-08T00:00:00");

function updateCountdown() {
  let now = new Date();
  let target = new Date(birthday);

  if (now > target) {
    target.setFullYear(target.getFullYear() + 1);
  }

  let diff = target - now;

  document.getElementById("days").textContent =
    Math.floor(diff / 86400000);
  document.getElementById("hours").textContent =
    Math.floor(diff / 3600000) % 24;
  document.getElementById("minutes").textContent =
    Math.floor(diff / 60000) % 60;
  document.getElementById("seconds").textContent =
    Math.floor(diff / 1000) % 60;
}

updateCountdown();
setInterval(updateCountdown,1000);

/* PHOTO UPLOAD */
function changePhoto(input) {
  if (input.files && input.files[0]) {
    input.previousElementSibling.src =
      URL.createObjectURL(input.files[0]);
  }
}

/* QUIZ */
function quizAnswer(message) {
  document.getElementById("quizResult").textContent = message;
}

/* CAKE */
let cakeClicked = false;

function cutCake() {
  if (!cakeClicked) {
    document.getElementById("cake").textContent = "🍰";
    document.getElementById("cakeMessage").textContent =
      "WISH GRANTED! May all your dreams come true! 💗";
    cakeClicked = true;
    celebrate();
  } else {
    document.getElementById("cakeMessage").textContent =
      "You already made your wish, greedy birthday girl! 😂";
  }
}

/* GIFT */
function openGift() {
  document.getElementById("gift").textContent = "💝";
  document.getElementById("giftMessage").textContent =
    "SURPRISE! Your gift is a lifetime supply of my friendship. No refunds. 😭💗";
  celebrate();
}

/* SECRET PASSWORD */
function unlockSecret() {
  let password = document.getElementById("password").value;

  if (password.toLowerCase() === "mangseer22") {
    document.getElementById("secretMessage").style.display = "block";
    celebrate();
  } else {
    alert("Wrong password, boni! Try again 😭");
  }
}

/* MINI GAME */
let score = 0;
let time = 30;
let gameInterval;
let heartInterval;
let gameRunning = false;

function startGame() {
  clearInterval(gameInterval);
  clearInterval(heartInterval);

  score = 0;
  time = 30;
  gameRunning = true;

  document.getElementById("score").textContent = score;
  document.getElementById("timer").textContent = time;
  document.getElementById("gameResult").textContent = "";
  document.getElementById("gameArea").innerHTML = "";

  heartInterval = setInterval(createHeart,700);

  gameInterval = setInterval(() => {
    time--;
    document.getElementById("timer").textContent = time;

    if (time <= 0 || score >= 10) {
      endGame();
    }
  },1000);
}

function createHeart() {
  if (!gameRunning) return;

  let area = document.getElementById("gameArea");
  let heart = document.createElement("div");

  heart.className = "heart";
  heart.textContent = "💗";

  heart.style.left = Math.random() * (area.clientWidth - 40) + "px";
  heart.style.top = Math.random() * (area.clientHeight - 40) + "px";

  heart.onclick = function() {
    if (!gameRunning) return;

    score++;
    document.getElementById("score").textContent = score;
    heart.remove();

    if (score >= 10) endGame();
  };

  area.appendChild(heart);

  setTimeout(() => {
    if (heart.parentNode) heart.remove();
  },1500);
}

function endGame() {
  if (!gameRunning) return;

  gameRunning = false;
  clearInterval(gameInterval);
  clearInterval(heartInterval);

  document.getElementById("gameArea").innerHTML = "";

  if (score >= 10) {
    document.getElementById("gameResult").textContent =
      "YOU WONNN! You're the birthday queen! 👑💗";
    celebrate();
  } else {
    document.getElementById("gameResult").textContent =
      "Time's up! You caught " + score + " hearts. Try again, boni! 😂";
  }
}

/* MUSIC UPLOAD */
document.getElementById("musicFile").addEventListener("change",function() {
  let file = this.files[0];

  if (file) {
    let audio = document.getElementById("audio");
    audio.src = URL.createObjectURL(file);
    audio.play();
  }
});

function toggleMusic() {
  let audio = document.getElementById("audio");

  if (!audio.src) {
    alert("Choose a song first! 🎶");
    return;
  }

  if (audio.paused) audio.play();
  else audio.pause();
}

/* FLOATING HEARTS */
function createFloatingHeart() {
  let heart = document.createElement("div");

  heart.className = "float";
  heart.textContent = ["💗","💕","🎀","✨","🌸"][Math.floor(Math.random()*5)];

  heart.style.left = Math.random()*100 + "vw";
  heart.style.bottom = "-30px";
  heart.style.fontSize = (15+Math.random()*25) + "px";

  document.body.appendChild(heart);

  setTimeout(() => heart.remove(),4000);
}

setInterval(createFloatingHeart,700);

/* CELEBRATION */
function celebrate() {
  for (let i=0;i<35;i++) {
    setTimeout(createFloatingHeart,i*35);
  }
}
</script>

</body>
</html>

