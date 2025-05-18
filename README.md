<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Power Wash Pros</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Power Wash Pros</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="book.html">Book Now</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Professional Power Washing Services</h2>
    <p>Clean homes. Sparkling driveways. Satisfaction guaranteed.</p>
    <a href="book.html" class="btn">Book Now</a>
  </section>

  <footer>
    <p>&copy; 2025 Power Wash Pros. All rights reserved.</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Our Services</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Our Services</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="book.html">Book Now</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <ul>
      <li><strong>House Washing:</strong> $150+</li>
      <li><strong>Driveway Cleaning:</strong> $80+</li>
      <li><strong>Deck & Patio Washing:</strong> $100+</li>
      <li><strong>Commercial Properties:</strong> Contact for quote</li>
    </ul>
  </section>

  <footer>
    <p>&copy; 2025 Power Wash Pros</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Book a Service</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Book a Service</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="book.html">Book Now</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <form>
      <label for="name">Full Name:</label>
      <input type="text" id="name" name="name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required />

      <label for="service">Service:</label>
      <select id="service" name="service">
        <option>House Washing</option>
        <option>Driveway Cleaning</option>
        <option>Deck & Patio Washing</option>
        <option>Commercial Property</option>
      </select>

      <label for="date">Preferred Date:</label>
      <input type="date" id="date" name="date" required />

      <input type="submit" value="Submit Booking" class="btn" />
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Power Wash Pros</p>
  </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Contact Us</title>
  <link rel="stylesheet" href="style.css"/>
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="book.html">Book Now</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="content">
    <p>Email: <a href="mailto:info@powerwashpros.com">info@powerwashpros.com</a></p>
    <p>Phone: (555) 123-4567</p>
    <form>
      <label for="msg-name">Name:</label>
      <input type="text" id="msg-name" required />

      <label for="msg">Message:</label>
      <textarea id="msg" rows="4" required></textarea>

      <input type="submit" value="Send Message" class="btn"/>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Power Wash Pros</p>
  </footer>
</body>
</html>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  line-height: 1.6;
  background: #f4f4f4;
}

header {
  background: #1c87c9;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 10px;
  text-decoration: none;
}

.hero {
  background: url('https://source.unsplash.com/1600x400/?power-wash') no-repeat center center/cover;
  color: white;
  padding: 100px 20px;
  text-align: center;
}

.content {
  padding: 20px;
  background: white;
  max-width: 800px;
  margin: auto;
}

form input, form select, form textarea {
  display: block;
  width: 100%;
  padding: 10px;
  margin-bottom: 15px;
}

.btn {
  background: #1c87c9;
  color: white;
  border: none;
  padding: 10px 20px;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  background: #333;
  color: white;
  margin-top: 20px;
}
