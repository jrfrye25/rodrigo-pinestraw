
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rodrigo's Pine Straw</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #333;
    }
    header {
      background: #f97316;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header img {
      max-width: 180px;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      background: #222;
      padding: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('Rod Pic 1.jpg') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-align: center;
      background-blend-mode: darken;
      background-color: rgba(0,0,0,0.4);
    }
    .hero h1 {
      font-size: 42px;
    }
    .section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .card {
      border: 1px solid #ddd;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    .cta {
      background: #16a34a;
      color: white;
      text-align: center;
      padding: 40px 20px;
    }
    .cta a {
      background: white;
      color: #16a34a;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      background: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>

<header>
  <img src="Rodrigo Logo.png" alt="Rodrigo Logo">
  <h1>Rodrigo's Pine Straw</h1>
  <p>We Sell • We Spread • We Produce</p>
</header>

<nav>
  <a href="#services">Services</a>
  <a href="#gallery">Gallery</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <div>
    <h1>Premium Pine Straw & Mulching</h1>
    <p>Serving Apex, Cary & Surrounding Areas</p>
  </div>
</section>

<section class="section" id="services">
  <h2>Our Services</h2>
  <div class="services">
    <div class="card">
      <h3>Pine Straw Installation</h3>
      <p>Fresh, clean, and professionally installed pine straw.</p>
    </div>
    <div class="card">
      <h3>Mulching</h3>
      <p>Enhance your landscape with premium mulch.</p>
    </div>
    <div class="card">
      <h3>Commercial Services</h3>
      <p>Reliable service for businesses and properties.</p>
    </div>
  </div>
</section>

<section class="section" id="gallery">
  <h2>Our Work</h2>
  <div class="gallery">
    <img src="doc/Rod Pic 1.jpg" alt="Work 1">
    <img src="doc/Rod pic 2.jpg" alt="Work 2">
  </div>
</section>

<section class="cta">
  <h2>Call Now for a Free Quote</h2>
  <p>(919) 352-0554</p>
  <a href="tel:19193520554">Call Now</a>
</section>

<section class="section" id="contact">
  <h2>Contact Us</h2>
  <p>Phone: (919) 352-0554</p>
  <p>Email: Rodgonzalez1010@gmail.com</p>
  <p>Service Areas: Apex, Cary, NC & surrounding areas</p>
</section>

<footer>
  <p>© 2026 Rodrigo's Pine Straw</p>
</footer>

</body>
</html>
