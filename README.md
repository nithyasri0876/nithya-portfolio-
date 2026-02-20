<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Nithya Sri | Portfolio</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<!-- Icons -->
<link rel="stylesheet"
href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css"/>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(135deg,#0f172a,#1e3a8a);
color:white;
}

/* NAVBAR */
nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 50px;
background:#020617;
position:sticky;
top:0;
z-index:100;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
font-weight:500;
}

nav a:hover{
color:#60a5fa;
}

/* HERO SECTION */
header{
height:90vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
}

header h1{
font-size:3rem;
}

header p{
margin-top:10px;
color:#cbd5e1;
}

/* SECTION */
section{
padding:60px 20px;
text-align:center;
}

.card{
background:white;
color:black;
max-width:700px;
margin:20px auto;
padding:30px;
border-radius:15px;
box-shadow:0 10px 25px rgba(0,0,0,0.3);
transition:0.4s;
}

.card:hover{
transform:translateY(-10px);
}

/* SKILLS */
.skills span{
display:inline-block;
background:#2563eb;
color:white;
padding:8px 15px;
margin:5px;
border-radius:20px;
font-size:14px;
}

/* BUTTON */
button{
background:#2563eb;
color:white;
border:none;
padding:12px 20px;
border-radius:8px;
cursor:pointer;
margin-top:15px;
}

button:hover{
background:#1d4ed8;
}

/* FOOTER */
footer{
padding:20px;
background:#020617;
text-align:center;
margin-top:40px;
}

.icons i{
margin:10px;
font-size:22px;
cursor:pointer;
}

.icons i:hover{
color:#60a5fa;
}

</style>
</head>

<body>

<!-- NAVBAR -->
<nav>
<h2>Nithya Sri</h2>
<div>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</div>
</nav>

<!-- HERO -->
<header>
<h1>Hi, I'm Nithya Sri 👋</h1>
<h2>Aspiring Full Stack Developer | AI Enthusiast
</h2>
<p>I design modern interfaces & build AI-powered applications.</p>
</header>

<!-- ABOUT -->
<section id="about">
<div class="card">
<h2>About Me</h2>
<p>
I am a motivated and adaptable third-year B.Tech Information Technology student with hands-on experience in Python, full-stack web development, and AI-based systems. Having completed three internships across software development, cybersecurity, and digital marketing, I am eager to apply my technical and problem-solving skills in a dynamic organization, and continually learn from industry professionals
</p>
</div>
</section>

<!-- SKILLS -->
<section id="skills">
<div class="card">
<h2>Skills</h2>
<div class="skills">
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<span>React</span>
<span>React Native</span>
<span>Python</span>
<span>FastAPI</span>
<span>java</span>
</div>
</div>
</section>

<!-- PROJECT -->
<section id="projects">
<div class="card">
<h2>Project</h2>
<h3>Multimedia Deepfake Detection System</h3>
<p>
Developed an AI-based system to detect deepfake manipulation in video calls
and phone conversations using multimedia analysis and machine learning techniques

  RecipeBook – Full Stack Web Application
Built a full-stack recipe web app with a FastAPI backend exposing 8+ RESTful API endpoints supporting pagination, filtering, and
sorting.
Developed a responsive JavaScript frontend with live search, cuisine filters, star-rating filter, and sort controls connected to live
API.
Configured CORS middleware for seamless browser-to-backend communication; added real-time API status indicator.
Packaged the full project (frontend + backend) as a deployable ZIP with documentation and requirements file.
  
</p>
</div>
</section>

<!-- RESUME -->
<section>
<div class="card">
<h2>Resume</h2>
<a href="resume.pdf" download>
<button>Download Resume</button>
</a>
</div>
</section>

<!-- CONTACT -->
<section id="contact">
<div class="card">
<h2>Contact</h2>
<p>Email: yourmail@gmail.com</p>
<p>GitHub: github.com/nithyasri0876</p>

<div class="icons">
<i class="fa-brands fa-github"></i>
<i class="fa-brands fa-linkedin"></i>
<i class="fa-solid fa-envelope"></i>
</div>

</div>
</section>

<footer>
<p>© 2026 Nithya Sri | Portfolio</p>
</footer>

</body>
</html>
