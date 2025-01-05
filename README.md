<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Janryll | Video Editor Portfolio</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f8f9fa;
            color: #343a40;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            background-color: #343a40;
            padding: 0.5em 1em;
            display: flex;
            justify-content: center;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            max-width: 900px;
            margin: 2em auto;
            padding: 1em;
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #007bff;
            color: white;
            margin-top: 2em;
        }
        .project {
            margin-bottom: 2em;
        }
        .project img {
            width: 100%;
            border-radius: 5px;
        }
        .contact {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact a {
            margin: 0.5em 0;
            text-decoration: none;
            color: #007bff;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Janryll's Video Editing Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Janryll, a passionate video editor with 2 years of experience. I specialize in both short-form and long-form content, creating engaging visuals that captivate audiences. Let's make something amazing together!</p>
    </section>
    <section id="projects">
        <h2>Projects</h2>
        <div class="project">
            <h3>Project Title 1</h3>
            <img src="project1-thumbnail.jpg" alt="Project 1 Thumbnail">
            <p>Description of the project showcasing editing skills.</p>
        </div>
        <div class="project">
            <h3>Project Title 2</h3>
            <img src="project2-thumbnail.jpg" alt="Project 2 Thumbnail">
            <p>Description of the project showcasing editing skills.</p>
        </div>
    </section>
    <section id="contact">
        <h2>Contact</h2>
        <div class="contact">
            <p>Have a project in mind? Let's connect!</p>
            <a href="mailto:janryll@example.com">janryll@example.com</a>
            <a href="https://www.linkedin.com/in/janryll">LinkedIn</a>
            <a href="https://www.behance.net/janryll">Behance</a>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Janryll. All Rights Reserved.</p>
    </footer>
</body>
</html>
