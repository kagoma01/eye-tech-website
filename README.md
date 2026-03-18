
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Eye Tech Company</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
}

/* NAVBAR */
nav {
    background: #0A192F;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
}

nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
}

/* HERO */
.hero {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 80px;
    background: linear-gradient(to right, #0A192F, #00A86B);
    color: white;
}

.hero h1 {
    font-size: 40px;
}

.hero button {
    padding: 12px 20px;
    background: white;
    border: none;
    cursor: pointer;
}

/* SECTION */
.section {
    padding: 60px 40px;
    text-align: center;
}

/* SERVICES */
.services {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.card {
    background: white;
    padding: 20px;
    margin: 15px;
    width: 200px;
    border-radius: 10px;
    box-shadow: 0px 4px 10px rgba(0,0,0,0.1);
}

/* PROJECT */
.project {
    background: white;
    padding: 30px;
    border-radius: 10px;
}

/* CONTACT */
.contact input, .contact textarea {
    width: 80%;
    padding: 10px;
    margin: 10px 0;
}

.contact button {
    padding: 10px 20px;
    background: #00A86B;
    border: none;
    color: white;
}
</style>

</head>
<body>

<!-- NAVBAR -->
<nav>
    <div><b>Eye Tech</b></div>
    <div>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Projects</a>
        <a href="#">Contact</a>
    </div>
</nav>

<!-- HERO -->
<section class="hero">
    <div>
        <h1>Empowering Communities Through Smart Technology</h1>
        <p>AI, IoT & Digital Solutions for Agriculture and Innovation</p>
        <button>Get Started</button>
    </div>
    <div>
        <img src="https://via.placeholder.com/300" alt="tech image">
    </div>
</section>

<!-- ABOUT -->
<section class="section">
    <h2>About Us</h2>
    <p>
        Eye Tech Company is an innovative ICT and AI company focused on solving real-world challenges 
        through smart technologies in agriculture and digital transformation.
    </p>
</section>

<!-- SERVICES -->
<section class="section">
    <h2>Our Services</h2>
    <div class="services">
        <div class="card">🤖 AI Solutions</div>
        <div class="card">🌱 AgriTech</div>
        <div class="card">🌐 ICT Systems</div>
        <div class="card">🚁 Drone Technology</div>
    </div>
</section>

<!-- PROJECT -->
<section class="section">
    <h2>Our Projects</h2>
    <div class="project">
        <h3>Kilimo Sauti</h3>
        <p>AI-powered platform helping farmers monitor crops and detect diseases early.</p>
    </div>
</section>

<!-- IMPACT -->
<section class="section">
    <h2>Our Impact</h2>
    <p><b>100+ Farmers Supported | 5+ Projects | 3 Regions Covered</b></p>
</section>

<!-- CONTACT -->
<section class="section contact">
    <h2>Contact Us</h2>
    <input type="text" placeholder="Your Name"><br>
    <input type="email" placeholder="Your Email"><br>
    <textarea placeholder="Your Message"></textarea><br>
    <button>Send Message</button>
</section>

</body>
</html>

