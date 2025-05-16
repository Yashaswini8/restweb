# Ex.07 Restaurant Website
## Name:Yashaswini.S
## Register Number:212224220123
## Date:16/05/2025

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Delish Dine</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fffdf7;
      color: #333;
    }

    header {
      background-color: #8B0000;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav ul {
      list-style: none;
      display: flex;
      justify-content: center;
      margin-top: 10px;
    }

    nav ul li {
      margin: 0 15px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 40px 20px;
      max-width: 1100px;
      margin: auto;
    }

    #about {
      background-color: #f8f8f8;
      border-left: 5px solid #8B0000;
      padding: 20px;
      margin-bottom: 40px;
    }

    #menu {
      background-color: #fff0e5;
      border-left: 5px solid #8B0000;
      padding: 20px;
    }

    .menu-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .menu-item {
      background-color: #fff;
      border: 1px solid #ddd;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .menu-item:hover {
      transform: scale(1.02);
    }

    .menu-item img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .menu-item .content {
      padding: 15px;
    }

    .menu-item h4 {
      margin-bottom: 10px;
      color: #8B0000;
    }

    .menu-item p {
      font-size: 16px;
      display: flex;
      justify-content: space-between;
    }

    footer {
      background-color: #8B0000;
      color: white;
      text-align: center;
      padding: 15px 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Saffron and Sage</h1>
    <nav>
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#menu">Menu</a></li>
      </ul>
    </nav>
  </header>

  <section id="about">
    <h2>About Us</h2>
    <p>Welcome to Saffron and Sage, where flavor meets elegance. We specialize in delicious, handcrafted dishes made with fresh, locally sourced ingredients. Whether you're here for a quick bite or a romantic dinner, we aim to give you an unforgettable experience.</p>
  </section>

  <section id="menu">
    <h2>Our Menu</h2>
    <div class="menu-grid">
      <!-- Dish 1 -->
      <div class="menu-item">
        <img src="bruschetta.jpg" alt="Bruschetta">
        <div class="content">
          <h4>Bruschetta</h4>
          <p>Appetizer <span>$8</span></p>
        </div>
      </div>
      <!-- Dish 2 -->
      <div class="menu-item">
        <img src="garlic bread.jpg" alt="Garlic Bread">
        <div class="content">
          <h4>Garlic Bread</h4>
          <p>Appetizer <span>$5</span></p>
        </div>
      </div>
      <!-- Dish 3 -->
      <div class="menu-item">
        <img src="cheese cake.jpg" alt="Stuffed Mushrooms">
        <div class="content">
          <h4>Cheese Cake</h4>
          <p>Appetizer <span>$9</span></p>
        </div>
      </div>
      <!-- Dish 4 -->
      <div class="menu-item">
        <img src="salmon.jpg" alt="Grilled Salmon">
        <div class="content">
          <h4>Grilled Salmon</h4>
          <p>Main Course <span>$18</span></p>
        </div>
      </div>
      <!-- Dish 5 -->
      <div class="menu-item">
        <img src="ice cake.jpg" alt="Spaghetti Carbonara">
        <div class="content">
          <h4>Ice cakeA</h4>
          <p>Main Course <span>$15</span></p>
        </div>
      </div>
      <!-- Dish 6 -->
      <div class="menu-item">
        <img src="noodels.jpg" alt="Chicken Parmesan">
        <div class="content">
          <h4>Chicken Parmesan</h4>
          <p>Main Course <span>$17</span></p>
        </div>
      </div>
      <!-- Dish 7 -->
      <div class="menu-item">
        <img src="tiramise.jpg" alt="Tiramisu">
        <div class="content">
          <h4>Tiramisu</h4>
          <p>Dessert <span>$7</span></p>
        </div>
      </div>
      <!-- Dish 8 -->
      <div class="menu-item">
        <img src="lava.jpg" alt="Chocolate Lava Cake">
        <div class="content">
          <h4>Chocolate Lava Cake</h4>
          <p>Dessert <span>$8</span></p>
        </div>
      </div>
      <!-- Dish 9 -->
      <div class="menu-item">
        <img src="cheese cake.jpg" alt="Cheesecake">
        <div class="content">
          <h4>Cheesecake</h4>
          <p>Dessert <span>$6</span></p>
        </div>
      </div>
      <!-- Dish 10 -->
      <div class="menu-item">
        <img src="chicken.jpeg" alt="Grilled Steak">
        <div class="content">
          <h4>Grilled Steak</h4>
          <p>Main Course <span>$22</span></p>
        </div>
      </div>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Delish Dine. All rights reserved.</p>
  </footer>
</body>
</html>



```

## OUTPUT:
![alt text](<Screenshot 2025-05-16 142523.png>)
![alt text](<Screenshot 2025-05-16 142546.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
