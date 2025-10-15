# Ex.07 Restaurant Website
## Date:15.10.2025

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VAISHNAVI T-25017435</title>
    <link rel="stylesheet" href="style-index.css">
</head>
<body>
    <header>
        <h1>URBAN SPOON</h1>
        <nav>
             <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="team.html">Our Team</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero-section">
            <div class="hero-content">
                <h2>Welcome to urban spoon!</h2>
                <p>Experience the essence of Italy</p>
                <p class="offer">New Series: "The Subatomic Sampler" tasting menu available this week!</p>
            </div>
        </section>

        <section class="info-cards">
            <div class="card">
                <h3>View The Menu</h3>
                <p>For a more modern,elevated experience</p>
                <a href="menu.html">Explore our new creations</a>
            </div>
            <div class="card">
                <h3>Reserve Your Table</h3>
                <p>We managed to secure a table near the table</p>
                <a href="contact.html">Book your reservation</a>
            </div>
            <div class="card">
                <h3>Current Service Hours</h3>
                <p>Lunch: Mon - Fri, 11 AM - 2 PM</p>
                <p>Dinner: Mon - Sat, 5 PM - 11 PM</p>
                <p>Closed: Sunday</p>
            </div>
        </section>
    </main>

    <footer>
        <p>© 2025 Urban spoon | Developed by Vaishnavi T-25017435</p>
    </footer>
</body>
</html>

style-index.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #f06f6f; 
    background-color: #fd8585;
    text-align: center;
    overflow-x: hidden; 
}

header {
  
    height: 10vh; 
    background-color: #b2d6da;
    padding: 1vh 0; 
    color: #9fd9e1;
    display: flex; 
    flex-direction: column;
    justify-content: center;
}

h1 {
    font-size: 1.5em; 
    margin: 0;
    color: #ffd700;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    font-size: 0.8em; 
    padding: 0;
}


.hero-section {
   
    height: 55vh; 
    
   
    background: url(Background1.jpg)no-repeat center center/cover;
    
    display: flex;
    align-items: center; 
    justify-content: center; 
    
    text-shadow: 1px 1px 5px rgba(0, 0, 0, 0.8);
}

.hero-content {
  
    background-color: rgba(0, 0, 0, 0.7); 
    padding: 3vh 5vw; 
    border-radius: 10px;
    max-width: 80%;
    margin: 0; 
}

.hero-content h2 {
    color: #e2d06a;
    font-size: 2.5em; 
    margin-bottom: 10px;
}

.hero-content p {
    font-size: 1em;
    margin-bottom: 10px;
    color: #fff;
}

.hero-content p.offer {
    color: #edaf98; 
    font-weight: bold;
    font-size: 1.2em; 
}

.info-cards {
    
    height: 25vh; 
    
    display: flex;
    justify-content: center;
    align-items: center; 
    gap: 20px; 
    padding: 0 10px; 
    background-color: #ffffff; 
    color: #333; 
}

.card {
    background-color: #ffffff; 
    border: 1px solid #ccc;
    height: 85%; 
    padding: 10px; 
    width: 30%;
    max-width: 350px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.05);
    border-radius: 8px; 
    display: flex; 
    flex-direction: column;
    justify-content: center;
}

.card h3 {
    color: #8ed6df;
    margin-top: 0;
    border-bottom: 2px solid #ff4500;
    padding-bottom: 3px;
    margin-bottom: 5px;
    font-size: 1em; 
}

.card p {
    font-size: 0.8em; 
    color: #dc65aa;
}

.card a {
    color: #eaa3f0;
    text-decoration: none;
    font-weight: bold;
    display: block;
    margin-top: 5px;
    font-size: 0.8em;
}


footer {
   
    height: 10vh; 
    background-color: #333;
    color: #ccc;
    font-size: 0.9em;
    
    display: flex;
    justify-content: center;
    align-items: center;
}

footer p {
    margin: 0;
}

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urban spoon - Menu</title>
    <link rel="stylesheet" href="style-menu.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Urban spoon</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="menu-container">
        <div class="menu-grid">
            <div class="menu-item">
                <img src="pizza.jpg "alt="Margherita Pizza">
                <h4>Margherita Pizza</h4>
                <p class="description">Each bite offers a perfect balance of fressness and flavour.</p>
                <p class="price">Price: RS.600/-</p>
            </div>
            <div class="menu-item">
                <img src="noodles.jpg" alt="Saucy noodles">
                <h4>Saucy noodles</h4>
                <p class="description">Every bite is soft,saucy,and bursting with flavor.</p>
                <p class="price">Price: RS.350/-</p>
            </div>
            <div class="menu-item">
                <img src="chicken roll.jpg" alt="Chicken stuffed roll">
                <h4>Chicken stuffed roll</h4>
                <p class="description">A soft ,warm roll filled with juicy,spiced chicken with creamy sauce.</p>
                <p class="price">Price: RS.400/-</p>
            </div>
            <div class="menu-item">
                <img src="garlic bread.jpg" alt="Cheesy garlic bread">
                <h4>Cheesy garlic bread</h4>
                <p class="description">golden bread is topped with melted cheese.</p>
                <p class="price">Price: RS.280/-</p>
            </div>
            <div class="menu-item">
                <img src="clam.jpg" alt="spicy clam">
                <h4>spicy clam</h4>
                <p class="description">this dish offers perfect blend of heat and freshness.</p>
                <p class="price">Price: RS.500/-</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Urban spoon | Developed by Vaishnavi T-25017435</p>
    </footer>
</body>
</html>    

style-menu.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #74f8ed;
    text-align: center;
    color: #333;
}

header {
    background-color: #b496f8; 
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #efdb6b;
}


.menu-container {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.menu-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.menu-item {
    background-color: #e46565;
    border: 1px solid #f640d4;
    border-radius: 8px;
    overflow: hidden;
    width: 300px;
    text-align: left;
    padding: 15px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.menu-item img {
    width: 100%;
    height: auto;
    border-radius: 4px;
    margin-bottom: 10px;
}

.menu-item h4 {
    margin: 5px 0;
    color: #90d3f5; 
}

.menu-item .description {
    font-size: 0.9em;
    color: #666;
    height: 40px;
    overflow: hidden;
}

.menu-item .price {
    font-weight: bold;
    color: #333;
    margin-top: 10px;
}

footer {
    background-color: #666; 
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
}

team.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urban spoon - Our Team</title>
    <link rel="stylesheet" href="style-admin.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Urban spoon</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="team-container">
        <h2>Our Culinary Engineers</h2>
        <div class="team-grid">
            <div class="team-member">
                <div class="profile-image">
                    <img src="mypic.jpg" alt="CEO Vaishnavi">
                </div>
                <h4>Miss Vaishnavi T</h4>
                <p>CEO of the Restaurant</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="vijay.jpg" alt="Marketing Manager Vijay">
                </div>
                <h4>Mr Vijay C</h4>
                <p>Marketing Manager and asst.ceo </p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="Smriti.jpg" alt="Operations Manager">
                </div>
                <h4>Miss Smriti Mandana</h4>
                <p>OPeration Mnager</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="samantha.jpg" alt="HR Manager">
                </div>
                <h4>miss Samanatha Ruth Prabhu</h4>
                <p>HR Manager</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="siva.jpg" alt="Executive chef">
                </div>
                <h4>Mr Sivakarthikeyan</h4>
                <p>Executive chef and Service</p>
            </div>
            <div class="team-member">
                <div class="profile-image">
                    <img src="shreyas.jpg" alt="Customer service Manager">
                </div>
                <h4>Mr Shreyas iyer</h4>
                <p>Customer service Manager</p>
            </div>
        </div>
    </main>

    <footer>
        <p>© 2025 Urban spoon | Developed by Vaishnavi T-25017435</p>
    </footer>
</body>
</html>


style-admin.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
}

header {
    background-color: #666; 
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #f9ea95;
}


.team-container {
    padding: 40px 20px;
    max-width: 1200px;
    margin: 0 auto;
}

.team-container h2 {
    text-align: left;
    margin-bottom: 30px;
    font-size: 1.8em;
}

.team-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-around;
    gap: 20px;
}

.team-member {
    background-color: #fff;
    border: 1px solid #ccc;
    border-radius: 8px;
    overflow: hidden;
    width: 200px;
    text-align: center;
    padding: 15px 0 20px 0;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-image {
    width: 150px;
    height: 200px;
    margin: 0 auto 15px auto;
    overflow: hidden;
    border-radius: 10px; 
    position: relative;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.profile-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%/70%; 
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
}

.team-member h4 {
    margin: 5px 0 2px 0;
    color: #333;
}

.team-member p {
    font-size: 0.9em;
    color: #666;
    margin: 0;
}

footer {
    background-color: #666;
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
}

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Urban spoon - Contact Us</title>
    <link rel="stylesheet" href="style-contact.css">
</head>
<body>
    <header>
        <div class="header-content">
            <h1>Urban spoon</h1>
            <nav>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="team.html">Our Team</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="contact-info">
        <h2>Contact & Reservations</h2>
        <p>Location: No.55 KK Nagar,chennai-53</p>
        <p>Phone: +91 7853678801</p>
        <p>Email: vaishnavi55@gmail.com</p>
        <p>Catering Inquiries: airashanthi@gmail.com</p>
    </main>

    <footer>
        <p>© 2025 Quantum Kitchen | Developed by Vaishnavi T - 25017435</p>
    </footer>
</body>
</html>


style-contact.css

body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    text-align: center;
    color: #333;
    min-height: 100vh; 
    display: flex;
    flex-direction: column;
}

header {
    background-color: #666;
    padding: 20px 0;
    color: #fff;
}

.header-content {
    max-width: 1200px;
    margin: 0 auto;
}

h1 {
    font-size: 2em;
    margin-bottom: 10px;
    color: #fff;
}

nav ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center;
    gap: 20px;
}

nav a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    padding: 5px 10px;
}

nav a:hover {
    color: #f6e274;
}


main {
    flex-grow: 1;
    max-width: 600px;
    margin: 0 auto;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    margin-top: 40px;
    margin-bottom: 40px;
}

.contact-info h2 {
    color: #333;
    margin-bottom: 20px;
    font-size: 2em;
}

.contact-info p {
    font-size: 1.1em;
    line-height: 1.6;
    margin: 10px 0;
}

footer {
    background-color: #666;
    color: #ccc;
    padding: 10px 0;
    font-size: 0.9em;
    margin-top: auto; 
}

```

## OUTPUT:
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)
![alt text](<Screenshot (43).png>)
![alt text](<Screenshot (44).png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
