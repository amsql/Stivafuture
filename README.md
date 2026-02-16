<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Friends Slider</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <div class="app">
    <header class="topbar">
      <h1>StivaFuture!</h1>

      <div class="controls">
        <button id="prevBtn">← Prev</button>
        <button id="nextBtn">Next →</button>
      </div>
    </header>

    <main class="slider">

      <!-- 1) DROP -->

      <section class="slide active" data-animation="drop">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/diddy.jpg" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Fau/Fauher31/Bartek</h2>

            <div class="info">
              <img class="big" src="photos/diddy blud.png" alt="Big">
              <p class="bio">
                He is the biggest pedo and the bigges digger i ever met. pronounse are YeaLookAtYou/1MMInsideHerAHH/YeaEmir/1FPS1FPSmHMhmHMmhmHM
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 2) SLIDE LEFT -->

      <section class="slide" data-animation="slide-left">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/Ziomek.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Zio/Jakub/Kuba/Ziomek/Pedo</h2>

            <div class="info">
              <img class="big" src="photos/zamy.png" alt="Big">
              <p class="bio">
                Told me to killmyself 1000 times on call for the first time 
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 3) ZOOM POP -->

      <section class="slide" data-animation="zoom">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/hawjddu.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Marvin/Hawk/BlackHawk</h2>

            <div class="info">
              <img class="big" src="photos/HAWK.png" alt="Big">
              <p class="bio">
                Pedo gay ass twink nigger fag his gender is unknown to the public is a specimine of sience. Too strong.
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 4) FLIP -->

      <section class="slide" data-animation="flip">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/arman.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Arman/Nany/EuGlacier/Balx.jr</h2>

            <div class="info">
              <img class="big" src="photos/armananny.png" alt="Big">
              <p class="bio">
                The BEST EU glacier OAT. Pedo, hates jypsies. Him and his family hate emir.
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 5) SWIPE UP -->

      <section class="slide" data-animation="swipe-up">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/diddy blud.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Emir/Edise/TheOneWhoSpeaksInHands</h2>

            <div class="info">
              <img class="big" src="photos/EMIR123123.png" alt="Big">
              <p class="bio">
                 "Started being argument i Never touchj grass while im playing the sports basketball every fucking day while YOU who is just playing THE VIDEOGAMES EVERYDAY
                 YOU FUCKING N LOOK AT YOU YOUR MOM IS SO SEXY AHH WHEN I PUT MY IN WHEN I PUT MY 1MM COCK INSIDE HER AHH".
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 6) GLITCH -->

      <section class="slide" data-animation="glitch">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/the guy with his teeth out.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Judah/Tito</h2>

            <div class="info">
              <img class="big" src="photos/judah.jpg" alt="Big">
              <p class="bio">
                Judah is the tito of the judah known to tito fought against emirs chromosomzes and won. "Would you lose?" "Nah I'd WIN"
              </p>
            </div>
          </div>
        </div>
      </section>

      <!-- 7) SPIN -->

      <section class="slide" data-animation="spin">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/kfc.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">KFC/TrentKFC/TrentLFC/Amsal</h2>

            <div class="info">
              <img class="big" src="photos/trhet.png" alt="Big">
              <p class="bio">
                Hardstuck Silver 1 valorant dinner master. Valorant is life for it, has the same name as me. But has to do valorant dinners with me daily.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="slide" data-animation="drop">
        <div class="card">
          <div class="pfp-wrap">
            <img class="pfp" src="photos/emireee.png" alt="PFP">
          </div>

          <div class="content">
            <h2 class="name">Bob</h2>

            <div class="info">
              <img class="big" src="photos/glticjh.png" alt="Big">
              <p class="bio">
                 Bob's Indentity Could not be revealed. He is to strong for his own good...
              </p>
            </div>
          </div>
        </div>
      </section>

    </main>
  </div>

   {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: system-ui, Arial, sans-serif;
}

body {
  background: #0b0d12;
  color: white;
  min-height: 100vh;
  overflow: hidden;
}

.app {
  height: 100vh;
  display: flex;
  flex-direction: column;
}

.topbar {
  padding: 18px 22px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.topbar h1 {
  font-size: 20px;
  opacity: 0.9;
}

.controls {
  display: flex;
  gap: 10px;
}

.controls button {
  background: #1c2330;
  color: white;
  border: 1px solid rgba(255,255,255,0.1);
  padding: 10px 14px;
  border-radius: 12px;
  cursor: pointer;
  transition: 0.2s;
}

.controls button:hover {
  transform: translateY(-2px);
  background: #273146;
}

.slider {
  flex: 1;
  position: relative;
}

.slide {
  position: absolute;
  inset: 0;
  display: grid;
  place-items: center;
  opacity: 0;
  pointer-events: none;
  transform: scale(0.98);
  transition: opacity 0.45s ease, transform 0.45s ease;
}

.slide.active {
  opacity: 1;
  pointer-events: auto;
  transform: scale(1);
}

.card {
  width: min(1000px, 92vw);
  background: rgba(255,255,255,0.04);
  border: 1px solid rgba(255,255,255,0.08);
  border-radius: 22px;
  padding: 26px;
  display: grid;
  grid-template-columns: 130px 1fr;
  gap: 24px;
  box-shadow: 0 20px 80px rgba(0,0,0,0.45);
  overflow: hidden;
}

/* PFP */
.pfp-wrap {
  width: 110px;
  height: 110px;
  border-radius: 24px;
  overflow: hidden;
  border: 1px solid rgba(255,255,255,0.12);
}

.pfp {
  width: 100%;
  height: 100%;
  object-fit: cover;
}

/* Content */
.name {
  font-size: 34px;
  margin-bottom: 14px;
}

.info {
  display: grid;
  grid-template-columns: 320px 1fr;
  gap: 20px;
  align-items: center;
}

.big {
  width: 100%;
  aspect-ratio: 1 / 1;
  object-fit: cover;
  border-radius: 18px;
  border: 1px solid rgba(255,255,255,0.12);
}

.bio {
  font-size: 17px;
  line-height: 1.55;
  opacity: 0.85;
}

/* Base hidden state */
.slide .pfp-wrap,
.slide .name,
.slide .big,
.slide .bio {
  opacity: 0;
}

/* -----------------------------
   1) DROP
-------------------------------- */
.slide.active[data-animation="drop"] .pfp-wrap {
  animation: dropPfp 0.7s cubic-bezier(.2,.9,.2,1) forwards;
}

.slide.active[data-animation="drop"] .name {
  animation: fadeUp 0.6s ease forwards;
  animation-delay: 0.15s;
}

.slide.active[data-animation="drop"] .big {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.25s;
}

.slide.active[data-animation="drop"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.35s;
}

/* -----------------------------
   2) SLIDE LEFT
-------------------------------- */
.slide.active[data-animation="slide-left"] .pfp-wrap {
  animation: slideInLeft 0.65s ease forwards;
}

.slide.active[data-animation="slide-left"] .name {
  animation: slideInLeft 0.7s ease forwards;
  animation-delay: 0.1s;
}

.slide.active[data-animation="slide-left"] .big {
  animation: slideInLeft 0.75s ease forwards;
  animation-delay: 0.2s;
}

.slide.active[data-animation="slide-left"] .bio {
  animation: slideInLeft 0.75s ease forwards;
  animation-delay: 0.3s;
}

/* -----------------------------
   3) ZOOM
-------------------------------- */
.slide.active[data-animation="zoom"] .pfp-wrap {
  animation: pop 0.55s ease forwards;
}

.slide.active[data-animation="zoom"] .name {
  animation: pop 0.6s ease forwards;
  animation-delay: 0.12s;
}

.slide.active[data-animation="zoom"] .big {
  animation: pop 0.65s ease forwards;
  animation-delay: 0.22s;
}

.slide.active[data-animation="zoom"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.32s;
}

/* -----------------------------
   4) FLIP
-------------------------------- */
.slide.active[data-animation="flip"] .pfp-wrap {
  animation: flipIn 0.7s ease forwards;
}

.slide.active[data-animation="flip"] .name {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.2s;
}

.slide.active[data-animation="flip"] .big {
  animation: flipIn 0.85s ease forwards;
  animation-delay: 0.25s;
}

.slide.active[data-animation="flip"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.35s;
}

/* -----------------------------
   5) SWIPE UP
-------------------------------- */
.slide.active[data-animation="swipe-up"] .pfp-wrap {
  animation: swipeUp 0.6s ease forwards;
}

.slide.active[data-animation="swipe-up"] .name {
  animation: swipeUp 0.7s ease forwards;
  animation-delay: 0.12s;
}

.slide.active[data-animation="swipe-up"] .big {
  animation: swipeUp 0.75s ease forwards;
  animation-delay: 0.22s;
}

.slide.active[data-animation="swipe-up"] .bio {
  animation: swipeUp 0.75s ease forwards;
  animation-delay: 0.32s;
}

/* -----------------------------
   6) GLITCH
-------------------------------- */
.slide.active[data-animation="glitch"] .pfp-wrap {
  animation: glitchIn 0.7s steps(2) forwards;
}

.slide.active[data-animation="glitch"] .name {
  animation: glitchIn 0.75s steps(2) forwards;
  animation-delay: 0.12s;
}

.slide.active[data-animation="glitch"] .big {
  animation: glitchIn 0.85s steps(2) forwards;
  animation-delay: 0.2s;
}

.slide.active[data-animation="glitch"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.35s;
}

/* -----------------------------
   7) SPIN
-------------------------------- */
.slide.active[data-animation="spin"] .pfp-wrap {
  animation: spinIn 0.7s ease forwards;
}

.slide.active[data-animation="spin"] .name {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.2s;
}

.slide.active[data-animation="spin"] .big {
  animation: spinIn 0.85s ease forwards;
  animation-delay: 0.25s;
}

.slide.active[data-animation="spin"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.35s;
}

/* -----------------------------
   1) DROP
-------------------------------- */
.slide.active[data-animation="drop"] .pfp-wrap {
  animation: dropPfp 0.7s cubic-bezier(.2,.9,.2,1) forwards;
}

.slide.active[data-animation="drop"] .name {
  animation: fadeUp 0.6s ease forwards;
  animation-delay: 0.15s;
}

.slide.active[data-animation="drop"] .big {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.25s;
}

.slide.active[data-animation="drop"] .bio {
  animation: fadeUp 0.7s ease forwards;
  animation-delay: 0.35s;
}


/* -----------------------------
   Keyframes
-------------------------------- */
@keyframes dropPfp {
  from { transform: translateY(-120px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}

@keyframes fadeUp {
  from { transform: translateY(20px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}

@keyframes slideInLeft {
  from { transform: translateX(-55px); opacity: 0; }
  to   { transform: translateX(0); opacity: 1; }
}

@keyframes pop {
  from { transform: scale(0.85); opacity: 0; }
  to   { transform: scale(1); opacity: 1; }
}

@keyframes flipIn {
  from { transform: rotateY(90deg); opacity: 0; }
  to   { transform: rotateY(0deg); opacity: 1; }
}

@keyframes swipeUp {
  from { transform: translateY(60px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}

@keyframes glitchIn {
  0%   { transform: translateX(-10px); opacity: 0; }
  25%  { transform: translateX(10px); opacity: 1; }
  50%  { transform: translateX(-6px); opacity: 1; }
  75%  { transform: translateX(6px); opacity: 1; }
  100% { transform: translateX(0); opacity: 1; }
}

@keyframes spinIn {
  from { transform: rotate(160deg) scale(0.4); opacity: 0; }
  to   { transform: rotate(0deg) scale(1); opacity: 1; }
}
@keyframes dropPfp {
  from { transform: translateY(-120px); opacity: 0; }
  to   { transform: translateY(0); opacity: 1; }
}


/* Responsive */
@media (max-width: 850px) {
  .card {
    grid-template-columns: 1fr;
  }

  .info {
    grid-template-columns: 1fr;
  }

  .pfp-wrap {
    width: 90px;
    height: 90px;
  }
}

const slides = document.querySelectorAll(".slide");
const prevBtn = document.getElementById("prevBtn");
const nextBtn = document.getElementById("nextBtn");

let currentIndex = 0;

function showSlide(newIndex) {
  // wrap around
  if (newIndex < 0) newIndex = slides.length - 1;
  if (newIndex >= slides.length) newIndex = 0;

  // remove active from current
  slides[currentIndex].classList.remove("active");

  // force animation reset by removing + re-adding active
  // (this makes your keyframes replay every time)
  slides[newIndex].classList.remove("active");
  void slides[newIndex].offsetWidth; // reflow trick
  slides[newIndex].classList.add("active");

  currentIndex = newIndex;
}

nextBtn.addEventListener("click", () => {
  showSlide(currentIndex + 1);
});

prevBtn.addEventListener("click", () => {
  showSlide(currentIndex - 1);
});

// Optional: keyboard support
document.addEventListener("keydown", (e) => {
  if (e.key === "ArrowRight") showSlide(currentIndex + 1);
  if (e.key === "ArrowLeft") showSlide(currentIndex - 1);
});

  <script src="script.js"></script>
</body>
</html>
