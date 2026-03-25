<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Casa Oro Del Toro Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600;700&family=Poppins:wght@300;400;500&display=swap" rel="stylesheet">

<style>

body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: #0B0B0B;
  color: #F5F5F5;
}

/* NAV */
nav {
  display: flex;
  justify-content: space-between;
  padding: 20px 50px;
  position: absolute;
  width: 100%;
  z-index: 10;
}

.logo {
  font-family: 'Cinzel', serif;
  color: #D4AF37;
  font-size: 22px;
  letter-spacing: 2px;
}

.nav-sub {
  font-size: 12px;
  color: #D4AF37;
}

/* HERO */
.hero {
  height: 100vh;
  display: flex;
  align-items: center;
  padding: 0 50px;
  background: linear-gradient(rgba(0,0,0,0.75), rgba(0,0,0,0.95)),
  url('https://images.unsplash.com/photo-1600891964599-f61ba0e24092');
  background-size: cover;
  background-position: center;
}

.hero-content {
  max-width: 700px;
}

.hero h1 {
  font-family: 'Cinzel', serif;
  font-size: 70px;
  color: #D4AF37;
  margin: 0;
  text-shadow: 0 0 25px rgba(212,175,55,0.5);
}

.hero p {
  font-size: 20px;
  margin: 20px 0;
  line-height: 1.6;
}

.hero button {
  background: #D4AF37;
  color: #0B0B0B;
  border: none;
  padding: 14px 30px;
  font-weight: bold;
  cursor: pointer;
}

.hero button:hover {
  background: #b8962e;
}

/* STRIP */
.strip {
  background: #8B0000;
  text-align: center;
  padding: 18px;
  font-weight: bold;
}

/* SECTIONS */
section {
  padding: 80px 50px;
  max-width: 1200px;
  margin: auto;
}

h2 {
  font-family: 'Cinzel', serif;
  color: #D4AF37;
  font-size: 32px;
  margin-bottom: 30px;
}

/* MENU */
.menu-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
  gap: 25px;
}

.menu-item {
  background: rgba(255,255,255,0.03);
  border: 1px solid rgba(212,175,55,0.2);
  padding: 25px;
  border-radius: 8px;
  transition: 0.3s;
}

.menu-item:hover {
  transform: translateY(-5px);
  border-color: #D4AF37;
}

/* EVENTS */
.event {
  margin-bottom: 12px;
  font-size: 18px;
}

/* FOOTER */
footer {
  text-align: center;
  padding: 40px;
  border-top: 1px solid rgba(212,175,55,0.2);
  font-size: 14px;
}

</style>
</head>

<body>

<nav>
  <div>
    <div class="logo">CASA ORO DEL TORO</div>
    <div class="nav-sub">Zacatecas, México</div>
  </div>
</nav>

<div class="hero">
  <div class="hero-content">
    <h1>Casa Oro Del Toro</h1>
    <p>De Nuestra Tierra Nace El Sabor, Donde El Toro Define El Sabor</p>
    <button>View Menu</button>
  </div>
</div>

<div class="strip">
  Zacatecas, México • De Nuestra Tierra Nace El Sabor
</div>

<section>
  <h2>About</h2>
  <p>
    Casa Oro Del Toro brings the authentic flavors of Zacatecas to life with slow-cooked birria,
    fire-grilled meats, and a bold cantina experience rooted in tradition.
  </p>
</section>

<section>
  <h2>Menu</h2>
  <div class="menu-grid">
    <div class="menu-item">QuesaBirrias</div>
    <div class="menu-item">Birria Pizza</div>
    <div class="menu-item">Hot Cheeto Birria Balls</div>
    <div class="menu-item">Handmade Tortillas</div>
    <div class="menu-item">Street Tacos (Steak, Pork, Chicken, Birria)</div>
    <div class="menu-item">Burritos</div>
    <div class="menu-item">Quesadillas</div>
  </div>
</section>

<section>
  <h2>Events</h2>
  <div class="event">🎺 Banda Night Fridays</div>
  <div class="event">🌙 Velada Ambiental Wednesdays</div>
</section>

<footer>
  <p>Casa Oro Del Toro Restaurant</p>
  <p>Zacatecas, México</p>
</footer>

</body>
</html>
