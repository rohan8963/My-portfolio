<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
background:#0f172a;
color:white;
}

header{
text-align:center;
padding:40px 20px;
background:#020617;
}

header h1{
font-size:32px;
margin:0;
}

nav{
display:flex;
justify-content:center;
gap:20px;
margin-top:15px;
}

nav a{
color:#38bdf8;
text-decoration:none;
font-weight:bold;
}

section{
padding:40px 20px;
max-width:900px;
margin:auto;
}

.card{
background:#1e293b;
padding:20px;
border-radius:10px;
margin-top:20px;
}

.skills span{
display:inline-block;
background:#38bdf8;
color:black;
padding:6px 12px;
margin:5px;
border-radius:20px;
font-size:14px;
}

.project{
background:#334155;
padding:15px;
border-radius:8px;
margin-top:10px;
}

footer{
text-align:center;
padding:20px;
background:#020617;
font-size:14px;
}

button{
padding:10px 20px;
border:none;
background:#38bdf8;
border-radius:5px;
cursor:pointer;
}

</style>
</head>

<body>

<header>
<h1>Rohan</h1>
<p>Web Developer | Student</p>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section id="about">
<h2>About Me</h2>
<div class="card">
<p>Hello! I'm Rohan. I am learning web development and enjoy creating websites and creative projects.</p>
</div>
</section>

<section id="skills">
<h2>Skills</h2>
<div class="card skills">
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<span>Git</span>
</div>
</section>

<section id="projects">
<h2>Projects</h2>

<div class="project">
<h3>Galaxy Animation</h3>
<p>A space animation made using HTML, CSS and JavaScript.</p>
</div>

<div class="project">
<h3>Portfolio Website</h3>
<p>A responsive personal portfolio website.</p>
</div>

</section>

<section id="contact">
<h2>Contact</h2>
<div class="card">
<p>Email: your@email.com</p>
<p>Instagram: @yourusername</p>

<button onclick="showMessage()">Say Hello</button>
</div>
</section>

<footer>
<p>© 2026 Rohan | My Portfolio</p>
</footer>

<script>

function showMessage(){
alert("Thanks for visiting my portfolio!");
}

</script>

</body>
</html>
