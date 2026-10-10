<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Things I Loved About You 💕</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Chewy&family=Fredoka:wght@400;500;600&display=swap" rel="stylesheet">
<style>
  :root {
    --pink: #ff8fb8;
    --peach: #ffc9a8;
    --butter: #fff3b0;
    --ink: #5a3a52;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body {
    font-family: 'Fredoka', 'Segoe UI', sans-serif;
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
    font-family: 'Chewy', cursive;
    font-weight: 400;
    font-size: clamp(2.4rem, 9vw, 4rem);
    line-height: 1.15;
    color: #ff5c97;
    text-shadow: 3px 3px 0 #fff, 5px 5px 0 var(--peach);
  }
  .sub { margin-top: 14px; font-size: 1.15rem; font-weight: 500; }
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
    font-weight: 400;
    line-height: 1.55;
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
  .card b { color: #ff5c97; font-weight: 600; }

  .finale {
    margin-top: 34px; text-align: center;
    background: var(--butter);
    border: 3px solid #fff;
    border-radius: 30px;
    padding: 26px 18px;
    box-shadow: 0 10px 0 rgba(255,201,168,.6);
  }
  .finale p { font-family: 'Chewy', cursive; font-size: 1.9rem; color: #ff5c97; line-height: 1.3; }
  .finale .sig { margin-top: 12px; font-family: 'Chewy', cursive; font-size: 1.6rem; color: var(--ink); }

  @media (max-width: 480px) {
    .card { padding: 16px 14px 16px 66px; font-size: 1.02rem; }
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
    <p class="sub">from our very first stay together ✨</p>
    <div class="sticker-row" aria-hidden="true">🌸🧸🍓🎀🌈</div>
  </header>

  <section>
    <div class="card"><span class="sticker">🤗</span>The second you saw me, you <b>scooped me up in your arms</b> like I weigh nothing. My heart did a little happy dance! 💃</div>

    <div class="card"><span class="sticker">🎬</span>Our <b>first movie night</b>! I love watching movies with you, snuggled up right next to you 🍿</div>

    <div class="card"><span class="sticker">🧸</span>Our first cuddles were the <b>BEST</b>. You're the comfiest cuddler ever, like my very own human teddy bear!</div>

    <div class="card"><span class="sticker">☕</span>You make the <b>best coffee</b>. Every cup tastes like a little hug in a mug 💞</div>

    <div class="card"><span class="sticker">😌</span>I thought you were short-tempered, but you're sooo <b>calm</b>, all the time! At that market you wanted to explore, my mom called, and you just said "okay, let's go home" with no fuss and no drama. You always make sure I'm <b>comfy</b> first 🥹</div>

    <div class="card"><span class="sticker">🚗</span>The whole way on our trip, in the back seat of the car, you kept <b>caressing and cuddling me</b>. I never wanted that ride to end 💕</div>

    <div class="card"><span class="sticker">😴</span>When I slept on your lap I loved it, and when you slept on mine I loved it too. Those were my favourite little naps!</div>

    <div class="card"><span class="sticker">👗</span>We <b>got ready together</b>, and it never felt like our firsts at all. It felt like we'd been doing it forever 🎀</div>

    <div class="card"><span class="sticker">👭</span>You <b>blended into my friends' circle</b> even when you didn't feel like it. You kept your ego aside and even said sorry once, even though it wasn't really your fault. So sweet! 🥺</div>

    <div class="card"><span class="sticker">📸</span>You capture me in my <b>most raw, real form</b>, and somehow I always look happiest in your photos.</div>

    <div class="card"><span class="sticker">🍕</span>You always make sure we eat the <b>yummiest food</b>. My tummy loves you too! 😋</div>

    <div class="card"><span class="sticker">🥰</span>You keep <b>adoring me</b> all the time, and I feel so loved every single day.</div>

    <div class="card"><span class="sticker">🫶</span>You're always <b>open to hugs</b>, and your hugs are my favourite place ever.</div>

    <div class="card"><span class="sticker">💋</span>And you give the <b>best kisses</b>. Muah! 😘</div>
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
