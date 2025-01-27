<!DOCTYPE html>
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
            background: linear-gradient(135deg, #1E1E2C, #444);
            color: white;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        h1 {
            font-size: 3rem;
            margin: 1em 0 0.5em;
        }
        p {
            font-size: 1.2rem;
            margin: 0.5em 0;
        }
        .line {
            width: 50px;
            height: 3px;
            background-color: #FFD700;
            margin: 1em auto;
        }
        .contact {
            margin: 1em 0;
            font-size: 1rem;
        }
        .contact a {
            color: #FFD700;
            text-decoration: none;
            font-weight: 600;
            margin: 0 10px;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        .experience, .projects {
            margin: 2em auto;
            text-align: left;
            width: 80%;
            max-width: 800px;
        }
        .experience h2, .projects h2 {
            font-size: 2rem;
            margin-bottom: 1em;
            color: #FFD700;
            text-align: center;
        }
        .experience p, .projects p {
            font-size: 1rem;
            margin: 1em 0;
            line-height: 1.8;
        }
        .experience strong, .projects strong {
            font-weight: bold;
        }
        .projects a {
            color: #FFD700;
            text-decoration: none;
            font-weight: 600;
        }
        .projects a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <h1>HI! I'M SARANG PANDIT</h1>
    <div class="line"></div>
    <p>Master's in Information Technology | Data Analyst</p>
    <p>Analyzing and visualizing data to drive smarter, informed business decisions.</p>

    <div class="contact">
        <a href="mailto:spandit1@wpi.edu">Email: spandit1@wpi.edu</a> |
        <a href="https://github.com/SarangPandit" target="_blank">GitHub: github.com/SarangPandit</a> |
        <a href="https://linkedin.com/in/sarang-pandit" target="_blank">LinkedIn: linkedin.com/in/sarang-pandit</a>
    </div>

    <div class="experience">
        <h2>Experience</h2>
        <p><strong>TCS Experience</strong></p>
        <p>At <strong>Tata Consultancy Services</strong>, I worked as a Data Analyst, leading the development of a robust ETL pipeline to process over 100,000 records with near-zero errors, significantly enhancing decision-making accuracy. I designed and implemented 14+ interactive dashboards in Tableau and Power BI, delivering real-time insights that contributed to measurable revenue growth. By optimizing SQL-based reporting systems, I achieved a 40% reduction in query execution times and improved data consistency by 20%. I also automated reporting workflows, reducing manual efforts by 30%, and optimized AWS pipelines for faster data accessibility.</p>

        <p><strong>CISB Experience</strong></p>
        <p>During my internship at <strong>CISB Bureaus Facility Services</strong>, I developed and optimized SQL queries to aggregate and analyze sales data, reducing execution times by 20% for timely decision-making. I conducted exploratory data analysis on large datasets, uncovering patterns that led to a 12% increase in operational efficiency. My role also involved cleaning and organizing raw datasets to ensure accuracy and readiness for advanced analysis.</p>
    </div>

    <div class="projects">
        <h2>Projects</h2>
        <p><strong>Goodwill Analytics Dashboard</strong></p>
        <p>Designed a real-time analytics dashboard to track donation flows and sustainability metrics, improving donation strategies by 25%.</p>
        <p><a href="https://github.com/SarangPandit23/Donation-Insights-and-Sustainability-Dashboard-Tactical-Dashboard-" target="_blank">View Project on GitHub</a></p>

        <p><strong>Instagram Interaction Insights</strong></p>
        <p>Analyzed user interactions to deliver actionable insights, enhancing engagement through optimized social media strategies.</p>
        <p><a href="https://github.com/SarangPandit/Instagram-Interaction-Insights" target="_blank">View Project on GitHub</a></p>

        <p><strong>Car Price Prediction System</strong></p>
        <p>Built a machine learning model to predict car prices, improving forecasting accuracy by 20% and automating data processing.</p>
        <p><a href="https://github.com/SarangPandit/Car-Price-Prediction" target="_blank">View Project on GitHub</a></p>
    </div>
</body>
</html>
