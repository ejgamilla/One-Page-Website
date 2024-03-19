<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My One Page Website</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        /* Add more styles as needed */
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#pictures">Pictures</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#video">Video</a></li>
        </ul>
    </nav>

    <!-- Home Page Section -->
    <section id="home">
        <h1>Welcome to My Website</h1>
        <p>This is the home page section. You can put your content here.</p>
    </section>

    <!-- Pictures Section -->
    <section id="pictures">
        <h2>Pictures</h2>
        <img src="picture1.jpg" alt="Picture 1">
        <img src="picture2.jpg" alt="Picture 2">
        <!-- Add more images as needed -->
    </section>

    <!-- Contact Form Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message" rows="4" required></textarea><br>
            <input type="submit" value="Submit">
        </form>
    </section>

    <!-- Video Section -->
    <section id="video">
        <h2>Video</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>
        <!-- Add more videos as needed -->
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 My One Page Website</p>
    </footer>
</body>
</html>
