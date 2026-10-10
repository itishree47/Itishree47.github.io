<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Things I Loved About You 💕</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Mali:wght@500;600;700&display=swap" rel="stylesheet">
<style>
  :root {
    --pink: #ff8fb8;
    --peach: #ffc9a8;
    --mint: #b5ead7;
    --lilac: #d4c1ff;
    --butter: #fff3b0;
    --ink: #5a3a52;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'Mali', 'Segoe UI', cursive, sans-serif;
    font-weight: 500;
    color: var(--ink);
    min-height: 100vh;
    background: linear-gradient(135deg, #ffe0ec, #ffe9d6, #e3f7ee, #ece3ff);
    background-size: 300% 300%;
    animation: drift 18s ease infinite;
    overflow-x: hidden;
  }
  @keyframes drift {
    0% { background-position: 0% 50%; }
    50% { background-position: 100% 50%; }
    100% { background-position: 0% 50%; }
  }
  .hearts { position: fixed; inset: 0; pointer-events: none; z-index: 0; overflow: hidden; }
  .heart {
    position: absolute; bottom: -40px;
    animation: rise linear forwards;
    opacity: .8;
  }
  @keyframes rise {
    to { transform: translateY(-115vh) rotate(25deg); opacity: 0; }
  }
  main {
    position: relative; z-index: 1;
    max-width: 720px; margin: 0 auto;
    padding: 48px 18px 70px;
  }
  header { text-align: center; margin-bottom: 36px; }
  h1 {
    font-family: 'Pacifico', cursive;
    font-weight: 400;
    font-size: clamp(2.2rem, 8vw, 3.6rem);
    line-height: 1.25;
    color: #ff5c97;
    text-shadow: 3px 3px 0 #fff, 5px 5px 0 var(--peach);
  }
  .sub { margin-top: 14px; font-size: 1.1rem; font-weight: 700; }
  .sticker-row { font-size: 2rem; margin-top: 12px; letter-spacing: 6px; }

  .card {
    position: relative;
    background: #fff;
    border: 3px dashed var(--pink);
    border-radius: 26px;
    padding: 20px 20px 20px 78px;
    margin-bottom: 20px;
    box-shadow: 0 8px 0 rgba(255, 143, 184, .25);
    font-size: 1.1rem;
    line-height: 1.65;
  }
  .card:nth-child(4n+2) { border-color: #7fd6b3; box-shadow: 0 8px 0 rgba(127,214,179,.3); transform: rotate(.6deg); }
  .card:nth-child(4n+3) { border-color: #b79cff; box-shadow: 0 8px 0 rgba(183,156,255,.3); transform: rotate(-.6deg); }
  .card:nth-child(4n+4) { border-color: #ffb27d; box-shadow: 0 8px 0 rgba(255,178,125,.3); }
  .card .sticker {
    position: absolute; left: 14px; top: 50%;
    transform: translateY(-50%) rotate(-8deg);
    font-size: 2.6rem;
    width: 52px; text-align: center;
  }
  .card b { color: #ff5c97; font-weight: 700; }

  .finale {
    margin-top: 34px; text-align: center;
    background: var(--butter);
    border: 3px solid #fff;
    border-radius: 30px;
    padding: 26px 18px;
    box-shadow: 0 10px 0 rgba(255,201,168,.6);
  }
  .finale p { font-family: 'Pacifico', cursive; font-size: 1.5rem; color: #ff5c97; line-height: 1.5; }
  .finale .sig { margin-top: 12px; font-family: 'Pacifico', cursive; font-size: 1.3rem; color: var(--ink); }

  @media (max-width: 480px) {
    .card { padding: 16px 14px 16px 66px; font-size: 1rem; }
    .card .sticker { font-size: 2.2rem; left: 10px; width: 46px; }
  }
  @media (prefers-reduced-motion: reduce) {
    body { animation: none; }
    .hearts { display: none; }
  }
</style>
</head>
<body>
<div class="hearts" id="hearts" aria-hidden="true"></div>

<main>
  <header>
    <h1>Things I Loved About You 💕</h1>
    <p class="sub">From our first stay together ✨</p>
    <div class="sticker-row" aria-hidden="true">🌸🧸🍓🎀🌈</div>
  </header>

  <section>
    <div class="card"><span class="sticker">🤗</span>The moment you saw me, you <b>lifted me in your arms</b>.</div>

    <div class="card"><span class="sticker">🎬</span>Our <b>first movie night</b>. I loved watching movies with you.</div>

    <div class="card"><span class="sticker">🧸</span>We had the <b>best first cuddles</b>. You are the best cuddler, and so comfy!</div>

    <div class="card"><span class="sticker">☕</span>You make the <b>best coffee</b>.</div>

    <div class="card"><span class="sticker">😌</span>I thought you were short-tempered, but you are so <b>calm</b>, all the time. At that market you wanted to explore, my mom called, and you just said "okay, let's go home" without making any fuss. Your main motive was always to make me <b>comfortable</b>.</div>

    <div class="card"><span class="sticker">🚗</span>All through the trip, in the back seat of the car, you kept <b>caressing and cuddling me</b>.</div>

    <div class="card"><span class="sticker">😴</span>I loved it when I slept on your lap, and I loved it when you slept on mine.</div>

    <div class="card"><span class="sticker">👗</span>We <b>got ready together</b>, and it never felt like our firsts at all.</div>

    <div class="card"><span class="sticker">👭</span>You <b>blended into my friends' circle</b> even when you didn't want to. You kept your ego aside, and you even said sorry once, even though it wasn't really your fault.</div>

    <div class="card"><span class="sticker">📸</span>You capture me in my <b>most raw form</b>.</div>

    <div class="card"><span class="sticker">🍕</span>You make sure we eat the <b>best food</b>.</div>

    <div class="card"><span class="sticker">🥰</span>You keep <b>adoring me</b> all the time.</div>

    <div class="card"><span class="sticker">🫶</span>You are always <b>open to hugs</b>.</div>

    <div class="card"><span class="sticker">💋</span>And you give the <b>best kisses</b>.</div>
  </section>

  <div class="finale">
    <p>Thank you for being you 💖</p>
    <div class="sig">Your cutu patootoo 🌷</div>
  </div>
</main>

<script>
  (function () {
    var box = document.getElementById('hearts');
    var icons = ['💗', '💖', '💕', '🌸', '✨', '💝'];
    function spawn() {
      var h = document.createElement('span');
      h.className = 'heart';
      h.textContent = icons[Math.floor(Math.random() * icons.length)];
      h.style.left = Math.random() * 100 + 'vw';
      h.style.fontSize = (14 + Math.random() * 22) + 'px';
      var dur = 7 + Math.random() * 7;
      h.style.animationDuration = dur + 's';
      box.appendChild(h);
      setTimeout(function () { h.remove(); }, dur * 1000);
    }
    setInterval(spawn, 700);
  })();
</script>
</body>
</html>
