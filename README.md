<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Orchard High School</title>
  <link href="https://fonts.googleapis.com/css2?family=Segoe+UI:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: url('background.jpg') no-repeat center center fixed;
      background-size: cover;
      color: #333;
    }
    .top-bar {
      background: #003366;
      color: white;
      text-align: right;
      padding: 10px 20px;
      font-size: 14px;
    }
    .top-bar a {
      color: white;
      margin-left: 15px;
      text-decoration: none;
    }
    header {
      background: rgba(0, 51, 102, 0.9);
      color: white;
      padding: 30px 20px;
      text-align: center;
    }
    header img {
      width: 100px;
      height: auto;
      display: block;
      margin: 0 auto 10px;
      border-radius: 10px;
    }
    nav {
      background: #0066cc;
      padding: 15px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
      transition: 0.3s;
    }
    nav a:hover {
      color: #ffcc00;
    }
    .hero {
      text-align: center;
      padding: 60px 20px;
      background: rgba(255, 255, 255, 0.85);
    }
    .hero h1 {
      color: #003366;
      font-size: 2.5em;
      margin-bottom: 10px;
    }
    .hero p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }
    .hero a {
      padding: 10px 20px;
      background: #ffcc00;
      color: #003366;
      text-decoration: none;
      border-radius: 4px;
      font-weight: bold;
    }
    section {
      background-color: rgba(255, 255, 255, 0.95);
      padding: 40px;
      max-width: 900px;
      margin: 30px auto;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.15);
      border-radius: 10px;
    }
    h2 {
      color: #003366;
      margin-bottom: 15px;
    }
    .features {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }
    .card {
      flex: 1;
      min-width: 250px;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }
    footer {
      background: #003366;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
    .footer-content {
      display: flex;
      justify-content: space-around;
      flex-wrap: wrap;
      margin-bottom: 10px;
    }
    .footer-content div {
      margin: 10px;
    }
  </style>
</head>
<body>
  <div class="top-bar">
    <a href="#">Student Login</a>
    <a href="#">Parent Login</a>
  </div>

  <header>
    <!-- Base64 image inserted below -->
    <img src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAYAAACqaXHeAAABFUlEQVR4nO3QQREAAAQDMO5fNCM+x2aYAwMAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAADgG+6AAXk5p1QAAAAASUVORK5CYII=" alt="Orchard High School Logo" />
    <h1>Orchard High School</h1>
    <p>Nursery to Matric – Located near Shadman Town, Karachi</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#admissions">Admissions</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="hero">
    <h1>Inspire • Learn • Achieve</h1>
    <p>Empowering young minds for a better tomorrow.</p>
    <a href="#admissions">Apply Now</a>
  </div>

  <section id="about">
    <h2>About Us</h2>
    <p>Orchard High School is a reputable institution offering quality education from Nursery to Matric. Our mission is to nurture young minds with values, knowledge, and skills to help them grow into responsible citizens.</p>
  </section>

  <section id="admissions">
    <h2>Admissions</h2>
    <p>Admissions are open for all grades. Please visit our campus near Shadman Town, Karachi, or contact us for more information.</p>
    <div class="features">
      <div class="card">
        <h3>Modern Campus</h3>
        <p>Equipped with science labs, computer rooms, and libraries.</p>
      </div>
      <div class="card">
        <h3>Experienced Faculty</h3>
        <p>Qualified teachers committed to academic excellence.</p>
      </div>
      <div class="card">
        <h3>Holistic Learning</h3>
        <p>We focus on character, academics, and co-curricular activities.</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Us</h2>
    <p><strong>Location:</strong> Near Shadman Town, Karachi</p>
    <p><strong>Phone:</strong> 0300-1234567</p>
    <p><strong>Email:</strong> info@orchardhigh.edu.pk</p>
  </section>

  <footer>
    <div class="footer-content">
      <div>
        <h4>Contact</h4>
        <p>0300‑1234567<br>info@orchardhigh.edu.pk</p>
      </div>
      <div>
        <h4>Address</h4>
        <p>Near Shadman Town, Karachi</p>
      </div>
      <div>
        <h4>Connect</h4>
        <a href="#" style="color: white; text-decoration: underline;">Facebook</a> |
        <a href="#" style="color: white; text-decoration: underline;">Instagram</a>
      </div>
    </div>
    <p>&copy; 2025 Orchard High School. All rights reserved.</p>
  </footer>
</body>
</html>
