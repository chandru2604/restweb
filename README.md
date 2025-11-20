# Ex.07 Restuarant Website
## Date:

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Velvet and Vine Restaurant</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #A16B56;

    }
    header {
      background-color:#E2D7A7;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #ccc;
    }
    header img {
      height: 50px;
      vertical-align: middle;
    }
    header h1 {
      display: inline;
      margin-left: 10px;
      font-size: 24px;
      color: #333;
    }
    nav {
      background-color: #333;
      overflow: hidden;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;   
      display: block;
      float:left;
      
    }
    nav a:hover {
      background-color: #575757;

    }
    .content {
      display: flex;
      justify-content: space-around;
      padding: 20px;
    }
    .content div {
      background-color: #f8f8f8;
      padding: 20px;
      margin: 10px;
      flex: 1;
      text-align: center;
      border-radius: 8px;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);

    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <img src="Logo.jpg" alt="Velvet and Vine Logo">
    <br>
    <h1><font face="Goudy Oid Style Italic"size="7">Velvet  and  Vine </font></h1>
  </header>
  <nav>
    <a href="index.html" >Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="content">
    <div>
      <h3>Our New Menu</h3>
      <img src="menu cover.jpg" alt="Menu img 1" height="200" width="300">
      <p>Discover our latest dishes with unique flavors!</p>
      <a href="menu.html">See our menu</a>
    </div>
    <div>
      <h3>Book a Table</h3>
      <img src="table.jpg" alt="Menu img 1" height="200" width="300">
      <p>Reserve your spot to enjoy a delightful dining experience.</p>
      <a href="contact.html">Book now</a>
    </div>
    <div>
      <h3>Opening Hours</h3>
      <img src="serving.jpg" alt="Menu img 1" height="200" width="300">
      <p>Mon-Fri: 2pm-10pm<br>Sat: 2pm-11pm<br>Sun: 2pm-9pm</p>
    </div>
  </div>
  <footer>
    Designed and Developed by sahithi
  </footer>
</body>
</html>
```
administration.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Administration - Velevt And Vine </title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #A16B56;
    }
    header, nav, footer {
      background-color: #333;
      color: white;
    }
    header {
      background-color:#E2D7A7;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .administration {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 20px;
    }
    .chef {
      background-color: #f8f8f8;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 20px;
      text-align: center;
      width: 30%;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <img src="Logo.jpg" alt="Velvet and VIne Logo">
    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Velvet  and  Vine </font></h1>
    <h1><font face="Goudy Oid Style Italic" size="5"color="#333">Administration</font></h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="administration">
    <div class="chef">
      <h3>Chef Marco Romano</h3>
      <p>Specialty: Authentic Italian Cuisine
        With over 15 years of experience, Chef Marco brings the heart of Italy to your plate with his handmade pasta and wood-fired pizzas.</p>
    </div>
    <div class="chef">
      <h3>Chef Lisa Chen</h3>
      <p>Specialty: Pan-Asian Delights
        Expert in fusing flavors from across Asia, Chef Lisa’s signature dishes include spicy noodles and sushi with a modern twist.</p>
    </div>
    <div class="chef">
      <h3>Chef Rajiv Mehta</h3>
      <p>Specialty: Modern Indian Cuisine
        Combining traditional spices with contemporary techniques, Chef Rajiv creates vibrant, flavorful Indian dishes.</p>
    </div>
    <div class="chef">
      <h3>Chef Amelia Torres</h3>
      <p>Specialty: Pastry and Desserts
        An award-winning pastry chef, Amelia’s creations, from macarons to molten lava cakes, are a feast for the eyes and the palate.</p>
    </div>
    <div class="chef">
      <h3>Chef David Miller</h3>
      <p>Specialty: Grill and Barbecue
        Known for his expertise in smoking and grilling, Chef David serves up juicy steaks, ribs, and gourmet burgers.</p>
    </div>
    <div class="chef">
      <h3>Chef Sofia Hernandez</h3>
      <p>Specialty: Mediterranean Cuisine
        Chef Sofia’s dishes are inspired by the coasts of Greece and Spain, featuring fresh seafood, olive oil, and vibrant herbs.</p>
    </div>
  </div>
  <footer>
    Designed and Developed by sahithi
  </footer>
</body>
</html>
```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Menu - Velvet and Vine</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #A16B56;

    }
    header, nav, footer {
      background-color: #333;
      color: white;
    }
    header {
      background-color:#E2D7A7;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .menu {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      padding: 20px;
    }
    .dish {
      background-color: #f8f8f8;
      border: 1px solid #ddd;
      border-radius: 8px;
      margin: 10px;
      padding: 20px;
      text-align: center;
      width: 30%;
    }
    .dish img {
      max-width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position:relative;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <img src="Logo.jpg" alt="Velvet and VIne Logo">
    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Velvet  and  Vine </font></h1>
    <h1><font face="Goudy Oid Style Italic" size="5" color="#333">Menu</font></h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="menu">
    <div class="dish">
      <img src="margherita pizza.jpg" height="200" width="300" alt="Margherita Pizza">
      <h3>Margherita Pizza</h3>
      <p>A classic Italian pizza topped with fresh mozzarella, ripe tomatoes, and fragrant basil leaves on a thin, crispy crust</p>
    </div>
    <div class="dish">
      <img src="alfredo pasta.jpg" height="200" width="300" alt="Pasta Alfredo">
      <h3>Pasta Alfredo</h3>
      <p>Rich and creamy pasta tossed in a decadent Alfredo sauce made with butter, cream, and Parmesan, served with your choice of chicken or vegetables.</p>
    </div>
    <div class="dish">
      <img src="caesar salad.jpg" height="200" width="300" alt="Caesar Salad">
      <h3>Caesar Salad</h3>
      <p>Fresh romaine lettuce tossed with creamy Caesar dressing, crunchy croutons, and Parmesan cheese, served with your choice of grilled chicken or shrimp</p>
    </div>
    <div class="dish">
      <img src="momo.avif" height="200" width="300" alt="Momos">
      <h3>Momos</h3>
      <p>Delicious steamed or fried dumplings filled with your choice of meat or veggies, served with a spicy dipping sauce.</p>
    </div>
    <div class="dish">
      <img src="mushrrom caps.jpg" height="200" width="300" alt="Mushroom Caps">
      <h3></h3>
      <p>Button mushrooms stuffed with herbed cream cheese and breadcrumbs, baked to golden perfection.</p>
    </div>
    <div class="dish">
      <img src="Avacado salad.jpg" height="200" width="300" alt="salad">
      <h3>Quinoa & Avocado Salad</h3>
      <p>A refreshing mix of quinoa, avocado, cherry tomatoes, cucumber, and a lemon vinaigrette.</p>
    </div>
    <div class="dish">
      <img src="Calamri.jpg" height="200" width="300" alt="calamri">
      <h3>Crispy Calamari</h3>
      <p>Lightly breaded and fried squid rings served with a tangy marinara or garlic aioli dip.</p>
    </div>
    <div class="dish">
      <img src="caprese panini.jpg" height="200" width="300" alt="caprese panini">
      <h3>Caprese Panini</h3>
      <p>Mozzarella, tomatoes, fresh basil, and balsamic glaze pressed into crusty bread.</p>
    </div>
    <div class="dish">
      <img src="herb chicken.jpg" height="200" width="300" alt="Herb Chicken">
      <h3>Grilled Lemon Herb Chicken</h3>
      <p>Juicy chicken breast marinated in lemon and fresh herbs, served with roasted vegetables.</p>
    </div>
    <div class="dish">
      <img src="Pasta primavera.jpg" height="200" width="300" alt="Pasta primavera">
      <h3>Pasta Primavera</h3>
      <p>Freshly made pasta tossed with seasonal vegetables in a light garlic and olive oil sauce.</p>
    </div>
    <div class="dish">
      <img src="Ribeye steak.jpg" height="200" width="300" alt="Ribeye steak">
      <h3>Ribeye steak</h3>
      <p>Juicy, tender ribeye steak, expertly grilled to your preference, bursting with rich marbling and flavor, served with your choice of sides.</p>
    </div>
    <div class="dish">
      <img src="salmon.jpg" height="200" width="300" alt="salmon">
      <h3>Pan-Seared Salmon</h3>
      <p>Crispy-skinned salmon fillet with a dill butter sauce, accompanied by mashed potatoes.</p>
    </div>
    <div class="dish">
      <img src="Spicy Garlig noodles.jpg" height="200" width="300" alt="noodles">
      <h3>Spicy Garlic Noodles</h3>
      <p>Stir-fried noodles tossed in a bold garlic sauce with chili peppers, fresh veggies, and your choice of protein for a fiery, flavorful kick.</p>
    </div>
    <div class="dish">
      <img src="tomato basil.jpg" height="200" width="300" alt="Tomato Basil">
      <h3>Creamy Tomato Basil Soup</h3>
      <p>A velvety blend of roasted tomatoes and fresh basil, served with a garlic breadstick.</p>
    </div> 
    <div class="dish">
      <img src="cheesecake.jpg" height="200" width="300" alt="cheescake">
      <h3>New York Cheesecake</h3>
      <p>Classic creamy cheesecake with a buttery graham cracker crust, topped with berry compote.</p>
    </div>
    <footer>
      Designed and Developed by sahithi
    </footer>
</body>
</html>
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contact Us - Velvet and Vine</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #A16B56;
    }
    header, nav, footer {
      background-color: #333;
      color: white;
    }
    header {
      background-color:#E2D7A7;
      padding: 20px;
      text-align: center;
    }
    header img {
      height: 50px;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #575757;
    }
    .contact {
      padding: 20px;
      text-align: center;
      color: white;
    }
    footer {
      text-align: center;
      padding: 10px;
      background-color: #333;
      color: white;
      position: absolute;
      bottom: 0;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <img src="Logo.jpg" alt="Velvet and VIne Logo">
    <h1><font face="Goudy Oid Style Italic"size="6" color="#333">Velvet  and  Vine </font></h1>
    <h1><font face="Goudy Oid Style Italic" size="5" color="#333">Contact Us</font></h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="administration.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>
  <div class="contact">
    <h2>Get in Touch</h2>
    <p>Phone: 123-456-7890</p>
    <p>Email: contact@velvetandvine.com</p>
    <p>Address: 123 Main Street, Cityville</p>
  </div>
  <footer>
    Designed and Developed by sahithi
  </footer>
</body>
</html>
```

## OUTPUT:
![web 7](https://github.com/user-attachments/assets/c82d8c4a-8145-4b13-a6ff-f4d75dfab423)


<img width="1217" height="700" alt="Screenshot 2025-11-20 225050" src="https://github.com/user-attachments/assets/2e3ae757-9804-440f-a863-5eb6f482c9b7" />
<img width="1134" height="666" alt="Screenshot 2025-11-20 225106" src="https://github.com/user-attachments/assets/169b827d-cbba-456f-988e-5533dd611625" />
<img width="1161" height="629" alt="Screenshot 2025-11-20 225114" src="https://github.com/user-attachments/assets/99bad37b-f9aa-4e3d-9db5-680d5a24f39e" />
<img width="1132" height="719" alt="Screenshot 2025-11-20 225124" src="https://github.com/user-attachments/assets/c20246f0-8839-4e9f-9c82-b6c13fbce277" />
<img width="1210" height="730" alt="Screenshot 2025-11-20 225136" src="https://github.com/user-attachments/assets/00ef78ff-2e80-49a9-aab2-e02a13a9ab2a" />
<img width="1144" height="760" alt="Screenshot 2025-11-20 225205" src="https://github.com/user-attachments/assets/c50b660b-9f38-4c6e-ac99-944fc2ea25f1" />

<img width="1264" height="727" alt="Screenshot 2025-11-20 225221" src="https://github.com/user-attachments/assets/1726364b-6196-42bf-a7d2-eb14a0aff6ce" />



## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
