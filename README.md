
moving forward

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SIZOVA HOLDINGS PRIVATE LIMITED</title>

<style>
:root {
    --blue: #123e91;
    --purple: #6b32b6;
    --light: #f5f7fc;
    --dark: #101b35;
    --white: #ffffff;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body {
    color: var(--dark);
    background: var(--white);
    line-height: 1.6;
}

html {
    scroll-behavior: smooth;
}

header {
    background: white;
    padding: 18px 7%;
    display: flex;
    align-items: center;
    justify-content: space-between;
    position: sticky;
    top: 0;
    z-index: 1000;
    box-shadow: 0 2px 12px rgba(0,0,0,0.08);
}

.logo {
    font-size: 27px;
    font-weight: 900;
    letter-spacing: 2px;
    color: var(--blue);
}

.logo span {
    color: var(--purple);
}

.logo small {
    display: block;
    font-size: 10px;
    letter-spacing: 4px;
    color: #555;
}

nav a {
    text-decoration: none;
    color: #222;
    margin-left: 25px;
    font-size: 14px;
    font-weight: bold;
}

nav a:hover {
    color: var(--purple);
}

.hero {
    min-height: 600px;
    padding: 90px 8%;
    display: flex;
    align-items: center;
    color: white;
    background:
      linear-gradient(115deg, rgba(12,40,104,.95), rgba(94,36,158,.82)),
      url("https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?auto=format&fit=crop&w=1800&q=85");
    background-size: cover;
    background-position: center;
}

.hero-content {
    max-width: 780px;
}

.hero h1 {
    font-size: clamp(40px, 6vw, 72px);
    line-height: 1.1;
    margin-bottom: 25px;
    font-weight: 900;
}

.hero h1 span {
    color: #c8b5ff;
}

.hero p {
    font-size: 19px;
    max-width: 650px;
    margin-bottom: 35px;
    color: #f0f2ff;
}

.btn {
    display: inline-block;
    background: white;
    color: var(--blue);
    padding: 14px 27px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    margin-right: 12px;
    transition: 0.3s;
}

.btn:hover {
    background: #dcd1ff;
    transform: translateY(-3px);
}

.btn-purple {
    background: var(--purple);
    color: white;
}

section {
    padding: 85px 8%;
}

.section-title {
    text-align: center;
    margin-bottom: 50px;
}

.section-title h2 {
    font-size: 36px;
    font-weight: 900;
    color: var(--blue);
}

.section-title p {
    color: #777;
    margin-top: 10px;
}

.about {
    background: var(--light);
}

.about-content {
    max-width: 900px;
    margin: auto;
    text-align: center;
}

.about-content h3 {
    font-size: 27px;
    margin-bottom: 20px;
}

.about-content p {
    color: #555;
    margin-bottom: 15px;
}

.business-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.business-card {
    background: white;
    padding: 32px 26px;
    border-radius: 12px;
    border: 1px solid #e8eaf2;
    box-shadow: 0 8px 25px rgba(15, 40, 90, 0.06);
    transition: 0.3s;
}

.business-card:hover {
    transform: translateY(-8px);
    border-color: var(--purple);
    box-shadow: 0 12px 30px rgba(107,50,182,0.15);
}

.business-icon {
    width: 55px;
    height: 55px;
    border-radius: 12px;
    background: linear-gradient(135deg, var(--blue), var(--purple));
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 25px;
    margin-bottom: 22px;
}

.business-card h3 {
    color: var(--blue);
    font-size: 19px;
    margin-bottom: 12px;
}

.business-card p {
    font-size: 14px;
    color: #666;
}

.business-card a {
    display: inline-block;
    margin-top: 18px;
    text-decoration: none;
    color: var(--purple);
    font-size: 13px;
    font-weight: bold;
}

.stats {
    background: linear-gradient(110deg, var(--blue), var(--purple));
    color: white;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    text-align: center;
    gap: 25px;
}

.stat h3 {
    font-size: 32px;
    font-weight: 900;
}

.stat p {
    font-size: 14px;
    color: #e0ddff;
}

.contact {
    background: var(--light);
}

.contact-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 40px;
}

.contact-info {
    background: white;
    padding: 35px;
    border-radius: 12px;
}

.contact-info h3 {
    color: var(--blue);
    margin-bottom: 20px;
}

.contact-info p {
    margin-bottom: 15px;
    color: #555;
}

.contact-info a {
    color: var(--purple);
    text-decoration: none;
}

.contact-box {
    background: linear-gradient(140deg, var(--blue), var(--purple));
    color: white;
    padding: 40px;
    border-radius: 12px;
}

.contact-box h3 {
    font-size: 27px;
    margin-bottom: 15px;
}

.contact-box p {
    margin-bottom: 25px;
}

footer {
    background: #101a34;
    color: white;
    padding: 40px 8%;
    text-align: center;
}

footer .footer-logo {
    font-size: 25px;
    font-weight: 900;
    letter-spacing: 2px;
}

footer .footer-logo span {
    color: #a985ff;
}

footer p {
    color: #bbb;
    font-size: 13px;
    margin-top: 12px;
}

.footer-links {
    margin: 20px 0;
}

.footer-links a {
    color: #ddd;
    text-decoration: none;
    margin: 0 12px;
    font-size: 13px;
}

.whatsapp {
    position: fixed;
    bottom: 22px;
    right: 22px;
    background: #25D366;
    color: white;
    padding: 15px 20px;
    border-radius: 50px;
    text-decoration: none;
    font-weight: bold;
    box-shadow: 0 5px 20px rgba(0,0,0,.2);
    z-index: 999;
}

@media (max-width: 900px) {
    .business-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    nav a {
        margin-left: 12px;
    }
}

@media (max-width: 600px) {
    header {
        flex-direction: column;
        gap: 15px;
    }

    nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 12px;
    }

    nav a {
        margin: 0;
        font-size: 12px;
    }

    .hero {
        min-height: 500px;
        padding: 70px 7%;
    }

    .hero p {
        font-size: 16px;
    }

    section {
        padding: 60px 6%;
    }

    .business-grid,
    .contact-grid,
    .stats {
        grid-template-columns: 1fr;
    }

    .section-title h2 {
        font-size: 29px;
    }

    .btn {
        margin-bottom: 12px;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">
        SIZOVA <span>HOLDINGS</span>
        <small>PRIVATE LIMITED</small>
    </div>


</header>

<!-- HERO SECTION -->
<section class="hero" id="home">
    <div class="hero-content">
        <h1>BUILDING<br>
        <span>OPPORTUNITIES.</span><br>
        CREATING THE FUTURE.</h1>

  
</section>

<!-- ABOUT SECTION -->
<section class="about" id="about">
    <div class="section-title">
        <h2>ABOUT SIZOVA</h2>
        <p>A diversified business group from the Maldives</p>
    </div>


            
</section>

<!-- BUSINESS DIVISIONS -->
<section id="business">
    <div class="section-title">
        <h2>OUR BUSINESSES</h2>
        <p>Explore our group companies and business divisions</p>
    </div>

  
</section>

<!-- GROUP STATS -->
<section class="stats">
    <div class="stat">
        <h3>07</h3>
        <p>Business Divisions</p>
    </div>

 
</section>

<!-- CONTACT -->
<section class="contact" id="contact">
    <div class="section-title">
        <h2>CONTACT US</h2>
        <p>Let's build business opportunities together</p>
    </div>


</section>

<!-- FOOTER -->
<footer>
    <div class="footer-logo">SIZOVA <span>HOLDINGS</span></div>

    </p>
</footer>

<a class="whatsapp" href="https://wa.me/9607444146" target="_blank">
    WhatsApp
</a>

<script>
document.getElementById("year").textContent = new Date().getFullYear();
</script>
