<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
 
  
</head>
<body>
    <style>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        scroll-behavior: smooth;
      }
      
        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            background: #f4f4f4;
            color: #333;
      }
      
      header {
        background: #333;
        color: #fff;
        padding: 1rem 0;
      }
      
      nav {
        display: flex;
        justify-content: space-between;
        align-items: center;
        max-width: 1100px;
        margin: auto;
        padding: 0 1rem;
      }
      
      .logo {
        font-size: 1.5rem;
      }
      
      .nav-links {
        list-style: none;
        display: flex;
        gap: 1.5rem;
      }
      
      .nav-links a {
        color: white;
        text-decoration: none;
        font-weight: bold;
      }
      
      .section {
        padding: 4rem 2rem;
        max-width: 1000px;
        margin: auto;
      }
      
      .project-card {
        background: #fff;
        padding: 1rem;
        margin: 1rem 0;
        border-left: 5px solid #3498db;
      }
      
      form {
        display: flex;
        flex-direction: column;
        gap: 1rem;
      }
      
      input, textarea {
        padding: 0.8rem;
        border: 1px solid #ccc;
        border-radius: 5px;
      }
      
      button {
        padding: 0.8rem;
        background: #3498db;
        color: white;
        border: none;
        border-radius: 5px;
        cursor: pointer;
      }
      
      footer {
        background: #222;
        color: white;
        text-align: center;
        padding: 1rem 0;
        margin-top: 2rem;
      }
      </style>
  <header>
    <nav>
      <h1 class="logo">MyPortfolio</h1>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section">
    <h2>Hi, I'm Mohd Rehan</h2>
    <p>Web Developer | student</p>
  </section>

  <section id="about" class="section">
    <h2>About Me</h2>
    <p>I am a passionate web developer with experience in creating responsive and user-friendly websites using HTML, CSS, JavaScript, and frameworks.</p>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project-card">
      <h3>Portfolio Website</h3>
      <p>A personal website to showcase my skills and projects.</p>
    </div>
    <div class="project-card">
      <h3>To-Do App</h3>
      <p>A simple to-do list app with JavaScript for task management.</p>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea placeholder="Your Message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Rehan. All rights reserved.</p>
  </footer>

  <script src="script.js">
  document.querySelector("form").addEventListener("submit", function (e) {
    e.preventDefault();
    alert("Message sent! Thank you for contacting.");
  });
  </script>
</body>
</html>
