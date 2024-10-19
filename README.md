<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Round House Power Wash</title>
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            background: #1C1C1C;
            color: #FFD700;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
        }
        header {
            background-color: #000;
            color: #FFD700;
            padding: 40px;
            text-align: center;
            border-bottom: 5px solid #FFD700;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.6);
        }
        nav {
            padding: 20px;
            background-color: #333;
            color: #FFD700;
            text-align: center;
            border-bottom: 5px solid #FFD700;
        }
        nav a {
            color: #FFD700;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #FFF;
        }
        .container {
            max-width: 1200px;
            margin: auto;
            padding: 30px;
        }
        .hero {
            text-align: center;
            padding: 80px 20px;
            background: url('https://images.unsplash.com/photo-1516632664305-e673c5e7257b') center/cover no-repeat;
            color: #FFD700;
            border-radius: 15px;
            border: 5px solid #FFD700;
            position: relative;
            overflow: hidden;
        }
        .hero::before {
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.4);
        }
        .hero h2, .hero p {
            position: relative;
            z-index: 1;
            font-family: 'Montserrat', sans-serif;
        }
        .content-section {
            padding: 30px;
            background-color: #333;
            border-radius: 15px;
            border: 3px solid #FFD700;
            margin-bottom: 30px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.4);
        }
        footer {
            text-align: center;
            padding: 30px;
            background-color: #000;
            color: #FFD700;
            position: relative;
            border-top: 5px solid #FFD700;
            box-shadow: 0 -5px 15px rgba(0, 0, 0, 0.6);
        }
        .wet-effect {
            font-family: 'Dancing Script', cursive;
            text-shadow: 1px 1px 5px rgba(255, 223, 0, 0.5);
            letter-spacing: 1px;
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <h1 class="wet-effect" style="font-size: 4em;">Round House Power Wash</h1>
    </header>
    <nav>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
    <section class="hero">
        <h2 class="wet-effect">Servicing All of Connecticut</h2>
        <p class="wet-effect">Professional power washing services for residential and commercial properties. Let us help you keep your property clean and well-maintained.</p>
    </section>
    <div class="container">
        <section id="about" class="content-section">
            <h2>About Us</h2>
            <p>Round House Power Wash offers reliable and high-quality power washing services to both residential and commercial clients. We pride ourselves on delivering excellent results and ensuring customer satisfaction across Connecticut.</p>
        </section>
        <section id="services" class="content-section">
            <h2>Our Services</h2>
            <ul>
                <li>Residential Pressure Washing</li>
                <li>Commercial Pressure Washing</li>
                <li>Deck and Patio Cleaning</li>
                <li>Driveway and Sidewalk Cleaning</li>
            </ul>
        </section>
        <section id="contact" class="content-section">
            <h2>Contact Us</h2>
            <p>Reach out to us today for a free estimate or to schedule your service. We're here to help make your property shine!</p>
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
