<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Blazing Nachos</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #fff8e1;
      color: #333;
    }
    header {
      background-color: #e53935;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #ffb300;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://your-image-link.jpg') center/cover no-repeat;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      font-size: 2em;
      font-weight: bold;
      text-shadow: 2px 2px #000;
    }
    .content {
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔥 Blazing Nachos</h1>
    <p>Home of the Spiciest Nachos in Town</p>
  </header>
  <nav>
    <a href="#">Home</a>
    <a href="#">Menu</a>
    <a href="#">About</a>
    <a href="#">Order</a>
  </nav>
  <div class="hero">
    WELCOME TO FLAVOR CITY 🌶️
  </div>
  <div class="content">
    <h2>Why Blazing Nachos?</h2>
    <p>We bring heat, flavor, and crunch to every bite. Come taste what everyone’s raving about.</p>
  </div>
</body>
</html> 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Menu | Blazing Nachos</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background-color: #fffaf0;
      color: #333;
    }
    header {
      background-color: #e53935;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #ffb300;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .menu-section {
      padding: 20px;
    }
    .menu-category {
      margin-top: 30px;
    }
    h2 {
      color: #e53935;
    }
    .menu-item {
      margin: 10px 0;
      border-bottom: 1px solid #ccc;
      padding-bottom: 10px;
    }
    .menu-item h3 {
      margin: 0;
      display: flex;
      justify-content: space-between;
    }
    .menu-item p {
      margin: 5px 0 0 0;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔥 Blazing Nachos</h1>
    <p>Our Full Menu – Made Fresh Daily!</p>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="#">About</a>
    <a href="#">Order</a>
  </nav>

  <div class="menu-section">
    <div class="menu-category">
      <h2>Nachos</h2>
      <div class="menu-item">
        <h3>Classic Cheese Nachos <span>$6.99</span></h3>
        <p>Crispy tortilla chips loaded with melted cheddar cheese.</p>
      </div>
      <div class="menu-item">
        <h3>Blazing Beef Nachos <span>$9.99</span></h3>
        <p>Seasoned ground beef, jalapeños, cheese, and spicy sauce.</p>
      </div>
    </div>

    <div class="menu-category">
      <h2>Tacos</h2>
      <div class="menu-item">
        <h3>Street Tacos (3 pcs) <span>$7.50</span></h3>
        <p>Choose chicken, beef, or veggie. Served with salsa & lime.</p>
      </div>
    </div>

    <div class="menu-category">
      <h2>Sides & Extras</h2>
      <div class="menu-item">
        <h3>Guacamole & Chips <span>$4.50</span></h3>
        <p>Freshly made guac served with crunchy tortilla chips.</p>
      </div>
      <div class="menu-item">
        <h3>Spicy Queso Dip <span>$3.99</span></h3>
        <p>Hot and creamy cheese dip with a kick.</p>
      </div>
    </div>

    <div class="menu-category">
      <h2>Drinks</h2>
      <div class="menu-item">
        <h3>Mexican Cola <span>$2.50</span></h3>
        <p>Authentic glass-bottled cola imported from Mexico.</p>
      </div>
      <div class="menu-item">
        <h3>Frozen Lime Margarita <span>$5.99</span></h3>
        <p>Classic and refreshing (alcoholic – 21+ only).</p>
      </div>
    </div>
  </div>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Order / Contact | Blazing Nachos</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      background-color: #fffaf0;
      color: #333;
    }
    header {
      background-color: #e53935;
      color: white;
      text-align: center;
      padding: 20px;
    }
    nav {
      background-color: #ffb300;
      display: flex;
      justify-content: center;
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      padding: 20px;
    }
    form {
      max-width: 500px;
      margin: 0 auto;
      background-color: #fff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 0 10px #ccc;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    form button {
      margin-top: 15px;
      background-color: #e53935;
      color: white;
      border: none;
      padding: 10px;
      cursor: pointer;
      font-weight: bold;
      border-radius: 5px;
    }
    .contact-info {
      text-align: center;
      margin-top: 30px;
    }
    .map {
      text-align: center;
      margin-top: 30px;
    }
    iframe {
      width: 100%;
      height: 300px;
      border: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>🔥 Blazing Nachos</h1>
    <p>Place an Order or Get in Touch</p>
  </header>

  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="#">About</a>
    <a href="order.html">Order</a>
  </nav>

  <div class="container">
    <form action="https://formspree.io/f/your-form-id" method="POST">
      <h2>Order / Contact Form</h2>
      <input type="text" name="name" placeholder="Your Name" required />
      <input type="email" name="email" placeholder="Your Email" required />
      <input type="text" name="phone" placeholder="Phone Number" />
      <textarea name="message" rows="5" placeholder="What would you like to order or ask?" required></textarea>
      <button type="submit">Send</button>
    </form>

    <div class="contact-info">
      <h3>📍 Location:</h3>
      <p>123 Spicy Ave, Lusaka, Zambia</p>
      <h3>📞 Phone:</h3>
      <p>+260 978 123 456</p>
      <h3>📧 Email:</h3>
      <p>orders@blazingnachos.com</p>
    </div>

    <div class="map">
      <h3>Find Us</h3>
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3918.632960826388!2d28.293756999999998!3d-15.3875254!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x19408cb18aee4b13%3A0x4c9aef982ea9d6c!2sLusaka%2C%20Zambia!5e0!3m2!1sen!2szm!4v1700000000000!5m2!1sen!2szm" 
        allowfullscreen="" 
        loading="lazy">
      </iframe>
    </div>
  </div>
</body>
</html>
C1658C11-1A8E-4A9A-A6B4-EE639BE8FEE9.png
