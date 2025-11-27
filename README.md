<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech Stack README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 40px 20px;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 20px;
            padding: 50px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
        }

        h1 {
            text-align: center;
            color: #2d3748;
            font-size: 3em;
            margin-bottom: 20px;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .subtitle {
            text-align: center;
            color: #718096;
            font-size: 1.2em;
            margin-bottom: 50px;
        }

        .tech-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }

        .tech-card {
            background: white;
            border-radius: 15px;
            padding: 30px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 2px solid transparent;
        }

        .tech-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 40px rgba(0, 0, 0, 0.2);
        }

        .tech-card.cpp {
            border-color: #00599C;
        }

        .tech-card.cpp:hover {
            background: linear-gradient(135deg, #00599C 0%, #004482 100%);
            color: white;
        }

        .tech-card.html {
            border-color: #E34F26;
        }

        .tech-card.html:hover {
            background: linear-gradient(135deg, #E34F26 0%, #C73E1D 100%);
            color: white;
        }

        .tech-card.mysql {
            border-color: #4479A1;
        }

        .tech-card.mysql:hover {
            background: linear-gradient(135deg, #4479A1 0%, #336791 100%);
            color: white;
        }

        .tech-card.sql {
            border-color: #CC2927;
        }

        .tech-card.sql:hover {
            background: linear-gradient(135deg, #CC2927 0%, #A61F1F 100%);
            color: white;
        }

        .tech-card.database {
            border-color: #4DB33D;
        }

        .tech-card.database:hover {
            background: linear-gradient(135deg, #4DB33D 0%, #3A8E2E 100%);
            color: white;
        }

        .tech-card.android {
            border-color: #3DDC84;
        }

        .tech-card.android:hover {
            background: linear-gradient(135deg, #3DDC84 0%, #2DB86A 100%);
            color: white;
        }

        .tech-icon {
            font-size: 3.5em;
            margin-bottom: 20px;
            text-align: center;
        }

        .tech-title {
            font-size: 1.8em;
            font-weight: bold;
            margin-bottom: 15px;
            text-align: center;
        }

        .tech-description {
            font-size: 1em;
            line-height: 1.6;
            color: #4a5568;
            text-align: center;
        }

        .tech-card:hover .tech-description {
            color: rgba(255, 255, 255, 0.95);
        }

        .badge-container {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
            margin-top: 15px;
        }

        .badge {
            background: #edf2f7;
            padding: 5px 12px;
            border-radius: 20px;
            font-size: 0.85em;
            color: #2d3748;
            font-weight: 600;
        }

        .tech-card:hover .badge {
            background: rgba(255, 255, 255, 0.3);
            color: white;
        }

        footer {
            text-align: center;
            margin-top: 50px;
            color: #4a5568;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🚀 Technology Stack</h1>
        <p class="subtitle">Comprehensive overview of our development technologies</p>

        <div class="tech-grid">
            <div class="tech-card cpp">
                <div class="tech-icon">⚙️</div>
                <div class="tech-title">C++</div>
                <div class="tech-description">
                    High-performance programming language for system software, game development, and applications requiring speed and efficiency.
                </div>
                <div class="badge-container">
                    <span class="badge">Performance</span>
                    <span class="badge">OOP</span>
                    <span class="badge">Systems</span>
                </div>
            </div>

            <div class="tech-card html">
                <div class="tech-icon">🌐</div>
                <div class="tech-title">HTML</div>
                <div class="tech-description">
                    Standard markup language for creating web pages and web applications. Foundation of all web content structure.
                </div>
                <div class="badge-container">
                    <span class="badge">Frontend</span>
                    <span class="badge">Web</span>
                    <span class="badge">Markup</span>
                </div>
            </div>

            <div class="tech-card mysql">
                <div class="tech-icon">🐬</div>
                <div class="tech-title">MySQL</div>
                <div class="tech-description">
                    Open-source relational database management system. Popular choice for web applications and data storage solutions.
                </div>
                <div class="badge-container">
                    <span class="badge">RDBMS</span>
                    <span class="badge">Open Source</span>
                    <span class="badge">Scalable</span>
                </div>
            </div>

            <div class="tech-card sql">
                <div class="tech-icon">📊</div>
                <div class="tech-title">SQL</div>
                <div class="tech-description">
                    Structured Query Language for managing and manipulating relational databases. Essential for data operations and queries.
                </div>
                <div class="badge-container">
                    <span class="badge">Queries</span>
                    <span class="badge">Data</span>
                    <span class="badge">Standard</span>
                </div>
            </div>

            <div class="tech-card database">
                <div class="tech-icon">💾</div>
                <div class="tech-title">Database</div>
                <div class="tech-description">
                    Organized collection of structured information stored electronically. Core component for data persistence and management.
                </div>
                <div class="badge-container">
                    <span class="badge">Storage</span>
                    <span class="badge">NoSQL</span>
                    <span class="badge">Relational</span>
                </div>
            </div>

            <div class="tech-card android">
                <div class="tech-icon">🤖</div>
                <div class="tech-title">Android</div>
                <div class="tech-description">
                    Mobile operating system and development platform. Build powerful native applications for billions of devices worldwide.
                </div>
                <div class="badge-container">
                    <span class="badge">Mobile</span>
                    <span class="badge">Kotlin</span>
                    <span class="badge">Java</span>
                </div>
            </div>
        </div>

        <footer>
            <p>💻 Built with passion for technology | Last updated: 2024</p>
        </footer>
    </div>
</body>
</html>
