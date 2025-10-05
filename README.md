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
      background-color:teal;
      color: black;
    }
    header {
      background-color: teal;
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
      padding: 12px 0;
    }
    nav a {
      color: black;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1em;
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
      margin-bottom: 20px;
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
      <a href="booking.html">Book Table</a>
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
      <div class="dish-item"><h3>MEALS</h3></div>
      <div class="dish-item"><h3>PANI PURI</h3></div>
      <div class="dish-item"><h3>EGG MASALA</h3></div>
      <div class="dish-item"><h3>SANDWICH</h3></div>
      <div class="dish-item"><h3>BUTTER CHICKEN</h3></div>
      <div class="dish-item"><h3>CHICKEN WINGS</h3></div>
    </div>
  </section>

  <footer>
    <p>© 2025 Designed By Tamilselvi</p>
  </footer>
</body>
</html>

admin.html

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

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Restaurant - Contact</title>
  <link rel="stylesheet" href="css/style.css">
</head>
<body>
<header>
  <h1>Tamil Restaurant</h1>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="contact.html">Contact</a>
    <a href="admin.html">Administration</a>
  </nav>
</header>

<section class="contact">
  <h2>Contact Us</h2>
  <p>📍 no.143 kalaingnar street,Thanjavur</p>
  <p>📞 ‪+91 9875432456 ‬</p>
  <p>📧 EMAIL : tamil2008@gmail.com</p>
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
  <title>TAMIL RESTAURANT</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: papayawhip;
            color: #291515;
        }
        header {
            background-color: black;
            color: white;
            padding: 20px 0;
            text-align: center;
            font-size: 2em;
            font-weight: bold;
        }
        nav {
            background-color:palevioletred;
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
            color: white;
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
            color: whitesmoke;
        }
        .menu-item p {
            font-size: 1em;
            color: green;
        }
        footer {
            background-color: blue;
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
 <section id="Menu" class="Menu">
        <h1>Welcome to Tamil Restaurant</h1>
        <p>Experience the best flavors of traditional and modern cuisine in a warm and welcoming atmosphere.</p>
    </section>
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
 




 <footer>

  <p>© 2025 Designed By Tamilselvi</p>
</footer>
</body>
</html>

book.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>TAMIL RESTAURANT - Book Table</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: pink;
      color: #291515;
    }
    header {
      background-color: blue;
      color: black;
      padding: 20px 0;
      text-align: center;
      font-size: 2em;
      font-weight: bold;
    }
    nav {
      background-color: skyblue;
      display: flex;
      justify-content: center;
      gap: 30px;
      padding: 12px 0;
    }
    nav a {
      color: black;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1em;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .booking-form {
      max-width: 600px;
      margin: 40px auto;
      background-color: cyan;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    .booking-form h2 {
      text-align: center;
      color: black;
      margin-bottom: 25px;
      font-size: 2em;
    }
    .booking-form label {
      display: block;
      margin-bottom: 8px;
      font-weight: 600;
    }
    .booking-form input, 
    .booking-form select, 
    .booking-form textarea {
      width: 100%;
      padding: 5px;
      margin-bottom: 10px;
      border-radius: 6px;
      border: 1px solid #ccc;
      font-size: 1em;
    }
    .booking-form button {
      background-color: white;
      color: white;
      padding: 12px 20px;
      border: none;
      border-radius: 6px;
      font-size: 1.1em;
      cursor: pointer;
      width: 100%;
    }
    .booking-form button:hover {
      background-color: black;
    }
    footer {
      background-color: yellowgreen;
      color: black;
      text-align: center;
      padding: 12px 10px;
      margin-top: 5px;
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
      <a href="booking.html">Book Table</a>
    </nav>
  </header>

  <section class="booking-form">
    <h2>Book a Table</h2>
    <form action="#" method="POST">
      <label for="name">Full Name</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email</label>
      <input type="email" id="email" name="email" placeholder="Your Email" required>

      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" placeholder="Your Phone Number" required>

      <label for="guests">Number of Guests</label>
      <input type="number" id="guests" name="guests" min="1" placeholder="Number of Guests" required>

      <label for="date">Date</label>
      <input type="date" id="date" name="date" required>

      <label for="time">Time</label>
      <input type="time" id="time" name="time" required>

      <button type="submit">Book Now</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Designed By Tamilselvi-25017628</p>
  </footer>
</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (50)-1.png>)
![alt text](<Screenshot (51)-1.png>)
![alt text](<Screenshot (52)-1.png>)
![alt text](<Screenshot (53)-1.png>)
![alt text](<Screenshot (54)-1.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
