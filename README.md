<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarang Pandit's Portfolio</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f2; /* Off-white background */
            color: #333;
        }
        header {
            background-color: #1E1E2C;
            color: white;
            padding: 20px 10px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }
        nav a {
            margin: 0 15px;
            color: #FFD700;
            text-decoration: none;
            font-weight: 600;
        }
        nav a:hover {
            color: #fff;
        }
        section {
            padding: 60px 20px;
        }
        section h2 {
            text-align: center;
            color: #1E1E2C;
        }
        .intro {
            text-align: center;
            background: #FFD700;
            color: #1E1E2C;
            padding: 40px 20px;
            border-radius: 10px;
            margin: 20px;
        }
        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            max-width: 300px;
            transition: transform 0.3s ease;
        }
        .card:hover {
            transform: translateY(-10px);
        }
        .card h3 {
            margin-top: 0;
            color: #1E1E2C;
        }
        footer {
            background-color: #1E1E2C;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        footer a {
            color: #FFD700;
            text-decoration: none;
        }
        footer a:hover {
            color: #fff;
        }
    </style>
</head>
<body>
    <header>
        <h1>Sarang Pandit</h1>
        <p>MS in Information Technology | Data Analyst | Machine Learning Enthusiast</p>
        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>Goodwill Analytics Dashboard</h3>
                <p>Created a real-time dashboard integrating multi-state donation data and sustainability metrics, improving donation strategies by 25%.</p>
                <p><a href="https://github.com/SarangPandit23/Donation-Insights-and-Sustainability-Dashboard-Tactical-Dashboard-" target="_blank">View Project</a></p>
            </div>
            <div class="card">
                <h3>Instagram Insights</h3>
                <p>Analyzed user interactions and engagement strategies to deliver actionable insights for better social media impact.</p>
            </div>
            <div class="card">
                <h3>Car Price Prediction</h3>
                <p>Developed a machine learning model for car price prediction, improving forecast accuracy by 20%.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <div class="intro">
            <h2>About Me</h2>
            <p>I am a passionate Data Analyst with experience in Python, SQL, Tableau, and AWS. With a solid foundation in engineering and a master's degree in Information Technology from WPI, I aim to leverage data to drive impactful insights and solutions. My expertise lies in data visualization, ETL pipelines, and machine learning applications.</p>
        </div>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <div class="skills">
            <div class="card">
                <h3>Programming</h3>
                <p>Python (Pandas, NumPy, Matplotlib), SQL, R, Java</p>
            </div>
            <div class="card">
                <h3>Tools</h3>
                <p>Tableau, Power BI, Databricks, Excel, VBA</p>
            </div>
            <div class="card">
                <h3>Cloud & Databases</h3>
                <p>AWS, Azure, MySQL, SQLite, Spark SQL</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <div class="intro">
            <p>Email: <a href="mailto:spandit1@wpi.edu">spandit1@wpi.edu</a></p>
            <p>GitHub: <a href="https://github.com/SarangPandit" target="_blank">github.com/SarangPandit</a></p>
            <p>LinkedIn: <a href="https://linkedin.com/in/sarang-pandit" target="_blank">linkedin.com/in/sarang-pandit</a></p>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Sarang Pandit | <a href="#">Back to top</a></p>
    </footer>
</body>
</html>
