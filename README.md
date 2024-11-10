<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* Global styles */
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        nav {
            background-color: #333;
            padding: 1rem;
            position: sticky;
            top: 0;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-right: 1rem;
        }

        nav a:hover {
            color: #ddd;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }

        .hero {
            text-align: center;
            padding: 4rem 2rem;
            background-color: #2c3e50;
            color: white;
            margin-bottom: 2rem;
        }

        .project-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
        }

        .project-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.3s ease;
        }

        .project-card:hover {
            transform: translateY(-5px);
        }

        .project-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
        }

        .project-card .content {
            padding: 1.5rem;
        }

        .project-card h3 {
            margin-top: 0;
            color: #2c3e50;
        }

        .btn {
            display: inline-block;
            padding: 0.5rem 1rem;
            background-color: #3498db;
            color: white;
            text-decoration: none;
            border-radius: 4px;
            transition: background-color 0.3s ease;
        }

        .btn:hover {
            background-color: #2980b9;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background-color: #333;
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Home</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="hero">
        <h1>Welcome to My Portfolio</h1>
        <p>Showcasing my journey in web development and design</p>
    </div>

    <div class="container">
        <section id="projects" class="project-grid">
            <!-- Project 1 -->
            <div class="project-card">
                <img src="/api/placeholder/400/320" alt="Weather App Screenshot">
                <div class="content">
                    <h3>Weather Dashboard</h3>
                    <p>A responsive weather dashboard that displays current weather conditions and forecasts for multiple cities. Built with React and OpenWeather API.</p>
                    <a href="projects/weather-app.html" class="btn">Learn More</a>
                </div>
            </div>

            <!-- Project 2 -->
            <div class="project-card">
                <img src="/api/placeholder/400/320" alt="Task Manager Screenshot">
                <div class="content">
                    <h3>Task Manager</h3>
                    <p>A full-stack task management application with user authentication, task categorization, and real-time updates.</p>
                    <a href="projects/task-manager.html" class="btn">Learn More</a>
                </div>
            </div>

            <!-- Project 3 -->
            <div class="project-card">
                <img src="/api/placeholder/400/320" alt="E-commerce Site Screenshot">
                <div class="content">
                    <h3>E-commerce Platform</h3>
                    <p>An online store platform with product catalog, shopping cart, and secure checkout functionality.</p>
                    <a href="projects/ecommerce.html" class="btn">Learn More</a>
                </div>
            </div>

            <!-- Project 4 -->
            <div class="project-card">
                <img src="/api/placeholder/400/320" alt="Recipe App Screenshot">
                <div class="content">
                    <h3>Recipe Finder</h3>
                    <p>A recipe search application that helps users find recipes based on available ingredients and dietary preferences.</p>
                    <a href="projects/recipe-finder.html" class="btn">Learn More</a>
                </div>
            </div>

            <!-- Project 5 -->
            <div class="project-card">
                <img src="/api/placeholder/400/320" alt="Portfolio Site Screenshot">
                <div class="content">
                    <h3>Portfolio Website</h3>
                    <p>A responsive portfolio website built with HTML, CSS, and JavaScript to showcase my web development projects.</p>
                    <a href="projects/portfolio.html" class="btn">Learn More</a>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 My Portfolio. All rights reserved.</p>
    </footer>
</body>
</html>
