<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ROUNDHOUSE Powerwash LLC</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Russo+One&family=Roboto:wght@400;700&display=swap');
        body {
            font-family: 'Roboto', sans-serif;
            color: #B8860B;
            margin: 0;
            padding: 0;
            background: #191970 url('https://www.transparenttextures.com/patterns/dark-mosaic.png');
            line-height: 1.4;
            font-size: 14px;
        }
        header {
            background: #191970;
            text-align: center;
            padding: 50px 20px;
            border-bottom: 8px solid #DC143C;
            position: relative;
            box-shadow: 0 0 20px rgba(220, 20, 60, 0.5);
        }
        h1 {
            font-family: 'Russo One', sans-serif;
            margin: 0;
            text-shadow: 4px 4px 0 #DC143C, 3px 3px 0 #B8860B, -2px -2px 0 #fff;
        }
        h1 span.roundhouse {
            font-size: 5em;
            color: #B8860B;
        }
        h1 span.powerwash {
            font-size: 2.5em;
            color: #DC143C;
        }
        .swoosh {
            position: absolute;
            top: 15px;
            right: 20px;
            font-family: 'Russo One', sans-serif;
            font-size: 2em;
            color: #fff;
            transform: rotate(20deg) skewX(-10deg);
            text-shadow: 3px 3px 0 #DC143C;
        }
        .landing {
            max-width: 100%;
            margin: 20px auto;
            padding: 20px;
            text-align: center;
        }
        .landing-btn {
            display: inline-block;
            background: #B8860B;
            color: #191970;
            padding: 15px 25px;
            margin: 10px;
            border: 5px solid #DC143C;
            border-radius: 30px;
            font-weight: bold;
            font-size: 16px;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 0 10px rgba(220, 20, 60, 0.7);
        }
        .landing-btn:hover {
            background: #DC143C;
            color: #fff;
            transform: scale(1.15) rotate(5deg);
            box-shadow: 0 0 20px rgba(220, 20, 60, 1);
        }
        .contact-btn {
            background: #DC143C;
            color: #fff;
            padding: 18px 35px;
            margin: 15px;
            border: 5px solid #B8860B;
            border-radius: 35px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            box-shadow: 0 0 15px rgba(184, 134, 11, 0.7);
        }
        .contact-btn:hover {
            background: #B8860B;
            color: #191970;
            transform: scale(1.2);
            box-shadow: 0 0 25px rgba(184, 134, 11, 1);
        }
        .dropdown {
            display: none;
            position: absolute;
            background: #fff;
            border: 6px solid #DC143C;
            border-radius: 20px;
            padding: 25px;
            width: 90%;
            max-width: 700px;
            left: 50%;
            transform: translateX(-50%) rotate(-2deg);
            box-shadow: 0 10px 25px rgba(220, 20, 60, 0.5);
            z-index: 20;
        }
        .dropdown.active {
            display: block;
        }
        h2 {
            color: #191970;
            font-size: 28px;
            text-align: center;
            margin-bottom: 15px;
            border-bottom: 3px dashed #DC143C;
            padding-bottom: 5px;
            text-shadow: 1px 1px 0 #B8860B;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 10px 0;
            padding: 15px;
            background: #f0f0f0;
            border-left: 5px solid #B8860B;
            border-radius: 8px;
            font-size: 18px;
            color: #191970;
            transition: all 0.3s ease;
        }
        ul li:hover {
            background: #DC143C;
            color: #fff;
            transform: translateX(10px);
        }
        .quote-generator {
            background: #B8860B;
            padding: 20px;
            border: 5px solid #DC143C;
            border-radius: 15px;
            margin-top: 15px;
        }
        .quote-generator label {
            display: block;
            margin: 10px 0;
            color: #191970;
            font-size: 16px;
        }
        .quote-generator input[type="checkbox"] {
            margin-right: 10px;
            transform: scale(1.5);
        }
        .quote-generator textarea {
            width: 90%;
            padding: 10px;
            border: 3px solid #DC143C;
            border-radius: 8px;
            font-size: 16px;
            resize: none;
            background: #fff;
            color: #191970;
        }
        .quote-generator button {
            background: #DC143C;
            color: #fff;
            border: none;
            padding: 12px 25px;
            margin-top: 15px;
            border-radius: 25px;
            font-weight: bold;
            cursor: pointer;
            transition: all 0.3s ease;
            font-size: 18px;
            box-shadow: 0 0 10px rgba(220, 20, 60, 0.7);
        }
        .quote-generator button:hover {
            background: #191970;
            transform: scale(1.15) rotate(-5deg);
            box-shadow: 0 0 20px rgba(220, 20, 60, 1);
        }
        .price-note {
            font-size: 14px;
            color: #191970;
            margin-top: 10px;
            text-align: center;
        }
        footer {
            background: #191970;
            color: #B8860B;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            border-top: 8px solid #DC143C;
            box-shadow: 0 -10px 20px rgba(220, 20, 60, 0.5);
        }
        footer p {
            margin: 5px 0;
            font-size: 16px;
        }
        @media (max-width: 768px) {
            h1 span.roundhouse { font-size: 3.5em; }
            h1 span.powerwash { font-size: 1.8em; }
            .swoosh { font-size: 1.5em; }
            .landing-btn { padding: 12px 18px; font-size: 14px; }
            .contact-btn { padding: 14px 25px; font-size: 16px; }
            .dropdown { width: 85%; padding: 15px; }
            h2 { font-size: 24px; }
            ul li { font-size: 16px; padding: 12px; }
        }
    </style>
    <script>
        function toggleDropdown(id) {
            const dropdown = document.getElementById(id);
            const isActive = dropdown.classList.contains('active');
            document.querySelectorAll('.dropdown').forEach(d => d.classList.remove('active'));
            if (!isActive) dropdown.classList.add('active');
        }
    </script>
</head>
<body>
    <header>
        <span class="swoosh">SWOOSH</span>
        <h1><span class="roundhouse">ROUNDHOUSE</span> <span class="powerwash">Powerwash</span></h1>
    </header>
    <div class="landing">
        <div class="landing-btn" onclick="toggleDropdown('bio')">About Me</div>
        <div class="landing-btn" onclick="toggleDropdown('beer')">Beer & Keg Services</div>
        <div class="landing-btn" onclick="toggleDropdown('power')">Power Washing Solutions</div>
        <div class="landing-btn" onclick="toggleDropdown('hauling')">Hauling Services</div>
        <div class="landing-btn" onclick="toggleDropdown('seasonal')">Seasonal Maintenance</div>
        <div class="landing-btn" onclick="toggleDropdown('oddjobs')">Specialty Tasks</div>
        <div class="landing-btn" onclick="toggleDropdown('pricing')">Pricing Details</div>
        <div class="contact-btn" onclick="toggleDropdown('contact')">Contact Me</div>
        <div class="landing-btn" onclick="toggleDropdown('quote')">Request a Quote</div>
    </div>

    <div class="dropdown" id="bio">
        <h2>About Me</h2>
        <ul>
            <li>Based in Bristol, CT - Serving Hartford County</li>
            <li>Your Premier Round-the-House Specialist</li>
            <li>Expertise in Power Washing, Specialty Tasks, and More</li>
        </ul>
    </div>

    <div class="dropdown" id="beer">
        <h2>Beer & Keg Services</h2>
        <ul>
            <li>Beer Line Cleaning</li>
            <li>Draft System Installation</li>
            <li>Keg Delivery & Setup</li>
            <li>CO₂ Tank & Gas Line Services</li>
            <li>Tap & Equipment Maintenance</li>
        </ul>
    </div>

    <div class="dropdown" id="power">
        <h2>Power Washing Solutions</h2>
        <ul>
            <li>House & Siding Power Washing</li>
            <li>Driveway & Sidewalk Cleaning</li>
            <li>Deck & Patio Restoration</li>
            <li>Gutter Cleaning & Maintenance</li>
            <li>Outdoor Furniture & Fire Pit Cleaning</li>
        </ul>
    </div>

    <div class="dropdown" id="hauling">
        <h2>Hauling Services</h2>
        <ul>
            <li>Household Junk & Trash Removal</li>
            <li>Appliance & Furniture Disposal</li>
            <li>Garage & Basement Cleanouts</li>
            <li>Construction & Yard Debris Hauling</li>
            <li>Estate & Storage Unit Cleanouts</li>
        </ul>
    </div>

    <div class="dropdown" id="seasonal">
        <h2>Seasonal Maintenance</h2>
        <ul>
            <li>Driveway Plowing (Quick, No Shoveling)</li>
            <li>Leaf Blowing & Yard Cleanup</li>
            <li>Salting & Ice Prevention</li>
            <li>Firewood Delivery & Stacking</li>
            <li>Gutter Ice Dam Removal</li>
        </ul>
    </div>

    <div class="dropdown" id="oddjobs">
        <h2>Specialty Tasks</h2>
        <ul>
            <li>Chicken Coop Sitting (Bristol/Southington)</li>
            <li>Fence & Shed Maintenance</li>
            <li>Outdoor Fire Pit & Gravel Work</li>
            <li>Small Retaining Wall & Patio Repairs</li>
            <li>Event & Backyard Setup (Tents, Firewood)</li>
        </ul>
    </div>

    <div class="dropdown" id="pricing">
        <h2>Pricing Details</h2>
        <ul>
            <li>Beer Line Cleaning: $50-$90</li>
            <li>Draft System Installation: $75-$150</li>
            <li>Keg Delivery & Setup: $30-$50 + keg cost</li>
            <li>House Power Washing: $100-$200</li>
            <li>Driveway/Sidewalk Cleaning: $40-$80</li>
            <li>Deck/Patio Restoration: $60-$120</li>
            <li>Gutter Cleaning: $75-$150</li>
            <li>Furniture/Fire Pit Cleaning: $30-$70</li>
            <li>Dump Runs: $50-$120</li>
            <li>Bulk Pickup: $40-$100</li>
            <li>Leaf Blowing: $40-$80</li>
            <li>Driveway Plowing: $40-$60</li>
            <li>Firewood Delivery: $50-$100</li>
            <li>Chicken Coop Sitting: $20-$40/day</li>
            <li>Fence Maintenance: $80-$160</li>
        </ul>
    </div>

    <div class="dropdown" id="contact">
        <h2>Contact Me</h2>
        <ul>
            <li>Phone: (860) 906-6883</li>
            <li>Area: Bristol, CT & Hartford County</li>
            <li>Email: roundhouselandscape@gmail.com</li>
        </ul>
    </div>

    <div class="dropdown" id="quote">
        <h2>Request a Quote</h2>
        <div class="quote-generator">
            <form action="mailto:roundhouselandscape@gmail.com" method="post" enctype="text/plain">
                <label><input type="checkbox" name="services" value="Beer Line Cleaning ($50-$90)"> Beer Line Cleaning ($50-$90)</label>
                <label><input type="checkbox" name="services" value="Draft System Installation ($75-$150)"> Draft System Installation ($75-$150)</label>
                <label><input type="checkbox" name="services" value="Keg Delivery & Setup ($30-$50 + keg cost)"> Keg Delivery & Setup ($30-$50 + keg cost)</label>
                <label><input type="checkbox" name="services" value="CO₂ Tank & Gas Line Services ($40-$80)"> CO₂ Tank & Gas Line Services ($40-$80)</label>
                <label><input type="checkbox" name="services" value="Tap & Equipment Maintenance ($30-$60)"> Tap & Equipment Maintenance ($30-$60)</label>
                <label><input type="checkbox" name="services" value="House & Siding Power Washing ($100-$200)"> House & Siding Power Washing ($100-$200)</label>
                <label><input type="checkbox" name="services" value="Driveway & Sidewalk Cleaning ($40-$80)"> Driveway & Sidewalk Cleaning ($40-$80)</label>
                <label><input type="checkbox" name="services" value="Deck & Patio Restoration ($60-$120)"> Deck & Patio Restoration ($60-$120)</label>
                <label><input type="checkbox" name="services" value="Gutter Cleaning & Maintenance ($75-$150)"> Gutter Cleaning & Maintenance ($75-$150)</label>
                <label><input type="checkbox" name="services" value="Outdoor Furniture & Fire Pit Cleaning ($30-$70)"> Outdoor Furniture & Fire Pit Cleaning ($30-$70)</label>
                <label><input type="checkbox" name="services" value="Household Junk & Trash Removal ($50-$120)"> Household Junk & Trash Removal ($50-$120)</label>
                <label><input type="checkbox" name="services" value="Appliance & Furniture Disposal ($40-$100)"> Appliance & Furniture Disposal ($40-$100)</label>
                <label><input type="checkbox" name="services" value="Garage & Basement Cleanouts ($80-$150)"> Garage & Basement Cleanouts ($80-$150)</label>
                <label><input type="checkbox" name="services" value="Construction & Yard Debris Hauling ($60-$130)"> Construction & Yard Debris Hauling ($60-$130)</label>
                <label><input type="checkbox" name="services" value="Estate & Storage Unit Cleanouts ($100-$200)"> Estate & Storage Unit Cleanouts ($100-$200)</label>
                <label><input type="checkbox" name="services" value="Driveway Plowing ($40-$60)"> Driveway Plowing ($40-$60)</label>
                <label><input type="checkbox" name="services" value="Leaf Blowing & Yard Cleanup ($40-$80)"> Leaf Blowing & Yard Cleanup ($40-$80)</label>
                <label><input type="checkbox" name="services" value="Salting & Ice Prevention ($30-$60)"> Salting & Ice Prevention ($30-$60)</label>
                <label><input type="checkbox" name="services" value="Firewood Delivery & Stacking ($50-$100)"> Firewood Delivery & Stacking ($50-$100)</label>
                <label><input type="checkbox" name="services" value="Gutter Ice Dam Removal ($80-$150)"> Gutter Ice Dam Removal ($80-$150)</label>
                <label><input type="checkbox" name="services" value="Chicken Coop Sitting ($20-$40/day)"> Chicken Coop Sitting ($20-$40/day)</label>
                <label><input type="checkbox" name="services" value="Fence & Shed Maintenance ($80-$160)"> Fence & Shed Maintenance ($80-$160)</label>
                <label><input type="checkbox" name="services" value="Outdoor Fire Pit & Gravel Work ($50-$100)"> Outdoor Fire Pit & Gravel Work ($50-$100)</label>
                <label><input type="checkbox" name="services" value="Small Retaining Wall & Patio Repairs ($100-$200)"> Small Retaining Wall & Patio Repairs ($100-$200)</label>
                <label><input type="checkbox" name="services" value="Event & Backyard Setup ($60-$120)"> Event & Backyard Setup ($60-$120)</label>
                <textarea rows="4" name="notes" placeholder="Lay it on me, what’s the job?"></textarea><br>
                <button type="submit">Submit Quote Request</button>
                <p class="price-note">*Estimates are a starting point. Final price set after in-person review, but I’ll keep it close!</p>
            </form>
        </div>
    </div>

    <footer>
        <p>© 2025 ROUNDHOUSE Powerwash LLC</p>
        <p>(860) 906-6883 • Bristol, CT</p>
    </footer>
</body>
</html>
