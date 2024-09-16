<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Your Personal Portfolio">
    <title>Your Name - Portfolio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Name</h1>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
                <li id="theme-toggle">🌞</li>
            </ul>
        </nav>
    </header>

    <div id="time-location">
        <p>Current Time: <span id="time"></span></p>
        <p>Your Location: <span id="location"></span></p>
    </div>

    <section id="about">
        <h2>About Me</h2>
        <p>Welcome to my portfolio! I'm passionate about web development, design, and creating impactful projects.</p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project 1</h3>
            <p>A brief description of the project goes here.</p>
        </div>
        <div class="project">
            <h3>Project 2</h3>
            <p>A brief description of the project goes here.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:yourname@example.com">yourname@example.com</a></p>
    </section>

    <footer>
        <p>&copy; 2024 Your Name</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    transition: background-color 0.3s, color 0.3s;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
    padding: 20px;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 30px;
}

header h1 {
    font-size: 2em;
}

nav ul {
    list-style-type: none;
    display: flex;
    gap: 20px;
}

nav ul li {
    display: inline;
    cursor: pointer;
}

section {
    margin-bottom: 30px;
}

#time-location {
    text-align: center;
    margin: 20px 0;
}

h2 {
    margin-bottom: 10px;
}

footer {
    text-align: center;
    padding-top: 20px;
    border-top: 1px solid #ccc;
}

.dark-mode {
    background-color: #333;
    color: #f4f4f4;
}
