# Ex.07 Restaurant Website
## Date:12/12/2024

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
Restaurant.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currylicious</title>
    <link rel="stylesheet" href="styles.css">

    
</head>
<body>
    <header>
        <div class="container">
            <h1>Masala Magic</h1>
            <nav>
                <ul>
                    <li><a href="restaurant.html">Home</a></li>
                    <li><a href="Adminstration.html">Administration</a></li>
                    <li><a href="contact.html">Contact Us</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="Adminstration">
        <div class="container">
            <h2>Sangamam</h2>
            <p>Sangamam Restaurant (also known as Sangamam Biriyani) is a restaurant chain that operates primarily in the Indian state of Tamil Nadu. The first outlet was opened in 1957 at Dindigul. Since then, it operates with over 101 outlets globally with 92 outlets in India, and 9 outlets overseas.</p>
            <p>The biryani is highly flavorful and it is different because of the spice mix that is used to make this biryani.</p>
        </div>
    </section>

    <section id="menu">
        <div class="container">
            <h2>Menu</h2>
            <div class="menu-item">
                <img src="Mutton Biryani.jpg"alt="Mutton Biryani">
                <h3>Mutton Biryani</h3>
                <p>Authentic biryani made with mutton and a rich blend of spices.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Biryani.jpg" alt="Chicken Biryani">
                <h3>Chicken Biryani</h3>
                <p>Delicious chicken biryani with a mix of aromatic spices.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Lollipop.webp" alt="Chicken Lollipop">
                <h3>Chicken Lollipop</h3>
                <p>Chicken lollipop is a flavorful, crispy, and spicy appetizer made from chicken wings shaped like a lollipop.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Grilled.jpg" alt="Chicken Grilled">
                <h3>Chicken Grilled</h3>
                <p>Grilled chicken is a healthy, flavorful dish where marinated chicken is cooked over a grill for a smoky, charred taste.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Shawarma.jpg" alt="Chicken Shawarma">
                <h3>Chicken Shawarma</h3>
                <p>Chicken shawarma is a Middle Eastern dish of marinated, served in wraps or platters.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Fried Rice.webp" alt="Chicken Fried Rice">
                <h3>Chicken Fried Rice</h3>
                <p>Chicken fried rice is a flavorful stir-fried dish of rice, chicken, vegetables, and seasonings.</p>
            </div>
            <div class="menu-item">
                <img src="Chicken Noodles.jpg" alt="Chicken Noodles">
                <h3>Chicken Noodles</h3>
                <p>Chicken noodles are a savory stir-fried dish combining noodles, chicken, and vegetables in flavorful seasonings.</p>
            </div>
            <div class="menu-item">
                <img src="Chilli Chicken.jpg" alt="Chilli Chicken">
                <h3>Chilli Chicken</h3>
                <p>Chilli chicken is a spicy Indo-Chinese dish of fried chicken tossed in a tangy, savory chili sauce.</p>
            </div>
            <div class="menu-item">
                <img src="Prawn Fry.jpg" alt="Prawn Fry">
                
                    <h3>Prawn Fry</h3>
                    <p>Prawn fry is a delicious and aromatic dish made by sautéing prawns with spices, herbs.</p>
                
            </div>
            <div class="menu-item">
                <img src="Smoothie.jpeg" alt="Smoothie">
                
                    <h3>Smoothie</h3>
                    <p>A smoothie is a thick, creamy drink made from blended fruits or vegetables.</p>
                
            </div>
            <div class="menu-item">
                <img src="lychee.jpg" alt="Litchi Juice">
               
                    <h3>Litchi Juice</h3>
                    <p>A refreshing drink made from fresh litchis, blended for natural sweetness.</p>
               
            </div>
            <div class="menu-item">
                <img src="coffee.jpg" alt="Coffee">
                
                    <h3>Coffee</h3>
                    <p>A rich, aromatic beverage brewed from freshly ground coffee beans.</p>
                
            </div>
    </section>

    <footer>
        <div class="container">
            <h2>Contact Us</h2>
            <p>Email: Sangamam@gmail.com</p>
            <p>Phone: 9940063801</p>
            <p>Address: 19/32 Murugappa Reddy Street, Ambattur, Chennai - 600053</p>
            <P>Designed and Developed by A.T Manasa Devi</P>
        </div>
    </footer>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<body>
    <header>
        <h1>ADMINISTRATION TEAM</h1>
        <nav>
            <ul>
                <li><a href="restaurant.html">Home</a></li>
                <li><a href="administration.html">Administration</a></li>
                <li><a href="contact.html">Contact Us</a></li>
            </ul>
        </nav>
    </header>
   
    <div class="container">
       
        <section class="mission">
            <h2 style="text-align: center;">Our Mission</h2>
            <p style="text-align: center;">
                <b>
                At Our Masala Magic, our mission is to bring the authentic taste of Indian cuisine to your table. We are committed to
                providing our guests with an unforgettable dining experience through exceptional service, high-quality
                ingredients, and a passion for culinary excellence.
            </b>
            </p>
        </section>

Adminstration.html
 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Masala Magic</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color:white;
            color: black;
        }

        header {
            background-color: brown;
            color: white;
            padding: 15px;
            text-align: center;
        }

        header h1 {
            font-weight: 400;
        }

        header nav ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }

        header nav ul li {
            display: inline;
            margin: 0 15px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        header nav ul li a:hover {
            color: rgb(251, 150, 110);
            font-weight: bold;
        }

        .admin-container {
            width: 80%;
            margin: 20px auto;
            text-align: center;
        }

        .admin-card {
            display: inline-block;
            width: 200px;
            margin: 15px;
            padding: 15px;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }

        .admin-card img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        footer p {
            margin: 5px 0;
        }

        ::-webkit-scrollbar {
            width: 0px;
        }
    </style>
</head>
<body>


<div class="admin-container">
    <div class="admin-card">
        <img src="Rebicca.jpeg" alt="Chef">
        <h3>Rebicca</h3>
        <p>Head Chef</p>
    </div>
    <div class="admin-card">
        <img src="Smithanand.png" alt="Chef">
        <h3>Smithanand</h3>
        <p>Chef</p>
    </div>
    <div class="admin-card">
        <img src="Saratend.jpg" alt="Senior Chef">
        <h3>Saratend</h3>
        <p>Senior Chef</p>
    </div>
    <div class="admin-card">
        <img src="Shilpa.jpeg" alt="Assistant Chef">
        <h3>Shilpa</h3>
        <p>Assistant Chef</p>
    </div>
    <div class="admin-card">
        <img src="Angelina.jpg" alt="Junior Chef">
        <h3>Angelina</h3>
        <p>Angelina Chef</p>
    </div>
</div>
        
        <section class="testimonials">
            <h2 style="text-align: center;">What Our Guests Say</h2>
            <p style="text-align: center;" ><b>
                "Sangamam is the best Indian restaurant I've ever visited! The Biriyani's flavour is amazing, and the service
                is top-notch." - Noor jahan.R
            </b></p>
            <p style="text-align: center;"><B>
                "I love the ambiance and the food. The Grilled Chicken a must-try!" - Vikram M.
            </B>
                
            </p>
        </section>
    </div>

    <footer>
        <p>© 2024 Masala Magic| <a href="index.html">Back to Home</a></p>
        <P>Designed and Developed by A.T Manasa Devi</P>
    </footer>
</body>
</html>

Contact.html

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Masala Magic</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }

        header {
            background-color: brown;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }

        h2 {
            color: #c0392b;
            margin-bottom: 10px;
            text-align: center;
        }

        .contact-info,
        .contact-form {
            background-color: #ffffff;
            margin: 20px 0;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }

        .contact-info h3,
        .contact-form h3 {
            margin-top: 0;
        }

        .contact-info p {
            line-height: 1.6;
        }

        .contact-info .map {
            margin-top: 15px;
            text-align: center;
        }

        .map iframe {
            width: 100%;
            height: 300px;
            border: none;
            border-radius: 10px;
        }

        .contact-form form {
            display: flex;
            flex-direction: column;
        }

        .contact-form label {
            margin: 10px 0 5px;
        }

        .contact-form input,
        .contact-form textarea,
        .contact-form button {
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .contact-form button {
            background-color:brown;
            color: #fff;
            border: none;
            cursor: pointer;
            font-size: 1em;
        }

        .contact-form button:hover {
            background-color: #c0392b;
        }

        footer {
            background-color: brown;
            color: #fff;
            text-align: center;
            padding: 10px 0;
            margin-top: 20px;
        }

        footer a {
            color: #ffd700;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>

<body>
    <header>
        <h1>Contact Us</h1>
    </header>

    <div class="container">
        <section class="contact-info">
            <h2>Get in Touch</h2>
            <h3>Contact Details</h3>
            <p>
                Email: <a href="mailto:MasalaMagic">MasalaMagic</a><br>
                Phone: <a href="tel:+917890934356">+91 9940006150</a><br>
                Address: 19/32 Murugappa Reddy Street,venkatapuram,Ambattur,Chennai.<Chennai600-053></Chennai600-053>
        </section>

        <section class="contact-form">
            <h2>Send Us a Message</h2>
            <form action="submit_form.php" method="POST">
                <label for="name">Your Name</label>
                <input type="text" id="name" name="name" placeholder="Enter your name" required>

                <label for="email">Your Email</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>

                <label for="message">Your Message</label>
                <textarea id="message" name="message" rows="5" placeholder="Write your message here" required></textarea>

                <button type="submit">Send Message</button>
            </form>
        </section>
    </div>

    <footer>
        <p>©MasalaMagic | <a href="index.html">Back to Home</a></p>
        <P>Designed and Developed by A.T Manasa Devi</P>
    </footer>
</body>

</html>

```


## OUTPUT:

![Screenshot (68)](https://github.com/user-attachments/assets/8ce40ce9-3ae2-42f9-a4ce-ee9c3c90e9ea)
![Screenshot (69)](https://github.com/user-attachments/assets/988bedf5-bef4-462b-acad-4dd80a2fcaef)
![Screenshot (71)](https://github.com/user-attachments/assets/10e7f2da-0b21-4803-97b8-fd3b9e41eb1a)
![Screenshot (73)](https://github.com/user-attachments/assets/75bad94f-77b0-44e2-8017-2a730917aa1c)

