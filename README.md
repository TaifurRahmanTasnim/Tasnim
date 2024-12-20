

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Md.Taifur Rahman Tasnim  - Portfolio</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background-color: #f4f4f4;
        }

        /* Navigation */
        nav {
            background-color: #333;
            padding: 15px;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: white;
            font-size: 18px;
        }

        nav ul li a:hover {
            color: #f4f4f4;
        }

        /* Hero Section */
        .hero {
            background: url('https://via.placeholder.com/1600x600') no-repeat center center/cover;
            height: 100vh;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 50px;
            font-weight: 600;
        }

        .hero p {
            font-size: 20px;
            margin-top: 20px;
        }

        /* About Me Section */
        #about {
            padding: 80px 20px;
            background-color: white;
            text-align: center;
        }

        #about h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        #about p {
            font-size: 18px;
            max-width: 800px;
            margin: 0 auto;
            line-height: 1.8;
        }

        /* Skills Section */
        #skills {
            padding: 80px 20px;
            background-color: #f4f4f4;
            text-align: center;
        }

        #skills h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .skills-list {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 40px;
        }

        .skill {
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            width: 200px;
            text-align: center;
        }

        .skill h3 {
            font-size: 24px;
            margin-bottom: 10px;
        }

        /* My Work Section */
        #work {
            padding: 80px 20px;
            background-color: white;
            text-align: center;
        }

        #work h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .work-gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .work-item {
            width: 300px;
            height: 200px;
            background-color: #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            position: relative;
        }

        .work-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Contact Section */
        #contact {
            padding: 80px 20px;
            background-color: #333;
            color: white;
            text-align: center;
        }

        #contact h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        #contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        #contact input,
        #contact textarea {
            width: 100%;
            max-width: 600px;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: 1px solid #ccc;
            font-size: 16px;
        }

        #contact button {
            padding: 10px 20px;
            background-color: #f4f4f4;
            border: none;
            color: #333;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        #contact button:hover {
            background-color: #555;
            color: white;
        }

        /* Footer */
        footer {
            padding: 20px;
            text-align: center;
            background-color: #333;
            color: white;
        }

        footer p {
            font-size: 14px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 36px;
            }

            #about p,
            #skills p {
                font-size: 16px;
            }

            .skills-list {
                flex-direction: column;
            }
        }
    </style>
</head>

<body>
    <!-- Navigation Bar -->
    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#work">My Work</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <section class="hero">
        <div>
            <h1>Your Name</h1>
            <p>Web Developer | Designer | Creator</p>
        </div>
    </section>

    <!-- About Me Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a passionate web developer with a love for creating beautiful and functional websites. With a background in design and front-end development, I enjoy solving problems and bringing creative ideas to life.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <div class="skills-list">
            <div class="skill">
                <h3>HTML</h3>
                <p>Building the structure of websites with semantic HTML.</p>
            </div>
            <div class="skill">
                <h3>CSS</h3>
                <p>Styling websites and ensuring they are responsive.</p>
            </div>
            <div class="skill">
                <h3>JavaScript</h3>
                <p>Creating interactive and dynamic web pages with JavaScript.</p>
            </div>
            <div class="skill">
                <h3>React</h3>
                <p>Building modern, dynamic web apps with React.js.</p>
            </div>
        </div>
    </section>

    <!-- My Work Section -->
    <section id="work">
        <h2>My Work</h2>
        <div class="work-gallery">
            <div class="work-item">
                <img src="https://via.placeholder.com/300x200" alt="Project 1">
            </div>
            <div class="work-item">
                <img src="https://via.placeholder.com/300x200" alt="Project 2">
            </div>
            <div class="work-item">
                <img src="https://via.placeholder.com/300x200" alt="Project 3">
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <form action="#" method="post">
            <input type="text" placeholder="Md. Taifur Rahman Tasnim " required>
            <input type="email" placeholder="tasnimtaifur@gmail.com" required>
            <textarea placeholder="Your Message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Your Name | All rights reserved</p>
    </footer>
</body>

</html>



