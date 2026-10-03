# pikachu
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Maa Yashoda Convent School</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

header {
    background: #123c69;
    color: white;
    padding: 20px;
    text-align: center;
}

nav {
    background: #f4b942;
    padding: 15px;
    text-align: center;
}

nav a {
    color: #123c69;
    text-decoration: none;
    margin: 12px;
    font-weight: bold;
}

.hero {
    background: linear-gradient(120deg, #123c69, #247ba0);
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.hero h2 {
    font-size: 38px;
    margin-bottom: 15px;
}

.btn {
    display: inline-block;
    background: #f4b942;
    color: #123c69;
    padding: 12px 25px;
    margin-top: 20px;
    text-decoration: none;
    border-radius: 5px;
    font-weight: bold;
}

section {
    padding: 55px 20px;
    text-align: center;
}

section h2 {
    color: #123c69;
    margin-bottom: 20px;
}

.cards {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.card {
    background: #f2f6fa;
    padding: 25px;
    width: 250px;
    border-radius: 10px;
}

footer {
    background: #123c69;
    color: white;
    text-align: center;
    padding: 25px;
}

@media(max-width:600px) {
    nav a {
        display: inline-block;
        margin: 8px;
    }

    .hero h2 {
        font-size: 28px;
    }
}
</style>
</head>

<body>

<header>
    <h1>MAA YASHODA CONVENT SCHOOL</h1>
    <p>Inspiring Excellence, Rooted in Culture</p>
</header>

<nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#facilities">Facilities</a>
    <a href="#admission">Admission</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="home">
    <h2>Welcome to Maa Yashoda Convent School</h2>
    <p>Learn Today, Lead Tomorrow</p>
    <a href="#admission" class="btn">Admission Enquiry</a>
</div>

<section id="about">
    <h2>About Our School</h2>
    <p>
        We are committed to providing quality education,
        developing creativity, confidence and discipline
        among students.
    </p>
</section>

<section id="facilities">
    <h2>Our Facilities</h2>

    <div class="cards">
        <div class="card">
            <h3>📚 Smart Classes</h3>
            <p>Modern learning environment.</p>
        </div>

        <div class="card">
            <h3>💻 Computer Lab</h3>
            <p>Technology-based education.</p>
        </div>

        <div class="card">
            <h3>⚽ Sports</h3>
            <p>Physical fitness and activities.</p>
        </div>
    </div>
</section>

<section id="admission">
    <h2>Admission Open</h2>
    <p>Give your child a bright future with us.</p>
    <a href="tel:+919425863968" class="btn">
        Contact For Admission
    </a>
</section>

<section id="contact">
    <h2>Contact Us</h2>
    <p>Barotha, Dewas, Madhya Pradesh</p>
    <p>Phone: +91 94258 63968</p>
    <p>Email: maayashodaconvent@gmail.com</p>
</section>

<footer>
    <p>© 2026 Maa Yashoda Convent School</p>
    <p>All Rights Reserved</p>
</footer>

</body>
</html>
