<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saikumar Juloori Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 0.5rem 0;
            background: #444;
        }
        nav a {
            color: #fff;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 2rem;
            max-width: 800px;
            margin: auto;
        }
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }
        .project-card {
            background: #fff;
            border: 1px solid #ccc;
            border-radius: 8px;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1rem;
            background: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Saikumar Juloori</h1>
        <p>Aspiring Full Stack Web Developer</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <section id="about">
        <h2>About Me</h2>
        <p>
            I am a passionate full stack web developer specializing in ReactJS, Node.js, Express.js, and PostgreSQL. I aim to build scalable, user-friendly, and efficient web applications. My academic background in computer science and professional experience in quality assurance have equipped me with a robust understanding of both front-end and back-end development.
        </p>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="project-card">
                <h3>Ship Reservation System</h3>
                <p>Developed a Java and J2EE-based system with user-friendly interfaces for booking and order management.</p>
            </div>
            <div class="project-card">
                <h3>Sliding Window Clustering</h3>
                <p>Optimized clustering algorithms to enhance execution time by 20%, improving centroid pruning accuracy.</p>
            </div>
            <div class="project-card">
                <h3>Student Management System</h3>
                <p>Created a Python-based system for managing student records, including functionalities for adding, updating, and deleting data.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>Email: juloorisaikumar2821@gmail.com</p>
        <p>Phone: +1 (806) 730-3898</p>
        <p><a href="https://www.linkedin.com/in/juloorisai" target="_blank">LinkedIn</a> | <a href="https://github.com/SaikumarJuloori" target="_blank">GitHub</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Saikumar Juloori. All rights reserved.</p>
    </footer>
</body>
</html>
