<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jeevan Shrestha | Software Developer & Tech Enthusiast</title>
    <style>
        /* General reset */
        body, h1, h2, h3, p, a, img {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
        }

        /* Page background */
        body {
            background: linear-gradient(135deg, #1f3c70, #4b74c2);
            color: #fff;
            text-align: center;
            padding: 50px 0;
            font-size: 16px;
        }

        /* Main container */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Header Section */
        .header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 50px;
        }

        .header img {
            border-radius: 50%;
            border: 5px solid #fff;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        .header h1 {
            font-size: 48px;
            font-weight: 700;
            color: #fff;
        }

        .header p {
            font-size: 20px;
            color: #ccc;
        }

        /* Contact Section */
        .contact {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-bottom: 40px;
        }

        .contact a {
            text-decoration: none;
            background-color: #e74c3c;
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 16px;
            color: #fff;
            transition: background-color 0.3s ease;
        }

        .contact a:hover {
            background-color: #c0392b;
        }

        /* Tech Stack Section */
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-bottom: 50px;
        }

        .tech-stack img {
            width: 60px;
            height: 60px;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }

        .tech-stack img:hover {
            transform: scale(1.1);
        }

        /* About Section */
        .about {
            margin-bottom: 50px;
        }

        .about h2 {
            font-size: 36px;
            font-weight: 600;
            color: #fff;
            margin-bottom: 20px;
        }

        .about p {
            font-size: 18px;
            line-height: 1.6;
            color: #ddd;
            max-width: 800px;
            margin: 0 auto;
        }

        /* Project Section */
        .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 30px;
            justify-content: center;
            margin-bottom: 50px;
        }

        .project {
            background: #2c3e50;
            border-radius: 10px;
            padding: 30px;
            width: 280px;
            box-shadow: 0 6px 20px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .project:hover {
            transform: translateY(-10px);
        }

        .project h3 {
            font-size: 24px;
            color: #fff;
            margin-bottom: 10px;
        }

        .project p {
            font-size: 16px;
            color: #bdc3c7;
            margin-bottom: 15px;
        }

        .project a {
            text-decoration: none;
            color: #3498db;
            font-weight: bold;
        }

        /* Stats Section */
        .stats {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-bottom: 50px;
        }

        .stat {
            background: #34495e;
            border-radius: 10px;
            padding: 20px;
            width: 250px;
            box-shadow: 0 6px 15px rgba(0, 0, 0, 0.2);
        }

        .stat img {
            max-width: 100%;
            border-radius: 8px;
        }

        /* Footer Section */
        .footer {
            margin-top: 50px;
            color: #ccc;
        }

        .footer a {
            color: #3498db;
            text-decoration: none;
            font-weight: bold;
        }

        .footer a:hover {
            color: #1abc9c;
        }
    </style>
</head>
<body>

<div class="container">
    <!-- Header Section -->
    <div class="header">
        <img src="https://camo.githubusercontent.com/24bc5cbe545b56cc2fcdf707c81cc575eb0071adcc7e5b8630a6a43c82b2817e/68747470733a2f2f6769746875622d726561646d652d73746174732e76657263656c2e6170702f6170693f757365726e616d653d736875657374686a656576616e26636f6c6f723d31323026646f63756d656e743d68776f7265732e676966" alt="Hi There 👋" width="150" height="150">
        <div>
            <h1>Jeevan Shrestha</h1>
            <p>Software Developer | Tech Enthusiast</p>
        </div>
    </div>

    <!-- Contact Section -->
    <div class="contact">
        <a href="mailto:shresthajeevan889@gmail.com">Email Me</a>
        <a href="https://www.linkedin.com/in/shresthajeevan">Connect on LinkedIn</a>
    </div>

    <!-- Tech Stack Section -->
    <div class="tech-stack">
        <img src="https://img.shields.io/badge/Java-blue?style=for-the-badge&logo=java&logoColor=white">
        <img src="https://img.shields.io/badge/Python-blue?style=for-the-badge&logo=python&logoColor=white">
        <img src="https://img.shields.io/badge/HTML5-orange?style=for-the-badge&logo=html5&logoColor=white">
        <img src="https://img.shields.io/badge/CSS3-blue?style=for-the-badge&logo=css3&logoColor=white">
        <img src="https://img.shields.io/badge/React-blue?style=for-the-badge&logo=react&logoColor=white">
        <img src="https://img.shields.io/badge/Docker-blue?style=for-the-badge&logo=docker&logoColor=white">
        <img src="https://img.shields.io/badge/Kubernetes-blue?style=for-the-badge&logo=kubernetes&logoColor=white">
    </div>

    <!-- About Section -->
    <div class="about">
        <h2>About Me</h2>
        <p>I'm a passionate Software Developer and Tech Enthusiast constantly evolving with the tech industry. My focus is on web development, cloud computing, and data-driven solutions. I enjoy solving complex problems and bringing impactful products to life.</p>
        <p>🛠️ I specialize in backend development, cloud architecture, and machine learning.<br>
           🌱 Currently learning more about blockchain technology and Artificial Intelligence.<br>
           👯 I love collaborating on open-source projects and building software solutions that make a difference.</p>
    </div>

    <!-- Projects Section -->
    <div class="projects">
        <div class="project">
            <h3>AI Chatbot</h3>
            <p>An AI-powered chatbot for customer service automation.</p>
            <a href="#">View Demo</a>
        </div>
    </div>

    <!-- Stats Section -->
    <div class="stats">
        <div class="stat">
            <img src="https://github-readme-stats.vercel.app/api?username=shresthajeevan&show_icons=true&theme=radical&hide_title=true&hide_border=true&count_private=true&hide=prs&include_all_commits=true" alt="GitHub Stats">
        </div>
        <div class="stat">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=shresthajeevan&langs_count=10&theme=radical&hide_border=true&count_private=true&layout=compact" alt="Top Languages">
        </div>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>Connect with me on <a href="https://www.linkedin.com/in/shresthajeevan">LinkedIn</a></p>
    </div>
</div>

</body>
</html>
