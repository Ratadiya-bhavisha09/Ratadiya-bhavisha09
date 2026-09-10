  <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
            line-height: 1.6;
        }

        /* Header & Navigation */
        header {
            background-color: #1f2937;
            color: #fff;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1100px;
            margin: auto;
            padding: 0 2rem;
        }

        nav .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #3b82f6;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 1.5rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #3b82f6;
        }

        /* Hero Section */
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            background: linear-gradient(rgba(31, 41, 55, 0.9), rgba(31, 41, 55, 0.9)), url('https://via.placeholder.com/1500') no-repeat center center/cover;
            color: #fff;
            padding: 0 1rem;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        .hero p {
            font-size: 1.25rem;
            color: #9ca3af;
            margin-bottom: 1.5rem;
        }

        .btn {
            display: inline-block;
            background: #3b82f6;
            color: #fff;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn:hover {
            background: #2563eb;
        }

        /* Sections General */
        section {
            padding: 5rem 2rem;
            max-width: 1100px;
            margin: auto;
        }

        .section-title {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 2rem;
            position: relative;
        }

        .section-title::after {
            content: '';
            width: 50px;
            height: 4px;
            background: #3b82f6;
            display: block;
            margin: 0.5rem auto 0;
            border-radius: 2px;
        }

        /* About Section */
        .about-content {
            text-align: center;
            max-width: 800px;
            margin: auto;
            font-size: 1.1rem;
        }

        /* Skills Section */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1.5rem;
            text-align: center;
        }

        .skill-card {
            background: #fff;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
            font-weight: bold;
        }

        /* Projects Section */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: #fff;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .project-info {
            padding: 1.5rem;
        }

        .project-info h3 {
            margin-bottom: 0.5rem;
        }

        .project-info p {
            color: #6b7280;
            margin-bottom: 1rem;
        }

        /* Contact Section */
        .contact {
            text-align: center;
        }

        .contact p {
            margin-bottom: 1.5rem;
            font-size: 1.1rem;
        }

        /* Footer */
        footer {
            background: #1f2937;
            color: #9ca3af;
            text-align: center;
            padding: 1.5rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <!-- Header / Navbar -->
    <header>
        <nav>
            <div class="logo">MyPortfolio</div>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Hello, I'm Bhavisha</h1>
        <p>Computer Applications Graduate & Aspiring Software Developer</p>
        <a href="#projects" class="btn">View My Work</a>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2 class="section-title">About Me</h2>
        <div class="about-content">
            <p>
                I am a passionate Computer Applications graduate with a strong foundation in software development, web technologies, and database management. I love building practical projects, learning new programming languages, and creating clean, user-friendly applications.
            </p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2 class="section-title">Skills</h2>
        <div class="skills-grid">
            <div class="skill-card">HTML & CSS</div>
            <div class="skill-card">JavaScript</div>
            <div class="skill-card">PHP / Database</div>
            <div class="skill-card">Git & GitHub</div>
            <div class="skill-card">C / C++</div>
            <div class="skill-card">Problem Solving</div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2 class="section-title">Projects</h2>
        <div class="projects-grid">
            
            <!-- Project 1 -->
            <div class="project-card">
                <div class="project-info">
                    <h3>Jewellery Shop Management System</h3>
                    <p>A web-based academic application designed to manage inventory, product listings, and customer transactions efficiently.</p>
                    <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="project-card">
                <div class="project-info">
                    <h3>Personal Portfolio Website</h3>
                    <p>A responsive personal portfolio website built with HTML and CSS to showcase projects, skills, and background.</p>
                    <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank" class="btn">View on GitHub</a>
                </div>
            </div>

        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2 class="section-title">Get In Touch</h2>
        <p>I am currently open to new opportunities and collaborations. Feel free to connect with me!</p>
        <a href="mailto:your-email@example.com" class="btn">Send Email</a>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Bhavisha. All rights reserved.</p>
    </footer>

</body>
</html>
