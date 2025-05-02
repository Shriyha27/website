# Ex.07 Restaurant Website
# Date: 02.05.2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```
website.html

index.html


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SHAA:The Grind</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-image: url('back.jpg');
            background-size: cover;
            background-attachment: fixed;
        }
        .banner {
            background-color: rgba(244, 97, 183, 0.9);
            padding: 15px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #3badd0;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
            margin: 0;
        }
        .nav-links a {
            display: inline-block;
            padding: 8px 12px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #208bb5;
        }
        .welcome-section, .features-section {
            padding: 15px;
            background-color: rgba(255, 255, 255, 0.8);
            margin: 10px auto;
            width: 70%;
            border-radius: 8px;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 8px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .food-images {
            display: flex;
            justify-content: center;
            gap: 8px;
            margin: 15px 0;
        }
        .food-images img {
            width: 200px;
            height: auto;
            border-radius: 8px;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>SHAA:The Grind</h1>
        <p>Every bite is a sweet escape!</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="website.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Main Content Section -->
    <div class="welcome-section">
        <h2>About Us</h2>
        <p>At "SHAA:The Grind", we believe that dessert is more than just a treat; it's an experience. Founded by Shriyha and Deshnaa, our passion for crafting unique and delicious desserts has led us to create a space where everyone can enjoy a moment of pure indulgence. We use only the finest ingredients and our talented team is dedicated to providing exceptional service and creating a warm and welcoming atmosphere. Whether you're craving a classic pastry, a decadent chocolate creation, or a refreshing sorbet, we have something for everyone.</p>
    </div>

    <div class="features-section">
        <h2>Why Choose Us?</h2>
        <ul>
            <li>We offer superior customer service.</li>
            <li>Unique and diversities of desserts and breads.</li>
            <li>Peaceful and self-reliefing ambiance.</li>
        </ul>
    </div>

    <!-- Food Images Section -->
    <div class="food-images">
        <img src="photo0jpg.jpg">
        <img src="d24a30ada2fef6c54cef8739d94823b0.jpeg">
    </div>

    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY: V. SHRIYHA</p>
    </footer>
</body>
</html>
```
```
menu.html

menu


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - Our Specialties</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        h2 {
            background-color: #3badd0;
            color: white;
            padding: 20px;
        }
        table {
            width: 100%;
            max-width: 800px;
            margin: 20px auto;
            border-collapse: collapse;
        }
        th, td {
            padding: 10px;
            border: 1px solid #ddd;
            text-align: left;
        }
        img {
            width: 100px;
            height: auto;
            border-radius: 8px;
        }
        caption {
            font-size: 1.5em;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <h2>Our Uniques</h2>
    <table>
        <caption>Your favourites</caption>
        <tr>
            <td><img src="images (1)-1.jpg" ></td>
            <td>
                <h3>1. Krunky Sandwich</h3>
                <p>A mouthwatering delight with a crispy, golden-brown chicken fillet nestled between a soft brioche bun.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (6).jpg"></td>
            <td>
                <h3>2. Overloaded Double Decker</h3>
                <p>It is an overloaded two layer burger with two crispy patties and filled with extra cheese and love.</p>
            </td>
        </tr>
        <tr>
            <td><img src="images (3).jpg"></td>
            <td>
                <h3>3. Garlic Chilli Slices</h3>
                <p>Garlic chilli slices is a special variety of breads stuffed with garlic sauce and chilli flakes. Upper layer is coated with mozzarella cheese.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (5).jpg"></td>
            <td>
                <h3>4. The Baconator</h3>
                <p>The Baconator is a juicy wheesy pizza with spinach nack and tomato smuck.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (9).jpg"></td>
            <td>
                <h3>5. Loaded Pile</h3>
                <p>They are known for being a hearty; french fries generously topped with various ingredients like cheese, sauces, and meat.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (7).jpg"></td>
            <td>
                <h3>6. Strawberry Honey Pancakes</h3>
                <p>Strawberry and honey is combined in the batter to enhance the hidden taste of strawberries. They are made into pan cakes and topped with berries and honey.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (8).jpg"></td>
            <td>
                <h3>7. Blue Bannana French Toast</h3>
                <p>Assortment of fresh blueberries and bannanas with milk and bread toasted by butter. It melts yourself from your own world!</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (10).jpg"></td>
            <td>
                <h3>8. Pispink Waffles</h3>
                <p>Greeny and pinky Waffles flavoured of raspberry and green apple. It has its own customisation on its stuffing and toppings.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (12).jpg"></td>
            <td>
                <h3>9. Wavy Cappuccino</h3>
                <p>A cappuccino is a popular coffee beverage, traditionally made with equal parts espresso, steamed milk, and milk foam, creating a balanced and frothy experience.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (11).jpg"></td>
            <td>
                <h3>10. Milk shakes</h3>
                <p>A milkshake is a sweet, cold drink typically made by blending milk, ice cream, and flavorings or sweeteners.</p>
            </td>
        </tr>
        <tr>
            <td><img src="7eafbf49d26d04afc385f37c25029635.jpg"></td>
            <td>
                <h3>11. Malai Velvet</h3>
                <p>Sandwiched between the layers of cake lies a luscious filling of creamy, Rasmalai, red velvet pieces and cherries dotted with plump pieces of soft, spongy paneer and drenched in a decadent milk syrup.</p>
            </td>
        </tr>
        <tr>
            <td><img src="download (13).jpg"></td>
            <td>
                <h3>12. MOJITO MOCKTAIL</h3>
                <p>Refreshing blend of lime, mint, and sparkling soda.</p>
            </td>
        </tr>
    </table>
    <!-- Footer Section -->
    <footer>
        <p>&copy; DESIGNED BY : V.SHRIYHA</p>
    </footer>
</body>
</html>
```
```
administration.html

administration


<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Cherry's Kitchen</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #3badd0;
        }
        .admin-section {
            padding: 20px;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .admin-card {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 15px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }
        .admin-card h3 {
            font-size: 18px;
            margin: 10px 0;
        }
        .admin-card p {
            font-size: 14px;
            color: #555;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Meet Our Administration</h1>
        <p>The pillars of SHAA</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Administration Section -->
    <div class="admin-section">
        <h2>Our Dedicated Team</h2>
        <div class="admin-grid">
            <div class="admin-card">
                <img src="download (2).jpg">
                <h3>Richard Henrid</h3>
                <p>C.E.O</p>
                <p>EMAIL:richardthemaster@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="download (3).jpg">
                <h3>Rachael Ray</h3>
                <p>Head Chef</p>
                <p>EMAIL:RachaelRay@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="download (4).jpg">
                <h3>Janes Willaim Oliver</h3>
                <p>Desserts Specialst</p>
                <p>EMAIL:Olivejanes@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="download.jpg">
                <h3>ATHEWS SHELBY</h3>
                <p>Chineese Chef</p>
                <p>athewby@gmail.com</p>
            </div>
            <div class="admin-card">
                <img src="south-indian-chef-500x500.webp">
                <h3>Samnivas Sharen</h3>
                <p>Assistant Chef</p>
                <p>EMAIL:sharenivas@gmail.com</p>
            </div>
        </div>
    </div>
</body>
<!-- Footer Section -->
<footer>
    <p>&copy; DESIGNED BY : V.SHRIYHA</p>
</footer>
</html>
```
```
contact.html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - SHAA:The Grind</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #f8f9fa;
        }
        .banner {
            background-color: #2a9d8f;
            padding: 20px;
            color: white;
        }
        .nav-links {
            list-style-type: none;
            padding: 0;
            background-color: #264653;
            margin: 0;
            overflow: hidden;
        }
        .nav-links li {
            display: inline;
        }
        .nav-links a {
            display: inline-block;
            padding: 10px 15px;
            color: white;
            text-decoration: none;
        }
        .nav-links a:hover {
            background-color: #3badd0;
        }
        .contact-section {
            padding: 20px;
        }
        .contact-details {
            background-color: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 20px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 500px;
            text-align: left;
        }
        .contact-details h2 {
            font-size: 20px;
            margin-bottom: 15px;
        }
        .contact-details p {
            font-size: 16px;
            margin: 5px 0;
        }
        footer {
            background-color: #264653;
            color: white;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <!-- Header Section -->
    <div class="banner">
        <h1>Contact Us</h1>
        <p>Savoring every bite</p>
    </div>

    <!-- Navigation Bar -->
    <ul class="nav-links">
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="administration.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
    </ul>

    <!-- Contact Section -->
    <div class="contact-section">
        <h2>Get in Touch</h2>
        <h2>𝑊𝑒’𝑑 𝑙𝑜𝑣𝑒 𝑡𝑜 ℎ𝑒𝑎𝑟 𝑓𝑟𝑜𝑚 𝑦𝑜𝑢</h2>
        <div class="contact-details">
            <h2>Our Address</h2>
            <p>Tiruchengode</p>
            <p>Namakkal</p>

            <h2>Phone</h2>
            <p>9442494857</p>

            <h2>Email</h2>
            <p>shaathegrind@gmail.com</p>

            <h2>Cafe Timings:</h2>
            <p>Monday to Sunday, 10:00 AM - 10:00 PM</p>
        </div>
    </div>
</body>
</html>
```
# OUTPUT:

![alt text](<respro/resapp/static/Screenshot 2025-05-02 113327.png>)
![alt text](<respro/resapp/static/Screenshot 2025-05-02 113455.png>)
![alt text](<respro/resapp/static/Screenshot 2025-05-02 113511.png>)
![alt text](<respro/resapp/static/Screenshot 2025-05-02 113522.png>)
![alt text](<respro/resapp/static/Screenshot 2025-05-02 113407.png>)
![alt text](<respro/resapp/static/Screenshot 2025-05-02 113537.png>)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
