<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name | Colorful Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
:root {
  --grad-1: linear-gradient(135deg, #ff6a00, #ee0979);
  --grad-2: linear-gradient(135deg, #00c6ff, #0072ff);
  --grad-3: linear-gradient(135deg, #7f00ff, #e100ff);
  --bg-dark: #0b1020;
  --glass: rgba(255,255,255,0.1);
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Inter', sans-serif;
}

body {
  background: radial-gradient(circle at top, #1a1f3c, #0b1020);
  color: #fff;
}

/* Header */
header {
  min-height: 100vh;
  background: linear-gradient(120deg, #667eea, #764ba2);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  padding: 40px;
}

header h1 {
  font-size: 4rem;
  background: linear-gradient(90deg, #ffdd00, #ff6a00, #ee0979);
  -webkit-background-clip: text;
  color: transparent;
}

header p {
  font-size: 1.3rem;
  margin-top: 10px;
  opacity: 0.9;
}

nav {
  margin-top: 25px;
}

nav a {
  text-decoration: none;
  color: #fff;
  margin: 0 15px;
  padding: 10px 18px;
  border-radius: 30px;
  background: rgba(255,255,255,0.15);
  transition: 0.3s;
}

nav a:hover {
  background: #fff;
  color: #000;
}

/* Sections */
section {
  padding: 90px 20px;
  max-width: 1200px;
  margin: auto;
}

h2 {
  text-align: center;
  font-size: 2.8rem;
  margin-bottom: 60px;
  background: linear-gradient(90deg, #00c6ff, #7f00ff);
  -webkit-background-clip: text;
  color: transparent;
}

/* About */
.about {
  max-width: 850px;
  margin: auto;
  font-size: 1.1rem;
  text-align: center;
  line-height: 1.9;
  background: var(--glass);
  padding: 40px;
  border-radius: 20px;
  backdrop-filter: blur(15px);
}

/* Cards */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
  gap: 30px;
}

.card {
  padding: 30px;
  border-radius: 22px;
  backdrop-filter: blur(18px);
  background: var(--glass);
  transition: 0.4s;
  position: relative;
  overflow: hidden;
}

.card::before {
  content: "";
  position: absolute;
  inset: 0;
  background: var(--grad-1);
  opacity: 0.25;
  z-index: -1;
}

.card:hover {
  transform: translateY(-15px) scale(1.02);
}

/* Skills */
.skills .card:nth-child(2)::before { background: var(--grad-2); }
.skills .card:nth-child(3)::before { background: var(--grad-3); }

/* Projects */
.projects .card::before { background: linear-gradient(135deg, #ff512f, #dd2476); }

/* Contact */
.contact {
  text-align: center;
  font-size: 1.1rem;
}

.contact a {
  display: inline-block;
  margin: 15px;
  padding: 14px 26px;
  border-radius: 40px;
  background: linear-gradient(135deg, #00c6ff, #7f00ff);
  color: #fff;
  text-decoration: none;
  transition: 0.3s;
}

.contact a:hover {
  transform: scale(1.1);
}

/* Footer */
footer {
  text-align: center;
  padding: 30px;
  background: #050816;
  opacity: 0.9;
}

/* Responsive */
@media (max-width: 768px) {
  header h1 {
    font-size: 2.8rem;
  }
}
</style>
</head>

<body>

<header>
  <h1>Your Name</h1>
  <p>Developer • Designer • Problem Solver</p>
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section id="about">
  <h2>About Me</h2>
  <div class="about">
    I am a passionate developer focused on building visually appealing and
    impactful applications. I enjoy working with modern web technologies,
    AI/ML systems, and creating user-friendly experiences.
  </div>
</section>

<section id="skills">
  <h2>Skills</h2>
  <div class="grid skills">
    <div class="card"><h3>Programming</h3><p>Python, Java, JavaScript</p></div>
    <div class="card"><h3>Web</h3><p>HTML, CSS, React</p></div>
    <div class="card"><h3>AI / ML</h3><p>ML, DL, Data Science</p></div>
    <div class="card"><h3>Tools</h3><p>Git, Docker, Linux</p></div>
  </div>
</section>

<section id="projects">
  <h2>Projects</h2>
  <div class="grid projects">
    <div class="card">
      <h3>Project One</h3>
      <p>Description of your project and key technologies.</p>
    </div>
    <div class="card">
      <h3>Project Two</h3>
      <p>Description of your project and key technologies.</p>
    </div>
    <div class="card">
      <h3>Project Three</h3>
      <p>Description of your project and key technologies.</p>
    </div>
  </div>
</section>

<section id="contact">
  <h2>Contact</h2>
  <div class="contact">
    <p>Email: your.email@example.com</p>
    <a href="#">GitHub</a>
    <a href="#">LinkedIn</a>
    <a href="#">Resume</a>
  </div>
</section>

<footer>
  © 2025 Your Name | Colorful Portfolio
</footer>

</body>
</html>
