# Ex.07 Restaurant Website
# Date: 17/12/2024
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
inde.html:
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
         
                        <!--font for body-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Merienda:wght@300..900&display=swap" rel="stylesheet">
    
                             <!--font awesome icons w3 schools-->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
        <link rel="stylesheet" href="style.css">
        <title>Bibimbap Bliss</title>
    </head>
    <body>
        <!--session begins-->
        <div id="resto">
            <div id="restocontent">
                <h1>Bibimbap Bliss</h1>
                <h2>"Bringing Seoul to Your Plate"</h2>
                <b><a href="" id="menu">See Our Blissful K-Plate</a></b>
            </div>
        </div>
        <!--session ends-->
    
        <!-- header begins-->
         <div id="header">
            <nav id="navbar">
                <h1>Korean-Indo restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                    <div id="email">
                        <a href="mailto:bibimbapbliss@gmail.com">bibimbapbliss@gmail.com</a>
                    </div>
                </ul>
            </nav>
         </div>
        <!-- header ends-->
    
        <!--menu section begins-->
        <div id="menu">
            <h1 id="section">Menu</h1>
            <div id="menu_row">
                <div id="menu_col">
                    <h2>Main course</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Kimchi and Dumpling Noodle Soup.jpg">
                        </div>
                        <div id="rate">
                            <h3>Kimchi and Dumpling Ramen</h3>
                            <h4>Rs.350</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Spicy Korean Silken Tofu Ramen - Sundubu Ramen (20 Minutes) - Tiffy Cooks.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Tofu Ramen</h3>
                            <h4>Rs.400</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Bibimbap Recipe_ A Delicious and Colorful Dish.jpg">
                        </div>
                        <div id="rate">
                            <h3>Bibimbap</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                        <div id="image">
                            <img src="Gimbap (Korean Seaweed Rolls) -.jpg">
                        </div>
                        <div id="rate">
                            <h3>Gimbap</h3>
                            <h4>Rs.350</h4>
                        </div>
                        </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Snacks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Korean corn dogs.jpg">
                        </div>
                        <div id="rate">
                            <h3>Corn Dogs</h3>
                            <h4>Rs.150</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean rolled omelette (Gyeran-mari_ 계란말이).jpg">
                        </div>
                        <div id="rate">
                            <h3>Rolled omelette</h3>
                            <h4>Rs.100</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Spicy Chicken - Khin's Kitchen _ Korean Fried Chicken.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Chicken</h3>
                            <h4>Rs.200</h4>
                        <div class="box">
                            <div id="image">
                                <img src="Korean Tteokbokki with Boiled Eggs.jpg">
                            </div>
                        <div id="rate">
                            <h3>Tteokbeokki Spicy</h3>
                            <h4>Rs.250</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Drinks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Dalgona Coffee (Whipped Coffee) - Host The Toast.jpg">
                        </div>
                        <div id="rate">
                            <h3>Dalgona Coffee</h3>
                            <h4>Rs.380</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Soju Yakult Cocktail.jpg">
                        </div>
                        <div id="rate">
                            <h3>Soju</h3>
                            <h4>Rs.200</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Mango Milk - Bake with Shivesh.jpg">
                        </div>
                    <div id="rate">
                        <h3>Mango Milk</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                                <div id="image">
                                    <img src="Korean Strawberry Milk Recipe (3 Ingredients) + Video.jpg">
                                </div>
                                <div id="rate">
                                    <h3>Mango Milk</h3>
                                    <h4>Rs.450</h4>
                                </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--menu section ends-->
    
        <!--About section begins-->
        <div id="about">
            <h1 id="section">About</h1>
            <div id="about_row">
                <h1>About Us</h1>
                <p>
                    <center>Welcome to Bibimbap Bliss, where the vibrant flavors of Korea and India unite in a delicious fusion experience! Our menu features a delightful array of dishes, from customizable bibimbap bowls to unique twists like kimchi samosas and tandoori chicken tacos. Committed to using fresh, locally sourced ingredients, we cater to all dietary preferences, ensuring everyone can savor our culinary creations. Join us for a meal that celebrates the joy of food and the warmth of community!</center>
                </p>
                </div>
            <div class="about_col">
                <div id="about_img">
                <img src="Girl_Eating_With_Chopsticks-removebg-preview.png">
                </div>
            </div>
        </div>
        <!--About section ends-->
    
        <!--Contact section begins-->
    <div id="contact">
        <h1 id="section">Contact</h1>
    <div id="contact_row">
        <div class="contact_col">
            </div>
            <div class="contact_col">
                <center>
                <p>
                    <i class="fa fa-map-marker"></i>
                    Anna Nagar, Chennai, Tamil-Nadu
                </p>
                <p>
                    <a href="mailto: bibimbapbliss@gmail.com">
                        <i class="fa fa-envelope-o"></i>
                        bibimbapbliss@gmail.com
                    </a>
                
                </p>
                <p>
                    <a href="tel: +918928364456">
                        <i class="	fa fa-phone"></i>
                        +918928364456
                    </a>
                </p>
                        <h3>
                            Follow Us on
                        </h3>
                    <p id="social">
                    <a href="">
                        <i class="	fa fa-instagram">
                        </i>
                    </a>
                    
                    <a href="">
                        <i class="fa fa-youtube-play">
                        </i>
                    </a>
    
                    <a href="">
                        <i class="fa fa-twitter">
                        </i>
                    </a>
                    <a href="">
                        <i class="fa fa-facebook-official">
                        </i>
                    </a>
                    </p>
                </p>
                </p>
            </center>    
            </div>
            <div class="contact-form-container">
                <h2>Get in Touch with Us</h2>
                <p>We'd love to hear from you! Please fill out the form below and we'll get back to you shortly.</p>
                <form method="POST" action="submit_form.php">
                    <!-- Name Input -->
                    <div class="form-group">
                        <label for="name">Name:</label>
                        <input type="text" id="name" name="name" placeholder="Enter your full name" required>
                    </div>
            
                    <!-- Email Input -->
                    <div class="form-group">
                        <label for="email">Email:</label>
                        <input type="email" id="email" name="email" placeholder="Enter your email address" required>
                    </div>
            
                    <!-- Subject Input -->
                    <div class="form-group">
                        <label for="subject">Subject:</label>
                        <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
                    </div>
            
                    <!-- Message Input -->
                    <div class="form-group">
                        <label for="message">Message:</label>
                        <textarea id="message" name="message" rows="6" placeholder="Type your message here..." required></textarea>
                    </div>
            
                    <!-- Submit Button -->
                    <div class="form-group">
                        <button type="submit" class="btn-submit">Send Message</button>
                    </div>
                    </form>                                                                          
        </div>
    </div>
    </div>
        <!--Contact section ends-->
    
    </body>
    </html>

menu.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Menu - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <!-- Menu Section -->
        <div id="menu">
            <h1 id="section">Menu</h1>
            <div id="menu_row">
                <div id="menu_col">
                    <h2>Main course</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Kimchi and Dumpling Noodle Soup.jpg">
                        </div>
                        <div id="rate">
                            <h3>Kimchi and Dumpling Ramen</h3>
                            <h4>Rs.350</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Spicy Korean Silken Tofu Ramen - Sundubu Ramen (20 Minutes) - Tiffy Cooks.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Tofu Ramen</h3>
                            <h4>Rs.400</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Bibimbap Recipe_ A Delicious and Colorful Dish.jpg">
                        </div>
                        <div id="rate">
                            <h3>Bibimbap</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                        <div id="image">
                            <img src="Gimbap (Korean Seaweed Rolls) -.jpg">
                        </div>
                        <div id="rate">
                            <h3>Gimbap</h3>
                            <h4>Rs.350</h4>
                        </div>
                        </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Snacks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Korean corn dogs.jpg">
                        </div>
                        <div id="rate">
                            <h3>Corn Dogs</h3>
                            <h4>Rs.150</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean rolled omelette (Gyeran-mari_ 계란말이).jpg">
                        </div>
                        <div id="rate">
                            <h3>Rolled omelette</h3>
                            <h4>Rs.100</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Spicy Chicken - Khin's Kitchen _ Korean Fried Chicken.jpg">
                        </div>
                        <div id="rate">
                            <h3>Spicy Chicken</h3>
                            <h4>Rs.200</h4>
                        <div class="box">
                            <div id="image">
                                <img src="Korean Tteokbokki with Boiled Eggs.jpg">
                            </div>
                        <div id="rate">
                            <h3>Tteokbeokki Spicy</h3>
                            <h4>Rs.250</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Drinks</h2>
                    <div class="box">
                        <div id="image">
                            <img src="Dalgona Coffee (Whipped Coffee) - Host The Toast.jpg">
                        </div>
                        <div id="rate">
                            <h3>Dalgona Coffee</h3>
                            <h4>Rs.380</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Soju Yakult Cocktail.jpg">
                        </div>
                        <div id="rate">
                            <h3>Soju</h3>
                            <h4>Rs.200</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="Korean Mango Milk - Bake with Shivesh.jpg">
                        </div>
                    <div id="rate">
                        <h3>Mango Milk</h3>
                            <h4>Rs.450</h4>
                    <div class="box">
                                <div id="image">
                                    <img src="Korean Strawberry Milk Recipe (3 Ingredients) + Video.jpg">
                                </div>
                                <div id="rate">
                                    <h3>Mango Milk</h3>
                                    <h4>Rs.450</h4>
                                </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </body>
    </html>

about.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>About - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <!-- About Section -->
        <div id="about">
            <h1 id="section">About</h1>
            <div id="about_row">
                <h1>About Us</h1>
                <p>
                    Welcome to Bibimbap Bliss, where the vibrant flavors of Korea and India unite in a delicious fusion experience! 
                    Our menu features a delightful array of dishes, from customizable bibimbap bowls to unique twists like kimchi samosas and tandoori chicken tacos. 
                    Committed to using fresh, locally sourced ingredients, we cater to all dietary preferences, ensuring everyone can savor our culinary creations.
                    Join us for a meal that celebrates the joy of food and the warmth of community!
                </p>
                <div class="about_col">
                    <img src="Girl_Eating_With_Chopsticks-removebg-preview.png" alt="Girl Eating with Chopsticks">
                </div>
            </div>
        </div>
    </body>
    </html>

contact.html:

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="stylesheet" href="style.css">
        <title>Menu - Bibimbap Bliss</title>
    </head>
    <body>
        <!-- Navbar -->
        <nav id="navbar">
            <h1>Bibimbap Bliss</h1>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="about.html">About</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    
        <div id="contact">
            <h1 id="section">Contact</h1>
        <div id="contact_row">
            <div class="contact_col">
                </div>
                <div class="contact_col">
                    <center>
                    <p>
                        <i class="fa fa-map-marker"></i>
                        Anna Nagar, Chennai, Tamil-Nadu
                    </p>
                    <p>
                        <a href="mailto: bibimbapbliss@gmail.com">
                            <i class="fa fa-envelope-o"></i>
                            bibimbapbliss@gmail.com
                        </a>
                    
                    </p>
                    <p>
                        <a href="tel: +918928364456">
                            <i class="	fa fa-phone"></i>
                            +918928364456
                        </a>
                    </p>
                            <h3>
                                Follow Us on
                            </h3>
                        <p id="social">
                        <a href="">
                            <i class="	fa fa-instagram">
                            </i>
                        </a>
                        
                        <a href="">
                            <i class="fa fa-youtube-play">
                            </i>
                        </a>
        
                        <a href="">
                            <i class="fa fa-twitter">
                            </i>
                        </a>
                        <a href="">
                            <i class="fa fa-facebook-official">
                            </i>
                        </a>
                        </p>
                    </p>
                    </p>
                </center>    
                </div>
                <div class="contact-form-container">
                    <h2>Get in Touch with Us</h2>
                    <p>We'd love to hear from you! Please fill out the form below and we'll get back to you shortly.</p>
                    <form method="POST" action="submit_form.php">
                        <!-- Name Input -->
                        <div class="form-group">
                            <label for="name">Name:</label>
                            <input type="text" id="name" name="name" placeholder="Enter your full name" required>
                        </div>
                
                        <!-- Email Input -->
                        <div class="form-group">
                            <label for="email">Email:</label>
                            <input type="email" id="email" name="email" placeholder="Enter your email address" required>
                        </div>
                
                        <!-- Subject Input -->
                        <div class="form-group">
                            <label for="subject">Subject:</label>
                            <input type="text" id="subject" name="subject" placeholder="Subject of your message" required>
                        </div>
                
                        <!-- Message Input -->
                        <div class="form-group">
                            <label for="message">Message:</label>
                            <textarea id="message" name="message" rows="6" placeholder="Type your message here..." required></textarea>
                        </div>
                
                        <!-- Submit Button -->
                        <div class="form-group">
                            <button type="submit" class="btn-submit">Send Message</button>
                        </div>
                        </form>                                                                          
            </div>
        </div>
        </div>
    </body>
    </html>
    
# OUTPUT:

![image](https://github.com/user-attachments/assets/5211a5fd-0198-468f-9fcc-22c701ece70d)
![image](https://github.com/user-attachments/assets/c822fcd7-7209-47cb-bab8-4c4b0b5ba4a9)
![image](https://github.com/user-attachments/assets/cab20d20-5d42-4a45-8c07-39817edea4b8)
![image](https://github.com/user-attachments/assets/c6eedcce-e3bb-4f4a-b36a-5d02b862ed47)
![image](https://github.com/user-attachments/assets/23501534-b43d-492d-a373-ec4c7a13b6c6)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
