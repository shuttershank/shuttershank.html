# shuttershank.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shuttershank - Photography Portfolio</title>
    <style>
        body {
            background-color: #000;
            color: #fff;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 50px 0;
            background-color: #111;
        }

        header h1 {
            font-size: 3em;
            color: #fff;
            margin: 0;
        }

        nav {
            text-align: center;
            padding: 20px 0;
            background-color: #222;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-size: 1.2em;
        }

        nav a:hover {
            color: #f0a500;
        }

        .section {
            padding: 50px 20px;
            text-align: center;
        }

        .section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

        .about {
            background-color: #111;
        }

        .portfolio {
            background-color: #1a1a1a;
        }

        .portfolio .category {
            margin: 20px 0;
        }

        .portfolio .category h3 {
            font-size: 1.8em;
            margin-bottom: 15px;
        }

        .portfolio .gallery {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .portfolio .gallery img {
            margin: 10px;
            width: 300px;
            height: 200px;
            object-fit: cover;
            border: 3px solid #333;
        }

        .portfolio .gallery img:hover {
            border-color: #f0a500;
        }

        .contact {
            background-color: #111;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #222;
        }

        footer p {
            margin: 0;
            font-size: 1em;
        }

    </style>
</head>
<body>

    <header>
        <h1>Shuttershank</h1>
        <p>Professional Photographer - Capturing Moments</p>
    </header>

    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about" class="section about">
        <h2>About Me</h2>
        <p>Hi! I'm Shuttershank, a professional photographer with a passion for capturing life's most beautiful moments. From landscapes to portraits, I love to bring out the beauty in every scene. Browse my portfolio to see the world through my lens!</p>
    </section>

    <section id="portfolio" class="section portfolio">
        <h2>Portfolio</h2>

        <div class="category">
            <h3>Landscapes</h3>
            <div class="gallery">
                <img src="your-image1.jpg" alt="Landscape 1">
                <img src="your-image2.jpg" alt="Landscape 2">
                <img src="your-image3.jpg" alt="Landscape 3">
            </div>
        </div>

        <div class="category">
            <h3>Portraits</h3>
            <div class="gallery">
                <img src="your-image4.jpg" alt="Portrait 1">
                <img src="your-image5.jpg" alt="Portrait 2">
                <img src="your-image6.jpg" alt="Portrait 3">
            </div>
        </div>

        <div class="category">
            <h3>Street Photography</h3>
            <div class="gallery">
                <img src="your-image7.jpg" alt="Street 1">
                <img src="your-image8.jpg" alt="Street 2">
                <img src="your-image9.jpg" alt="Street 3">
            </div>
        </div>

    </section>

    <section id="contact" class="section contact">
        <h2>Contact</h2>
        <p>Interested in working together? Reach out to me!</p>
        <p>Email: <a href="mailto:your-email@example.com" style="color: #f0a500;">your-email@example.com</a></p>
        <p>Phone: +1234567890</p>
    </section>

    <footer>
        <p>&copy; 2024 Shuttershank. All Rights Reserved.</p>
    </footer>

</body>
</html>
