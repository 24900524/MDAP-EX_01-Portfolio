# MDAP-EX_01-Portfolio
## Date: 11-08-2025

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
## HTML
```
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>My Portfolio</title>
  <link rel="stylesheet" href="web1.css">
</head>
<body>
  <header>
    <div class="container">
        <img src="me1.jpg" class="abc">
      <h1>Dharshini S N</h1>
      <p>AI & Data Science Student | Student at Saveetha Engineering College</p>
    </div>
  </header>

  <section class="about container">
    <h2>About Me</h2>
    <p> I'm Dharshini S N, a passionate learner and undergraduate student in Artificial Intelligence and Data Science at Saveetha Engineering College. I'm deeply curious about how technology (especially machine learning, data science, and web development) can be used to solve real-world problems. As a learner, I believe in experimenting, collaborating, and improving constantly. I'm currently looking for opportunities like internships where I can grow through practical experience.</p>
  </section>

  <section class="projects container">
    <h2>Projects</h2>
    <div class="project-cards">
      <div class="card">
        <h3>GenAI Chatbot</h3>
        <p>An interactive chatbot clone built using HTML, CSS, and JavaScript.</p>
        <a href="http://127.0.0.1:5500/genaiclone/gen1.html">Visit Chatbox</a>
      </div>
      <div class="card">
        <h3> Simple Calculator</h3>
        <p>This project is a basic calculator built using HTML, CSS, and JavaScript that allows users to perform simple arithmetic operations like addition, subtraction, multiplication, and division.</p>
        <a href="http://127.0.0.1:5500/calculator/calc.html">Visit Simple Calculator</a>
      </div>
      <div class="card">
        <h3>To Do List</h3>
        <p>This project is a To-Do List application built using HTML, CSS, and JavaScript, designed to help users manage daily tasks effectively. Users can add, and delete , making it a simple yet practical productivity tool.</p>
        <a href="http://127.0.0.1:5500/ds1.html">Visit To Do List </a>
      </div>
    </div>
  </section>
  <section class="skill container">
  <h2>> Skills</h2>
  <ul>
    <li>Programming: Python, C , Actively learning Java</li>
    <li>Web: HTML, CSS, JavaScript, React (learning currently)</li>
    <li>Tools: Git, GitHub, VS Code, Jupyter</li>
  </ul>
  </section> 
  
  <section class="certifications container">
  <h2>> Certifications</h2>
  <ul>
    <li>UI/UX & Graphic Design - Simplilearn</li>
    <li>INTRODUCTION TO DATA SCIENCE - Simplilearn</li>
    <li>UX Design for Web Developers - Infosys SpringboardInfosys</li>
  </ul>
</section>

  <section class="contact container">
    <h2>> Contact</h2>
    <p>📧 dharshinisureshhh@email.com</p>
    <h2>> LinkedIn URL</h2>
    <a href="https://www.linkedin.com/in/dharshini--sn/">https://www.linkedin.com/in/dharshini--sn/</a>
    <h2>> GitHub URL</h2>
    <a href="https://github.com/24900524">https://github.com/24900524</a>
  </section>

  <footer>
    <p>© 2025 Dharshini S N</p>
  </footer>
</body>
</html>

```
## CSS
```
body {
  font-family: 'Poppins', sans-serif;
  background: #a10facb6;
  color: #333;
  line-height: 1.6;
}
.abc{
    border-radius: 180px;
    float: left;
    width: 150px;
    margin-bottom: 20px;
}
.container {
  width: 90%;
  max-width: 1000px;
  margin: auto;
  padding: 20px 0;
}
header {
  background: linear-gradient(135deg, #5f11cb 0%, #8d199c61 100%);
  color: rgb(34, 15, 36);
  padding: 50px 0;
  text-align: center;
}
header h1 {
  font-size: 2.5;
}
header p {
  font-size: 1.2;
}

section {
  margin: 40px 0;
}
.about p, .contact p {
  font-size: 1.1rem;
}

.project-cards {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
.card {
  background: white;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
  padding: 20px;
  flex: 1 1 300px;
  transition: transform 0.3s ease;
}
.card:hover {
  transform: translate(5px);
}
.card h3 {
  color: #2575fc;
  margin-bottom: 10px;
}

footer {
  text-align: center;
  padding: 20px;
  background: #222;
  color: white;
}

```
## OUTPUT
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/7121ff66-431d-4180-a591-d8d1787d0e95" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/af4fb436-8dc3-4723-8531-62a3679b8aec" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/fc9963b3-ddc0-41ae-a1a6-05803f04687b" />



## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
