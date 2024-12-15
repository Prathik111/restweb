# Ex.07 Restaurant Website
## Date:15 / 12/ 24

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
    <title>Restaurant Website</title>
</head>
<body style="margin: 0; font-family: Arial, sans-serif;">

    <!-- Header Section -->
    <div style="background-color: #333; color: white; text-align: center; padding: 20px;">
        <h1 style="margin: 0;">Delicious Bites</h1>
        <p style="margin: 5px 0;">Taste the Difference</p>
    </div>

    <!-- Navigation Bar -->
    <div style="background-color: #444; text-align: center; padding: 10px;">
        <a href="rest-menu.html" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Menu</a>
        <a href="rest-admin.html" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Administration</a>
        <a href="rest-contact.html" style="color: white; margin: 0 15px; text-decoration: none; font-weight: bold;">Contact Us</a>
    </div>

    <!-- Menu Section -->
    <div id="menu" style="padding: 20px; background-color: #f4f4f4;">
        <h2 style="text-align: center; color: #333;">Menu</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 20px;">
            <!-- Dish 1 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image.png" alt="Dish 1" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Our New Menu</h3>
                <p style="font-size: 14px;">At [Restaurant Name], we are passionate about delivering a delightful dining experience with a menu that caters to every taste.
                     Our carefully curated selection of dishes is crafted with the finest, freshest ingredients, blending flavors and textures to satisfy your cravings.
                    Whether you're looking for a hearty meal, a light snack, or something sweet to end your meal, we have something for everyone.</p>
            </div>
            <!-- Dish 2 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Book a Table</h3>
                <p style="font-size: 14px;">Planning a special evening, a family gathering, or just a casual dining experience? Reserve your table with us and enjoy a seamless and stress-free experience.

                    At [Restaurant Name], we believe every moment spent with us should be memorable. By booking your table in advance, you ensure that your dining experience is tailored to perfection.
                     Whether you're celebrating a special occasion or simply enjoying a night out, our team is ready to welcome you with warm hospitality.</p>
            </div>
            <!-- Dish 3 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 2.png" alt="Dish 3" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Open Hours</h3>
                <p style="font-size: 14px;">Open from :        
                    <br><br>
                    Mon - Fri : 2pm - 10pm<br>
                    Sat : 2pm - 11pm<br>    
                    Sun : 2pm - 9pm
                </p>
            </div>
            
        </div>
    </div>


    <!-- Contact Section -->
    <div id="contact" style="padding: 20px; background-color: #f4f4f4; text-align: center;">
        <h2 style="color: #333;">Contact Us</h2>
        <p style="font-size: 14px;">Email: contact@deliciousbites.com</p>
        <p style="font-size: 14px;">Phone: +123-456-7890</p>
    </div>

    <!-- Footer -->
    <div style="background-color: #333; color: white; text-align: center; padding: 10px;">
        <p style="margin: 0;">&copy; 2024 Delicious Bites. All rights reserved.</p>
    </div>

</body>
</html>
```
```
    <!-- Administration Section -->
    <div id="administration" style="padding: 20px; background-color: #fff;">
        <h2 style="text-align: center; color: #333;">Our Team</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 20px;">
            <!-- Team Member 1 -->
            <div style="width: 150px; text-align: center;">
                <img src="image copy 3.png" alt="Team Member 1" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">John Doe</h3>
                <p style="font-size: 14px;">Head Chef</p>
            </div>
            <!-- Repeat for 6 team members -->
            <div style="width: 150px; text-align: center;">
                <img src="image copy 4.png" alt="Team Member 2" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">Jane Smith</h3>
                <p style="font-size: 14px;">Sous Chef</p>
            </div>
            <div style="width: 150px; text-align: center;">
                <img src="image copy 5.png" alt="Team Member 3" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">Emily Clark</h3>
                <p style="font-size: 14px;">Manager</p>
            </div>
            <div style="width: 150px; text-align: center;">
                <img src="image copy 6.png" alt="Team Member 4" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">Michael Lee</h3>
                <p style="font-size: 14px;">Bartender</p>
            </div>
            <div style="width: 150px; text-align: center;">
                <img src="image copy 7.png" alt="Team Member 5" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">Sarah Taylor</h3>
                <p style="font-size: 14px;">Event Planner</p>
            </div>
            <div style="width: 150px; text-align: center;">
                <img src="image copy 8.png" alt="Team Member 6" style="width: 100%; border-radius: 50%;">
                <h3 style="margin-top: 10px; font-size: 16px;">Chris Evans</h3>
                <p style="font-size: 14px;">Pastry Chef</p>
            </div>
        </div>
    </div>
```
```
<!-- Contact Section -->
<div id="contact" style="padding: 20px; background-color: #f4f4f4; text-align: center;">
    <h2 style="color: #333;">Contact Us</h2>
    <p style="font-size: 14px;">Email: contact@deliciousbites.com</p>
    <p style="font-size: 14px;">Phone: +123-456-7890</p>
</div>

<!-- Footer -->
<div style="background-color: #333; color: white; text-align: center; padding: 10px;">
    <p style="margin: 0;">&copy; 2024 Delicious Bites. All rights reserved.</p>
</div>
```
```
    <!-- Menu Section -->
    <div id="menu" style="padding: 20px; background-color: #f4f4f4;">
        <h2 style="text-align: center; color: #333;">Menu</h2>
        <div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; margin-top: 20px;">
            <!-- Dish 1 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 9.png" alt="Dish 1" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Margherita Pizza</h3>
                <p style="font-size: 14px;">A classic Italian favorite topped with fresh mozzarella, tomatoes, and basil, baked to perfection.</p>
            </div>
            <!-- Dish 2 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 10.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Caesar Salad</h3>
                <p style="font-size: 14px;">Crisp romaine lettuce tossed with creamy Caesar dressing, croutons, and Parmesan cheese.</p>
            </div>
            <!-- Dish 3 -->
            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 11.png" alt="Dish 3" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Grilled Chicken Burger
                </h3>
                <p style="font-size: 14px;">A juicy grilled chicken patty, fresh lettuce, tomatoes, and mayo served in a soft bun.</p>
            </div>

            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 12.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Chocolate Lava Cake</h3>
                <p style="font-size: 14px;"> A warm, rich chocolate cake with a molten center, served with a scoop of vanilla ice cream.</p>
            </div>

            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 13.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Sushi Platter

                </h3>
                <p style="font-size: 14px;"> An assortment of freshly rolled sushi with tuna, salmon, avocado, and cucumber, served with soy sauce and wasabi.</p>
            </div>

            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 14.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Spaghetti Carbonara

                </h3>
                <p style="font-size: 14px;">Creamy pasta tossed with egg, Parmesan, pancetta, and black pepper for a hearty Italian meal.</p>
            </div>

            <div style="width: 200px; border: 1px solid #ccc; background-color: white; text-align: center; border-radius: 8px; padding: 10px; margin: 10px;">
                <img src="image copy 15.png" alt="Dish 2" style="width: 100%; border-radius: 8px;">
                <h3 style="margin: 10px 0;">Butter Chicken

                </h3>
                <p style="font-size: 14px;"> Tender chicken cooked in a rich, creamy tomato-based gravy, served with naan or rice.</p>
            </div>
            
        </div>
    </div>
```
## OUTPUT:


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
