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
            background-color: #f9f9f9; /* Off-white background */
            color: #333; /* Dark text for readability */
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        h1 {
            font-size: 3rem;
            margin: 1em 0;
            color: #2c3e50; /* Slightly darker text for titles */
        }
        p {
            font-size: 1.2rem;
            margin: 0.5em 0;
            color: #444; /* Text color for readability */
        }
        .line {
            width: 50px;
            height: 3px;
            background-color: #ff9800; /* Highlight color for the line */
            margin: 1em auto;
        }
        .contact {
            margin: 1em 0;
            font-size: 1rem;
        }
        .contact a {
            color: #e67e22; /* Link color matching the theme */
            text-decoration: none;
            font-weight: 600;
            margin: 0 10px;
        }
        .contact a:hover {
            text-decoration: underline;
        }
        .experience {
            margin: 2em auto;
            text-align: left;
            width: 80%;
            max-width: 800px;
        }
        .experience h2 {
            font-size: 2rem;
            margin-bottom: 1em;
            color: #2c3e50;
            text-align: center;
        }
        .experience p {
            font-size: 1rem;
            margin: 1em 0;
            line-height: 1.8;
            color: #555;
        }
        .experience strong {
            font-weight: bold;
        }
        .projects {
            margin: 2em auto;
            text-align: left;
            width: 80%;
            max-width: 1200px;
        }
        .projects h2 {
            font-size: 2rem;
            margin-bottom: 1em;
            color: #2c3e50;
            text-align: center;
        }
        .project-container {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: space-between;
        }
        .project-box {
            background: #ffffff; /* Box background */
            padding: 20px;
            width: calc(33% - 20px);
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
            border: 1px solid #ddd; /* Subtle border */
        }
        .project-box h3 {
            font-size: 1.5rem;
            margin-bottom: 10px;
            color: #e67e22;
        }
        .project-box p {
            font-size: 1rem;
            margin: 10px 0;
            line-height: 1.6;
            color: #555;
        }
        .project-box a {
            color: #e67e22;
            text-decoration: none;
            font-weight: 600;
        }
        .project-box a:hover {
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
        <a href="https://github.com/SarangPandit" target="_blank">GitHub: github.com/SarangPandit23</a> |
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
        <div class="project-container">
            <div class="project-box">
                <h3>Goodwill Analytics Dashboard</h3>
                <p>Designed a real-time analytics dashboard to unify donation data and sustainability metrics. Enhanced decision-making for regional donation strategies, leading to a 25% improvement in operational efficiency. Features included Sankey and forecast visualizations for actionable insights.</p>
                <a href="https://github.com/SarangPandit23/Donation-Insights-and-Sustainability-Dashboard-Tactical-Dashboard-" target="_blank">GitHub</a>
            </div>

            <div class="project-box">
                <h3>Instagram Interaction Insights</h3>
                <p>Analyzed Instagram user interaction data to optimize engagement strategies. Delivered actionable insights on influencer types, posting schedules, and content performance. Improved overall engagement by understanding key audience behavior patterns.</p>
                <a href="https://github.com/SarangPandit23/Instagram-_Interaction_Insights_Analysis" target="_blank">GitHub</a>
            </div>

            <div class="project-box">
                <h3>Car Price Prediction System</h3>
                <p>Built a machine learning model to predict car prices based on key features. Improved forecast accuracy by 20% and automated data collection, saving 150+ hours of manual effort. Deployed the solution for real-time price evaluation in the used car market.</p>
                <a href="https://www.jetir.org/view?paper=JETIR2204201" target="_blank">Research Paper</a>
            </div>
        </div>
    </div>
</body>
</html>
