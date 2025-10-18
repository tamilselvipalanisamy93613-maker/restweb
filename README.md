# Ex.07 Restaurant Website
## Date:05/10/2025

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
rest.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>TAMIL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color:white;
            color: #291515;
        }
        header {
            background-color: green;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color:pink;
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 12px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: 600;
            font-size: 1.1em;
        }
        nav a:hover {
            text-decoration: underline;
        }
                .menu {
            padding: 40px 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        .menu h2 {
            text-align: center;
            color: blueviolet;
            margin-bottom: 30px;
            font-size: 2em;
        }
        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            gap: 30px;
        }
        .menu-item {
            background-color: grey;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            padding: 20px;
            width: 250px;
            text-align: center;
        }
        .menu-item img {
            width: 100%;
            border-radius: 6px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            margin-bottom: 8px;
            color: pink;
        }
        .menu-item p {
            font-size: 1em;
            color:blueviolet;
        }
        footer {
            background-color: black;
            color: white;
            text-align: center;
            padding: 18px 10px;
            margin-top: 40px;
        }
    </style>    

</head>
<body>
<header>
  <h1>TAMIL RESTAURANT</h1>
  <nav>
    <a href="home.html">Home</a>
    <a href="about.html">About</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="booking.html">Book Table</a>
  </nav>
</header>
 <section id="About" class="About">
        <h1>Welcome to Tamil Restaurant</h1>
        <p>our staffs</p>
        </section>
 <img src="myphoto.jpg"height="400",width="400"style="display:">
<img src="dddddd.jpg"height="400",width="400"style="display:">
 <img src="bbbbbb.jpg"height="400",width="400"style="display">
 <img src="aaaa.jpg"height="400",width="400"style="display:">
 <img src="cccccc.jpg"height="400",width="400"style="display:">
 <img src="eeeee.jpg"height="400",width="400"style="display:>
 




 <footer>

  <p>© 2025 Designed By Tamilselvi-25017628</p>
</footer>
</body>
</html>

home.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>TAMIL RESTAURANT - Home</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color:aqua;
      color: black;
    }
    header {
      background-color: cyan;
      color:black;
      padding: 1px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: skyblue;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 6px 0;
    }
    nav a {
      color: black;
      text-decoration: none;
      font-weight: 600;
      font-size: 1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      text-align: center;
      padding: 50px 20px;
      background-color: lavender;
    }
    .hero h2 {
      font-size: 2.5em;
      color: black;
      margin-bottom: 1px;
    }
    .hero p {
      font-size: 1em;
      color: black;
    }
    .dishes {
      max-width: 1000px;
      margin: 40px auto;
      padding: 0 20px;
    }
    .dishes h2 {
      text-align: center;
      color: cadetblue;
      margin-bottom: 30px;
      font-size: 2em;
    }
    .dish-list {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      gap: 20px;
    }
    .dish-item {
      background-color:lavenderblush;
      padding: 20px;
      border-radius: 8px;
      width: 200px;
      text-align: center;
      color: black;
      box-shadow: 0 4px 6px rgba(0,0,0);
    }
    .dish-item h3 {
      margin-bottom: 1px;
    }
    footer {
      background-color: honeydew;
      color:black;
      text-align: center;
      padding: 8px 5px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <header>
    TAMIL RESTAURANT
    <nav>
      <a href="home.html">Home</a>
      <a href="about.html">About</a>
      <a href="menu.html">Menu</a>
      <a href="contact.html">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Welcome to Tamil Restaurant</h2>
    <p>Delicious food made with love. Enjoy our special dishes prepared by our talented chefs!</p>
  </section>

  <section class="dishes">
    <h2>Our Popular Dishes</h2>
    <div class="dish-list">
      <div class="dish-item"><h3>PASTHA</h3></div>
      <div class="dish-item"><h3>BURGER</h3></div>
      <div class="dish-item"><h3>MUTTON CURRY</h3></div>
      <div class="dish-item"><h3>POORI</h3></div>
      <div class="dish-item"><h3>CHICKEN</h3></div>
      <div class="dish-item"><h3>CHICKEN BIRIYANI</h3></div>

    </div>
  </section>

  <footer>
    <p>© 2025 Designed By Tamilselvi</p>
  </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Admin Dashboard</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Admin Dashboard</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Logout</a>
  </nav>
</header>

<section class="dashboard">
  <h2>Available Dishes</h2>
  <ul>
    <li>burger</li>
    <li>corndog</li>
    <li>momos </li>
    <li>pancake</li>
    <li>Chicken Biryani</li>
    <li>dosa</li>
    <li>meals</li>
    <li>panipoori</li>
    <li>prawn</li>
    <li>sandwich</li>
    <li>butter Chicken</li>
    <li>chickenwing</li>
,  </ul>

  <h2>Add New Dish</h2>
  <form>
    <input type="text" placeholder="Dish Name">
    <input type="text" placeholder="Price">
    <button type="submit">Add Dish</button>
  </form>

  <h2>Employees on Shift</h2>
  <ul>
    <li>kiran- Chef</li>
    <li>Sanjai - Waitress</li>
    <li>Mithra - Manager</li>
  </ul>
</section>

<footer>
  <p>© 2025 Tamil Restaurant</p>
</footer>
</body>
</html>


menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tamil Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      color: burlywood
      background-size: cover;
    }

    header {
      background-color: pink;
      text-align: center;
      padding: 20px;
    }

    nav a {
      color:black;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    section {
      background-color: rgba(0, 0, 0, 0.6);
      margin: 20px auto;
      padding: 20px;
      width: 80%;
      border-radius: 10px;
      text-align: center;
    }

    img {
      border-radius: 10px;
      margin: 10px;
    }

    h2 {
      color: pink;
    }

    footer {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 10px;
      color: white;
    }

    .gallery, .admin-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .gallery img, .admin-gallery img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      transition: transform 0.3s;
    }

    .gallery img:hover, .admin-gallery img:hover {
      transform: scale(1.05);
    }
  </style>
</head>
<body>
  <header>
    <h1>Tamil Restaurant</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>Welcome to Tamil Restaurant</h2>
    <p>Enjoy the taste of authentic Tamil cuisine made with love and tradition.</p>
    <img src="4.jpg" width="400">
  </section>

  <section>
    <h2>Our Delicious Dishes</h2>
    <div class="gallery">
<img src="1.jpg"height="270",width="280"style="display:">
<img src="2.jpg"height="270",width="280"style="display:">
 <img src="3.jpg"height="270",width="280"style="display:">
 <img src="4.jpg"height="270",width="280"style="display:">
 <img src="5.jpg"height="270",width="280"style="display:">
 <img src="6.jpg"height="270",width="280"style="display:">
 <img src="7.jpg"height="270",width="280"style="display:">
 <img src="8.jpg"height="270",width="280"style="display:">
 <img src="9.jpg"height="270",width="280"style="display:">
 <img src="10.jpg"height="270",width="280"style="display:">
 <img src="11.jpg"height="270",width="280"style="display:">
 <img src="12.jpg"height="270",width="280"style="display:">   


    </div>
  </section>


 <footer>

  <p>© 2025 Designed By Tamilselvi</p>
</footer>
</body>
</html>


contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Tamil Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color: #fff;
      background: url('https://images.unsplash.com/photo-1556911220-84d65d7e2c05?q=80&w=1400') no-repeat center center fixed;
      background-size: cover;
    }

    header {
      background-color: rgba(0, 100, 0, 0.85);
      text-align: center;
      padding: 20px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover { text-decoration: underline; }

    section {
      background-color: rgba(0, 0, 0, 0.7);
      margin: 20px auto;
      padding: 20px;
      width: 85%;
      border-radius: 10px;
    }

    h2 { color: #FFD700; text-align: center; }

    form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    label {
      font-weight: bold;
      margin-top: 10px;
      margin-bottom: 5px;
    }

    input, textarea, button {
      width: 80%;
      padding: 10px;
      margin-bottom: 15px;
      border-radius: 5px;
      border: none;
    }

    textarea { resize: vertical; }

    button {
      background-color: green;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: darkgreen;
    }

    footer {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 10px;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>Get in Touch</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" placeholder="Your Name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" placeholder="Your Email" required>

      <label for="message">Message:</label>
      <textarea id="message" rows="5" placeholder="Your Message" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Tamil Restaurant | All Rights Reserved</p>
  </footer>
</body>
</html>


admin.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Tamil Restaurant</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      color:black;
      background: url('https://images.unsplash.com/photo-1560264280-44a2f8e6e8a1?q=80&w=1400') no-repeat center center fixed;
      background-size: cover;
    }

    header {
      background-color: pink;
      text-align: center;
      padding: 20px;
    }

    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover { text-decoration: underline; }

    section {
      background-color: rgba(0, 0, 0, 0.7);
      margin: 20px auto;
      padding: 20px;
      width: 85%;
      border-radius: 10px;
    }

    h2 { color: #FFD700; text-align: center; }

    form {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    label {
      font-weight: bold;
      margin-top: 10px;
      margin-bottom: 5px;
    }

    input, textarea, button {
      width: 80%;
      padding: 8px;
      margin-bottom: 10px;
      border-radius: 5px;
      border: none;
    }

    button {
      background-color:pink;
      color: white;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background-color: blueviolet;
    }

    .admin-gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
      gap: 15px;
      margin-top: 20px;
    }

    .admin-gallery img {
      width: 100%;
      height: 150px;
      object-fit: cover;
      border-radius: 10px;
      transition: transform 0.3s;
    }

    .admin-gallery img:hover {
      transform: scale(1.05);
    }

    footer {
      background-color: rgba(0, 0, 0, 0.8);
      text-align: center;
      padding: 10px;
      color: white;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Administration Panel</h1>
    <nav>
      <a href="home.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="admin.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section>
    <h2>Manage Menu Items</h2>
    <form>
      <label>Dish Name:</label>
      <input type="text" placeholder="Enter dish name">

      <label>Price:</label>
      <input type="number" placeholder="Enter price">

      <label>Description:</label>
      <textarea placeholder="Enter description"></textarea>

      <button type="submit">Add Item</button>
    </form>
  </section>

  

  <footer>
    <p>© 2025 Tamil Restaurant | All Rights Reserved</p>
  </footer>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot (79).png>)
![alt text](<Screenshot (74).png>)
![alt text](<Screenshot (78).png>)
![alt text](<Screenshot (80).png>)
![alt text](<Screenshot (81).png>)
![alt text](<Screenshot (83).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
