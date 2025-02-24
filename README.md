<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Demo Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            text-align: center;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
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
        section {
            padding: 2em;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to the Demo Website</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Home</h2>
        <p>This is a simple demo website created using HTML and CSS.</p>
    </section>

    <section id="about">
        <h2>About</h2>
        <p>This demo showcases a basic structure of a website with a header, navigation, content sections, and a footer.</p>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach us at <a href="mailto:info@demo.com">info@demo.com</a>.</p>
    </section>

    <footer>
        <p>&copy; 2025 Demo Website. All rights reserved.</p>
    </footer>
</body>
</html>
