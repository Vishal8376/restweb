# Ex.07 Restaurant Website
## Date:24/12/24

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
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Little Lemon Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body >
    <header class="header">
        <div class="container">
            <h1>Welcome to Little Lemon</h1>
            <p>Your favorite dining destination</p>
            <a href="menu.html" class="btn">Explore Our Menu</a>
        </div>
    </header>
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admin.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <br><br><br><br><br><br><b><br><br><br><br><br><br><br><br><br><br><br><br>
    
    <footer>
        <center>
        <p>&copy; 2024 Little Lemon Restaurant | Designed by Vishal </p>
    </center>
    </footer>
</body>
</html>

```
menu.html
```
<html>
<head>
    <title>Food Menu</title>
    
    <style>
        body {
            background-image: url('images.jpeg');
            background-size: cover; 
            background-attachment: fixed; 
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }
        .box1 {
            display: flex;
            justify-content: space-around;
            width: 80%;
        }
        .box {
            background-color: rgba(250, 235, 215, 0.553);
            border-color: beige;
            border-radius: 20px;
            border-width: 1px;
            border-style: solid;
            width: 30%;
            padding: 15px;
            line-height: 25px;
            text-align: center;
            margin: 10px;
        }
        .box{
            text-align: left;
        }
        
        .head{
            display: flex;
            align-items: center;
        }
        .rate li{
            display: flex;
            justify-content: space-between;
            margin: 5px 0;
        }
        .con{
            display: flex;
            align-items: center;
            margin-left: 450px;
          }
          h1{
            margin-bottom: 20px;
          }
          .ke{
            color: #097d3d;
          }
          
    </style>
</head>
<body>
    <div class="box1">
        <div class="box">
            <center><h2>Non Veg</h2></center>
            <hr>
            <ul>
                <div class="rate">
                    <li>Mutton Biriyani<span class="ke">$ 499</span></li> 
                <li>Chicken biriyani<span class="ke">$ 399</span></li>  
                <li>Grill Chicken<span class="ke">$ 399</span></li>    
                <li>Barbeque<span class="ke">$ 349</span></li>
                <li>Chicken Rice<span class="ke">$ 210</span></li>
                <li>Chiken 65<span class="ke">$ 149</span></li>
                <li>Shavarma<span class="ke">$ 149</span></li>
                <li>Boneless Wings Chicken<span class="ke">$ 119</span></li>
                </div>
            </ul>
        </div>
        <div class="box">
            <center><h2>Veg</h2></center>
            <hr>
            <ul>
                <div class="rate">
                <li>Meals<span class="ke">$ 199</span></li>
                <li>Veg Biriyani<span class="ke">$ 149</span></li>
                <li>Veg Fried rice<span class="ke">$ 119</span></li>
                <li>Pongal<span class="ke">$ 99</span></li>
                <li>Ghee rice<span class="ke">$ 89</span></li>
                <li>Curd rice<span class="ke">$ 79</span></li>
                <li>Butter Naan<span class="ke">$ 69</span></li>
                <li>Rotti<span class="ke">$ 59</span></li>
            </div>
            </ul>
        </div>
        <div class="box">
            <center><h2>Ice & Juice</h2></center>
            <hr>
            <ul>
                <div class="rate">
                    <li>Badam milk<span class="ke">$ 89</span></li>
                <li>Rose Milk<span class="ke">$ 79</span></li>
                <li>Apple Juice<span class="ke">$ 69</span></li>
                <li>lazzy<span class="ke">$ 49</span></li>
                <li>falooda<span class="ke">$ 99</span></li>
                <li>Choco Truffle<span class="ke">$ 79</span></li>
                <li>Triple Bar<span class="ke">$ 59</span></li>
                <li>Choco Bites<span class="ke">$ 20</span></li>
            </div>
            </ul>
        </div>
    </div>
</body>
</html>


```
admin.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Administration - Little Lemon Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>Our Team</h1>
    </header>
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admin.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <main>
        <div class="team">
            <!-- Add 6 team members with photos -->
            <div class="team-member">
                <img src="man-male-young-person-icon-vector-10458750.jpg" alt="Team Member" width="300px">
                <h2>John Doe</h2>
                <p>Head Chef</p>
            </div>
            <!-- Repeat similar blocks for other team members -->
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Little Lemon Restaurant | Designed by Vishal</p>
    </footer>
</body>
</html>

```
contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us - Little Lemon Restaurant</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="header">
        <h1>Contact Us</h1>
    </header>
    <nav class="navbar">
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="menu.html">Menu</a></li>
            <li><a href="admin.html">Administration</a></li>
            <li><a href="contact.html">Contact Us</a></li>
        </ul>
    </nav>
    <main>
        <b>
        <address>   
            <p>123 Food Street, Gourmet City</p>
            <p>Phone: (123) 456-7890</p>
            <p>Email: info@littlelemon.com</p>
        </address>
    </b>
    </main>
    <footer>
        <p>&copy; 2024 Little Lemon Restaurant | Designed by Vishal</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-26 135433.png>)
![alt text](<Screenshot 2024-12-26 135534.png>)
![alt text](<Screenshot 2024-12-26 135708.png>)
![alt text](<Screenshot 2024-12-26 135554.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
