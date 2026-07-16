<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Abhishek Kumar | Full Stack Developer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Poppins,sans-serif;
    scroll-behavior:smooth;
}

body{
    background:#0f172a;
    color:#fff;
}

header{
    position:fixed;
    width:100%;
    top:0;
    background:rgba(15,23,42,.9);
    backdrop-filter:blur(10px);
    z-index:1000;
}

nav{
    width:90%;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 0;
}

.logo{
    font-size:30px;
    font-weight:700;
}

.logo span{
    color:#38bdf8;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:30px;
}

nav a{
    color:white;
    text-decoration:none;
    transition:.3s;
}

nav a:hover{
    color:#38bdf8;
}

section{
    padding:100px 10%;
}

.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    min-height:100vh;
}

.hero h1{
    font-size:50px;
}

.hero h2{
    color:#38bdf8;
    font-size:65px;
}

.hero h3{
    margin:15px 0;
    font-size:30px;
}

.hero p{
    margin:20px 0;
    color:#cbd5e1;
    line-height:1.8;
}

.btn{
    display:inline-block;
    margin-top:20px;
    padding:12px 28px;
    text-decoration:none;
    border-radius:40px;
    background:#38bdf8;
    color:white;
    transition:.3s;
}

.btn:hover{
    transform:translateY(-5px);
    box-shadow:0 0 20px #38bdf8;
}

.hero img{
    width:330px;
    border-radius:50%;
    border:5px solid #38bdf8;
    box-shadow:0 0 40px #38bdf8;
}

.title{
    text-align:center;
    font-size:40px;
    color:#38bdf8;
    margin-bottom:50px;
}

.skills,.projects{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    padding:30px;
    border-radius:15px;
    transition:.3s;
    text-align:center;
}

.card:hover{
    transform:translateY(-10px);
    background:#38bdf8;
}

.project{
    background:#1e293b;
    border-radius:15px;
    padding:25px;
    transition:.3s;
}

.project:hover{
    transform:scale(1.05);
}

.project a{
    color:#38bdf8;
    text-decoration:none;
}

.social{
    text-align:center;
}

.social a{
    color:white;
    font-size:35px;
    margin:15px;
    transition:.3s;
}

.social a:hover{
    color:#38bdf8;
}

footer{
    padding:25px;
    text-align:center;
    background:#111827;
}

@media(max-width:900px){

.hero{
    flex-direction:column-reverse;
    text-align:center;
}

.hero img{
    width:250px;
    margin-bottom:30px;
}

nav ul{
    display:none;
}

.hero h2{
    font-size:45px;
}

}
</style>

</head>
<body>

<header>

<nav>

<div class="logo">
Abhishek<span>.</span>
</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

</header>

<section class="hero" id="home">

<div>

<h1>Hello 👋 I'm</h1>

<h2>Abhishek Kumar</h2>

<h3 id="typing"></h3>

<p>
Full Stack Developer passionate about building fast, secure and modern web applications with beautiful user experiences.
</p>

<a href="#projects" class="btn">View Projects</a>

</div>

<div>

<img src="https://i.pravatar.cc/500" alt="Profile">

</div>

</section>

<section id="about">

<h2 class="title">About Me</h2>

<p style="text-align:center;font-size:18px;line-height:1.8;max-width:900px;margin:auto;color:#cbd5e1;">
I'm a Full Stack Developer specializing in HTML, CSS, JavaScript, React, Node.js, Express, MongoDB and MySQL. I enjoy creating responsive websites, REST APIs, dashboards and scalable web applications.
</p>

</section>

<section id="skills">

<h2 class="title">Skills</h2>

<div class="skills">

<div class="card">HTML5</div>

<div class="card">CSS3</div>

<div class="card">JavaScript</div>

<div class="card">React</div>

<div class="card">Node.js</div>

<div class="card">Express.js</div>

<div class="card">MongoDB</div>

<div class="card">MySQL</div>

<div class="card">Git & GitHub</div>

<div class="card">Python</div>

</div>

</section>

<section id="projects">

<h2 class="title">Projects</h2>

<div class="projects">

<div class="project">
<h3>E-Commerce Website</h3>
<p>Modern shopping website using MERN Stack.</p>
<br>
<a href="#">View GitHub →</a>
</div>

<div class="project">
<h3>Task Manager</h3>
<p>Task management application with authentication.</p>
<br>
<a href="#">View GitHub →</a>
</div>

<div class="project">
<h3>AI Chat App</h3>
<p>AI powered chatbot using OpenAI API.</p>
<br>
<a href="#">View GitHub →</a>
</div>

</div>

</section>

<section id="contact">

<h2 class="title">Connect With Me</h2>

<div class="social">

<a href="#"><i class="fab fa-github"></i></a>

<a href="#"><i class="fab fa-linkedin"></i></a>

<a href="#"><i class="fab fa-instagram"></i></a>

<a href="#"><i class="fas fa-envelope"></i></a>

</div>

</section>

<footer>

© 2026 Abhishek Kumar | Full Stack Developer

</footer>

<script>
const words=[
"Full Stack Developer",
"MERN Stack Developer",
"Frontend Developer",
"Backend Developer",
"Open Source Enthusiast"
];

let i=0;
let j=0;
let deleting=false;

function type(){

let current=words[i];

if(!deleting){

document.getElementById("typing").innerHTML=current.substring(0,j++);

if(j>current.length){

deleting=true;

setTimeout(type,1200);

return;

}

}else{

document.getElementById("typing").innerHTML=current.substring(0,j--);

if(j==0){

deleting=false;

i=(i+1)%words.length;

}

}

setTimeout(type,deleting?50:100);

}

type();
</script>

</body>
</html>
