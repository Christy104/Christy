<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wood Collection</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f4f4f4;
    }

    header {
      background-color: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
      font-size: 24px;
      letter-spacing: 1px;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }

    .card {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      overflow: hidden;
      width: 300px;
      transition: transform 0.3s;
    }

    .card:hover {
      transform: scale(1.03);
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card .info {
      padding: 15px;
      text-align: center;
    }

    .card .info h3 {
      margin: 10px 0 5px;
      font-size: 20px;
      color: #333;
    }

    .card .info p {
      color: green;
      font-size: 18px;
      margin: 0;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #2c3e50;
      color: white;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>🌳 Premium Wood Collection & Prices</header>

  <div class="container">

    <!-- CARD START -->
    <div class="card">
      <img src="https://i.postimg.cc/Y9t4DzMN/teak-wood.jpg" alt="Teak Wood" />
      <div class="info">
        <h3>Teak Wood</h3>
        <p>₹3,500 per cft</p>
      </div>
    </div>
    <!-- CARD END -->

    <div class="card">
      <img src="https://i.postimg.cc/VLJkg49K/rosewood.jpg" alt="Rosewood" />
      <div class="info">
        <h3>Rosewood</h3>
        <p>₹4,200 per cft</p>
      </div>
    </div>

    <div class="card">
      <img src="https://i.postimg.cc/hPjgxRMm/mahogany.jpg" alt="Mahogany" />
      <div class="info">
        <h3>Mahogany</h3>
        <p>₹3,800 per cft</p>
      </div>
    </div>

    <div class="card">
      <img src="https://i.postimg.cc/NjpnTtBt/sandalwood.jpg" alt="Sandalwood" />
      <div class="info">
        <h3>Sandalwood</h3>
        <p>₹7,500 per cft</p>
      </div>
    </div>

  </div>

  <footer>
    © 2025 YourWoodStore.in | Prices are approximate and subject to market changes.
  </footer>

</body>
</html>
