<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Resin Art Shop</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f7f7f7;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #fff;
            padding: 20px 0;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #333;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        nav a:hover {
            color: #007BFF;
        }
        section {
            padding: 50px 20px;
            max-width: 1000px;
            margin: auto;
        }
        .about, .projects, .shop, .contact {
            margin-bottom: 50px;
        }
        h2 {
            font-size: 2em;
            margin-bottom: 20px;
            color: #333;
            border-bottom: 2px solid #ccc;
            display: inline-block;
        }
        p {
            margin-bottom: 20px;
            font-size: 1.1em;
        }
        .projects img, .shop img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .shop .item {
            margin-bottom: 30px;
        }
        .contact form {
            display: flex;
            flex-direction: column;
            max-width: 500px;
            margin: auto;
        }
        .contact input, .contact textarea {
            padding: 10px;
            margin-bottom: 20px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1em;
        }
        .contact button {
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #007BFF;
            color: white;
            font-size: 1em;
            cursor: pointer;
        }
        .contact button:hover {
            background-color: #0056b3;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px 0;
            margin-top: 50px;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Resin Art Shop</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#projects">Projects</a>
            <a href="#shop">Shop</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about" class="about">
        <h2>About Me</h2>
        <p>Welcome to my art shop! I am an artist who specializes in creating unique and elegant resin moldage pieces. Each item is carefully crafted with a combination of vibrant colors and gold leafs, making every piece one of a kind. My passion for art and attention to detail are reflected in every creation, and I hope they bring as much joy to you as they do to me.</p>
    </section>

    <section id="projects" class="projects">
        <h2>Projects</h2>
        <p>Here are some of my recent creations:</p>
        <img src="project1.jpg" alt="Project 1">
        <img src="project2.jpg" alt="Project 2">
        <img src="project3.jpg" alt="Project 3">
    </section>

    <section id="shop" class="shop">
        <h2>Shop</h2>
        <p>Browse and purchase my available resin moldage pieces:</p>
        <div class="item">
            <img src="product1.jpg" alt="Product 1">
            <p>Elegant Gold Leaf Moldage - $50</p>
        </div>
        <div class="item">
            <img src="product2.jpg" alt="Product 2">
            <p>Colorful Resin Art - $60</p>
        </div>
        <div class="item">
            <img src="product3.jpg" alt="Product 3">
            <p>Abstract Gold and Color - $70</p>
        </div>
    </section>

    <section id="contact" class="contact">
        <h2>Contact</h2>
        <p>If you have any questions or would like to commission a custom piece, please get in touch using the form below:</p>
        <form action="#" method="post">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Your Resin Art Shop. All rights reserved.</p>
    </footer>

</body>
</html>
