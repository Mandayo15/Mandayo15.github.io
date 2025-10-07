<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Andrea Joyce | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Dancing+Script:wght@600&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #ffe6eb, #fffafc);
      color: #333;
      overflow-x: hidden;
    }

    header {
      text-align: center;
      padding: 80px 20px;
      background: linear-gradient(135deg, #ffb6c1, #ffd6d6);
      color: #fff;
      position: relative;
      overflow: hidden;
      box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    }

    header::after {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(255, 255, 255, 0.15);
      z-index: 0;
    }

    header img {
      width: 160px;
      height: 160px;
      border-radius: 50%;
      border: 5px solid #fff;
      box-shadow: 0 4px 15px rgba(0,0,0,0.3);
      position: relative;
      z-index: 1;
      animation: float 3s ease-in-out infinite;
    }

    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
    }

    header h1 {
      margin-top: 25px;
      font-family: 'Dancing Script', cursive;
      font-size: 3rem;
      position: relative;
      z-index: 1;
      text-shadow: 2px 2px 5px rgba(0,0,0,0.2);
    }

    header p {
      font-size: 1.2rem;
      font-style: italic;
      color: #fff;
      position: relative;
      z-index: 1;
    }

    section {
      max-width: 900px;
      margin: 60px auto;
      background: #ffffffb0;
      backdrop-filter: blur(10px);
      padding: 40px;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
      animation: fadeIn 1.5s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h2 {
      color: #ff6b81;
      font-family: 'Dancing Script', cursive;
      font-size: 2.2rem;
      margin-bottom: 15px;
      text-align: center;
    }

    .about p, .contact p {
      text-align: center;
      font-size: 1.1rem;
      line-height: 1.8;
    }

    .projects {
      text-align: center;
    }

    .project {
      background: #ffeef2;
      border-radius: 15px;
      padding: 20px;
      margin: 25px auto;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .project:hover {
      transform: translateY(-8px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .project h3 {
      color: #ff6b81;
      font-family: 'Dancing Script', cursive;
      font-size: 1.8rem;
      margin-bottom: 8px;
    }

    footer {
      background: #ff6b81;
      color: #fff;
      text-align: center;
      padding: 20px;
      font-size: 0.95rem;
      letter-spacing: 1px;
    }

    a {
      color: #ff6b81;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover {
      color: #d94662;
      text-decoration: underline;
    }

    /* Subtle floating hearts background */
    .hearts {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      overflow: hidden;
      z-index: -1;
      pointer-events: none;
    }

    .hearts span {
      position: absolute;
      display: block;
      width: 20px;
      height: 20px;
      background: rgba(255, 182, 193, 0.3);
      animation: animateHearts 10s linear infinite;
      bottom: -150px;
      transform: rotate(45deg);
    }

    .hearts span:nth-child(1) {
      left: 10%;
      animation-delay: 0s;
    }
    .hearts span:nth-child(2) {
      left: 40%;
      animation-delay: 2s;
      width: 25px;
      height: 25px;
    }
    .hearts span:nth-child(3) {
      left: 70%;
      animation-delay: 4s;
    }

    @keyframes animateHearts {
      0% {
        transform: translateY(0) rotate(45deg);
        opacity: 1;
      }
      100% {
        transform: translateY(-800px) rotate(45deg);
        opacity: 0;
      }
    }
  </style>
</head>

<body>

  <div class="hearts">
    <span></span>
    <span></span>
    <span></span>
  </div>

  <header>
    <img src="a1aeec3e-19c7-4e2c-b842-0a1ae597b667.png" alt="Andrea Joyce">
    <h1>Andrea Joyce</h1>
    <p>Bachelor of Science in Information Technology</p>
  </header>

  <section class="about">
    <h2>About Me</h2>
    <p>Hi! I’m <strong>Andrea Joyce</strong> — an artistic dreamer who finds beauty in simplicity and stories in colors. I love exploring art, creativity, and design while expressing emotions through my work. Every creation I make is a reflection of who I am — passionate, curious, and full of heart.</p>
  </section>

  <section class="contact">
    <h2>Contact Me</h2>
    <p>Let’s collaborate or chat about art, design, and creativity! Reach me at:</p>
    <p>Email: <a href="mailto:mandayoandrea@gmail.com">mandayoandrea@gmail.com</a></p>
  </section>

  <footer>
    <p>© 2025 Andrea Joyce | Designed with ❤️</p>
  </footer>

</body>
</html>
