<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Ishneet Kaur | Technical Portfolio</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<style>
/* Reset */
* { margin:0; padding:0; box-sizing:border-box; }

body {
    font-family: 'Segoe UI', sans-serif;
    background: #0f172a;
    color: #e2e8f0;
    scroll-behavior: smooth;
}

/* Header */
header {
    position: fixed;
    width: 100%;
    background: #111827;
    border-bottom: 3px solid #3b82f6;
    padding: 15px 30px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    z-index: 1000;
}

header h1 {
    color: #3b82f6;
    font-size: 28px;
    text-align: left;
    flex-shrink: 0;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 25px;
}

nav ul li a {
    color: #e2e8f0;
    text-decoration: none;
    font-weight: 500;
}

nav ul li a:hover {
    color: #3b82f6;
}

/* Hamburger */
.hamburger {
    display: none;
    flex-direction: column;
    cursor: pointer;
    gap: 5px;
}

.hamburger div {
    width: 25px;
    height: 3px;
    background: #3b82f6;
}

/* Responsive */
@media(max-width:768px){
    nav ul { 
        display:none; 
        flex-direction: column; 
        background:#111827; 
        position:absolute; 
        top:60px; right:0; 
        width:200px; 
        padding:10px; 
        border-left: 1px solid #3b82f6;
    }
    nav ul.show { display:flex; }
    .hamburger { display:flex; }
}

section {
    padding: 120px 30px 50px 30px; /* header offset */
    width: 85%;
    margin: 0 auto;
}

h2 {
    color: #3b82f6;
    margin-bottom: 20px;
    font-size: 28px;
}

p, li {
    color: #cbd5e1;
    line-height: 1.8;
}

.card {
    background: #1e293b;
    padding: 25px;
    margin-bottom: 25px;
    border-left: 5px solid #3b82f6;
    border-radius: 8px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.4);
}

button {
    padding: 10px 20px;
    background: transparent;
    border: 2px solid #3b82f6;
    color: #3b82f6;
    cursor: pointer;
    border-radius: 5px;
    margin-top: 10px;
    transition:0.3s;
}

button:hover {
    background:#3b82f6;
    color:#0f172a;
}

footer {
    text-align: center;
    padding: 20px;
    border-top:1px solid #334155;
    font-size: 14px;
    color: #94a3b8;
    margin-top: 40px;
}

/* Projects Grid */
.projects-grid {
    display:grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.project-card {
    background:#1e293b;
    padding:20px;
    border-left:4px solid #facc15;
    border-radius:8px;
    box-shadow:0 4px 10px rgba(0,0,0,0.4);
    transition: transform 0.3s;
}

.project-card:hover { transform: translateY(-5px); }

.project-card h3 { color:#facc15; margin-bottom:10px; }
.project-card p { font-size:14px; }

/* Section buttons */
.section-btns { display:flex; gap:15px; margin-bottom:30px; flex-wrap: wrap; }
.section-btns button { border:2px solid #f59e0b; color:#f59e0b; }
.section-btns button:hover { background:#f59e0b; color:#0f172a; }

</style>
</head>
<body>

<header>
    <h1>Ishneet Kaur</h1>
    <nav>
        <ul id="nav-links">
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <div class="hamburger" onclick="toggleNav()">
        <div></div>
        <div></div>
        <div></div>
    </div>
</header>

<section id="about">
    <h2>About Me</h2>
    <div class="section-btns">
        <button>Technical Student</button>
        <button>Cybersecurity Enthusiast</button>
        <button>Programmer</button>
    </div>
    <p>
        I am a BCA student focused on programming, cybersecurity, and technical problem solving. 
        I enjoy learning new technologies, building dynamic projects, and exploring the world of web development and security.
        I recently completed a cybersecurity internship where I analyzed security vulnerabilities and implemented protective measures.
        My goal is to grow as a technical professional and contribute to real-world innovative projects.
    </p>
</section>

<section id="skills">
    <h2>Technical Skills</h2>
    <ul>
        <li>Python Programming</li>
        <li>C Language</li>
        <li>Web Development (HTML, CSS, JavaScript)</li>
        <li>Cybersecurity Practices & Tools</li>
        <li>Video Editing & Canva Designing</li>
    </ul>
</s

