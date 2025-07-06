<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Sri Ram Academy</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f8f9fa;
      color: #333;
    }
    header {
      background-color: #004AAD;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background: #003B8B;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      padding: 40px 20px;
      background: white;
      margin: 20px auto;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      max-width: 1000px;
    }
    footer {
      text-align: center;
      background: #002D6A;
      color: white;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      max-width: 250px;
      margin: 10px;
      border-radius: 10px;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .team {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .team-member {
      width: 100%;
      max-width: 250px;
      text-align: center;
    }
    .team-member img {
      width: 100%;
      border-radius: 10px;
    }
    @media (max-width: 600px) {
      nav {
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
      }
      nav a {
        margin: 5px 10px;
      }
    }
  </style>
</head>
<body>  <header>
    <h1>Sri Ram Academy</h1>
    <p>Empowering Education for a Better Tomorrow</p>
  </header>  <nav>
    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="admission.html">Admission</a>
    <a href="contact.html">Contact</a>
    <a href="gallery.html">Gallery</a>
    <a href="location.html">Location</a>
  </nav>  <section>
    <h2>Welcome to Sri Ram Academy</h2>
    <p>We are committed to nurturing young minds with value-based education and a joyful learning experience. Explore our vibrant community and enroll your child for a brighter future.</p>
  </section>  <section>
    <h2>Our Team</h2>
    <div class="team">
      <div class="team-member">
        <img src="principal.jpg" alt="Principal">
        <h3>Principal</h3>
        <p>"Education is the most powerful weapon to change the world."</p>
      </div>
      <div class="team-member">
        <img src="teacher1.jpg" alt="Teacher">
        <h3>Mrs. Sharma - Science Teacher</h3>
        <p>"Inspiring curiosity and critical thinking every day."</p>
      </div>
    </div>
  </section>  <footer>
    &copy; 2025 Sri Ram Academy. All Rights Reserved.
  </footer></body>
</html>