<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>AI World - Explore the Future of Technology</title>
    <style>
        /* Reset default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and background styles */
        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(100deg, #06ee12, #0652f7);
            color: rgb(238, 227, 227);
        }

        /* Navbar styles */
        .navbar {
            display: flex;
            justify-content: space-between;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.5);
        }

        .navbar .logo {
            font-size: 2.0em;
            font-weight: bold;
        }

        .navbar nav ul {
            list-style-type: none;
            display: flex;
            gap: 20px;
        }

        .navbar nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 1.2em;
            transition: color 0.3s ease;
        }

        .navbar nav ul li a:hover {
            color: #f808ec;
        }

        /* Hero Section */
        .hero-section {
            background: url('https://www.example.com/ai-background.jpg') center/cover no-repeat;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: rgb(250, 244, 244);
            padding: 0 20px;
        }

        .hero-section .hero-text h1 {
            font-size: 3em;
            font-weight: bold;
        }

        .hero-section .cta-button {
            margin-top: 20px;
            padding: 10px 10px;
            background-color: #0cfc18;
            color: rgb(3, 3, 3);
            border: none;
            font-size: 1.2em;
            cursor: pointer;
            text-decoration: none;
            border-radius: 15px;
        }

        .hero-section .cta-button:hover {
            background-color: #f56608;
        }

        /* About Section */
        .about-section {
            padding: 60px 20px;
            background-color: rgba(3, 3, 3, 0.7);
            text-align: center;
        }

        .about-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .about-section p {
            font-size: 1.2em;
        }

        /* Applications Section */
        .applications-section {
            padding: 60px 20px;
            background-color: #292b2c;
            text-align: center;
        }

        .applications-section h2 {
            font-size: 2.5em;
            margin-bottom: 40px;
        }

        .cards {
            display: flex;
            gap: 20px;
            justify-content: center;
        }

        .card {
            background-color: #020202;
            padding: 20px;
            width: 30%;
            border-radius: 50px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
            text-align: center;
        }

        .card h3 {
            font-size: 2.0em;
            margin-bottom: 20px;
        }

        .card p {
            font-size: 1.3em;
        }

        /* Contact Section */
        .contact-section {
            padding: 60px 20px;
            background-color: rgba(0, 0, 0, 0.8);
            text-align: center;
        }

        .contact-section h2 {
            font-size: 3.0em;
            margin-bottom: 30px;
        }

        .contact-section form {
            max-width: 600px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 15px;
        }

        .contact-section input, .contact-section textarea {
            padding: 10px;
            font-size: 1.1em;
            border-radius: 5px;
            border: 1px solid #ccc;
        }

        .contact-section button {
            padding: 15px 30px;
            background-color: #5cff47;
            border: none;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
        }

        .contact-section button:hover {
            background-color: #f006f0;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            background-color: rgba(0, 0, 0, 0.7);
            color: #ccc;
        }
    </style>
</head>
<body>
    <header>
        <div class="navbar">
            <div class="logo">AI World</div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About AI</a></li>
                    <li><a href="#applications">Applications</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero-section">
        <div class="hero-text">
            <h1>Welcome to the World of Artificial Intelligence</h1>
            <p>Explore the future of technology and how AI is shaping our world.</p>
            <a href="#about" class="cta-button">Learn More</a>
        </div>
    </section>

    <section id="about" class="about-section">
        <h2>What is AI?</h2>
        <p>Artificial Intelligence (AI) is the simulation of human intelligence processes by machines, especially computer systems. These processes include learning, reasoning, problem-solving, perception, and language understanding.</p>
    </section>

    <section id="applications" class="applications-section">
        <h2>Applications of AI</h2>
        <div class="cards">
            <div class="card">
                <h3>Healthcare</h3>
                <p>AI is revolutionizing healthcare by providing personalized treatment, improving diagnostics, and enabling better patient care.</p>
            </div>
            <div class="card">
                <h3>Autonomous Vehicles</h3>
                <p>AI plays a crucial role in the development of self-driving cars, enabling them to learn from their surroundings and make intelligent decisions.</p>
            </div>
            <div class="card">
                <h3>Finance</h3>
                <p>AI is used in finance for fraud detection, investment strategies, and algorithmic trading, transforming the financial industry.</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-section">
        <h2>Contact Us</h2>
        <form action="#">
            <label for="name">Name</label>
            <input type="text" id="name" name="name">

            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit" class="cta-button">Send Message</button>
        </form>
    </section>

    <footer>
        <p>@2024 AI World. All rights reserved.</p>
    </footer>
</body>
</html>
