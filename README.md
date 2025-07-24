# barbershop
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Classic Cuts Barbershop</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #444;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      text-transform: uppercase;
    }
    nav a:hover {
      background-color: #666;
    }
    .hero {
      background: url('https://images.unsplash.com/photo-1588776814546-0e934e234f3a') no-repeat center center/cover;
      height: 400px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 2px 2px 4px #000;
    }
    .hero h1 {
      font-size: 3em;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .services, .about, .contact, .booking {
      margin-bottom: 40px;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 500px;
      margin-top: 20px;
    }
    form input, form select, form textarea, form button {
      padding: 10px;
      margin: 10px 0;
      font-size: 1em;
    }
    form button {
      background-color: #222;
      color: white;
      border: none;
      cursor: pointer;
    }
    form button:hover {
      background-color: #444;
    }
    footer {
      background-color: #222;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Classic Cuts Barbershop</h1>
    <p>Your style, our scissors.</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
    <a href="#booking">Book Now</a>
  </nav>

  <section class="hero">
    <h1>Welcome to Classic Cuts</h1>
  </section>

  <div class="container">
    <section class="services" id="services">
      <h2>Our Services</h2>
      <ul>
        <li>Men's Haircuts</li>
        <li>Beard Trimming</li>
        <li>Hair Styling</li>
        <li>Hot Towel Shave</li>
        <li>Kids' Cuts</li>
      </ul>
    </section>

    <section class="about" id="about">
      <h2>About Us</h2>
      <p>
        Classic Cuts Barbershop is a modern barbershop with a traditional touch. Our skilled barbers provide quality haircuts, styles, and grooming services for men of all ages. We believe in making every customer feel sharp and confident.
      </p>
    </section>

    <section class="contact" id="contact">
      <h2>Contact Us</h2>
      <p>Email: info@classiccuts.com</p>
      <p>Phone: (123) 456-7890</p>
      <p>Location: 123 Main Street, YourCity</p>
    </section>

    <section class="booking" id="booking">
      <h2>Book an Appointment</h2>
      <form action="#" method="POST">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <input type="tel" name="phone" placeholder="Your Phone Number" required />
        <select name="service" required>
          <option value="">Select a Service</option>
          <option value="Mens Haircut">Men's Haircut</option>
          <option value="Beard Trim">Beard Trim</option>
          <option value="Hot Towel Shave">Hot Towel Shave</option>
        </select>
        <input type="date" name="date" required />
        <input type="time" name="time" required />
        <textarea name="notes" rows="4" placeholder="Additional Notes"></textarea>
        <button type="submit">Book Now</button>
      </form>
    </section>
  </div>

  <footer>
    <p>&copy; 2025 Classic Cuts Barbershop. All rights reserved.</p>
  </footer>
</body>
</html>
