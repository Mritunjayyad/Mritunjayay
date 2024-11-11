
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shirt Brand | Find Your Perfect Fit</title>
  <style>
    /* Basic styling for layout */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 20px;
      background-color: #333;
      color: #fff;
    }
    header a {
      color: #fff;
      text-decoration: none;
      margin: 0 10px;
    }
    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }
    nav a {
      padding: 5px 10px;
      font-size: 1em;
    }
    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      background-image: url('hero-image.jpg'); /* Replace with an actual image URL */
      background-size: cover;
      background-position: center;
      height: 70vh;
      color: #fff;
      text-align: center;
      padding: 20px;
    }
    .hero h1 {
      font-size: 2.5em;
      margin: 0;
    }
    .hero p {
      font-size: 1.2em;
      margin: 10px 0;
    }
    .cta-button {
      background-color: #ff6600;
      color: #fff;
      padding: 10px 20px;
      text-decoration: none;
      font-size: 1.2em;
      border-radius: 5px;
      margin-top: 15px;
    }
    .sections {
      padding: 20px;
      text-align: center;
    }
    .section {
      margin: 20px 0;
    }
    .footer {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="logo">ShirtBrand</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#shop">Shop</a>
      <a href="#about">About Us</a>
      <a href="#blog">Blog</a>
      <a href="#contact">Contact Us</a>
      <a href="#cart">Cart (0)</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="hero" id="home">
    <h1>Find Your Perfect Fit</h1>
    <p>Discover the latest styles, designed for comfort and style.</p>
    <a href="#shop" class="cta-button">Shop Now</a>
  </section>

  <!-- Main Content Sections -->
  <div class="sections">

    <!-- Featured Products Section -->
    <div class="section" id="shop">
      <h2>Our Bestsellers</h2>
      <p>Explore our popular shirt collections, handpicked just for you.</p>
      <!-- Add product cards or a gallery of images here -->
    </div>

    <!-- About Us Section -->
    <div class="section" id="about">
      <h2>About Us</h2>
      <p>We believe in quality, comfort, and style. Our shirts are designed to make you look and feel great.</p>
    </div>

    <!-- Blog Section -->
    <div class="section" id="blog">
      <h2>Style Tips & Trends</h2>
      <p>Check out our blog for the latest in fashion and tips on how to wear our shirts.</p>
    </div>

    <!-- Contact Section -->
    <div class="section" id="contact">
      <h2>Get in Touch</h2>
      <p>Questions? We'd love to hear from you! Contact us at info@shirtbrand.com.</p>
    </div>

  </div>

  <!-- Footer -->
  <footer class="footer">
    <p>&copy; 2023 ShirtBrand. All rights reserved.</p>
    <p>Follow us on social media: Facebook | Twitter | Instagram</p>
  </footer>

</body>
</html>

