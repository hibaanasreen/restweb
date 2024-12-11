# Ex.07 Restaurant Website
## Date:
11/12/24

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
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to our Restaurent</title>
   
    
</head>
<style>
   body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color:#fbf5b9;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: rgb(211, 201, 162);
    border-radius: 10px;
}

.menu{
    background-color: black;
    color: rgb(250, 4, 4);
    padding: 25px;
    border-radius: 30px;
}
.logo {
    display: flex;
    align-items: center;
}

.logo img {
    width: 50px;
    height: 80px;
    margin-right: 10px;
}

nav ul {
    list-style: none;
    display: flex;
    margin: 0;
    padding: 0;
}

nav ul li {
    margin-right: 20px;
}

.footer{
    padding: 10px 10px;
}

nav ul li a {
    text-decoration: none;
    color: #fcfafa;
    font-weight: bold;
}

.offer-txt{
    color: black;
}
.hours{
    width: 300px;
    height: 80px;
}

.banner {
    text-align: center;
    background: url('banner.jpg') no-repeat center center/cover;
    padding: 60px 20px;
    color: #fff;
    border-radius: 10px;
    margin: 25px;
}

.banner h2 {
    font-size: 2.5em;
    margin: 0 0 20px;
}

.features {
    display: flex;
    justify-content: space-around;
    padding: 20px;
    background-color: rgb(211, 205, 162);
}

.feature {
    text-align: center;
    background-color: rgb(240, 202, 133);
    padding: 20px;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    flex: 1;
    margin: 0 10px;
}

.feature h3 {
    font-size: 1.5em;
    margin-bottom: 20px;
}

.feature img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

p {
    text-align: left;
}

ul {
    text-align: left;
}

.copy{
    margin-left: auto
}

.hyperlink{
    color: blue;
} 
</style>
<body>
    <header>
        <div class="logo">
            <img src="/static/Screenshot 2024-12-08 164112.png" alt="Little Lemon Logo">
            <h1>Little Lemon</h1>
        </div>
        <nav class="menu">
            <ul>
                <li><a href="home.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contactus.html">Contact us</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="banner" style="background-image: url('offer.webp');">
            <h2 class="offer-txt" >Tradition,Untouched!!</h2>
              <h2 class="offer-txt"> "Welcome To Little Lemon Most Awarded Italian Restaurent"</h2>

            <p class = 'offer-txt'>Where Flavor Meets Experience
Dive into a culinary journey like no other, where every dish tells a story and every bite is a celebration,our restaurant blends exquisite flavors, fresh ingredients, and a warm, inviting ambiance. Whether you're craving a cozy dinner, a lively gathering, or a new taste adventure, we promise an unforgettable dining experience..</p>
        </section>
        <section class="features">
            <div class="feature">
                <h3>Our New Menu</h3>
                <img src="/static/menu.jpeg" alt="Our New Menu">
                <p>Excite your taste buds with our brand-new menu, crafted to bring fresh flavors and unique dishes to your table. From innovative creations to timeless classics reimagined, there’s something for everyone to savor. Explore our seasonal ingredients, bold spices, and mouthwatering combinations. Visit us today and experience the delicious difference.</p>
                <a href="www.google.com">See our new menu</a>
            </div>
            <div class="feature">
                <h3>Reserve your table</h3>
                <img src="/static/table.jpg" alt="Reserve your table">
                <p>Enjoy a seamless dining experience by reserving your table in advance. Whether it’s a romantic dinner, a family gathering, or a casual meal with friends, we’ve got the perfect spot for you. Select your preferred date, time, and party size, and let us take care of the rest. Book now to ensure your seat at our table.</p>
                <a href="www.google.com">Book your table now</a>
            </div>
            <div class="feature">
                <h3>Opening Hours</h3>
                <img src="/static/food 4.jpg" class="hours" alt="Opening Hours">
                <p>We’re here to serve you delicious meals and unforgettable moments every day of the week. Check out our opening hours below and plan your visit. Whether it’s a hearty breakfast, a leisurely lunch, or a delightful dinner, we’re ready to welcome you!.</p>
                <ul>
                    Monday - Friday: 11:00 AM - 10:00 PM <br>
                    Saturday: 10:00 AM - 11:00 PM <br>
                    Sunday: 10:00 AM - 9:00 PM <br>
                </ul>
            </div>
        </section>
        <footer>
            <div class="logo">
                <img src="/static/Screenshot 2024-12-08 164112.png" class="footer" alt="Little Lemon Logo">
                <p align="margin-right"> Design And Developed By Hiba Nasreen M </p>
            </div>
        </footer>
    </main>


   
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>home</title>
</head>

<style>
    header{
        font-size: 620%;
        font-style:peppy;
        background-color:#f6dba5;
    .content{
        font-size: larger;
        font-family: cursive;
    }
</style>
<body bgcolor="#f6dba5">
    <center>
        <header style="color: crimson;">
            LITTLE LEMON RESTAURENT
        </header>

        <img src="/static/NPT.webp" width="1100" height="500">
        
        <div class="content">
        <p>Welcome to The Little Lemon Restaurant: A Wonderful Dining Experience Like No Other
            Here's a mesmerizing description of a restaurant:

            "At Little Lemon, food is more than just a meal – it's an experience. Our chefs combine timeless culinary techniques with contemporary twists, ensuring every dish delights your palate.
             Our story began in [1980] with a simple mission: to create a space where family, friends, and food lovers could come together to share unforgettable moments."

"Our restaurant is named Little Lemon to reflect our philosophy: fresh, vibrant, and zestful! We take pride in creating dishes with a balance of flavors, freshness, and healthfulness."
                                     "WELCOME TO THE WORLD OF LITTLE LEMON!!"</p>
        </div>
    </center>

</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
        <div>
    <title>Restaurant Menu</title>
        </div>

    <style>
        /* General body styles */
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://example.com/background.jpg'); /* Replace with your background image */
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #ffffff;
        }

        /* Overlay to darken the background image */
        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-color: rgba(0, 0, 0, 0.5);
            z-index: -1;
        }

        /* Main container */
        .menu-container {
            width: 80%;
            margin: 50px auto;
            background-color: rgb(255, 255, 255);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            color: #333;
        }

        /* Header styles */
        header {
            text-align: center;
            padding: 20px 0;
            color: #ffffff;
            background-color: #d35400; /* Orange header */
            border-radius: 15px 15px 0 0;
        }

        header h1 {
            margin: 0;
            font-size: 48px;
        }

        /* Section titles */
        h2 {
            text-align: center;
            color: #27ae60; /* Green color */
            border-bottom: 2px solid #d35400;
            font-size: 36px;
            margin-bottom: 20px;
        }

        /* Menu items */
        .menu-item {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            align-items: center;
        }

        .menu-item img {
            width: 150px;
            height: 100px;
            border-radius: 10px;
            object-fit: cover;
        }

        .menu-item-details {
            flex-grow: 1;
            margin-left: 20px;
        }

        .menu-item-name {
            font-size: 24px;
            font-weight: bold;
            color: #34495e;
        }

        .menu-item-price {
            font-size: 22px;
            color: #e74c3c;
        }

        .description {
            font-size: 16px;
            color: #7f8c8d;
        }

        /* Footer */
        .footer {
            text-align: center;
            padding: 20px;
            color: #bdc3c7;
        }

        /* Responsive styles */
        @media screen and (max-width: 768px) {
            .menu-container {
                width: 95%;
            }

            .menu-item {
                flex-direction: column;
                align-items: flex-start;
            }

            .menu-item img {
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body bgcolor="black">
<div class="overlay"></div>

<header>
    <h1>WELCOME TO OUR RESTAURENT</h1>    
</header>

<div class="menu-container">

    <div class="menu-section">
        <h2>BITE BUZZ</h2>
        <div class="menu-item">
            <img src="/static/italian sandwich.jpg" alt="Italian Sandwich"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Italian Sandwich</p>
                <p class="description">Crusty bread, cured meats, cheese, fresh veggies, and olive oil for a flavorful, hearty meal.</p>
            </div>
            <p class="menu-item-price">rs.150</p>
        </div>

        <div class="menu-item">
            <img src="/static/potato foccacica.webp" alt="Potato Foccacia"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Potato Foccacia</p>
                <p class="description">Potato,vegetables, garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">rs.170</p>
        </div>
        <div class="menu-item">
            <img src="/static/noodles.png"alt="Noodles"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Noodles</p>
                <p class="description">Noodles,vegetables,mushrooms filled with garlic and cream cheese.</p>
            </div>
            <p class="menu-item-price">rs.110</p>
        </div>
        <div class="menu-item">
            <img src="/static/Autmn fritto misto.avif"alt="Autmn Frittto Misto"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Autmn Frittto Misto</p>
                <p class="description">Fritto,vegetables and cheese.</p>
            </div>
            <p class="menu-item-price">rs.135</p>
    </div>
    <div class="menu-item">
        <img src="/static/casprese salad.avif"alt="Caprese Salad"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Caprese Salad</p>
            <p class="description">Bread,vegetables,filled with garlic and cream cheese.<p>
        </div>
        <p class="menu-item-price">rs.95</p>
</div>
<div class="menu-item">
    <img src="/static/frenchfries.jpeg"alt="French Fries"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">French Fries</p>
        <p class="description">Potato fried in fresh oil.</p>
    </div>
    <p class="menu-item-price">rs.140</p>
</div>

<center>
    
    </center>
    <div class="menu-section">
        <h2>Desserts</h2>
        <div class="menu-item">
            <img src="/static/choco lava cake.jpeg" alt="Chocolate Lava Cake"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Chocolate Lava Cake</p>
                <p class="description">Warm cake with a molten chocolate center.</p>
            </div>
            <p class="menu-item-price">rs.70</p>
        </div>

        <div class="menu-item">
            <img src="/static/tiramisu.jpeg" alt="Tiramisu"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Tiramisu</p>
                <p class="description">Best dessert in the world.</p>
            </div>
            <p class="menu-item-price">rs.250</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="/static/caramel pudding.jpeg"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Pudding</p>
            <p class="description">Caramel Pudding.</p>
        </div>
        <p class="menu-item-price">rs.90</p>
    </div>
</div>
<div class="menu-item">
    <img src="/static/waffle.jpeg"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Waffle</p>
        <p class="description">Delecious waffle topped with berries and jam.</p>
    </div>
    <p class="menu-item-price">rs.100</p>
</div>
<div class="menu-item">
    <img src="/static/apple pie.jpeg" alt="Apple Pie"> <!-- Replace with your image -->
    <div class="menu-item-details">
        <p class="menu-item-name">Apple Pie</p>
        <p class="description">Made with spiced aplle with a flaky crust.</p>
    </div>
    <p class="menu-item-price">rs.135</p>
</div>

    <div class="menu-section">
        <h2>Beverages</h2>
        <div class="menu-item">
            <img src="/static/beer.jpeg" alt="Beer"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Beer</p>
                <p class="description">Fermented beverage made with malted grains.</p>
            </div>
            <p class="menu-item-price">rs.200</p>
        </div>

        <div class="menu-item">
            <img src="/static/champagne.jpeg" alt="Champagne"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Champagne</p>
                <p class="description">Sparkling wine with effervescenes.</p>
            </div>
            <p class="menu-item-price">rs.2500</p>
        </div>
    </div>
    <div class="menu-item">
        <img src="/static/mojito.jpeg" alt="Mojito"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Mojito</p>
            <p class="description">Refreshing drink made with rum,mint,sugar,lime juice,soda water.</p>
        </div>
        <p class="menu-item-price">rs.80</p>
    </div>
    <div class="menu-item">
        <img src="/static/cocktail.jpeg" alt="Cocktail"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Cocktail</p>
            <p class="description">Spirits servred in martini glass with fruits and herbs.</p>
        </div>
        <p class="menu-item-price">rs.200</p>
    </div>
    <div class="menu-item">
        <img src="/static/lemonade.jpeg" alt="Lemonade"> <!-- Replace with your image -->
        <div class="menu-item-details">
            <p class="menu-item-name">Lemonade</p>
            <p class="description">Made with water,lemon and mint.</p>
        </div>
        <p class="menu-item-price">rs.70</p>
    </div>
    
    <h2>BREWED BLISS</h2>
        <div class="menu-item">
            <img src="/static/esperesso.jpeg" alt="Espresso"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Espresso</p>
                <p class="description">Coffe brewed by hot water through finely ground coffee beans.</p>
            </div>
            <p class="menu-item-price">rs.130</p>
        </div>
        <div class="menu-item">
            <img src="/static/cold coffee.jpeg" alt="Cold Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cold Coffee</p>
                <p class="description">Milk,ice cubes,sugar and coffee powder.</p>
            </div>
            <p class="menu-item-price">rs.80</p>
        </div>
        <div class="menu-item">
            <img src="/static/cappucino.jpeg" alt="Cappucino"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Cappucino</p>
                <p class="description">Milk,foam,sugar and coffee powder.</p>
            </div>
            <p class="menu-item-price">rs.150</p>
        </div>
        <div class="menu-item">
            <img src="/static/creamy coffee.jpeg" alt="Creamy Coffee"> <!-- Replace with your image -->
            <div class="menu-item-details">
                <p class="menu-item-name">Creamy Coffee</p>
                <p class="description">Milk,cream,sugar and coffee powder.</p>
            </div>
            <p class="menu-item-price">rs.70</p>
        </div>
        <tr>
            <td><h4 style="font-size: larger;"><center>"From Our Kitchen to Your Heart<333"</center></h4></td>
        </tr>
        <h3>Contact</h3>
        <h4>Phone: +91 9876543210 Email id: littlelemon@gmail.com</h4>
        <p>Address: 11, Anna Nagar, Avadi, Chennai</p>
        

       
    
    </body>
    </html>
    ```
    ```
    <!DOCTYPE html>
<html lang="en">


<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>administartion</title>
</head>

<style>
    body{
        background-color: cornsilk;
    }
    header{
        font-size: 450%;
        background-color: burlywood;
    }
    footer{
        font-size: 350%;
        background-color: burlywood;
    }
</style>

<body>
    <center>
    <header>
        The Culinary Collective
    </header>

    <img src="/static/ybzz.jpg" width="600" height="500">
    <h1>Chef Hibaa</h1>
    <p style="font-size: x-large;">With over 10 years of culinary excellence, Chef 'Hibaa' brings a passion for crafting unforgettable dining experiences. Trained at British culinary school,she has worked in some of the most renowned kitchens around the world, blending global flavors with local ingredients.
       At Tasty Bites Restaurant, Chef 'Hibaa' leads the kitchen with a philosophy rooted in innovation and tradition. Every dish is a masterpiece, carefully curated to excite the palate and tell a story. Specializing in main Courses, the menu reflects a commitment to quality, sustainability, and creativity.
       When not in the kitchen, Chef 'Hibaa' enjoys exploring local farmers' markets, experimenting with new techniques, and mentoring the next generation of chefs.
       Come taste the passion, creativity, and dedication in every bite at Little Lemon  Restaurent.</p>

    <img src="/static/chef1.jpeg" width="600" height="500">
    <h1>Chef Johny</h1>
    <p style="font-size: x-large;">Chef 'Johny' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 6 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
       Under the guidance of our Chief Chef,'Johny' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
       Outside the kitchen,'Johny' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Tasty Bites Restaurant.
       Join us  to experience the artistry and dedication of Chef 'Johny' in every dish.</p>

    <img src="/static/chef 3.jpeg" width="600" height="500">
    <h1>Chef Pearly</h1>
    <p style="font-size: x-large;">A true artist in the world of desserts, Chef 'Pearly' brings a touch of magic to every sweet creation at Tasty Bites Restaurant. With a background in baking&pastry arts and over 4 years of experience in top patisseries and fine dining establishments,she transforms simple ingredients into exquisite works of art.
       Specializing in all pastry items, Chef 'Pearly' combines classic techniques with modern flavors. From decadent cakes to delicate pastries, every dessert is crafted to delight both the eye and the palate.
       Chef 'Pearly' believes that a perfect dessert is the grand finale of any meal.Her passion for precision and creativity is evident in every bite, ensuring that each guest’s experience ends on a sweet note.
       Indulge in the culinary artistry of Chef 'Pearly' at Tasty Bites Restaurent where every dessert tells a story.</p>
    
    <img src="/static/chef4.jpeg" width="600" height="500">
    <h1>Chef Charles</h1>
    <p style="font-size: x-large;">Chef 'Charles' is the creative force behind the scenes, bringing precision, passion, and innovation to every dish. With 3 years of experience in the culinary world,he has honed his skills in kitchens across countries, mastering a variety of cuisines and techniques.
        Under the guidance of our Chief 'Arnold','Charles' plays a vital role in maintaining the highest standards of quality and consistency. Known for Starters,he is dedicated to pushing culinary boundaries while respecting the essence of each ingredient.
        Outside the kitchen,'Charles' enjoys exploring new cuisines, perfecting baking techniques, or studying food pairings, which further inspires his work at Haunted Restaurant.
        Join us  to experience the artistry and dedication of Chef 'Charles' in every dish.</p>

    <img src="/static/new chef.jpg" width="600" height="500">
    <h1>Chef Dev</h1>
    <p style="font-size: x-large;">Behind every great dish is a team working in harmony, and our Helper Chef plays a vital role in ensuring everything runs smoothly in the kitchen. With a keen eye for detail and a passion for food, our Helper Chef assists in food preparation, maintains cleanliness, and supports the head chef to execute dishes with precision and care.
       From chopping vegetables to prepping ingredients and ensuring that every plate is perfect, they are dedicated to making sure your dining experience is nothing short of exceptional.
       At our restaurant, teamwork is key, and our Helper Chef brings skill, enthusiasm, and a love of cooking to the heart of our kitchen every day.</p>
      
       <img src="/static/cheff.jpeg" width="600" height="500">
       <h1>Chef Mathew</h1>
       <p style="font-size: x-large;">A masterful culinary artist who transforms raw ingredients into exquisite dishes, combining technical precision with artistic flair. They possess a deep understanding of flavors and culinary techniques, constantly innovating and redefining the culinary landscape. With a passionate dedication to their craft, 
        they lead and inspire their kitchen teams, creating memorable dining experiences that tantalize the senses and elevate the human experience.</p>
    
    <footer>
        Good food is the foundation of genuine happiness!..
    </footer>
   
        
    <p style="font-family: sans-serif;">Design And Developed By Hiba Nasreen M </p>
    
    </center>
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contact</title>
</head>
<style>
    header{
        font-size: 420%;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
    }
    .address{
        font-size: x-large;
    }
    .contact{
        font-size: larger;
        font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
    }
</style>
<body bgcolor="#fbf5b9">
    <center>
        <header style="color: rgb(176, 20, 20);">LITTLE LEMON RESTAURENT
        </header>
        <img src="/static/new t.jpg" width="750" height="450">
        
       
        </center>
        <side>
            
        </side>
        <center>
        <td><h3 style="font-size:25px"> CONTACT </h3></td>
    <td><h4 style="font-size:25px">PHONE: +91 9876543210|EMAIL ID:littlelemon@gmail.com</h4></td> 
    <td><h3 style="font-size:25px"> ADDRESS:11, Anna Nagar, Avadi, Chennai </h3></td>
    </center>
    </body>
    </html>
 ```


## OUTPUT:
![alt text](<Screenshot 2024-12-11 230736.png>)
![alt text](<Screenshot 2024-12-11 230810.png>)
![alt text](<Screenshot 2024-12-11 231035.png>)
![alt text](<Screenshot 2024-12-11 231049.png>)
![alt text](<Screenshot 2024-12-11 231104.png>)
![alt text](<Screenshot 2024-12-11 231137.png>)
![alt text](<Screenshot 2024-12-11 231204.png>)
![alt text](<Screenshot 2024-12-11 231213.png>)
![alt text](<Screenshot 2024-12-11 231231.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
