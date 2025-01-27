<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarang Pandit's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
        }
        section {
            padding: 40px 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        .projects, .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            flex: 1;
            max-width: 300px;
        }
        .card h3 {
            margin-top: 0;
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

    <section id="about">
        <h2>About Me</h2>
        <p>I am a dedicated Data Analyst with expertise in Python, SQL, Tableau, and AWS. With a strong foundation in engineering and a master's degree in Information Technology from WPI, I am passionate about leveraging data to drive meaningful insights.</p>
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
                <h3>Methodologies</h3>
                <p>SDLC, Agile, Data Visualization, Data Governance</p>
            </div>
        </div>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <div class="projects">
            <div class="card">
                <h3>Goodwill Analytics Dashboard</h3>
                <p>Designed a real-time analytics dashboard to track donation flow and sustainability metrics, improving strategies by 25%.</p>
            </div>
            <div class="card">
                <h3>Instagram Insights</h3>
                <p>Analyzed interactions to deliver actionable insights, enhancing engagement with optimized strategies.</p>
            </div>
            <div class="card">
                <h3>Car Price Prediction</h3>
                <p>Created a machine learning model for car price prediction, improving forecast accuracy by 20%.</p>
            </div>
        </div>
    </section>

    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: <a href="mailto:spandit1@wpi.edu">spandit1@wpi.edu</a></p>
        <p>GitHub: <a href="https://github.com/SarangPandit" target="_blank">github.com/SarangPandit</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/sarang-pandit" target="_blank">linkedin.com/in/sarang-pandit</a></p>
    </section>

    <footer>
        <p>&copy; 2025 Sarang Pandit</p>
    </footer>
</body>
</html>
