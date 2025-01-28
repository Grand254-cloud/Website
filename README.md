<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PhotoSell - Sell Your Photos Online</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">PhotoSell</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h1>Welcome to PhotoSell</h1>
        <p>Your destination for high-quality photos</p>
        <a href="#gallery" class="btn">Explore Gallery</a>
    </section>

    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="photo-grid">
            <div class="photo-item">
                <img src="photo1.jpg" alt="Photo 1">
                <p>Photo 1 - $20</p>
                <button class="btn">Buy Now</button>
            </div>
            <div class="photo-item">
                <img src="photo2.jpg" alt="Photo 2">
                <p>Photo 2 - $25</p>
                <button class="btn">Buy Now</button>
            </div>
            <!-- Add more photo items here -->
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Us</h2>
        <p>We are a team of passionate photographers dedicated to bringing you the best photos from around the world.</p>
    </section>

    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit" class="btn">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 PhotoSell. All rights reserved.</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html># Website
