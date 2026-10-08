<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our First Memories ✨</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Quicksand:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(135deg, #ff9ff3, #feca57, #5f27cd, #ff6b6b);
      background-size: 300% 300%;
      animation: colorShift 15s ease infinite;
      font-family: 'Quicksand', sans-serif;
      margin: 0;
      color: #3d3d3d;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    
    @keyframes colorShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    .container {
      background-color: rgba(255, 255, 255, 0.95);
      padding: 40px;
      border-radius: 30px;
      box-shadow: 0 15px 35px rgba(0,0,0,0.2);
      max-width: 600px;
      width: 90%;
      text-align: center;
      position: relative;
    }

    h1 {
      font-family: 'Fredoka One', cursive;
      color: #ff6b81;
      margin-top: 0;
      margin-bottom: 20px;
      font-size: 2.5rem;
    }

    .subtitle {
      font-family: 'Fredoka One', cursive;
      color: #54a0ff;
      margin-bottom: 30px;
      font-size: 1.3rem;
    }

    ul {
      padding-left: 0;
      list-style: none;
      text-align: left;
    }
    
    li {
      background-color: #f1f2f6;
      margin-bottom: 15px;
      padding: 15px 20px;
      border-radius: 15px;
      line-height: 1.4;
      font-weight: 600;
      color: #57606f;
      display: flex;
      align-items: center;
      transition: transform 0.2s, background-color 0.2s;
    }

    li:hover {
      transform: scale(1.02);
      background-color: #ffeaa7;
    }

    .icon {
      margin-right: 15px;
      font-size: 1.5rem;
    }

    .sticker-grid {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
      font-size: 2.5rem;
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Our First Trip & Stay 💖</h1>
    <p class="subtitle">All the little things I love about you...</p>

    <ul>
      <li><span class="icon">🥰</span>The moment we met, you lifted me in your arms.</li>
      <li><span class="icon">🍰</span>Sharing sweet cheesecake and delicious coffee.</li>
      <li><span class="icon">🎬</span>Introducing me to the movie "Yeh Dooriyan."</li>
      <li><span class="icon">🍜</span>Late-night Maggie and cuddling together for the first time.</li>
      <li><span class="icon">🧘‍♀️</span>Being so calm and understanding when my mom called suddenly.</li>
      <li><span class="icon">🤝</span>Managing the group's mess and reassuring me.</li>
      <li><span class="icon">🌟</span>Blending in so perfectly with my friends.</li>
    </ul>

    <div class="sticker-grid">
      <span>💛</span><span>✈️</span><span>🍕</span><span>💙</span><span>✨</span>
    </div>
  </div>

</body>
</html>
