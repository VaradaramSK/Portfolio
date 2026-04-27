# Ex01 Portfolio
## Date:27/04/2026

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

## HOME PAGE
```
<!DOCTYPE html>
<html>
<head>
    <title>Home | Harish</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="home">
    <h1>Hello, I'm Varadaram 👋</h1>
    <p>Frontend and Backend developer</p>
    <p>I build simple, clean and user-friendly websites.</p>
</div>

</body>
</html>


```
## ABOUT PAGE
```
<!DOCTYPE html>
<html>
<head>
    <title>About</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>About Me</h1>

    <p>
        I'm a passionate developer who enjoys creating websites that are clean,
        responsive and easy to use.
    </p>

    <p>
        I love learning new technologies and solving real-world problems
        through design and code.I enjoy working on DSA and leetcode problems
    </p>
</div>

</body>
</html>

```
## SKILL PAGE
```
<!DOCTYPE html>
<html>
<head>
    <title>Skills</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>My Skills</h1>

    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">Java</div>
    <div class="skill">C</div>
    <div class="skill">Python</div>
</div>

</body>
</html>

```

## PROJECT PAGE
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact </title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>




<div class="page">
    <h1>My Projects</h1>

    <div class="projects-container">

        <div class="project">
            <h3>Portfolio Website</h3>
            <p>Built a personal portfolio using HTML and CSS with responsive design.</p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>AI Kidney disease prediction system</h3>
            <p>
                AI-powered system that detects early signs of cyst,Kidney stone,
                cancer with the help of deep learning technologies and machine learning 
                techniques.
            </p>
            <a href="#">View Project</a>
        </div>

        <div class="project">
            <h3>To-Do Web App</h3>
            <p>Simple task manager built with JavaScript for daily productivity.</p>
            <a href="#">View Project</a>
        </div>

    </div>
</div>
</body></html>

```
## CONTACT PAGE
```
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<div class="nav">
    <a href="port.html">Home</a>
    <a href="about.html">About</a>
    <a href="skills.html">Skills</a>
    <a href="projects.html">Projects</a>
    <a href="contact.html">Contact</a>
</div>

<div class="page">
    <h1>Contact Me</h1>

    <p>Email: Varadaramsboa@gmail.com</p>
    <p>Phone: +91 9384627657</p>
    <p>LinkedIn: https://www.linkedin.com/in/varadaram-sk-912442290/</p>
</div>

</body>
</html>


```

## STYLE.CSS
```
/*full body */
body {
    margin: 0;
    font-family: "Segoe UI", Arial, sans-serif;
    background: #0f172a;      
    color: white;
}

/* Navbar */
.nav {
    text-align: center;
    padding: 20px;
    background: #111827;
    box-shadow: 0 4px 15px rgba(0,0,0,0.4);
}

.nav a {
    color: #e5e7eb;
    text-decoration: none;
    margin: 0 20px;
    font-size: 17px;
    font-weight: 600;
}

.nav a:hover {
    color: #8b5cf6;   
}

/* port.html */
.home {
    text-align: center;
    padding: 160px 20px;

    background: linear-gradient(135deg, #4f46e5, #7c3aed);
}

.home h1 {
    font-size: 52px;
    margin-bottom: 10px;
}

.home p {
    font-size: 18px;
    opacity: 0.95;
}

/*page */
.page {
    max-width: 1000px;
    margin: 60px auto;
    padding: 60px 30px;

    background: #1e293b;  
    border-radius: 18px;

    box-shadow: 0 15px 40px rgba(0,0,0,0.5);
}

/* skills.html */
.skill {
    display: inline-block;
    padding: 10px 18px;
    margin: 10px;
    border-radius: 25px;

    background: #8b5cf6;
    color: white;
    font-weight: bold;
}

/* Projects.html */
/* ===== GRID LAYOUT ===== */
.projects-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 30px;
    margin-top: 40px;
}

/* ===== CARD ===== */
.project {
    background: #1f2937;
    padding: 25px;
    border-radius: 14px;
    color: white;

    box-shadow: 0 10px 30px rgba(0,0,0,0.5);

    display: flex;
    flex-direction: column;
    justify-content: space-between;
}

/* button */
.project a {
    margin-top: 15px;
    display: inline-block;
    padding: 8px 14px;
    background: #38bdf8;
    color: black;
    border-radius: 6px;
    text-decoration: none;
    font-weight: 600;
}


/* Contact.html */
.contact p {
    margin: 10px 0;
    font-size: 16px;
}

/* Footer */
.footer {
    text-align: center;
    padding: 18px;
    background: #111827;
    margin-top: 40px;
}

/*responsive*/
@media(max-width: 600px){
    .project {
        width: 90%;
    }

    .home h1 {
        font-size: 34px;
    }
}



```
## OUTPUT
<img width="1908" height="905" alt="about page" src="https://github.com/user-attachments/assets/e061598b-d985-4528-bed0-fcb7cb366f4c" />

<img width="1918" height="870" alt="contact me page" src="https://github.com/user-attachments/assets/d1d57130-029a-4223-ace4-9411162d8e37" />

<img width="1918" height="892" alt="home page" src="https://github.com/user-attachments/assets/6db2c629-46d0-4c54-81bf-1a4d77d25984" />

<img width="1907" height="917" alt="project page" src="https://github.com/user-attachments/assets/1784d3dc-2656-4487-9ce9-b948d9eb4fbf" />

<img width="1907" height="945" alt="skills page" src="https://github.com/user-attachments/assets/66b863fd-2b7a-4030-8309-eaf5db59ad7a" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
