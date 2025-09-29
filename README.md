# portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Karina Sonawane • Portfolio</title>
  <meta name="description" content="Java Full Stack Developer and Web Developer portfolio of Karina Sonawane." />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <div class="container nav">
      <div class="brand">
        <div class="logo" aria-hidden="true">KS</div>
        <a href="#home"><strong>Karina Sonawane</strong></a>
      </div>
      <nav class="nav-links" aria-label="Primary">
        <a href="#projects">Projects</a>
        <a href="#skills">Skills</a>
        <a href="#experience">Experience</a>
        <a href="#education">Education</a>
        <a href="#contact">Contact</a>
        <button class="btn ghost" id="themeToggle" aria-label="Toggle dark mode">Toggle Theme</button>
        <a class="btn" href="https://www.linkedin.com/in/karina-sonawane-7a8bb2317" target="_blank">LinkedIn</a>
      </nav>
      <button class="btn ghost menu-btn" id="menuBtn" aria-label="Open menu">Menu</button>
    </div>
    <nav class="mobile-nav" id="mnav" aria-label="Mobile"></nav>
  </header>

  <main id="home" class="container">
    <!-- Hero Section -->
    <section class="hero">
      <div>
        <span class="chip">Java Full Stack Developer • Web Developer</span>
        <h1>Hi, I'm Karina — I build responsive web apps and intelligent UI.</h1>
        <p class="lead">
          Passionate about crafting modern, accessible interfaces and robust backends. Skilled in
          <strong>Java</strong>, <strong>MySQL/PostgreSQL</strong>, and front-end technologies. Exploring AI
          with Python for real-world problem solving.
        </p>
        <div class="actions">
          <a class="btn" href="#projects">View Projects</a>
          <a class="btn ghost" href="https://github.com/19kari" target="_blank">GitHub</a>
          <a class="btn ghost" href="#contact">Contact</a>
        </div>
        <div class="kbadges" style="margin-top:1rem">
          <span>Open to Work</span>
          <span>Pune, Maharashtra</span>
        </div>
      </div>
      <div class="portrait">
        <img src="img/passport.jpeg" alt="Karina Sonawane"
          style="width:100%;height:100%;border-radius:16px;object-fit:cover;">
      </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="projects">
      <h2>Featured Projects</h2>
      <div class="grid cols-2" style="margin-top:12px">
        <article class="card">
          <div class="p-thumb"><span class="tag">HTML • CSS • JS • API</span></div>
          <div class="p-body">
            <h3>WeatherNow – Real-time Weather Forecast</h3>
            <p class="muted">Responsive app that fetches live weather using OpenWeatherMap API with dynamic display.</p>
            <div class="kbadges"><span>Responsive UI</span><span>REST API</span><span>Clean UX</span></div>
            <div class="p-links">
              <a class="btn" href="https://github.com/19kari" target="_blank">Code</a>
              <a class="btn ghost" href="#" aria-disabled="true">Live Demo</a>
            </div>
          </div>
        </article>
        <article class="card">
          <div class="p-thumb"><span class="tag">Python • Flask • CNN • JS</span></div>
          <div class="p-body">
            <h3>SKIN AI CARE – Intelligent Dermatology</h3>
            <p class="muted">AI-powered tool for early skin disease detection using CNN with a Flask web UI.</p>
            <div class="kbadges"><span>Computer Vision</span><span>Flask</span><span>Data Pipeline</span></div>
            <div class="p-links">
              <a class="btn" href="https://github.com/19kari" target="_blank">Code</a>
              <a class="btn ghost" href="#" aria-disabled="true">Case Study</a>
            </div>
          </div>
        </article>
      </div>
    </section>

    <!-- Skills -->
    <section id="skills" class="skills">
      <h2>Skills</h2>
      <div class="grid cols-3" style="margin-top:12px">
        <div class="card">
          <h3>Languages & Core</h3>
          <ul>
            <li>Java</li>
            <li>Python (AI basics)</li>
            <li>JavaScript</li>
            <li>HTML5</li>
            <li>CSS3</li>
          </ul>
        </div>
        <div class="card">
          <h3>Frameworks & Tools</h3>
          <ul>
            <li>JDBC</li>
            <li>Flask</li>
            <li>Git</li>
            <li>VS Code</li>
            <li>Eclipse</li>
          </ul>
        </div>
        <div class="card">
          <h3>Databases</h3>
          <ul>
            <li>MySQL</li>
            <li>PostgreSQL</li>
            <li>JSON / REST</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Experience -->
    <section id="experience">
      <h2>Experience</h2>
      <div class="card timeline">
        <div class="t-item">
          <h3>Java Intern — FUEL</h3>
          <p class="muted">Nov 2024 – Dec 2024</p>
          <p>Worked on Core Java, OOPs and connected Java with MySQL via JDBC to build small apps.</p>
        </div>
        <div class="t-item">
          <h3>Web Development Intern — Prodigy Infotech</h3>
          <p class="muted">Sep 2022 – Oct 2022</p>
          <p>Completed hands-on internship building responsive pages and improving front-end skills.</p>
        </div>
      </div>
    </section>

    <!-- Education -->
    <section id="education">
      <h2>Education</h2>
      <div class="grid cols-2" style="margin-top:12px">
        <div class="card">
          <h3>B.E. in Computer Science</h3>
          <p class="muted">KCES’s College of Engineering & Management, Jalgaon — 2021–2025 (Pursuing)</p>
        </div>
        <div class="card">
          <h3>Diploma in IT</h3>
          <p class="muted">Government Polytechnic, Murtizapur — 2020–2023 (80.50%)</p>
        </div>
      </div>
    </section>

    <!-- Contact -->
    <section id="contact">
      <h2>Contact</h2>
      <div class="grid cols-2" style="margin-top:12px">
        <div class="card">
          <h3>Get in touch</h3>
          <p class="muted">I’m open to internships and full-time roles in web development and Java. Reach me on LinkedIn or email.</p>
          <div class="kbadges">
            <a class="btn" href="https://www.linkedin.com/in/karina-sonawane-7a8bb2317" target="_blank">Message on LinkedIn</a>
            <a class="btn ghost" href="https://github.com/19kari" target="_blank">GitHub</a>
          </div>
          <p class="muted" style="margin-top:.8rem">Email: <a href="mailto:karinasonawane61@gmail.com">karinasonawane61@gmail.com</a></p>
        </div>
        <form class="card" id="contactForm" onsubmit="return sendMail(event)">
          <h3>Quick message</h3>
          <label class="muted" for="name">Name</label>
          <input id="name" required placeholder="Your name" />
          <label class="muted" for="email">Email</label>
          <input id="email" type="email" required placeholder="you@example.com" />
          <label class="muted" for="msg">Message</label>
          <textarea id="msg" rows="4" required placeholder="Hello Karina, we’d like to talk about ..."></textarea>
          <button class="btn" type="submit">Send</button>
        </form>
      </div>
    </section>
  </main>

  <footer>
    <div class="container" style="display:flex;justify-content:space-between;gap:1rem;flex-wrap:wrap">
      <span>© <span id="year"></span> Karina Sonawane</span>
      <div style="display:flex;gap:.8rem;flex-wrap:wrap">
        <a href="#home">Top</a>
        <a href="https://www.linkedin.com/in/karina-sonawane-7a8bb2317" target="_blank">LinkedIn</a>
        <a href="https://github.com/19kari" target="_blank">GitHub</a>
      </div>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>
