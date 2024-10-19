<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Round House Power Wash</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: #333;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background: linear-gradient(to bottom, #ffffff, #cce7ff);
        }
        header {
            background-color: #004080;
            color: #fff;
            padding: 30px;
            text-align: center;
            font-size: 2.5em;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        header::after {
            content: " \1F4A7";
            position: absolute;
            right: 20px;
            top: 20px;
            font-size: 1.5em;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #003366;
            padding: 15px 0;
        }
        nav a {
            margin: 0 20px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #ffcc00;
        }
        .hero {
            background-color: #003366;
            color: #fff;
            padding: 80px 20px;
            text-align: center;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }
        .hero h2 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        .hero p::after {
            content: " \1F4A6";
        }
        .container {
            max-width: 900px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .content-section {
            margin-bottom: 40px;
        }
        h2 {
            color: #003366;
            font-size: 2em;
            border-bottom: 2px solid #004080;
            padding-bottom: 10px;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            background: #f0f8ff;
            margin: 10px 0;
            padding: 15px;
            border-left: 5px solid #004080;
            font-size: 1.2em;
            position: relative;
        }
        ul li::before {
            content: "\1F4A7";
            position: absolute;
            left: -30px;
            top: 15px;
            font-size: 1.5em;
        }
        #contact ul {
            padding-left: 20px;
        }
        footer {
            background-color: #004080;
            color: #fff;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.2);
            position: relative;
        }
        footer::after {
            content: "\1F4A6";
            position: absolute;
            right: 20px;
            bottom: 20px;
            font-size: 1.5em;
        }
        footer p {
            margin: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Round House Power Wash</h1>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2>Servicing All of Connecticut</h2>
        <p>Professional power washing services to keep your property clean and pristine.</p>
    </section>
    <div class="container">
        <section id="about" class="content-section">
            <h2>About Us</h2>
            <p>At Round House Power Wash, we are committed to providing reliable, high-quality power washing services for both residential and commercial properties throughout Connecticut. We take pride in our attention to detail and dedication to customer satisfaction.</p>
        </section>
        <section id="services" class="content-section">
            <h2>Our Services</h2>
            <ul>
                <li>Residential Pressure Washing</li>
                <li>Commercial Pressure Washing</li>
                <li>Deck & Patio Cleaning</li>
                <li>Driveway & Sidewalk Cleaning</li>
            </ul>
        </section>
        <section id="contact" class="content-section">
            <h2>Contact Us</h2>
            <p>Contact us today for a free estimate. We’re here to help make your property shine.</p>
            <ul>
                <li><strong>Phone:</strong> (860) 906-6883</li>
                <li><strong>Location:</strong> Bristol, CT 06010</li>
            </ul>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Round House Power Wash - All Rights Reserved</p>
        <p>Call us now: (860) 906-6883</p>
    </footer>
</body>
</html>
