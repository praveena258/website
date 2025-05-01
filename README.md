# Ex.07 Restaurant Website
# Date:1.05.2025
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
new.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>lavender fork</title>
    <style>
        body {
            background-image: url('lavender.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            color: white;
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .nav-list {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
        }

        .nav-list a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-list a:hover {
            text-decoration: underline;
        }

        h1 {
            color: rgb(54, 1, 88);
            font-size: 50px;
            margin-top: 20px;
        }

        img {
            height: 200px;
            margin-top: 20px;
        }
        .discount-banner {
    background-color: #c468f3;
    color: rgb(4, 25, 60);
    padding: 15px 30px;
    text-align: center;
    font-size: 20px;
    font-weight: bold;
    border-radius: 8px;
    margin: 20px auto;
    width: fit-content;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}
.our-story {
    background-color: rgba(240, 187, 246, 0.85);
    color: #000000;
    padding: 30px;
    margin: 30px auto;
    width: 80%;
    border-radius: 12px;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
    text-align: center;
}

.our-story h2 {
    font-size: 32px;
    margin-bottom: 15px;
    color: #02072a;
}

.our-story p {
    font-size: 18px;
    line-height: 1.6;
}


    </style>
</head>
<body>
    <nav class="nav-list">
        <a href="#">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
        <a href="administrator.html">administration</a>
    </nav>
    <img src="lavender.png" alt="Tasty Treasure Meal Image">
    <h1>LAVENDER FORK</h1>
    <div class="discount-banner">
        🎉 Get 30% OFF on all orders today!
    </div>
    <div class="our-story">
        <h2>Our Story</h2>
        <p>
            At lavender fork, we began with a simple idea — bringing delightful, home-cooked flavors to every plate. 
            What started as a small kitchen venture has now grown into a cherished food destination. 
            We blend tradition with innovation to serve meals that warm the heart and satisfy the soul.
        </p>
    </div>
</body>
</html>

```
menu.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Menu - Tasty Treasures</title>
    <style>
        body {
            background-image: url('lavenderbg.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            margin: 0;
            font-family: Arial, sans-serif;
            color: #fff;
        }
        .nav-list {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
        }

        .nav-list a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-list a:hover {
            text-decoration: underline;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            font-size: 48px;
            color: #370245;
        }

        .menu-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            padding: 40px;
            max-width: 1200px;
            margin: auto;
        }

        .menu-card {
            background-color: rgba(84, 8, 112, 0.303);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
            transition: transform 0.3s ease;
        }

        .menu-card:hover {
            transform: scale(1.03);
        }

        .menu-card img {
            width: 100%;
            height: 180px;
            object-fit: cover;
        }

        .menu-content {
            padding: 15px 20px;
            text-align: center;
        }

        .menu-name {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #370245;
        }

        .menu-price {
            font-size: 18px;
            color: #1c022e;
        }
    </style>
</head>
<body>
    <nav class="nav-list">
        <a href="new.html">Home</a>
        <a href="#">Menu</a>
        <a href="contact.html">Contact</a>
        <a href="administrator.html">Administration</a>
    </nav>
    <h1>Our Menu</h1>
    <div class="menu-grid">
        <div class="menu-card">
            <img src="tacos.jpg">
            <div class="menu-content">
                <div class="menu-name">TACOS</div>
                <div class="menu-price">$5.99</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="prawn.jpg">
            <div class="menu-content">
                <div class="menu-name">PRAWN</div>
                <div class="menu-price">$3.49</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="spaghetti.jpg" alt="Butter Chicken">
            <div class="menu-content">
                <div class="menu-name">SPAGHETTI</div>
                <div class="menu-price">$10.99</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="lasagna.jpg">
            <div class="menu-content">
                <div class="menu-name">LASAGNA</div>
                <div class="menu-price">$9.99</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="gourmetbeefslider.jpg" alt="Gulab Jamun">
            <div class="menu-content">
                <div class="menu-name">gourmet beef slider</div>
                <div class="menu-price">$3.99</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="dumpling.jpg" alt="Ice Cream">
            <div class="menu-content">
                <div class="menu-name">DUMPLING</div>
                <div class="menu-price">$4.50</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="pancake.jpeg" alt="Masala Chai">
            <div class="menu-content">
                <div class="menu-name">PANCAKE</div>
                <div class="menu-price">$2.99</div>
            </div>
        </div>

        <div class="menu-card">
            <img src="tiramisu.jpg" alt="Fresh Lime Soda">
            <div class="menu-content">
                <div class="menu-name">TIRAMISU</div>
                <div class="menu-price">$3.49</div>
            </div>
        </div>
    </div>
</body>
</html>

```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Contact Us - The Dandelion Cafe</title>
    <style>
        body {
            background-image: url('lavenderbg.jpg');
            background-repeat: no-repeat;
            background-size: cover;
            color: white;
            margin: 0;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .nav-list {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
        }

        .nav-list a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-list a:hover {
            text-decoration: underline;
        }

        h1 {
            font-size: 40px;
            margin-top: 30px;
            color: rgb(47, 4, 75);
        }

        .contact-box {
            background-color: rgba(216, 184, 251, 0.85);
            color: #000;
            width: 80%;
            max-width: 600px;
            margin: 40px auto;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            text-align: left;
        }

        .contact-box h2 {
            color: #02072a;
            font-size: 28px;
            margin-bottom: 20px;
            text-align: center;
        }

        .contact-box label {
            display: block;
            margin: 10px 0 5px;
            font-weight: bold;
        }

        .contact-box input,
        .contact-box textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 8px;
            font-size: 16px;
            box-sizing: border-box;
        }

        .contact-box button {
            margin-top: 20px;
            background-color: #6f16c3;
            color: white;
            padding: 12px 20px;
            border: none;
            border-radius: 8px;
            font-size: 16px;
            cursor: pointer;
            width: 100%;
        }

        .contact-box button:hover {
            background-color: #0097a7;
        }
        .para{
            color: #1b002e;
            align-content: flex-end;
        }
    </style>
</head>
<body>
    <nav class="nav-list">
        <a href="new.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="#">Contact</a>
        <a href="administrator.html">Administration</a>
    </nav>

    <h1>Contact Us</h1>

    <div class="contact-box">
        <h2>Get in Touch</h2>
        <form>
            <label for="name">Your Name</label>
            <input type="text" id="name" name="name" placeholder="Enter your name" required>

            <label for="email">Your Email</label>
            <input type="email" id="email" name="email" placeholder="Enter your email" required>

            <label for="message">Your Message</label>
            <textarea id="message" name="message" rows="5" placeholder="Write your message here..." required></textarea>

            <button type="submit">Send Message</button>
        </form>
    </div>
    <p class="para">
        For more details, contact:+91 8834924500
    </p>
</body>
</html>

```
administrator.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Admin - Tasty Treasures Chefs</title>
    <style>
        body {
            background-image: url('lavenderbg.jpg');
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center;
            margin: 0;
            font-family: Arial, sans-serif;
            color: #fff;
        }

        h1 {
            text-align: center;
            margin-top: 30px;
            font-size: 42px;
            color: #16032d;
        }

        .chef-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            padding: 40px;
            max-width: 1200px;
            margin: auto;
        }

        .chef-card {
            background-color: rgba(84, 8, 112, 0.303);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.5);
            text-align: center;
            transition: transform 0.3s ease;
        }

        .chef-card:hover {
            transform: scale(1.03);
        }

        .chef-card img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            size: cover;
        }

        .chef-content {
            padding: 20px;
        }

        .chef-name {
            font-size: 22px;
            font-weight: bold;
            color: #370245;
        }

        .chef-role {
            font-size: 16px;
            color: #08000c;
            margin-top: 5px;
        }
        .nav-list {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 15px;
        }

        .nav-list a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 18px;
        }

        .nav-list a:hover {
            text-decoration: underline;
        }

    </style>
</head>
<body>
    <nav class="nav-list">
        <a href="new.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="contact.html">Contact</a>
        <a href="#">Administration</a>
    </nav>
    <h1>Our Master Chefs</h1>
    <div class="chef-grid">
        <div class="chef-card">
            <img src="chef 1.jpg">
            <div class="chef-content">
                <div class="chef-name">Ram Singh</div>
                <div class="chef-role">Head Chef – Indian Cuisine</div>
            </div>
        </div>

        <div class="chef-card">
            <img src="cheff.jpg" alt="Chef Marco Rossi">
            <div class="chef-content">
                <div class="chef-name">Rosie</div>
                <div class="chef-role">Sous Chef – Continental</div>
            </div>
        </div>

        <div class="chef-card">
            <img src="chef 3.jpeg" alt="Chef Priya Menon">
            <div class="chef-content">
                <div class="chef-name">Priya Menon</div>
                <div class="chef-role">Pastry & Dessert Chef</div>
            </div>
        </div>

        <div class="chef-card">
            <img src="chef 4.jpeg" alt="Chef John Lee">
            <div class="chef-content">
                <div class="chef-name">John Lee</div>
                <div class="chef-role">Beverage Specialist</div>
            </div>
        </div>
    </div>
</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-05-01 202134.png>)
![alt text](<Screenshot 2025-05-01 202143.png>)
![alt text](<Screenshot 2025-05-01 202152.png>)
![alt text](<Screenshot 2025-05-01 202203.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
