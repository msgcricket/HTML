<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Gallery - MSG Cricket Organization</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #0d1b2a;
      color: white;
      margin: 0;
    }

    header {
      background-color: #1b263b;
      padding: 1rem 2rem;
      display: flex;
      align-items: center;
      justify-content: space-between;
    }

    header img {
      height: 60px;
    }

    nav a {
      color: gold;
      margin-left: 20px;
      text-decoration: none;
      font-weight: bold;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 16px;
      padding: 20px;
      background-color: #1e2a38;
    }

    .gallery img {
      width: 100%;
      border-radius: 8px;
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: #1b263b;
      padding: 20px;
      text-align: center;
      color: #ccc;
    }
  </style>
</head>
<body>

<header>
  <img src="logo.png" alt="MSG Logo" />
  <nav>
    <a href="index.html">Home</a>
    <a href="register.html">Register</a>
    <a href="matches.html">Matches</a>
    <a href="gallery.html">Gallery</a>
  </nav>
</header>

<section class="gallery">
  <img src="gallery/ground1.jpg" alt="Cricket Ground 1" />
  <img src="gallery/ground2.jpg" alt="Cricket Ground 2" />
  <img src="gallery/ground3.jpg" alt="Cricket Ground 3" />
  <img src="gallery/ground4.jpg" alt="Cricket Ground 4" />
</section>

<footer>
  &copy; 2025 MSG Cricket Organization<br/>
  📞 9548601919 | 9389087221<br/>
  📧 msgcricketorganization@gmail.com<br/>
  📍 Tajnagari, Agra, Uttar Pradesh, India
</footer>

</body>
</html>
