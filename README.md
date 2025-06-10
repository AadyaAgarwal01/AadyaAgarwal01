<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Portfolio of Aadya Agarwal - UI/UX Designer" />
  <meta name="author" content="Aadya Agarwal" />
  <title>Aadya Agarwal | UI/UX Designer</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@600&family=Quicksand&display=swap" rel="stylesheet">

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Quicksand', sans-serif;
      background: #fdfdfd;
      color: #222;
      text-align: center;
      padding: 30px 15px;
    }

    h1, h3 {
      font-family: 'Josefin Sans', sans-serif;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 10px;
    }

    h1 span {
      color: #ff66cc;
      display: inline-block;
      animation: fadeIn 2s ease-in-out;
    }

    h3 {
      font-size: 1.5rem;
      color: #00bcd4;
      margin-bottom: 10px;
    }

    img.gif {
      width: 300px;
      margin: 20px auto;
      border-radius: 15px;
      animation: fadeIn 2s ease-in-out;
    }

    p {
      font-size: 1rem;
      margin: 10px 0;
    }

    a {
      color: #ff4b2b;
      text-decoration: none;
    }

    .social-buttons a {
      display: inline-block;
      margin: 10px;
      padding: 10px 20px;
      background: linear-gradient(45deg, #ff4b2b, #ff416c);
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .social-buttons a:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.2);
    }

    .skills {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin: 40px auto;
      max-width: 900px;
    }

    .skills img {
      width: 50px;
      transition: transform 0.3s;
    }

    .skills img:hover {
      transform: scale(1.2);
    }

    .github-section {
      margin-top: 40px;
    }

    .github-section h3 {
      margin-bottom: 20px;
    }

    .github-section img {
      margin: 10px;
      max-width: 100%;
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      h1 { font-size: 2rem; }
      .skills { gap: 15px; }
      .social-buttons a {
        padding: 8px 16px;
        font-size: 14px;
      }
    }
  </style>
</head>
<body>

  <h1>Hi 👋, I'm <span>Aadya Agarwal</span></h1>
  <h3>UI/UX DESIGNER</h3>

  <img src="https://media.tenor.com/IF2JdxzmyN4AAAAj/coding-girl.gif" class="gif" alt="Animated girl coding" />

  <p>🌱 I’m currently learning <strong>JavaScript, React</strong></p>
  <p>📫 Reach me on <a href="https://www.linkedin.com/in/aadya-agarwal-a4780a330/" target="_blank" aria-label="LinkedIn Profile">LinkedIn</a></p>

  <div class="social-buttons">
    <a href="https://instagram.com/iconic_me7" target="_blank" aria-label="Instagram">Instagram</a>
    <a href="https://www.leetcode.com/astromyst" target="_blank" aria-label="LeetCode">LeetCode</a>
  </div>

  <h3>🛠️ Languages & Tools</h3>
  <div class="skills">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="JavaScript" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" alt="Java" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="Python" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="C Language" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="ReactJS" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="NodeJS" />
    <img src="https://www.vectorlogo.zone/logos/tailwindcss/tailwindcss-icon.svg" alt="TailwindCSS" />
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="VueJS" />
  </div>

  <div class="github-section">
    <h3>📊 GitHub Stats</h3>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=aadyaagarwal01&layout=compact&theme=radical" alt="Top Languages on GitHub" />
    <img src="https://github-readme-stats.vercel.app/api?username=aadyaagarwal01&show_icons=true&theme=radical" alt="GitHub Profile Stats" />
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=aadyaagarwal01&theme=radical" alt="GitHub Streak Stats" />
  </div>

</body>
</html>
