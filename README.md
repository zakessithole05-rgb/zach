<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Queens Way Capital</title>
<style>
/* ===== COLORS ===== */
:root {
  --dark-green: #1a2f20;
  --gold: #b38e42;
  --blackish: #dfa94c;
  --orange-gold: #041716;
  --white: #ffffff;
  --light-bg: #f5f5f5;
}

/* ===== RESET ===== */
body {
  margin: 0;
  font-family: "Poppins", Arial, sans-serif;
  background-color: var(--white);
  color: #222;
  line-height: 1.6;
}

/* ===== HEADER ===== */
header{
  background:#0b1c15;
  border-bottom:1px solid rgba(255,255,255,.08);
}
.nav-inner{
  max-width:1200px;
  margin:0 auto;
  padding:14px 24px;
  display:flex;
  align-items:center;
  justify-content:space-between;
}
nav a{
  color:#fff;
  margin-left:20px;
  text-decoration:none;
  font-weight:600;
  transition:color 0.3s ease;
}
nav a:hover{
  color:#b38e42;
}
.brand{
  display:flex;
  align-items:center;
  gap:10px;
}
.brand img{
  height:46px;
}
.brand h1{
  font-size:22px;
  color:#b38e42;
  letter-spacing:0.5px;
}

/* ===== HERO SECTION ===== */
.hero {
  background-color: var(--dark-green);
  color: var(--white);
  text-align: center;
  padding: 120px 20px;
}

.hero h1 {
  font-size: 48px;
  margin-bottom: 10px;
}

.hero p {
  font-size: 20px;
  margin-bottom: 30px;
}

.hero button {
  background-color: var(--gold);
  color: var(--dark-green);
  border: none;
  padding: 12px 30px;
  font-size: 16px;
  border-radius: 30px;
  cursor: pointer;
}

.hero button:hover {
  background-color: var(--blackish);
  color: var(--white);
}

/* ===== SERVICES SECTION ===== */
.services {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 80px 60px;
  background-color: var(--white);
  flex-wrap: wrap;
}

.services img {
  width: 350px;
  border-radius: 10px;
  margin-right: 40px;
}

.services-text {
  max-width: 500px;
}

.services-text h2 {
  color: var(--gold);
  font-size: 26px;
  margin-bottom: 15px;
}

.services-text p {
  color: #333;
}

.services-text button {
  margin-top: 20px;
  background-color: var(--gold);
  color: var(--white);
  border: none;
  padding: 10px 25px;
  border-radius: 5px;
  cursor: pointer;
}

.services-text button:hover {
  background-color: var(--dark-green);
}

/* ===== TEAM SECTION ===== */
.team {
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: var(--dark-green);
  color: var(--white);
  padding: 80px 60px;
  flex-wrap: wrap;
}

.team img {
  width: 300px;
  border-radius: 10px;
  margin-left: 40px;
}

.team-text {
  max-width: 480px;
}

.team-text p {
 color: var(--white);
}

.team-text button {
  margin-top: 20px;
  background-color: var(--gold);
  color: var(--dark-green);
  border: none;
  padding: 10px 25px;
  border-radius: 5px;
  cursor: pointer;
}

.team-text button:hover {
  background-color: var(--blackish);
  color: var(--white);
}

/* ===== PARTNERS SECTION ===== */
.partners {
  text-align: center;
  padding: 60px 30px;
  background-color: var(--white);
}

.partners h2 {
  color: var(--gold);
  font-size: 26px;
  margin-bottom: 30px;
}

.partners-logos img {
  height: 50px;
  margin: 0 25px;
  vertical-align: middle;
}

/* ===== FOOTER ===== */
footer {
  background-color: var(--light-bg);
  text-align: center;
  padding: 30px;
  color: #555;
  font-size: 14px;
}

footer a {
  color: var(--dark-green);
  margin: 0 10px;
  text-decoration: none;
}

footer a img {
  width: 25px;
  vertical-align: middle;
}
</style>
</head>
<body>

<!-- HEADER -->
<header>
  <div class="nav-inner">
    <div class="brand">
      <img src="logo.png" alt="Logo">
      <h1>Queens Way Capital</h1>
    </div>
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="service.html">Services</a>
      <a href="contact.html">Contact</a>
    </nav>
  </div>
</header>

<!-- HERO -->
<section class="hero" id="home">
  <h1>Queens Way Capital</h1>
  <p>We are an AI and technology advisory helping organisations make smarter investments, scaling, and optimisation decisions. We support startups, investors, and enterprises in unlocking growth, managing risk, and delivering measurable outcomes through technology.
</p>
 
</section>

<!-- SERVICES -->
<section class="services" id="services">
  <img src="service1.jpeg" alt="Business Meeting">
  <div class="services-text">
    <h2>Our Services</h2>
    <p> Queens Way Capital offers a range of services to support medium and large enterprises in embracing automation and AI without the need for significant capital expenditure or resource commitment. Our team evaluates startup maturity and scalability using customised models, provides fractional leadership and strategic advisory roles, and develops compelling value propositions for larger customers. Additionally, we assist venture capitalists and funders in optimising ROI and reducing failure risk, while guiding technology companies in capital approaches, fundraising, use case development, and operational enhancement.
</p>
  <button onclick="window.location.href='service.html'">Discover More</button>

  </div>
</section>

<!-- TEAM -->
<section class="team" id="about">
  <div class="team-text">
    <p>
      Meet the skilled team at Queens Way Capital, comprising tech investors, experienced deal makers, and corporate specialists dedicated to driving business transformation through automation and AI adoption. Our professionals are committed to delivering impactful solutions and strategic guidance to propel your business forward.
    </p>
<button onclick="window.location.href='about.html#leadership'">Meet the Team</button>
	
  </div>
  <img src="team.jpg" alt="Team Meeting">
</section>

<!-- PARTNERS -->
<section class="partners" id="partners">
  <h2>Our Partners</h2>
  <div class="partners-logos">
    <img src="aicampus.png" alt="AI Campus">
    <img src="empire.png" alt="Empire Partner Foundation">
    <img src="epf.png" alt="EPF Tech Fund">
    <img src="orcaa.png" alt="Orcaa.ai">
  </div>
</section>

<!-- FOOTER -->
<footer>
  <p>© 2025 by Queens Way Capital</p>

  
</footer>

</body>
</html>
