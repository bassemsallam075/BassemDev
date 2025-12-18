# BassemDev
Discipline-driven Lead Web Developer Portfolio showcasing high-performance, scalable web projects, clean code, and leadership skills.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bassem Sallam | Lead Web Developer</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
<style>
/* Base Reset */
* { margin:0; padding:0; box-sizing:border-box; font-family: 'Inter', sans-serif; }
body { background:#f5f5f5; color:#111; transition: background 0.3s, color 0.3s; }
a { text-decoration:none; color:#0070f3; }
h1,h2,h3 { margin-bottom:10px; }
section { padding:60px 20px; max-width:1000px; margin:0 auto; }

/* Navbar */
nav { position:fixed; top:0; width:100%; background:#111; color:#fff; display:flex; justify-content:space-between; padding:15px 30px; z-index:1000; }
nav a { color:#fff; margin-left:20px; transition:0.3s; }
nav a:hover { color:#0070f3; }
.toggle-btn { cursor:pointer; padding:5px 10px; border:1px solid #fff; border-radius:5px; }

/* Header */
header { text-align:center; padding:150px 20px 80px; }
header h1 { font-size:3rem; color:#111; }
header p { font-size:1.2rem; margin-top:10px; }
.btn { display:inline-block; padding:10px 20px; background:#0070f3; color:#fff; border-radius:8px; margin-top:10px; transition:0.3s; }
.btn:hover { background:#005bb5; }

/* Projects */
.projects { display:grid; grid-template-columns: repeat(auto-fit,minmax(280px,1fr)); gap:20px; }
.project-card { background:#fff; padding:20px; border-radius:12px; box-shadow:0 5px 20px rgba(0,0,0,0.1); transition:0.5s; opacity:0; transform: translateY(50px); }
.project-card img { width:100%; border-radius:10px; margin-bottom:15px; }
.project-card.visible { opacity:1; transform: translateY(0); }

/* Skills */
.skills ul { list-style:none; display:grid; grid-template-columns: repeat(auto-fit,minmax(200px,1fr)); gap:15px; }
.skills li { background:#0070f3; color:#fff; padding:10px; border-radius:8px; text-align:center; position:relative; overflow:hidden; }
.skills li span { display:block; height:100%; width:0; background:#005bb5; position:absolute; top:0; left:0; z-index:0; transition:0.7s; }
.skills li p { position:relative; z-index:1; }

/* Contact */
.contact p { margin-bottom:10px; }

/* Footer */
footer { text-align:center; padding:20px; background:#111; color:#fff; margin-top:50px; }

/* Dark Mode Styles */
body.dark-mode { background:#111; color:#f5f5f5; }
body.dark-mode .project-card { background:#222; box-shadow:0 5px 20px rgba(255,255,255,0.05); }
body.dark-mode .skills li { background:#444; }
</style>
</head>
<body>

<!-- Navbar -->
<nav>
  <div>Bassem Sallam</div>
  <div>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
    <span class="toggle-btn" onclick="toggleDarkMode()">🌙</span>
  </div>
</nav>

<!-- Header -->
<header>
  <h1>Bassem Sallam</h1>
  <p>Discipline-driven Lead Web Developer delivering scalable, high-performance web solutions.<br>
  Daily Rate: £300/day</p>
  <a class="btn" href="#contact">Contact Me</a>
</header>

<!-- Projects -->
<section id="projects">
  <h2>Projects</h2>
  <div class="projects">
    <div class="project-card">
      <img src="https://via.placeholder.com/400x200.png?text=Project+1" alt="Project 1">
      <h3>Project One</h3>
      <p>React, Node.js, MongoDB. Responsive, high-performance, and scalable.</p>
      <a href="https://github.com/BassemLeadDev/project1" target="_blank">View Code</a> | 
      <a href="#" target="_blank">Live Demo</a>
    </div>

    <div class="project-card">
      <img src="https://via.placeholder.com/400x200.png?text=Project+2" alt="Project 2">
      <h3>Project Two</h3>
      <p>Enterprise web app with clean architecture & CI/CD setup.</p>
      <a href="https://github.com/BassemLeadDev/project2" target="_blank">View Code</a> | 
      <a href="#" target="_blank">Live Demo</a>
    </div>

    <div class="project-card">
      <img src="https://via.placeholder.com/400x200.png?text=Project+3" alt="Project 3">
      <h3>Project Three</h3>
      <p>High-performance e-commerce platform with SEO optimization and secure payment integration.</p>
      <a href="https://github.com/BassemLeadDev/project3" target="_blank">View Code</a> | 
      <a href="#" target="_blank">Live Demo</a>
    </div>
  </div>
</section>

<!-- Skills -->
<section id="skills" class="skills">
  <h2>Key Skills</h2>
  <ul>
    <li><p>HTML5, CSS3, JS (ES6+)</p><span style="width:90%"></span></li>
    <li><p>React.js, Vue.js, Node.js</p><span style="width:85%"></span></li>
    <li><p>REST & GraphQL APIs</p><span style="width:80%"></span></li>
    <li><p>MongoDB, MySQL, PostgreSQL</p><span style="width:85%"></span></li>
    <li><p>Scalable Architecture & Clean Code</p><span style="width:95%"></span></li>
    <li><p>CI/CD & Docker</p><span style="width:80%"></span></li>
    <li><p>Code Review & Team Leadership</p><span style="width:90%"></span></li>
    <li><p>Agile & Scrum</p><span style="width:85%"></span></li>
  </ul>
</section>

<!-- Contact -->
<section id="contact" class="contact">
  <h2>Contact Me</h2>
  <p>Email: bassem@example.com</p>
  <p>LinkedIn: <a href="https://linkedin.com/in/BassemLeadDev" target="_blank">BassemLeadDev</a></p>
  <p>GitHub: <a href="https://github.com/BassemLeadDev" target="_blank">BassemLeadDev</a></p>
  <p>Featured Portfolio: <a href="https://github.com/BassemLeadDev" target="_blank">GitHub Portfolio</a></p>
</section>

<!-- Footer -->
<footer>
  <p>© 2025 Bassem Sallam - Lead Web Developer</p>
</footer>

<script>
// Dark Mode Toggle
function toggleDarkMode(){ document.body.classList.toggle('dark-mode'); }

// Smooth Scroll
document.querySelectorAll('nav a').forEach(link=>{
  link.addEventListener('click', e=>{
    e.preventDefault();
    document.querySelector(link.getAttribute('href')).scrollIntoView({behavior:'smooth'});
  });
});

// Scroll Reveal for Projects
const observer = new IntersectionObserver((entries)=>{
  entries.forEach(entry=>{
    if(entry.isIntersecting){
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.2 });

document.querySelectorAll('.project-card').forEach(card=>observer.observe(card));

// Skills Bars Animation
window.addEventListener('scroll', ()=>{
  const skills = document.querySelectorAll('.skills li span');
  skills.forEach(bar=>{
    const top = bar.getBoundingClientRect().top;
    if(top < window.innerHeight - 50){
      bar.style.width = bar.getAttribute('style').split('width:')[1];
    }
  });
});
</script>

</body>
</html>
