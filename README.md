<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sumit Kumar | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Arial, sans-serif;
    }

    body {
      background: linear-gradient(to right, #eef2f3, #dfe9f3);
      color: #333;
    }

    header {
      background: linear-gradient(135deg, #1f1f1f, #3a3a3a);
      color: white;
      text-align: center;
      padding: 30px 15px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    header h2 {
      font-size: 28px;
      margin-bottom: 8px;
    }

    header p {
      font-size: 15px;
      color: #ccc;
    }

    nav {
      background: #333;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px;
      position: sticky;
      top: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 15px;
      padding: 5px 10px;
      transition: 0.3s;
      border-radius: 4px;
    }

    nav a:hover {
      background: #555;
    }

    section {
      background: white;
      margin: 20px auto;
      padding: 20px;
      border-radius: 10px;
      max-width: 800px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      animation: fadeIn 0.6s ease;
    }

    section h3 {
      margin-bottom: 10px;
      border-bottom: 2px solid #eee;
      padding-bottom: 5px;
    }

    ul {
      padding-left: 20px;
    }

    ul li {
      margin-bottom: 8px;
    }

    .contact p {
      margin-bottom: 6px;
    }

    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
      font-size: 14px;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(10px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    /* Responsive */
    @media (max-width: 600px) {
      header h2 {
        font-size: 22px;
      }

      nav {
        flex-direction: column;
        gap: 10px;
      }

      section {
        margin: 15px;
      }
    }

  </style>
</head>

<body>

<header>
  <h2>Sumit Kumar</h2>
  <p>Student | Learning Coding Step by Step</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#projects">Projects</a>
  <a href="#contact">Contact</a>
</nav>

<section id="about">
  <h3>About Me</h3>
  <p>
    Hi, I am Sumit Kumar. I recently started learning programming and web development.
    I am still a beginner, but I enjoy building small projects and improving my skills every day.
  </p>
</section>

<section id="projects">
  <h3>Projects</h3>
  <ul>
    <li>Face Recognition Voting System (basic concept)</li>
    <li>Simple Calculator using HTML</li>
    <li>Personal Portfolio Website</li>
  </ul>
</section>

<section id="contact" class="contact">
  <h3>Contact</h3>
  <p>Email: sumitkumar@email.com</p>
  <p>Phone: 9876543210</p>
</section>

<footer>
  <p>© 2026 Sumit Kumar | Built with HTML & CSS</p>
</footer>

</body>
</html>
