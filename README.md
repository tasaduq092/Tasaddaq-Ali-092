<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Tasaddaq_Ali_092</title>
<style>
  body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
  }
  .menu {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: rgb(109, 73, 73);
    padding: 10px;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin-bottom: 20px;
  }
  .contact-link {
  display: flex;
  align-items: center;
  justify-content: center;
  margin-top: 10px;
}

.contact-link span {
  margin: 0 5px;
  color: #333;
  font-weight: bold;
}
  .menu a {
    color: #fff;
    padding: 10px;
    margin: 0 5px;
    text-decoration: none;
    border-radius: 5px;
  }
  .menu a:hover {
    background-color: rgb(113, 79, 79);
  }
  .search-bar {
    margin-left: auto;
    display: flex;
    align-items: center;
  }
  .search-bar input[type="text"] {
    padding: 6px;
    border-radius: 5px;
    border: 1px solid #ccc;
  }
  .search-bar button[type="submit"] {
    padding: 6px 10px;
    border-radius: 5px;
    background-color: #007bff;
    border: 1px solid #007bff;
    color: #fff;
    cursor: pointer;
    margin-left: 5px;
  }
  .search-bar button[type="submit"]:hover {
    background-color: #0056b3;
  }
  
  #container {
    padding: 20px;
    max-width: 1200px;
    margin: auto;
  }
  .contact-form {
    width: 100%;
    margin-bottom: 20px;
    padding: 20px;
    border: 1px solid #ccc;
    border-radius: 5px;
    background-color: #f0f0f0;
    background-image: url(landscape.jpg);
    background-repeat: no-repeat;
    background-size: cover;
  }
  .contact-form h2 {
    margin-top: 0;
    text-align: center;
    margin-bottom: 20px;
  }
  .form-group {
    margin-bottom: 15px;
  }
  .form-group label {
    display: block;
    margin-bottom: 5px;
  }
  .form-group input {
    width: 60%;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
  }
  button[type="submit"] {
    display: block;
    width: 62%;
    padding: 10px;
    border: none;
    border-radius: 5px;
    background-color: #333;
    color: #fff;
    cursor: pointer;
  }
  button[type="submit"]:hover {
    background-color: #000000;
  }
  .person-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
  }
  .person {
    width: 200px;
    text-align: center;
    margin: 10px;
  }
  .person img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 10px;
  }
  .person-info p {
    margin: 5px 0;
  }
  body {
            margin: 0;
            font-family: Arial, sans-serif;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 30px 0;
            text-align: center;
        }
        .footer-container {
            display: flex;
            justify-content: space-around;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
        }
        .footer-section {
            flex: 1;
            margin-right: 20px;
        }
        .footer-section:last-child {
            margin-right: 0;
        }
        .footer-section h3 {
            margin-bottom: 20px;
            font-size: 20px;
        }
        .footer-section ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .footer-section ul li {
            margin-bottom: 10px;
        }
        .footer-section a {
            color: #fff;
            text-decoration: none;
        }
        .footer-section a:hover {
            text-decoration: underline;
        }
        .logo {
            width: 150px;
            margin-bottom: 20px;
        }
        .social-icons {
            display: flex;
            gap: 10px;
            justify-content: center;
        }
        .social-icons img {
            width: 30px;
            height: auto;
        }
        @media screen and (max-width: 768px) {
            .footer-container {
                flex-direction: column;
                align-items: center;
            }
            .footer-section {
                flex: 1 1 auto;
                margin-right: 0;
                margin-bottom: 20px;
            }
        }
</style>
</head>
<body>

  <div class="menu">
    <a href="#">Home</a>
    <a href="#">About</a>
    <a href="#">Tour</a>
    <a href="#">Hotels</a>
    <a href="#">Blog</a>
    <a href="#">Pages</a>
    
    <div class="search-bar">
      <input type="text" placeholder="Search...">
      <button type="submit">Search</button>
    </div>
  </div>
  


  <div id="container">
  <div class="contact-form">
    <h2>Contact Form</h2>
    <form action="#">
      <div class="form-group">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" placeholder="Your Name" required>
      </div>
      <div class="form-group">
        <label for="address">Address:</label>
        <input type="text" id="address" name="address" placeholder="Address" required>
      </div>
      <div class="form-group">
        <label for="email">Your Email:</label>
        <input type="email" id="email" name="email" placeholder="Your Email" required>
      </div>
      <div class="form-group">
        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>
      </div>
      <button type="submit">Submit</button>
    </form>
  </div>

  <h1 style="text-align: center;">OUR ORGANIZATION</h1>

  <div class="person-container">
    <div class="person">
      <img src="1.jpg" alt="Ali">
      <div class="person-info">
        <p><strong>Ali</strong></p>
        <p><strong>COMMERCIAL DIRECTOR</strong></p>
        <p><strong>(000) 000-1234</strong></p>
        <p><strong>ali@gmail.com</strong></p>
      </div>
    </div>

    <div class="person">
      <img src="2.webp" alt="Alina">
      <div class="person-info">
        <p><strong>Alina</strong></p>
        <p><strong>COMMERCIAL DIRECTOR</strong></p>
        <p><strong>0300-0000000</strong></p>
        <p><strong>alina078@gmail.com</strong></p>
      </div>
    </div>

    <div class="person">
      <img src="3.webp" alt="Wood">
      <div class="person-info">
        <p><strong>Wood</strong></p>
        <p><strong>COMMERCIAL DIRECTOR</strong></p>
        <p><strong>0300-1111111</strong></p>
        <p><strong>wood@gmail.com</strong></p>
      </div>
    </div>
  </div>
</div>
<div>
<div style="text-align: center;">
  <img src="map.jpg" alt="Map" style="width: 100%; height: 400px;">
</div>
</div>
<footer>
  <div class="footer-container">
      <div class="footer-section">
          <img src="logo.png" alt="Logo" class="logo">
          <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
      </div>
      <div class="footer-section">
          <h3>Quick Links</h3>
          <ul>
              <li><a href="#">Home</a></li>
              <li><a href="#">About Us</a></li>
              <li><a href="#">Tours</a></li>
              <li><a href="#">Contact</a></li>
          </ul>
      </div>
      <div class="footer-section">
          <h3>Contact Us</h3>
          <ul>
              <li>Email: example@example.com</li>
              <li>Phone: +1234567890</li>
              <li>Address: 123 Street, City, Country</li>
          </ul>
      </div>
      <div class="footer-section">
          <h3>Follow Us</h3>
          <div class="social-icons">
              <a href="#"><img src="facebook.webp" alt="Facebook"></a>
              <a href="#"><img src="insta.png" alt="Instagram"></a>
              <a href="#"><img src="twitter-icon.webp" alt="Twitter"></a>
              <a href="#"><img src="linkedin.png" alt="LinkedIn"></a>
          </div>
      </div>
  </div>
</footer>

</body>
</html>
