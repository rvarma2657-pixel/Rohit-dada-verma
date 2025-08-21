<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Rohit Varma - Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f9ff;
      color: #333;
    }
    /* HEADER */
    header {
      background: linear-gradient(to right, #a639a2, #000405);
      color: white;
      text-align: center;
      padding: 60px 20px 40px;
      border-bottom-left-radius: 50px;
      border-bottom-right-radius: 50px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    header img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 4px solid white;
      margin-bottom: 15px;
    }
    header h1 {
      margin: 10px 0 5px;
      font-size: 2.5em;
    }
    header p {
      margin: 5px 0;
      font-size: 1.1em;
    }
    /* SECTION STYLE */
    section {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      border-left: 5px solid #fe4ff8;
      padding-left: 10px;
      color: #4facfe;
      margin-bottom: 15px;
    }
    /* LIST CARDS */
    ul {
      padding-left: 0;
      list-style-type: none;
    }
    ul li {
      background: #fff;
      margin: 10px 0;
      padding: 12px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    ul li:hover {
      transform: scale(1.03);
      background: #eaf6ff;
    }
    /* PROJECT GRID */
    .project-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 15px;
    }
    .project-card {
      background: #fff;
      padding: 15px;
      border-radius: 12px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }
    .project-card:hover {
      transform: translateY(-5px);
      background: #f0faff;
    }
    /* LINKS */
    a {
      color: #0077cc;
      text-decoration: none;
      font-weight: bold;
    }
    a:hover {
      text-decoration: underline;
    }
    /* FOOTER */
    footer {
      text-align: center;
      padding: 20px;
      background: linear-gradient(to right, #011617, #cb20ae);
      color: white;
      border-top-left-radius: 50px;
      border-top-right-radius: 50px;
      margin-top: 40px;
    }
  </style>
</head>
<body>

  <header>
    <!-- You can replace this with your real photo -->
    <img src="PHOTO-2025-08-21-11-22-49.jpg" alt="Profile Picture">
    <h1>Rohit Varma</h1>
    <p><strong>Aspiring Software Developer</strong></p>
    <p><strong>B.Tech in Computer Science & Engineering</strong></p>
  </header>

  <section>
    <h2>About Me</h2>
    <p>
      I am a beginner in software development, learning to build websites and applications. 
      I enjoy solving problems and exploring new technologies. 
      I am also a passionate Computer Science student eager to learn and grow in the field of technology.
    </p>
  </section>

  <section>
    <h2>Skills</h2>
    <ul>
      <li>Basic HTML & CSS</li>
      <li>JavaScript (Beginner)</li>
      <li>Git & GitHub</li>
    </ul>
  </section>

  <section>
    <h2>Education</h2>
    <ul>
      <li>B.Tech in Computer Science & Engineering - Ajeenkya Dy Patil</li>
      <a href="https://www.adypsoe.in/#gsc.tab=0"></a>
      <li>12th Grade - CBSE Board (2022)</li>
    </ul>
  </section>

  <section>
    <h2>Projects</h2>
    <div class="project-grid">
      <div class="project-card">
        <h3>Personal Webpage</h3>
        <p>A simple HTML/CSS site to showcase my work.</p>
      </div>
      <div class="project-card">
        <h3>To-Do List App</h3>
        <p>A basic task manager built with JavaScript.</p>
      </div>
    </div>
  </section>

  <section>
    <h2>Learning Goals</h2>
    <ul>
      <li>Improve my JavaScript skills</li>
      <li>Learn React and build dynamic web applications</li>
      <li>Contribute to open-source projects</li>
    </ul>
  </section>

  <section>
    <h2>Contact</h2>
    <p>Email: <a href="mailto:rvarma2657@gmail.com">rvarma2657@gmail.com</a></p>
    <p>GitHub: <a href="*https://github.com/rvarma2657-pixel*" target="_blank">*https://github.com/rvarma2657-pixel*</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Rohit Varma | Portfolio</p>
  </footer>

</body>
</html>
