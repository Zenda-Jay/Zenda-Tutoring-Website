<!-- ===================== index.html ===================== -->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Zenda Private Tutoring Academy</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header class="navbar">
    <div class="logo">
      <!-- Replace logo.png with your actual logo file -->
      <img src="logo.png" alt="Zenda Academy Logo" />
      <h1>Zenda Private Tutoring Academy</h1>
    </div>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#subjects">Subjects</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="hero">
    <div class="hero-content">
      <!-- Optional hero logo -->
      <img src="logo.png" alt="Academy Logo" class="hero-logo" />
      <h2>Quality Education for a Brighter Future</h2>
      <p>Mobile & Online Tutoring via Microsoft Teams</p>
      <a href="#contact" class="btn">Get Started</a>
    </div>
  </section>

  <section id="about" class="section">
    <h2>About Us</h2>
    <p>
      Zenda Private Tutoring Academy provides experienced teachers who are currently teaching and well qualified in their respective subjects. We focus on helping students achieve academic excellence through personalized tutoring.
    </p>
  </section>

  <section id="subjects" class="section">
    <h2>Subjects Offered</h2>
    <ul>
      <li>Computer Applications Technology</li>
      <li>Mathematics</li>
      <li>Life Sciences</li>
      <li>Physical Sciences</li>
    </ul>
  </section>

  <section id="contact" class="section">
    <h2>Contact Us</h2>
    <p>Phone: +27 81 361 7413</p>
    <p>Email: jtzenda@gmail.com</p>
  </section>

  <footer>
    <p>&copy; 2026 Zenda Private Tutoring Academy</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>


/* ===================== style.css ===================== */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  line-height: 1.6;
}

.navbar {
  background: #0b3d91;
  color: white;
  padding: 15px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo {
  display: flex;
  align-items: center;
  gap: 10px;
}

.logo img {
  height: 40px;
  width: 40px;
  object-fit: contain;
}

.navbar a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

.hero {
  background: linear-gradient(to right, #0b3d91, #1e90ff);
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.hero-logo {
  height: 80px;
  margin-bottom: 20px;
}

.btn {
  display: inline-block;
  margin-top: 20px;
  padding: 10px 20px;
  background: gold;
  color: black;
  text-decoration: none;
  border-radius: 5px;
}

.section {
  padding: 40px 20px;
  text-align: center;
}

ul {
  list-style: none;
  padding: 0;
}

footer {
  background: #0b3d91;
  color: white;
  text-align: center;
  padding: 15px;
}


// ===================== script.js =====================
console.log("Zenda Private Tutoring Academy website loaded");
