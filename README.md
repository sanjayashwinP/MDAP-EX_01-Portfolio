# MDAP-EX_01-Portfolio
## Date:11/08/2025

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
### index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjay Ashwin - The Next Level Portfolio</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Montserrat:wght@800&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <nav class="navbar container">
            <a href="index.html" class="logo">Sanjay Ashwin</a>
            <ul class="nav-links">
                <li><a href="index.html" class="nav-item">Home</a></li>
                <li><a href="about.html" class="nav-item">About</a></li>
                <li><a href="portfolio.html" class="nav-item">projects</a></li>
            </ul>
        </nav>
    </header>

    <main class="main-content">
        <section class="hero-section">
            <div class="hero-content">
                <h1>Hello, I'm <span class="name-highlight">Sanjay Ashwin</span>.</h1>
                <h2>  B.E. Computer Science & Engineering student with a passion for creating.</h2>
                <p>I build elegant and efficient digital solutions, from code to concept. Explore my journey and the projects that define my passion for technology.</p>
                <a href="portfolio.html" class="cta-button">See My Projects</a>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Sanjay Ashwin. All Rights Reserved.</p>
    </footer>
</body>
</html>

```
### about.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Sanjay Ashwin</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Montserrat:wght@800&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <nav class="navbar container">
            <a href="index.html" class="logo">Sanjay Ashwin</a>
            <ul class="nav-links">
                <li><a href="index.html" class="nav-item">Home</a></li>
                <li><a href="about.html" class="nav-item">About</a></li>
                <li><a href="portfolio.html" class="nav-item">Projects</a></li>
            </ul>
        </nav>
    </header>

    <main class="main-content">
        <section class="about-section container">
            <div class="about-flex">
                <div class="profile-card">
                    <img src="images\sanjay.jpg" alt="Sanjay Ashwin's photo" class="profile-pic">
                </div>
                <div class="bio-content">
                    <h2>About Me</h2>
                    <p>As a B.E. CSE student, my passion lies in the dynamic intersection of code and creativity. I've built a strong foundation in [mention key areas like data structures, algorithms, and software engineering] and have a keen interest in [mention your specific interests, e.g., Full-Stack Development, Machine Learning, UI/UX]. I am a dedicated problem-solver, driven to learn and grow with every new challenge. My goal is to create impactful and innovative solutions that push the boundaries of what's possible.</p>
                    <a href="path/to/your/resume.pdf" class="cta-button download-button" download>Download Resume</a>
                </div>
            </div>
        </section>

        <section class="skills-section container">
            <h2>Technical Skills</h2>
            <div class="skills-grid">
                <div class="skill-item">HTML5 & CSS3</div>
                <div class="skill-item">JavaScript (ES6+)</div>
                <div class="skill-item">React / Vue.js</div>
                <div class="skill-item">Python</div>
                <div class="skill-item">Node.js & Express</div>
                <div class="skill-item">Databases (SQL, MongoDB)</div>
                <div class="skill-item">Git & GitHub</div>
                <div class="skill-item">Cloud Platforms (AWS, Azure)</div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Sanjay Ashwin. All Rights Reserved.</p>
    </footer>
</body>
</html>
```
### portfolio.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sanjay Ashwin's Projects</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&family=Montserrat:wght@800&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header">
        <nav class="navbar container">
            <a href="index.html" class="logo">Sanjay Ashwin</a>
            <ul class="nav-links">
                <li><a href="index.html" class="nav-item">Home</a></li>
                <li><a href="about.html" class="nav-item">About</a></li>
                <li><a href="portfolio.html" class="nav-item">Projects</a></li>
            </ul>
        </nav>
    </header>

    <main class="main-content">
        <section class="portfolio-section container">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <img src="images\image1.jpeg" alt="E-commerce Platform Project" class="project-image">
                    <div class="project-info">
                        <h3>E-Mart</h3>
                        <p>A full-stack e-commerce site built with the MERN stack, featuring secure authentication and payment integration.</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                </div>

                <div class="project-card">
                    <img src="images\image2.jpg" alt="Machine Learning Project" class="project-image">
                    <div class="project-info">
                        <h3>SmartCrop</h3>
                        <p>An agricultural recommendation system using Python and Scikit-learn for predictive crop analysis.</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                </div>

                <div class="project-card">
                    <img src="images\image3.jpg" alt="Chat Application Project" class="project-image">
                    <div class="project-info">
                        <h3>EchoChat</h3>
                        <p>A real-time, multi-user chat application built with Node.js and Socket.IO for instant messaging.</p>
                        <a href="#" class="project-link">View Project</a>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="footer">
        <p>&copy; 2025 Sanjay Ashwin. All Rights Reserved.</p>
    </footer>
</body>
</html>
```
### style.css
```
:root {
    --primary-color: #1a237e;
    --secondary-color: #c62828;
    --accent-color: #e0e0e0;
    --text-color: #263238;
    --background-color: #fcf8e3;
    --card-background: #ffffff;
}

/* Base Styles & Typography */
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    font-family: 'Poppins', sans-serif;
    background: var(--background-color);
    color: var(--text-color);
    line-height: 1.6;
}

.container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
}

h1, h2, h3 {
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    color: var(--primary-color);
}

/* --- Header & Navigation --- */
.header {
    background-color: var(--card-background);
    padding: 1rem 0;
    border-bottom: 2px solid var(--accent-color);
    position: sticky;
    top: 0;
}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 2rem;
    font-weight: 800;
    color: var(--primary-color);
    text-decoration: none;
}

.nav-links {
    list-style: none;
    display: flex;
    gap: 1.5rem;
}

.nav-item {
    color: var(--text-color);
    text-decoration: none;
    font-weight: 600;
}

.hero-section {
    text-align: center;
    padding: 5rem 2rem;
    background: var(--card-background);
    border-radius: 20px;
    margin: 2rem 0;
}

.hero-section h1 {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.hero-section h2 {
    font-size: 1.5rem;
    color: var(--secondary-color);
    margin-bottom: 1rem;
}

.cta-button {
    display: inline-block;
    background-color: var(--secondary-color);
    color: var(--card-background);
    padding: 0.8rem 2rem;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 700;
}

.about-section {
    margin-top: 3rem;
}

.about-flex {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 2rem;
    background: var(--card-background);
    padding: 2rem;
    border-radius: 15px;
}

.profile-pic {
    width: 250px;
    height: 250px;
    border-radius: 15px;
    object-fit: cover;
}

.bio-content h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.download-button {
    background-color: var(--primary-color);
    color: var(--card-background);
    padding: 0.8rem 2rem;
    border-radius: 50px;
    text-decoration: none;
    display: inline-block;
}
.skills-section {
    margin-top: 3rem;
    text-align: center;
}

.skills-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1rem;
    margin-top: 1rem;
}

.skill-item {
    background-color: var(--primary-color);
    color: var(--card-background);
    padding: 0.6rem 1.5rem;
    border-radius: 50px;
    font-weight: 600;
}

.portfolio-section {
    margin-top: 3rem;
    text-align: center;
}

.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 1.5rem;
}

.project-card {
    background-color: var(--card-background);
    border-radius: 15px;
    border: 1px solid var(--accent-color);
    overflow: hidden;
}

.project-image {
    width: 100%;
    height: 200px;
    object-fit: cover;
}

.project-info {
    padding: 1rem;
    text-align: left;
}

.project-link {
    display: inline-block;
    background-color: var(--secondary-color);
    color: var(--card-background);
    padding: 0.6rem 1.5rem;
    text-decoration: none;
    border-radius: 50px;
    font-weight: 600;
    margin-top: 1rem;
}

.footer {
    text-align: center;
    padding: 2rem 0;
    background-color: var(--primary-color);
    color: var(--card-background);
    margin-top: 3rem;
}


@media (max-width: 768px) {
    .navbar {
        flex-direction: column;
        gap: 1rem;
    }
    .about-flex {
        flex-direction: column;
        text-align: center;
    }
}

```

## OUTPUT
<img width="1918" height="827" alt="image" src="https://github.com/user-attachments/assets/0a947579-b53e-4070-be05-774b26cc73d3" />
<img width="1897" height="901" alt="image" src="https://github.com/user-attachments/assets/cd67a6eb-0926-4cf6-8980-dd5079cd40ba" />
<img width="1908" height="894" alt="image" src="https://github.com/user-attachments/assets/ba7a19e7-7e78-4807-9565-2a771b5522c2" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
