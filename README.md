<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Portfolio</title>

  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #0f172a;
      color: #e5e7eb;
      line-height: 1.6;
    }

    header {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(135deg, #2563eb, #9333ea);
    }

    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }

    header p {
      font-size: 1.2rem;
      opacity: 0.9;
    }

    nav {
      margin-top: 20px;
    }

    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: 500;
    }

    section {
      padding: 70px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h2 {
      text-align: center;
      margin-bottom: 40px;
      font-size: 2.2rem;
      color: #38bdf8;
    }

    .about {
      text-align: center;
      max-width: 800px;
      margin: auto;
    }

    .skills, .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: #1e293b;
      padding: 25px;
      border-radius: 12px;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-8px);
    }

    .card h3 {
      margin-bottom: 10px;
      color: #facc15;
    }

    footer {
      text-align: center;
      padding: 30px;
      background: #020617;
      font-size: 0.9rem;
    }

    .social a {
      color: #38bdf8;
      margin: 0 10px;
      text-decoration: none;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2.2rem;
      }
    }
  </style>
</head>

<body>

  <!-- Header -->
  <header>
    <h1>Your Name</h1>
    <p>Software Developer | AI & ML Enthusiast</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <div class="about">
      <p>
        I am a passionate developer with interests in Artificial Intelligence,
        Machine Learning, and Web Development. I enjoy building impactful
        projects and continuously learning new technologies.
      </p>
    </div>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="card"><h3>Programming</h3><p>Python, Java, JavaScript</p></div>
      <div class="card"><h3>Web</h3><p>HTML, CSS, React</p></div>
      <div class="card"><h3>AI / ML</h3><p>Machine Learning, Deep Learning</p></div>
      <div class="card"><h3>Tools</h3><p>Git, GitHub, Docker</p></div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Project One</h3>
        <p>Short description of your project and technologies used.</p>
      </div>
      <div class="card">
        <h3>Project Two</h3>
        <p>Short description of your project and technologies used.</p>
      </div>
      <div class="card">
        <h3>Project Three</h3>
        <p>Short description of your project and technologies used.</p>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact</h2>
    <div class="about">
      <p>Email: your.email@example.com</p>
      <div class="social">
        <a href="#">GitHub</a> |
        <a href="#">LinkedIn</a> |
        <a href="#">Twitter</a>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    © 2025 Your Name | Built with ❤️
  </footer>

</body>
</html>
