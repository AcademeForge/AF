<html lang="en"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Devraj Kumar | Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }body {
  background: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

nav {
  background: #111;
  color: #fff;
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.15);
}

nav h1 {
  font-size: 1.5rem;
}

nav ul {
  list-style: none;
  display: flex;
  gap: 1.5rem;
}

nav ul li a {
  text-decoration: none;
  color: #fff;
  font-weight: 500;
  transition: color 0.3s ease;
}

nav ul li a:hover {
  color: #00adb5;
}

.container {
  padding: 2rem;
  max-width: 1100px;
  margin: auto;
}

section {
  margin-bottom: 3rem;
  background: #fff;
  padding: 2rem;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.05);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

section:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 30px rgba(0, 0, 0, 0.1);
}

h2 {
  margin-bottom: 1rem;
  color: #222;
}

p {
  margin-bottom: 0.8rem;
}

.video-container {
  display: flex;
  flex-direction: column;
  gap: 1rem;
}

iframe {
  width: 100%;
  height: 300px;
  border-radius: 12px;
  box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
}

.contact {
  background: #222;
  color: #fff;
  padding: 2rem;
  text-align: center;
  border-radius: 12px;
}

.contact p {
  margin: 0.5rem 0;
}

@media (max-width: 768px) {
  nav {
    flex-direction: column;
    align-items: flex-start;
  }

  nav ul {
    flex-direction: column;
    gap: 0.75rem;
    margin-top: 1rem;
  }

  iframe {
    height: 200px;
  }
}

  </style>
</head><body>
  <nav>
    <h1>Devraj Kumar</h1>
    <ul>
      <li><a href="#services">Services</a></li>
      <li><a href="#students">Students</a></li>
      <li><a href="#schools">Schools</a></li>
      <li><a href="#projects">Projects</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>  <div class="container">
    <section>
      <h2>What I Offer</h2>
      <p>Hi, I’m Devraj Kumar — a Class 12 student, educator, and founder of AcademeForge. I bring energy, creativity, and results through my work with students, schools, and local businesses.</p>
    </section><section id="services">
  <h2>Creative Services</h2>
  <p><strong>Video Editing:</strong> Short reels, promos, school videos — edited fast and professionally.</p>
  <p><strong>Photo Editing & Poster Design:</strong> Eye-catching posters, thumbnails, certificates, and digital creatives.</p>
  <p><strong>Content Creation:</strong> From ideas to execution — I help you plan and produce great content for students and marketing.</p>
  <p><strong>Social Media Management:</strong> Build and grow your presence on platforms like Instagram with regular, engaging posts.</p>
</section>

<section id="students">
  <h2>For Students</h2>
  <p><strong>AcademeForge Scholars Test (AST):</strong> Take part in a fun and rewarding competition — win medals, certificates, and scholarships.</p>
  <p><strong>Smart Study Materials:</strong> Free and paid sample papers, handpicked questions, and learning tools.</p>
  <p><strong>Motivation & Strategy:</strong> Learn how to stay consistent, focused, and future-ready.</p>
</section>

<section id="schools">
  <h2>For Schools & Businesses</h2>
  <p><strong>Marketing Support:</strong> I help you reach students and parents with smart social media campaigns.</p>
  <p><strong>Student Events & Engagement:</strong> Olympiads, quizzes, competitions — I manage it all, end-to-end.</p>
  <p><strong>Brand Visibility:</strong> Reels, posters, and promotions that make you stand out locally and online.</p>
</section>

<section id="projects">
  <h2>Project Demos</h2>
  <div class="video-container">
    <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID_1" title="Project Video 1" allowfullscreen></iframe>
    <iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID_2" title="Project Video 2" allowfullscreen></iframe>
  </div>
</section>

<section id="contact" class="contact">
  <h2>Let’s Connect</h2>
  <p>Email: <a href="mailto:devrajkumar.contact@gmail.com" style="color: #00adb5">devrajkumar.contact@gmail.com</a></p>
  <p>Instagram: <a href="https://instagram.com/devrajkumar.in" style="color: #00adb5">@devrajkumar.in</a></p>
</section>

  </div>
</body></html>