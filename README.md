# Hadi-Academy-EFA-
Hadi Academy (Education For All), is a platform to assist students all over the Pakistan. Notes of every topic is present and test session system, online classes and recorded lectures are offered by this platform.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hadi Academy (Education for All)</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Welcome to Hadi Academy (Education for All)</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="lectures.html">Lectures</a></li>
                    <li><a href="resources.html">Resources</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section class="intro">
            <h2>Your Path to Knowledge Begins Here</h2>
            <p>Welcome to Hadi Academy, where we aim to provide accessible education for everyone. Our mission is to make learning easy and affordable with high-quality video lectures, notes, and resources.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Hadi Academy. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lectures - Hadi Academy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Hadi Academy - Lectures</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="lectures.html">Lectures</a></li>
                    <li><a href="resources.html">Resources</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section class="lecture">
            <h2>Latest Video Lectures</h2>
            <div class="video-container">
                <h3>Class 9 Biology - Mitosis</h3>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/YOUR_VIDEO_LINK" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
            </div>
            <!-- Add more videos here in a similar format -->
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Hadi Academy. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Resources - Hadi Academy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Hadi Academy - Resources</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="lectures.html">Lectures</a></li>
                    <li><a href="resources.html">Resources</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section class="resources">
            <h2>Study Materials & PDFs</h2>
            <ul>
                <li><a href="path_to_your_pdf">Class 9 Biology Notes - PDF</a></li>
                <li><a href="path_to_your_pdf">Class 9 Biology Chapter 1 - PDF</a></li>
                <!-- Add more PDFs here -->
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Hadi Academy. All rights reserved.</p>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Hadi Academy</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Contact Hadi Academy</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="lectures.html">Lectures</a></li>
                    <li><a href="resources.html">Resources</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>
    
    <main>
        <section class="contact">
            <h2>Get in Touch</h2>
            <p>If you have any questions, feel free to contact us!</p>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Your Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <textarea name="message" placeholder="Your Message" required></textarea>
                <button type="submit">Submit</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Hadi Academy. All rights reserved.</p>
    </footer>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #007BFF;
    color: white;
    padding: 20px 0;
}

header .container {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

h1, h2 {
    margin: 0;
}

main {
    padding: 20px;
}

footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

button {
    background-color: #007BFF;
    color: white;
    padding: 10px 15px;
    border: none;
    cursor: pointer;
}

button:hover {
    background-color: #0056b3;
}

form input, form textarea {
    width: 100%;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ddd;
}

form textarea {
    height: 150px;
}
