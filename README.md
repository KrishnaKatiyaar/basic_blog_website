# basic_blog_website

  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="View the Canva design for a white, teal, and dark blue corporate website template. Created by Nitisha Gupta.">
    <title>Corporate Website Design - Canva</title>

    <!-- Google Tag (gtag.js) -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=G-W7G9RHH6MV"></script>
    <script>
        window.dataLayer = window.dataLayer || [];
        function gtag() {
            dataLayer.push(arguments);
        }
        gtag('js', new Date());
        gtag('config', 'G-W7G9RHH6MV');
    </script>

    <!-- Stylesheet -->
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 10%;
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            margin: 0;
            font-size: 1.8rem;
            color: #333;
        }

        nav {
            display: flex;
            gap: 15px;
        }

        nav a {
            color: #333;
            text-decoration: none;
            font-size: 1rem;
            font-weight: 500;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #0073e6;
        }

        .hero {
            text-align: center;
            padding: 80px 20px;
            background-color: #0073e6;
            color: white;
        }

        .hero h2 {
            font-size: 2.5rem;
            margin-bottom: 15px;
        }

        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }

        .hero .button {
            background-color: white;
            color: #0073e6;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s, color 0.3s;
        }

        .hero .button:hover {
            background-color: #005bb5;
            color: white;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
        }

        .embed-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-top: 56.25%; /* Maintain 16:9 Aspect Ratio */
            margin: 2rem 0;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
        }

        .embed-container iframe {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            border: none;
        }

        footer {
            background-color: #ffffff;
            color: #333;
            text-align: center;
            padding: 15px 10%;
            border-top: 1px solid #ddd;
        }

        footer p {
            margin: 0;
            font-size: 0.9rem;
        }

        footer a {
            color: #0073e6;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Corporate Website</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="#">Services</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Welcome to Our Corporate Website</h2>
        <p>Discover modern and professional designs that elevate your business.</p>
        <button class="button">Get Started</button>
    </section>

    <div class="container">
        <h2>Our Design Showcase</h2>
        <p>Explore our sleek corporate templates designed for success.</p>

        <div class="embed-container">
            <iframe loading="lazy" title="Canva Design - Corporate Website"
                src="https://www.canva.com/design/DAGcXnXl32I/G-FWTggHSlFMMTcXdVB2fw/view?embed"
                allowfullscreen>
            </iframe>
        </div>
    </div>

    <footer>
        <p>Created by <strong>Nitisha Gupta</strong> | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>

