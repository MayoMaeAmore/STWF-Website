<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Samahan ng Tagapagpalaganap ng Wikang Filipino">
    <title>Samahan ng Tagapagpalaganap ng Wikang Filipino</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Samahan ng Tagapagpalaganap ng Wikang Filipino</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="about.html">About Us</a></li>
                    <li><a href="activities.html">Activities</a></li>
                    <li><a href="news.html">News</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main>
        <section class="intro">
            <h2>Welcome to our official website!</h2>
            <p>We are dedicated to the promotion and advocacy of the Filipino language. Join us in our mission to strengthen and preserve our native tongue.</p>
        </section>

        <section class="events">
            <h2>Upcoming Events</h2>
            <p>Stay tuned for our upcoming events and activities!</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Samahan ng Tagapagpalaganap ng Wikang Filipino. All Rights Reserved.</p>
    </footer>
</body>
</html>

Part 2:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>About Samahan ng Tagapagpalaganap ng Wikang Filipino</h1>
    </header>

    <main>
        <section>
            <h2>Our Mission</h2>
            <p>Our mission is to advocate for the use and promotion of the Filipino language in all aspects of Filipino society and culture.</p>
        </section>

        <section>
            <h2>Our Vision</h2>
            <p>We envision a Philippines where the Filipino language is widely used and valued by all its people, preserving its rich cultural heritage.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Samahan ng Tagapagpalaganap ng Wikang Filipino. All Rights Reserved.</p>
    </footer>
</body>
</html>

Part 3
CSS for Styling.
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background: #333;
    color: white;
    padding: 10px 0;
}

header h1 {
    text-align: center;
    font-size: 2rem;
}

nav ul {
    list-style: none;
    text-align: center;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 1rem;
}

nav ul li a:hover {
    text-decoration: underline;
}

.container {
    width: 80%;
    margin: 0 auto;
}

main {
    padding: 20px;
    background: white;
    margin: 20px 0;
}

footer {
    text-align: center;
    padding: 10px 0;
    background: #333;
    color: white;
}

footer p {
    margin: 0;
}

h2 {
    font-size: 1.5rem;
    margin-bottom: 10px;
}

Part 4: create other pages..

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Contact Us</h1>
    </header>

    <main>
        <section>
            <h2>Get in Touch</h2>
            <p>If you have any questions or would like to join us, feel free to contact us!</p>
            <form action="submit_form.php" method="post">
                <label for="name">Your Name:</label>
                <input type="text" id="name" name="name" required>

                <label for="email">Your Email:</label>
                <input type="email" id="email" name="email" required>

                <label for="message">Your Message:</label>
                <textarea id="message" name="message" rows="4" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Samahan ng Tagapagpalaganap ng Wikang Filipino. All Rights Reserved.</p>
    </footer>
</body>
</html>
