<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Roadstar Assistance</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <h1>Roadstar Assistance</h1>
        <nav>
            <ul>
                <li><a href="#services">Services</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="services">
            <h2>Our Services</h2>
            <ul>
                <li>Flat Tire Change</li>
                <li>Battery Jump Start</li>
                <li>Fuel Delivery</li>
                <li>Lockout Assistance</li>
            </ul>
        </section>

        <section id="about">
            <h2>About Us</h2>
            <p>Roadstar Assistance is dedicated to providing reliable roadside assistance services 24/7. Our team of professionals is always ready to help you with any vehicle issues, except towing.</p>
        </section>

        <section id="contact">
            <h2>Contact Us</h2>
            <form id="contact-form">
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Send</button>
            </form>
        </section>
    </main>

    <footer>
        <p>Open 24/7 | Roadstar Assistance</p>
    </footer>

    <script src="scripts/main.js"></script>
</body>
</html>
