<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ophiraeon</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Ophiraeon</h1>
            <p>Your Journey of Healing and Growth</p>
        </div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#membership">Membership</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#blog">Blog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="about">
            <h2>About Us</h2>
            <p>Ophiraeon is a secret society dedicated to community, healing, and creativity. We provide a space for individuals to connect, grow, and transform their lives.</p>
        </section>

        <section id="membership">
            <h2>Membership</h2>
            <p>Join our community and gain access to exclusive events, workshops, and resources.</p>
            <button><a href="#join">Join Now</a></button>
        </section>

        <section id="events">
            <h2>Upcoming Events</h2>
            <ul>
                <li>Event 1: Date and Details</li>
                <li>Event 2: Date and Details</li>
                <li>Event 3: Date and Details</li>
            </ul>
        </section>

        <section id="blog">
            <h2>Blog</h2>
            <p>Read our latest articles on mental health, creativity, and community initiatives.</p>
            <button><a href="#read">Read More</a></button>
        </section>
    </main>

    <footer>
        <section id="contact">
            <h2>Contact Us</h2>
            <p>Email: <a href="mailto:info@ophiraeon.com">info@ophiraeon.com</a></p>
            <p>Follow us on social media!</p>
            <ul>
                <li><a href="#">Instagram</a></li>
                <li><a href="#">Facebook</a></li>
                <li><a href="#">Twitter</a></li>
            </ul>
        </section>
        <p>&copy; 2024 Ophiraeon. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header .logo h1 {
    margin: 0;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
}

main {
    padding: 20px;
}

section {
    margin: 20px 0;
    padding: 20px;
    background: #fff;
    border-radius: 5px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

footer {
    background: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

footer a {
    color: #fff;
    text-decoration: none;
}
