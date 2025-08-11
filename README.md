# MDAP-EX_01-Portfolio
## Date:11.08.2025

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
index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
  
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">
</head>
<body>

   
    <header>
        <div class="container header-content">
            <img src="myphoto.jpg" alt="My Photo" class="profile-pic">
            <div>
                <h1>Jessica Effrosini L</h1>
                <p>Web Developer | Student at Saveetha Engineering College</p>
            </div>
        </div>
    </header>

    
    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <p>
                I am a B.E. Computer Science and Engineering (IoT specialization)💻 student with a keen interest 
                in web application development. My skills include HTML, CSS, and Java, and I enjoy building 
                creative and functional websites. I am passionate about exploring new technologies, 
                learning modern design trends, and enhancing my coding abilities. I love experimenting with 
                innovative ideas, turning concepts into real, working applications. My goal is to continuously
                 improve my skills and create projects that provide value, usability, and an engaging user experience.
            </p>
        </div>
    </section>

  
    <section id="projects">
        <div class="container">
            <h2>My Projects</h2>
            <div class="project-grid">
                <div class="project-card">
                    <h3>Pet Portal Website🐶</h3>
                    <p>“A simple and cute pet adoption website featuring a gallery of cats, dogs, and
                         other animals, designed to connect visitors with their future pets.
                          Overall, it offers a warm and welcoming interface tailored to bring pets and people together.”</p>
                    <h3><a href="https://jessicaeffrosini.github.io/mini-project/#gallery" target="_blank">PetPortal Website</a></h3>
                </div>
                <div class="project-card">
                    <h3>image gallery🍄‍🟫</h3>
                    <p>“An interactive image gallery website that displays photos in a clean, organized layout.
                         Built with HTML, CSS, and JavaScript, it allows users to visually browse and enjoy 
                         high-quality images with a simple, responsive design.”</p>
                    <h3><a href="http://127.0.0.1:5501/igallery/jessica/igapp/static/picture.html" target="_blank">igallery</a></h3>
                </div>
                <div class="project-card">
                    <h3>Restaurant website🍒</h3>
                    <p>“A responsive restaurant web application designed to showcase menu items, special offers,
                         and contact information. Built using HTML, CSS, and JavaScript, it provides a clean and 
                         user-friendly interface for browsing and ordering.”</p>
                    <h3><a href="http://127.0.0.1:5501/restweb/jessica/restapp/static/rest.html" target="_blank">Restaurant website</a></h3>
                </div>
            </div>
        </div>
    </section>

    
    <section id="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>Email: <a href="mailto:jessieffro@gmail.com">jessieffro@gmail.com</a></p>
            <p>Phone: 7358107778</p>
        </div>
    </section>

   
    <footer>
        <p>© 2025 Jessica Effrosini. All Rights Reserved.</p>
    </footer>

</body>
</html>

style.css


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #4f6e78, #4f9cc5);
    color: #f5eded;
    line-height: 1.6;
}


header {
    background: linear-gradient(135deg, #022c3e, #123548);
    color: white;
    padding: 40px 0;
}

.header-content {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 20px;
}

.profile-pic {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    border: 4px solid white;
    object-fit: cover;
}

header h1 {
    font-size: 2.5rem;
}

header p {
    font-size: 1.2rem;
    font-weight: 300;
}


section {
    padding: 50px 20px;
}

.container {
    max-width: 1100px;
    margin: auto;
    text-align: center;
}


#about p {
    max-width: 700px;
    margin: 20px auto;
    font-size: 1.1rem;
}


.project-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-top: 30px;
}

.project-card {
    background: #013145;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(254, 254, 254, 0.1);
    transition: transform 0.3s, box-shadow 0.3s;
}

.project-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 6px 15px rgba(0,0,0,0.15);
}

#contact a {
    color: #0842a8;
    text-decoration: none;
    font-weight: 500;
}

#contact a:hover {
    text-decoration: underline;
}


footer {
    background: #222;
    color: white(188, 35, 35);
    text-align: center;
    padding: 15px 0;
}


@media (max-width: 600px) {
    .header-content {
        flex-direction: column;
        text-align: center;
    }
}
```

## OUTPUT
<img width="1913" height="1088" alt="Screenshot 2025-08-11 175422" src="https://github.com/user-attachments/assets/dc15c3d0-7f1c-4c44-bdbb-ef20d31c5826" />

<img width="1911" height="1091" alt="Screenshot 2025-08-11 175440" src="https://github.com/user-attachments/assets/acc2e9c8-7a9a-4642-a639-3ce067323935" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
