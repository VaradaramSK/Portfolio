# Ex01 Portfolio
## Date:02/02/2026

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>

    <style>
        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background: linear-gradient(120deg, #f6f9ff, #e9f0ff);
        }

        /* Header */
        .header {
            text-align: center;
            padding: 30px;
            background-color: #2b3cff;
            color: white;
        }

        /* Tabs */
        .tabs {
            display: flex;
            justify-content: center;
            background-color: white;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }

        .tabs button {
            background: none;
            border: none;
            padding: 15px 30px;
            cursor: pointer;
            font-size: 16px;
            transition: 0.3s;
        }

        .tabs button:hover {
            color: #2b3cff;
        }

        .tabs button.active {
            border-bottom: 3px solid #2b3cff;
            color: #2b3cff;
            font-weight: bold;
        }

        /* Content cards */
        .content {
            display: none;
            max-width: 800px;
            margin: 40px auto;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 8px 20px rgba(0,0,0,0.08);
        }

        .content h2 {
            color: #2b3cff;
        }

        .content.active {
            display: block;
        }

        footer {
            text-align: center;
            padding: 15px;
            color: #555;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Abisheik Raj</h1>
        <p>Student | AI & Data Science</p>
    </div>

    <div class="tabs">
        <button class="tab-btn active" onclick="openTab('home', this)">Home</button>
        <button class="tab-btn" onclick="openTab('about', this)">About</button>
        <button class="tab-btn" onclick="openTab('contact', this)">Contact</button>
    </div>

    <div id="home" class="content active">
        <h2>Welcome</h2>
        <p>
            Hi! 👋  
            This is my personal portfolio website where I showcase my skills and interests.
        </p>
    </div>

    <div id="about" class="content">
        <h2>About Me</h2>
        <p>
            I am a B.Tech AI & Data Science student.  
            Currently learning programming, data science, and web development.
        </p>
    </div>

    <div id="contact" class="content">
        <h2>Contact</h2>
        <p>Email: abisheikjar@email.com</p>
        <p>LinkedIn: linkedin.com/in/AbisheikRaj</p>
    </div>

    <footer>
        © 2026 My Portfolio
    </footer>

    <script>
        function openTab(tabName, element) {
            let contents = document.getElementsByClassName("content");
            let buttons = document.getElementsByClassName("tab-btn");

            for (let i = 0; i < contents.length; i++) {
                contents[i].classList.remove("active");
                buttons[i].classList.remove("active");
            }

            document.getElementById(tabName).classList.add("active");
            element.classList.add("active");
        }
    </script>

</body>
</html>

```
## OUTPUT
<img width="1908" height="905" alt="about page" src="https://github.com/user-attachments/assets/e061598b-d985-4528-bed0-fcb7cb366f4c" />
<img width="1918" height="870" alt="contact me page" src="https://github.com/user-attachments/assets/d1d57130-029a-4223-ace4-9411162d8e37" />
<img width="1918" height="892" alt="home page" src="https://github.com/user-attachments/assets/6db2c629-46d0-4c54-81bf-1a4d77d25984" />
<img width="1907" height="917" alt="project page" src="https://github.com/user-attachments/assets/1784d3dc-2656-4487-9ce9-b948d9eb4fbf" />
<img width="1907" height="945" alt="skills page" src="https://github.com/user-attachments/assets/66b863fd-2b7a-4030-8309-eaf5db59ad7a" />





## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
