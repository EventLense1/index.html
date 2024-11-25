<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EventLens - Connect with Photographers</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>EventLens</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#reviews">Reviews</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero">
        <h2>Find the Perfect Photographer or Videographer</h2>
        <p>Connecting talent with events, seamlessly.</p>
        <a href="#services" class="cta-button">Get Started</a>
    </section>

    <section id="about">
        <h2>About EventLens</h2>
        <p>Your one-stop platform for hiring professional photographers and videographers for events big and small. We make connecting easy and reliable.</p>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service-list">
            <div class="service-item">
                <h3>Event Photography</h3>
                <p>Capture memories that last a lifetime.</p>
            </div>
            <div class="service-item">
                <h3>Videography</h3>
                <p>Relive your special moments through video.</p>
            </div>
            <div class="service-item">
                <h3>Portfolio Promotion</h3>
                <p>Grow your photography business with exposure.</p>
            </div>
        </div>
    </section>

    <section id="reviews">
        <h2>What Our Users Say</h2>
        <p>"EventLens made finding a photographer for my wedding stress-free!"</p>
        <p>"The portfolio feature helped me land more gigs as a videographer!"</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message:</label>
            <textarea id="message" name="message" rows="5" required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 EventLens. All rights reserved.</p>
    </footer>
</body>
</html>
