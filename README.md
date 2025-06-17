<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>AcademeForge</title>
  <link rel="stylesheet" href="style.css" />
  <script>
    function toggleTheme() {
      document.body.classList.toggle('dark');
      const theme = document.body.classList.contains('dark') ? 'dark' : 'light';
      localStorage.setItem('theme', theme);
    }window.onload = () => {
  const savedTheme = localStorage.getItem('theme');
  if (savedTheme === 'dark') document.body.classList.add('dark');
};

  </script>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
      color: #222;
      transition: background 0.3s, color 0.3s;
    }
    header, footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .container {
      max-width: 1000px;
      margin: auto;
      padding: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      margin: 20px 0;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    .button {
      display: inline-block;
      background: #003366;
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      margin-top: 10px;
    }
    .theme-toggle {
      position: fixed;
      top: 10px;
      right: 10px;
      background: #003366;
      color: white;
      border: none;
      padding: 10px 15px;
      border-radius: 5px;
      cursor: pointer;
      z-index: 999;
    }
    body.dark {
      background: #121212;
      color: #eee;
    }
    body.dark .card {
      background: #1e1e1e;
    }
    body.dark header, body.dark footer, body.dark .theme-toggle {
      background: #000;
    }
  </style>
</head>
<body><button class="theme-toggle" onclick="toggleTheme()">🌓 Theme</button>

<header>
  <h1>AcademeForge</h1>
  <p># Your go-to resource hub for Class 9 & 10 students</p>
</header><div class="container">
  <div class="card">
    <h2>📘 Sample Notes</h2>
    <p>Download sample chapters:</p>
    <ul>
      <li>Class 9 Science – Chapter 1: <a href="#" class="button">Download</a></li>
      <li>Class 10 SST – Important Topics: <a href="#" class="button">Download</a></li>
    </ul>
  </div>  <div class="card">
    <h2>📝 School Purchase (₹500)</h2>
    <p>Schools can purchase full PDF access and distribute among students.</p>
    <a href="#" class="button">Contact via WhatsApp</a>
  </div>  <div class="card">
    <h2>🔥 Weekly Quiz</h2>
    <p>Attempt 5 MCQs each week to test your preparation.</p>
    <a href="quiz.html" class="button">Attempt Quiz</a>
  </div>  <div class="card">
    <h2>📚 Blog</h2>
    <p>Helpful articles for students:</p>
    <ul>
      <li><a href="blog.html"># How to Score 95+ in Class 10</a></li>
      <li><a href="blog.html"># Most Important Questions for Term 1</a></li>
    </ul>
  </div>  <div class="card">
    <h2>🎯 AST 2025</h2>
    <p>Registration for AcademeForge Scholars Test will open soon.</p>
    <a href="ast.html" class="button"># Register for AST</a>
  </div>
</div><footer>
  <p>&copy; 2025 AcademeForge | Empowering Young Minds</p>
</footer></body>
</html>