# Tun-<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Oyun Sitesi</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: white;
    }

    header {
      background: #1e293b;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      color: #38bdf8;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #111827;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .container {
      max-width: 1000px;
      margin: 30px auto;
      padding: 20px;
    }

    .game-card {
      background: #1e293b;
      padding: 20px;
      margin: 15px 0;
      border-radius: 10px;
    }

    .btn {
      display: inline-block;
      padding: 10px 15px;
      background: #38bdf8;
      color: black;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #111827;
      margin-top: 40px;
    }
  </style>
</head>
<body>

<header>
  <h1>🎮 Oyun Sitesi</h1>
  <p>En iyi mini oyunlar burada!</p>
</header>

<nav>
  <a href="#">Ana Sayfa</a>
  <a href="#oyunlar">Oyunlar</a>
  <a href="#hakkinda">Hakkında</a>
</nav>

<div class="container">

  <h2 id="oyunlar">Popüler Oyunlar</h2>

  <div class="game-card">
    <h3>🎯 Hedef Vurma Oyunu</h3>
    <p>Hedefi vur ve puan kazan!</p>
    <a class="btn" href="#">Oyna</a>
  </div>

  <div class="game-card">
    <h3>🐍 Yılan Oyunu</h3>
    <p>Klasik yılan oyununu oyna.</p>
    <a class="btn" href="#">Oyna</a>
  </div>

  <div class="game-card">
    <h3>🏃 Kaçış Oyunu</h3>
    <p>Engellerden kaç ve hayatta kal!</p>
    <a class="btn" href="#">Oyna</a>
  </div>

  <h2 id="hakkinda">Hakkında</h2>
  <p>Bu site basit HTML ile yapılmış bir oyun sitesidir. İstersen gerçek oyunlar ekleyebiliriz.</p>

</div>

<footer>
  <p>© 2026 Oyun Sitesi</p>
</footer>

</body>
</html>
