<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Our Memories</title>
  <style>
    body {
      background: linear-gradient(135deg, #fce4ec, #f8bbd0);
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 20px;
    }
    
    h1 {
      color: #880e4f;
      margin-top: 20px;
      margin-bottom: 30px;
    }
    
    .button-group {
      display: flex;
      gap: 15px;
      margin-bottom: 30px;
    }
    
    button {
      background-color: #d81b60;
      color: white;
      border: none;
      padding: 15px 30px;
      border-radius: 25px;
      font-size: 1.1rem;
      cursor: pointer;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
      transition: background-color 0.2s, transform 0.1s;
    }
    
    button:hover {
      background-color: #880e4f;
      transform: translateY(-2px);
    }
    
    button:active {
      transform: translateY(0);
    }
    
    .content-section {
      background-color: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.05);
      max-width: 600px;
      width: 90%;
      display: none;
      animation: fadeIn 0.3s ease-in-out;
    }
    
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }
    
    .content-section.active {
      display: block;
    }
    
    h2 {
      color: #c2185b;
      margin-top: 0;
    }
    
    .address {
      font-style: italic;
      color: #718096;
      border-bottom: 1px solid #e2e8f0;
      padding-bottom: 10px;
      margin-bottom: 20px;
    }
    
    ul {
      padding-left: 20px;
      text-align: left;
    }
    
    li {
      margin-bottom: 10px;
      line-height: 1.4;
      color: #880e4f;
    }
  </style>
</head>
<body>

  <h1>Our Trip Memories</h1>

  <div class="button-group">
    <button onclick="showContent('airbnb')">Airbnb Stay</button>
    <button onclick="showContent('travel')">Travel Memories</button>
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
  </div>

  <div id="travel" class="content-section">
    <h2>Amritsar & Chandigarh</h2>
    <ul>
      <li>Memories from the rest of our trip will be added here soon.</li>
    </ul>
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

