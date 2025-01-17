# Copy-Paste-Edit-this-template-to-create-your-website
You can copy paste and edit with the template I`ve given! Have fun change colour change blocks and add your own information!


```diff
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to the Awesome World of Sanyukta!</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }
        header, footer, section {
            padding: 20px;
        }
        header {
            background-color: #f4f4f4;
            text-align: center;
        }
        footer {
            background-color: #333;
            color:white;
            text-align: center;
            padding: 10px 0;
        }
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            margin: 5px 0;
        }
        button {
            padding: 10px 20px;
            background-color: #007BFF;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #0056b3;
        }
        .container {
            max-width: 800px;
            margin: auto;
        }
        .hero {
            text-align: center;
            background-color: #f9f9f9;
            padding: 50px;
            margin-bottom: 20px;
        }
        .hero button {
            margin-top: 20px;
        }
        .section-title {
            text-align: center;
            margin-bottom: 20px;
        }
        form label {
            display: block;
            margin-top: 10px;
        }
        form input, form textarea {
            width: 100%;
            padding: 8px;
            margin-top: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>NAMASTE</h1>
        <p>
            You can learn about the training services I offer! With an experience of teaching students from over 10+ countries with my engaging style of learning.
        </p>
    </header>

    <section class="hero">
        <h1>Welcome to the Awesome World of Sanyukta!</h1>
        <p>
            Empower your learning journey with interactive and fun training sessions.
            Join students from over 10+ countries who have unlocked their potential!
        </p>
        <button onclick="window.location.href='#services';">Explore Services</button>
    </section>

    <section id="about" class="container">
        <h2 class="section-title">About Me</h2>
        <p>
            I am Sanyukta, a passionate educator with years of experience in training students from diverse backgrounds. My teaching methods are interactive, engaging, and tailored to individual learning needs.
        </p>
    </section>

    <section id="services" class="container">
        <h2 class="section-title">My Services</h2>
        <ul>
            <li>One-on-one tutoring sessions</li>
            <li>Workshops on data analysis and visualization</li>
            <li>Corporate training programs</li>
            <li>Customized learning paths</li>
        </ul>
    </section>

    <section id="testimonials" class="container">
        <h2 class="section-title">What My Students Say</h2>
        <blockquote>
            "Sanyukta's teaching style is simply amazing! She makes complex topics so easy to understand."
            <footer>- A Student from Germany</footer>
        </blockquote>
        <blockquote>
            "The workshops were engaging and very practical. Highly recommend her services!"
            <footer>- A Corporate Trainee</footer>
        </blockquote>
    </section>

    <section id="contact" class="container">
        <h2 class="section-title">Contact Me</h2>
        <form action="submit_form.php" method="post">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>
            
            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>
            
            <label for="message">Your Message:</label>
            <textarea id="message" name="message" placeholder="Enter your message" rows="5" required></textarea>
            
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Sanyukta's Training Services. All Rights Reserved.</p>
        <p>Follow me on:
            <a href="https://twitter.com" target="_blank">Twitter</a> |
            <a href="https://linkedin.com" target="_blank">LinkedIn</a> |
            <a href="https://github.com" target="_blank">GitHub</a>
        </p>
    </footer>
</body>
</html>
```
