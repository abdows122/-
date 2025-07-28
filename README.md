<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>𝐑𝐚𝐝 𝐅𝐢𝐯𝐞 ᶜᶠʷ | المتجر</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #111;
      color: white;
    }
    header {
      background-color: #000;
      padding: 15px 30px;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }
    header img {
      height: 60px;
    }
    nav {
      display: flex;
      gap: 25px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      color: #f97316; /* Orange */
    }
    .hero {
      background: url('https://i.imgur.com/ojgTxqB.png') center/cover no-repeat;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      color: white;
      background: rgba(0, 0, 0, 0.6);
      padding: 20px;
      border-radius: 15px;
    }
    .section {
      padding: 40px 20px;
      text-align: center;
    }
    .section h2 {
      font-size: 32px;
      color: #f97316;
      margin-bottom: 30px;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      max-width: 1000px;
      margin: 0 auto;
    }
    .card {
      background-color: #1c1c1c;
      padding: 20px;
      border-radius: 15px;
      transition: 0.3s;
    }
    .card:hover {
      background-color: #2a2a2a;
    }
    .card h3 {
      margin: 10px 0;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/Reblact_2.png" alt="Rad Five Logo">
    <nav>
      <a href="#cars">السيارات</a>
      <a href="#ranks">الرتب</a>
      <a href="#characters">الشخصيات</a>
      <a href="#vip">VIP</a>
    </nav>
  </header>

  <div class="hero">
    <h1>مرحباً بك في 𝐑𝐚𝐝 𝐅𝐢𝐯𝐞 ᶜᶠʷ</h1>
  </div>

  <section class="section" id="cars">
    <h2>السيارات</h2>
    <div class="cards">
      <div class="card"><h3>سيارة 1</h3></div>
      <div class="card"><h3>سيارة 2</h3></div>
      <div class="card"><h3>سيارة 3</h3></div>
    </div>
  </section>

  <section class="section" id="ranks">
    <h2>الرتب</h2>
    <div class="cards">
      <div class="card"><h3>رتبة 1</h3></div>
      <div class="card"><h3>رتبة 2</h3></div>
      <div class="card"><h3>رتبة 3</h3></div>
    </div>
  </section>

  <section class="section" id="characters">
    <h2>الشخصيات</h2>
    <div class="cards">
      <div class="card"><h3>شخصية 1</h3></div>
      <div class="card"><h3>شخصية 2</h3></div>
      <div class="card"><h3>شخصية 3</h3></div>
    </div>
  </section>

  <section class="section" id="vip">
    <h2>VIP</h2>
    <div class="cards">
      <div class="card"><h3>باقة VIP 1</h3></div>
      <div class="card"><h3>باقة VIP 2</h3></div>
    </div>
  </section>
</body>
</html>
