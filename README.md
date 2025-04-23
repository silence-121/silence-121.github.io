<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
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
            background: #444;
            color: #fff;
            display: flex;
            justify-content: center;
            gap: 1rem;
            padding: 0.5rem 0;
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
            max-width: 900px;
            margin: auto;
        }
        .projects img {
            width: 100%;
            height: auto;
            display: block;
        }
        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }
        .btn:hover {
            background: #444;
        }
    </style>
</head>
<body>
    <header>
      
        <p>Welcome to my portfolio!</p>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contacts</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Humphrey Benedict B. Alpuerto, a Computer Engineering specializing in University Of Bohol. I am passionate about coding. I live in Poblacion,Catigbian, Bohol</p>
    </section>
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Coding</li>
            <li>Web Design</li>
            <li>Can do both sports and academic</li>
            
        </ul>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <article>
            <h3>Project Title</h3>
            <p>Short description of the project. <a href="#" class="btn">View Project</a></p>
            <img src="project-image-placeholder.jpg" alt="Project Image">
        </article>
        <article>
            <h3>Project Title</h3>
            <p>Short description of the project. <a href="#" class="btn">View Project</a></p>
            <img src="project-image-placeholder.jpg" alt="Project Image">
        </article>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <p>Feel free to reach out to me via the following:</p>
        <ul>
            <li>Email: <a href="humphrex543216@gmail.com">humphrex543216@gmail.com</a></li>
            <li>Phone: 09814916949</li>
         
        </ul>
    </section>
    <footer>
        <p>&copy; 2025 Alpuerto. All rights reserved.</p>
    </footer>
</body>
</html>
