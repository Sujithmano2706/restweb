# Ex.07 Restaurant Website
## Date:04.10.25

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
administration.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Administration - Copper Leaf</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Administration</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="admin-grid">
    <!-- Repeat for 6 people -->
    <div class="admin-card">
      <img src="MANAGER.jpg" alt="Admin 1">
      <h3>SATTIESH KUMAR</h3>
      <p>Manager</p>
    </div>
    <div class="admin-card">
      <img src="chef 1.jpg" alt="Admin 2">
      <h3>SANJEEV KAPOOR</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="chef 2.jpg" alt="Admin 3">
      <h3>DHAMODHARAN</h3>
      <p>Head Chef</p>
    </div>
    <div class="admin-card">
      <img src="chef 3.jpg" alt="Admin 4">
      <h3>VENKATESH BUUT</h3>
      <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
      <img src="lady chef.jpg" alt="Admin 5">
      <h3>PRARTHANA</h3>
      <p>Assistant chef</p>
    </div>
    <div class="admin-card">
      <img src="cash.jpg" alt="Admin 6">
      <h3>JONATHAN SAMRAJ</h3>
      <p>cashier</p>
    </div>
    <div class="admin-card">
      <img src="weighter.jpg" alt="Admin 7">
      <h3>GIYO</h3>
      <p>Inventory Manager</p>
    </div>
    <div class="admin-card">
      <img src="weighter 2.jpg" alt="Admin 8">
      <h3>DEEPSHI</h3>
      <p>Customer Service</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Sujith Mano</p>
  </footer>
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Contact Us - Copper Leaf</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Contact Us</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="contact-info">
    <h2>Get in Touch</h2>
    <p>📍 <strong>Address:</strong> 123 Food Street, Gourmet City, FL 45678</p>
    <p>📞 <strong>Phone:</strong> (123) 456-7890</p>
    <p>✉ <strong>Email:</strong> contact@ourrestaurant.com</p>
  </section>
  


 <!-- Optional: Contact Form (if needed) -->
  <!--
  <section class="contact-form">
    <form>
      <label for="name">Name:</label><br>
      <input type="text" id="name" name="name"><br><br>

      <label for="email">Email:</label><br>
      <input type="email" id="email" name="email"><br><br>

      <label for="message">Message:</label><br>
      <textarea id="message" name="message" rows="5"></textarea><br><br>

      <button type="submit">Send Message</button>
    </form>
  </section>
  -->

  <footer>
    <p>&copy; 2025. Designed by Sujith Mano</p>
  </footer>

</body>
</html>

index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Home - Copper Leaf</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1> Copper Leaf </h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="banner">
    <img src="leaf.avif" alt="Delicious Food Banner">
  </section>


  <section class="content">
    <h2>Welcome!</h2>
    <p>Discover the best food in town, made with passion and fresh ingredients.</p>
  </section>

  

  <footer>
    <p>&copy; 2025. Designed by Sujith Mano</p>
  </footer>
</body>
</html>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Menu - Copper Leaf</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Our Menu</h1>
    <nav>
      <a href="index.html">Home</a>
      <a href="menu.html">Menu</a>
      <a href="administration.html">Administration</a>
      <a href="contact.html">Contact Us</a>
    </nav>
  </header>

  <section class="menu-grid">
    <!-- Repeat for 12 items -->
    <div class="menu-item">
      <img src="biriyani.jpg" alt="Biriyani">
      <h3>Biriyani</h3>
      <p>Biryani with the taste of south Tamilnadu</p>
    </div>
    <div class="menu-item">
      <img src="grill chicken.jpg" alt="Grill">
      <h3>Grill chicken</h3>
      <p>Grilled chicken with vegies.</p>
    </div>
    <div class="menu-item">
      <img src="pasta.jpg" alt="Pasta">
      <h3>Spaghetti Carbonara</h3>
      <p>Rich and creamy with bacon.</p>
    </div>
    <div class="menu-item">
      <img src="sandwhich.jpg" alt="Sandwich">
      <h3>Sand Wich</h3>
      <p>Crisp Sandwich with creamy Flavours.</p>
    </div>
    <div class="menu-item">
      <img src="thanthuri.jpg" alt="Tandoori">
      <h3>tandoori chicken</h3>
      <p>Protien with the taste of Chicken.</p>
    </div>
    <div class="menu-item">
      <img src="burger.jpg" alt="Burger">
      <h3>Burger</h3>
      <p>Juicy steak with Crispy Burger.</p>
    </div>
    <div class="menu-item">
      <img src="steak.jpg" alt="steak">
      <h3>GRILLED steak</h3>
      <p>Juicy Steak with garlic Flavour.</p>
    </div>
    <div class="menu-item">
      <img src="soup.jpg" alt="Soup">
      <h3>Mutton soup</h3>
      <p>Warm and spicy mutton soup.</p>
    </div>
    <div class="menu-item">
      <img src="hariyali chicken.jpg" alt="Hariyali chicken">
      <h3>Hariyali chicken</h3>
      <p>Green coloured spicy chicken.</p>
    </div>
    <div class="menu-item">
      <img src="pancake.jpg" alt="Pancakes">
      <h3>Pancakes</h3>
      <p>Fluffy pancakes with syrup.</p>
    </div>
    <div class="menu-item">
      <img src="icecream.jpg" alt="Ice Cream">
      <h3>Ice Cream</h3>
      <p>Vanilla, chocolate, and strawberry scoops.</p>
    </div>
    <div class="menu-item">
      <img src="fries.jpg" alt="Fries">
      <h3>French Fries</h3>
      <p>Crispy golden fries.</p>
    </div>
  </section>

  <footer>
    <p>&copy; 2025. Designed by Sujith Mano</p>
  </footer>
</body>
</html>

style.css

/* style.css */
body {
  margin: 0;
  font-family: Arial, sans-serif;
  background-color: #fdf6f0;
  color: #333;
}

header {
  background-color: #8B0000;
  color: white;
  padding: 20px;
  text-align: center;
}

nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
}

.banner img {
  width: 100%;
  height: auto;
}

section.content {
  padding: 40px;
  text-align: center;
}

.menu-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  padding: 40px;
}

.menu-item {
  background-color: #fff;
  border: 1px solid #ccc;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
}

.menu-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 10px;
}

.admin-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  padding: 40px;
  justify-content: center;
}

.admin-card {
  width: 200px;
  background-color: #fff;
  padding: 15px;
  border-radius: 10px;
  text-align: center;
  border: 1px solid #ccc;
}

.admin-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
  border-radius: 10px;
}

.contact-info {
  padding: 40px;
  text-align: center;
  line-height: 1.8;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

```
## OUTPUT:
![alt text](<Screenshot 2025-10-04 114300.png>) 
![alt text](<Screenshot 2025-10-04 114315.png>) 
![alt text](<Screenshot 2025-10-04 114329.png>)
![alt text](<Screenshot 2025-10-04 114348.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
