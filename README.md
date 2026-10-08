<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Memories</title>
  <link href="https://fonts.googleapis.com/css2?family=Fredoka+One&family=Quicksand:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(135deg, #ffe066, #70a1ff, #ff7979);
      background-size: 200% 200%;
      animation: gradientShift 10s ease infinite;
      font-family: 'Quicksand', sans-serif;
      margin: 0;
      color: #3d3d3d;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }
    
    h1 {
      font-family: 'Fredoka One', cursive;
      color: #ffffff;
      margin-top: 20px;
      margin-bottom: 30px;
      text-shadow: 2px 4px 6px rgba(0,0,0,0.2);
    }
    
    .button-group {
      display: flex;
      gap: 15px;
      margin-bottom: 30px;
    }
    
    button {
      background-color: #ffffff;
      color: #ff4757;
      border: none;
      padding: 15px 30px;
      border-radius: 25px;
      font-size: 1.1rem;
      font-family: 'Fredoka One', cursive;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0,0,0,0.15);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    
    button:hover {
      transform: translateY(-4px) scale(1.05);
      box-shadow: 0 6px 15px rgba(0,0,0,0.2);
    }
    
    .content-section {
      background-color: rgba(255, 255, 255, 0.95);
      padding: 30px;
      border-radius: 25px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.1);
      max-width: 500px;
      width: 90%;
      display: none;
      animation: fadeIn 0.4s ease-in-out;
      text-align: center;
      position: relative;
    }
    
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px) scale(0.95); }
      to { opacity: 1; transform: translateY(0) scale(1); }
    }
    
    .content-section.active {
      display: block;
    }
    
    h2 {
      font-family: 'Fredoka One', cursive;
      color: #ff6b81;
      margin-top: 0;
    }
    
    .address {
      font-style: italic;
      color: #70a1ff;
      border-bottom: 2px dashed #ffeaa7;
      padding-bottom: 10px;
      margin-bottom: 20px;
      font-weight: bold;
      font-family: 'Fredoka One', cursive;
    }
    
    ul {
      padding-left: 25px;
      text-align: left;
    }
    
    li {
      margin-bottom: 15px;
      line-height: 1.4;
      list-style-type: "💖 ";
      font-weight: 600;
      color: #57606f;
    }

    .sticker {
      font-size: 2rem;
      margin-top: 15px;
    }
  </style>
</head>
<body>

  <h1>Our Trip Memories 🌟</h1>

  <div class="button-group">
    <button onclick="showContent('airbnb')">M 9/8</button>
    <button onclick="showContent('travel')">First Trip Together</button>
  </div>

  <div id="airbnb" class="content-section active">
    <h2>Our Airbnb Memories</h2>
    <p class="address">Address: M 9/8</p>
    <ul>
      <li>You lifted me in your arms the moment we met.</li>
      <li>We shared sweet cheesecake and good coffee.</li>
      <li>You introduced me to the movie "Yeh Dooriyan."</li>
      <li>Late-night Maggie and cuddling together for the first time.</li>
      <li>You were so calm when my mom called suddenly.</li>
      <li>You managed our group's mess and reassured me.</li>
    </ul>
    <div class="sticker">🍰☕✨</div>
  </div>

  <div id="travel" class="content-section">
    <h2>Amritsar & Chandigarh</h2>
    <ul>
      <li>Memories from the rest of our trip will be added here soon.</li>
    </ul>
    <div class="sticker">📸 Amritsar & Chandigarh ✈️</div>
  </div>

  <script>
    function showContent(sectionId) {
      document.querySelectorAll('.content-section').forEach(section => {
        section.classList.remove('active');
      });
      document.getElementById(sectionId).classList.add('active');
    }
  </script>

</body>
</html>
