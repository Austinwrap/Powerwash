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
            background: linear-gradient(to bottom, #cce7ff, #99ccff);
            overflow-x: hidden;
        }
        header {
            background-color: #003366;
            color: #fff;
            padding: 50px;
            text-align: center;
            font-size: 3em;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
            position: relative;
            border-bottom: 5px solid #99ccff;
            border-radius: 0 0 50px 50px;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #002244;
            padding: 20px 0;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.3);
        }
        nav a {
            margin: 0 25px;
            text-decoration: none;
            color: #fff;
            font-weight: bold;
            transition: all 0.3s ease;
            padding: 10px 15px;
            border-radius: 10px;
        }
        nav a:hover {
            color: #99ccff;
            background-color: #004080;
            transform: scale(1.1);
        }
        .hero {
            background: linear-gradient(to bottom, #004080, #003366);
            color: #fff;
            padding: 100px 20px;
            text-align: center;
            text-shadow: 2px 2px 10px rgba(0, 0, 0, 0.7);
            position: relative;
            border-radius: 0 0 100px 100px;
            box-shadow: inset 0 -5px 15px rgba(0, 0, 0, 0.5);
            overflow: hidden;
        }
        .hero::after {
            content: "";
            position: absolute;
            bottom: -20px;
            left: 0;
            right: 0;
            height: 20px;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0) 70%);
            filter: blur(8px);
        }
        .hero .drips {
            position: absolute;
            top: 100%;
            left: 50%;
            width: 200%;
            height: 100px;
            background: repeating-linear-gradient(
                to bottom,
                transparent,
                transparent 5px,
                rgba(255, 255, 255, 0.3) 5px,
                rgba(255, 255, 255, 0.3) 10px
            );
            transform: translateX(-50%) skewY(5deg);
        }
        .container {
            max-width: 900px;
            margin: 40px auto;
            padding: 30px;
            background-color: #f9f9f9;
            border-radius: 20px;
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.2);
            border: 5px solid #99ccff;
            position: relative;
        }
        .container::before {
            content: "";
            position: absolute;
            top: -20px;
            left: 0;
            right: 0;
            height: 20px;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0) 70%);
            filter: blur(8px);
        }
        .content-section {
            margin-bottom: 50px;
        }
        h2 {
            color: #003366;
            font-size: 2.5em;
            border-bottom: 3px solid #004080;
            padding-bottom: 10px;
            border-radius: 0 0 15px 15px;
            position: relative;
        }
        h2::after {
            content: "";
            position: absolute;
            left: 0;
            bottom: -5px;
            width: 100%;
            height: 5px;
            background: linear-gradient(to right, #99ccff, #003366);
            filter: blur(3px);
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        ul li {
            background: #e0f3ff;
            margin: 15px 0;
            padding: 20px;
            border-radius: 15px;
            border: 3px solid #004080;
            font-size: 1.3em;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
            position: relative;
        }
        ul li::before {
            content: "";
            position: absolute;
            top: -10px;
            left: 50%;
            width: 20px;
            height: 20px;
            background: radial-gradient(circle, #99ccff, transparent);
            border-radius: 50%;
            transform: translateX(-50%);
            filter: blur(5px);
        }
        #contact ul {
            padding-left: 20px;
        }
        footer {
            background-color: #003366;
            color: #fff;
            text-align: center;
            padding: 30px;
            margin-top: 40px;
            box-shadow: 0 -8px 15px rgba(0, 0, 0, 0.3);
            border-radius: 50px 50px 0 0;
            border-top: 5px solid #99ccff;
            position: relative;
        }
        footer::before {
            content: "";
            position: absolute;
            top: -20px;
            left: 0;
            right: 0;
            height: 20px;
            background: radial-gradient(circle, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0) 70%);
            filter: blur(8px);
        }
        footer p {
            margin: 10px;
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
        <div class="drips"></div>
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
