# Ex.07 Restaurant Website
## Date:19/05/25

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
home.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Bite & Bliss</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }

    .nav-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 20px 60px;
      background-color: black;
      color: white;
    }

    .nav-bar h1 {
      font-size: 36px;
      font-weight: bold;
    }

    .menu {
      list-style: none;
      display: flex;
      gap: 25px;
    }

    .menu li a {
      text-decoration: none;
      color: white;
      font-size: 18px;
      transition: 0.3s;
    }

    .menu li a:hover {
      color: #cce7cc;
    }

    .hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding: 0 20px;
  text-align: center;
  background: url('ChatGPT Image May 18, 2025, 09_34_01 PM.png') no-repeat center center/cover;
  color: white;
}

    .hero h2 {
      font-size: 42px;
      color: #f0f0f0;
      margin-bottom: 20px;
      text-shadow: 1px 1px 3px #000;
    }

    .hero p {
      font-size: 20px;
      color: #e0e0e0;
      text-shadow: 1px 1px 3px #000;
    }

    .image-row {
      text-align: center;
      margin-top: 40px;
    }

    .image-row img {
      width: 80%;
      max-height: 500px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }
  </style>
</head>
<body>
  <div class="nav-bar">
    <h1>Bite & Bliss</h1>
    <ul class="menu">
      <li><a href="home.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="administration.html">Admin</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>

  <div class="hero">
    <h2>“Delight in Every Bite, Bliss in Every Moment.”</h2>
    <p>At Bite & Bliss, we blend flavor, freshness, and elegance to create a memorable culinary experience.</p>
  </div>
</body>
</html>
menu.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Menu - Bite & Bliss</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
      color: #333;
      margin: 0;
    }

    header {
      background-color:black;
      padding: 20px;
      text-align: center;
      color: white;
    }

    header h1 {
      margin-bottom: 10px;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 0;
    }

    nav a {
      text-decoration: none;
      color: white;
      font-size: 18px;
    }

    nav a:hover {
      color: #cce7cc;
    }

    .menu-list {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 30px;
      padding: 40px;
    }

    .menu-list li {
      background-color: #e8f0e8;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 2px 8px rgba(46, 139, 87, 0.2);
    }

    .menu-list img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 8px;
    }

    .menu-list li p {
      margin-top: 10px;
      font-size: 16px;
      color: black;
      font-weight: bold;
    }

    footer {
      background: black;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Admin</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <ul class="menu-list">
    <li><img src="Screenshot 2025-05-18 220545.png" alt="Biryani" /><p>Biryani - $12</p></li>
    <li><img src="Screenshot 2025-05-18 220818.png" alt="Pizza" /><p>Pizza - $10</p></li>
    <li><img src="Screenshot 2025-05-18 220901.png" alt="Tandoori" /><p>Tandoori - $9</p></li>
    <li><img src="Screenshot 2025-05-18 220939.png" alt="Dessert" /><p>Dessert - $6</p></li>
    <li><img src="Screenshot 2025-05-18 221019.png" alt="Fish Fry" /><p>Fish Fry - $8</p></li>
    <li><img src="Screenshot 2025-05-18 221102.png" alt="Paratha" /><p>Paratha - $5</p></li>
    <!-- Additional Dishes -->
    <li><img src="Screenshot 2025-05-18 221131.png" alt="Noodles" /><p>Schezwan Noodles - $9</p></li>
    <li><img src="Screenshot 2025-05-18 221539.png" alt="Burger" /><p>Cheese Burger - $7</p></li>
    <li><img src="Screenshot 2025-05-18 221606.png" alt="Pasta" /><p>White Sauce Pasta - $8</p></li>
    <li><img src="Screenshot 2025-05-18 221653.png" alt="Ice Cream" /><p>Vanilla Ice Cream - $4</p></li>
    <li><img src="Screenshot 2025-05-18 221728.png" alt="Paneer Tikka" /><p>Paneer Tikka - $7</p></li>
    <li><img src="Screenshot 2025-05-18 221807.png" alt="Milkshake" /><p>Chocolate Milkshake - $5</p></li>
  </ul>

  <footer>
    &copy; 2025 Bite & Bliss
  </footer>
</body>
</html>
admin.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>Administration - Bite & Bliss</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #e8f0e8;
      color: #2e8b57;
      margin: 0;
    }

    header {
      background-color: black;
      padding: 20px;
      text-align: center;
      color: white;
    }

    nav ul {
      display: flex;
      justify-content: center;
      gap: 50px;
      list-style: none;
      padding: 0;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      font-size: 16px;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #cce7cc;
    }

    .team {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 100px;
      padding: 80px;
    }

    .member {
      background-color:black;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 4px 10px rgba(46, 139, 87, 0.2);
      color:white ;
    }

    .member img {
      width: 200px;
      height: 200px;
      border: 50%;
      object-fit: cover;
      border: 3px solid black ;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Administration Team</h1>
    <nav>
      <ul>
        <li><a href="home.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Admin</a></li>
        <li><a href="contact.html">Contact</a></li>
      </ul>
    </nav>
  </header>

  <div class="team">
    <div class="member">
      <img src="Screenshot 2025-05-18 225617.png" alt="CEO" />
      <h3>rajini</h3>
      <p>CEO</p>
    </div>
    <div class="member">
      <img src="Screenshot 2025-05-18 225707.png" alt="Marketing" />
      <h3>kamal</h3>
      <p> Manager</p>
    </div>
    <div class="member">
      <img src="Screenshot 2025-05-18 225845.png" alt="HR" />
      <h3>ajith</h3>
      <p>head chef</p>
    </div>
    <div class="member">
        <img src="Screenshot 2025-05-18 225727.png" alt="HR" />
        <h3>vijay</h3>
        <p>Accountant</p>
      </div>
     
    <!-- Add more team members as needed -->
  </div>
</body>
</html>
con.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us -Bite and bliss</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }

    .nav-bar {
      background-color: black;
      color: white;
      padding: 20px 60px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .nav-bar h1 {
      font-size: 32px;
      font-weight: bold;
    }

    .menu {
      list-style: none;
      display: flex;
      gap: 25px;
    }

    .menu li a {
      text-decoration: none;
      color: white;
      font-size: 16px;
      transition: 0.3s;
    }

    .menu li a:hover {
      color: #cce7cc;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      min-height: 80vh;
    }

    .contact-form {
      flex: 1;
      padding: 60px;
      background-color: #ffffff;
      display: flex;
      flex-direction: column;
      justify-content: center;
    }

    .contact-form h2 {
      color: black;
      margin-bottom: 20px;
    }

    .input-group {
      position: relative;
      margin-bottom: 25px;
    }

    .input-group input,
    .input-group textarea {
      width: 100%;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 6px;
      outline: none;
      font-size: 16px;
      background: none;
      transition: 0.3s ease;
    }

    .input-group label {
      position: absolute;
      left: 12px;
      top: 12px;
      color: #777;
      background-color: #fff;
      padding: 0 5px;
      transition: 0.3s;
      pointer-events: none;
    }

    .input-group input:focus + label,
    .input-group input:not(:placeholder-shown) + label,
    .input-group textarea:focus + label,
    .input-group textarea:not(:placeholder-shown) + label {
      top: -10px;
      font-size: 13px;
      color: black;
    }

    .input-group textarea {
      resize: vertical;
      height: 100px;
    }

    .contact-form button {
      padding: 12px 24px;
      background-color: black;
      color: white;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      font-size: 16px;
      transition: 0.3s ease;
    }

    .contact-form button:hover {
      background-color: black;
    }

    .map-container {
      flex: 1;
      min-height: 400px;
    }

    iframe {
      width: 100%;
      height: 100%;
      border: none;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
      }

      .contact-form, .map-container {
        padding: 30px;
      }
    }
  </style>
</head>
<body>
  <div class="nav-bar">
    <h1>Bite and Bliss</h1>
    <ul class="menu">
      <li><a href="home.html">Home</a></li>
      <li><a href="menu.html">Menu</a></li>
      <li><a href="administration.html">Admin</a></li>
      <li><a href="contact.html">Contact</a></li>
    </ul>
  </div>

  <div class="container">
    <div class="contact-form">
      <h2>We’d love to hear from you</h2>
      <form>
        <div class="input-group">
          <input type="text" id="name" placeholder=" " required>
          <label for="name">Your Name</label>
        </div>
        <div class="input-group">
          <input type="email" id="email" placeholder=" " required>
          <label for="email">Email Address</label>
        </div>
        <div class="input-group">
          <textarea id="message" placeholder=" " required></textarea>
          <label for="message">Your Message</label>
        </div>
        <button type="submit">Send Message</button>
      </form>
    </div>

    <div class="map-container">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d126743.07990295646!2d80.17922141851636!3d13.047807587338875!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a5266597f10b8b5%3A0xf8be8d527aa195eb!2sChennai%2C%20Tamil%20Nadu!5e0!3m2!1sen!2sin!4v1684948179397!5m2!1sen!2sin" 
        allowfullscreen="" 
        loading="lazy" 
        referrerpolicy="no-referrer-when-downgrade">
      </iframe>
    </div>
  </div>
</body>
</html>

```


## OUTPUT:
 ![alt text](<Screenshot 2025-05-19 064121.png>)
 ![alt text](<Screenshot 2025-05-19 064139.png>)
 ![alt text](<Screenshot 2025-05-19 064155.png>)
 ![alt text](<Screenshot 2025-05-19 064211.png>) 
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
