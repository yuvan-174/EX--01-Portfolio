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
## portfolio.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>

  <header class="site-header">
    <img src="profile-pic.png" alt="Yuvan Sundar S" class="profile-pic" />
    <div class="header-text">
      <h1>Yuvan Sundar S</h1>
      <p>Computer Science Student | Developer | Learner</p>
    </div>
  </header>

  <main>

    <section>
      <h2>About Me</h2>
      <p>
        I am a Computer Science student who is passionate about building real-world technology solutions. I enjoy understanding how systems work internally and applying that knowledge to create efficient and practical applications.
      </p>
      <p>
        My main interests include Artificial Intelligence, Software Development, and Problem Solving. I focus on learning concepts deeply rather than memorizing syntax, which helps me adapt quickly to new technologies.
      </p>
      <p>
        I believe in continuous improvement and exponential growth. I actively build projects to strengthen my understanding and aim to develop solutions that can solve meaningful real-world problems.
      </p>
    </section>

    <section>
      <h2>Profile Snapshot</h2>
      <ul>
        <li>Computer Science Engineering Student</li>
        <li>Focused on Deep Learning and Concept Mastery</li>
        <li>Strong Interest in AI, Software Development, and Problem Solving</li>
        <li>Believes in Rapid Improvement and Continuous Learning</li>
        <li>Hands-on Project Builder</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>
      <ul>
        <li>
          <strong>Deepfake Detection System</strong><br />
          Developed a project that detects AI-generated fake videos or images using machine learning techniques. The system analyzes facial patterns, inconsistencies, and digital artifacts to identify manipulated media.
        </li>
      </ul>
    </section>

    <section>
      <h2>Contact</h2>
      <p>Email: syuvansurya@gmail.com</p>
      <p>GitHub: <a href="https://github.com/yuvan-174">https://github.com/yuvan-174</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/yuvan-sundar-s-843033223/">https://www.linkedin.com/in/yuvan-sundar-s-843033223/</a></p>
    </section>

  </main>
</body>
</html>
```

## style.css
```css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  background: #f4f4f4;
  color: #333;
}

header {
  background: white;
  padding: 20px;
  border-bottom: 1px solid #ddd;
  display: flex;
  align-items: center;
  justify-content: center;  
  
}

.site-header .profile-pic{
  width:120px;
  height:120px;
  border-radius:50%;
  object-fit:cover;
  border:4px solid #fff;
  box-shadow:0 6px 18px rgba(0,0,0,0.12);
}

.header-text{ text-align:left }

main {
  max-width: 800px;
  margin: 40px auto;
  padding: 0 20px;
}

section {
  background: white;
  padding: 20px;
  margin-bottom: 20px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
}

h1, h2 {
  margin-top: 0;
}
```

## OUTPUT

<img width="1048" height="1441" alt="127 0 0 1_5500_portfolio html" src="https://github.com/user-attachments/assets/f0e45b6d-2e0b-4662-8165-ccfc0a027fa4" />


## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
