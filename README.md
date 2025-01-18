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
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(120deg, #e0f7fa, #004d40);
            color: #333;
        }

        header {
            background-color: #004d40;
            color: white;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #00695c;
            padding: 10px 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2rem;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #b2dfdb;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 0 20px;
            text-align: center;
        }

        .embed-container {
            position: relative;
            width: 100%;
            height: 0;
            padding-top: 56.25%; /* Maintain 16:9 Aspect Ratio */
            box-shadow: 0 2px 8px rgba(63, 69, 81, 0.16);
            margin: 2rem 0;
            overflow: hidden;
            border-radius: 8px;
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
            background-color: #004d40;
            color: white;
            text-align: center;
            padding: 15px 0;
            margin-top: 2rem;
        }

        footer p {
            margin: 0;
            font-size: 0.9rem;
        }

        footer a {
            color: #b2dfdb;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        .button {
            display: inline-block;
            padding: 10px 20px;
            margin: 20px 10px;
            background-color: #004d40;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
            transition: background-color 0.3s;
        }

        .button:hover {
            background-color: #00695c;
        }

        .button-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Corporate Website</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
        <a href="#">Services</a>
        <a href="#">Contact</a>
    </nav>

    <div class="container">
        <h2>Embedded Canva Design</h2>
        <p>Explore our modern corporate website design with a professional and sleek look.</p>

        <div class="embed-container">
            <iframe loading="lazy" title="Canva Design - Corporate Website"
                src="https://www.canva.com/design/DAGcXnXl32I/G-FWTggHSlFMMTcXdVB2fw/view?embed"
                allowfullscreen>
            </iframe>
        </div>

        <div class="button-container">
            <a class="button" href="#">Learn More</a>
            <a class="button" href="#">Sign Up</a>
            <a class="button" href="#">Get Started</a>
        </div>

        <a class="button" href="https://www.canva.com/design/DAGcXnXl32I/G-FWTggHSlFMMTcXdVB2fw/view?utm_content=DAGcXnXl32I&utm_campaign=designshare&utm_medium=embeds&utm_source=link" target="_blank" rel="noopener noreferrer">View Full Design</a>
    </div>

    <footer>
        <p>Created by <strong>Nitisha Gupta</strong> | <a href="#">Privacy Policy</a></p>
    </footer>
</body>
</html>
