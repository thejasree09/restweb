# Ex.07 Restaurant Website
## Date:

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
    <title>restweb</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f9;
            color: #333;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #4CAF50;
        }
        .banner {
            background-image: url("rest.jpg");
            background-size: cover;
            background-position: center;
            height: 300px;
            color: white;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 2rem;
        }
        .content {
            padding: 20px;
        }
        .menu-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .menu-item {
            background-color: white;
            padding: 10px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .admin-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
        }
        .admin-item {
            text-align: center;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>CULINARY CRUISE</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#menu">Menu</a>
        <a href="#administration">Administration</a>
        <a href="#contact">Contact Us</a>
    </nav>
    <div id="home" class="banner">
        <img src="banner.jpg" alt="Banner Image" style="width: 100%; height: 100%; object-fit: cover;">
    </div>
    <div id="menu" class="content">
        <h2>Menu</h2>
        <div class="menu-grid">
            <div class="menu-item">Quesadilla</div>
            <div class="menu-item">Lobster Bisque</div>
            <div class="menu-item">Butter Chicken</div>
            <div class="menu-item">Hyderabadi Biryani</div>
            <div class="menu-item">Paneer Tikka</div>
            <div class="menu-item">Truffle Pasta</div>
            <div class="menu-item">Caviar Tartine</div>
            <div class="menu-item">Dosa</div>
            <div class="menu-item">Idly</div>
            <div class="menu-item">Tiramisu</div>
            <div class="menu-item">Crème Brûlée</div>
        </div>
    </div>
    <div id="administration" class="content">
        <h2>Administration</h2>
        <div class="admin-grid">
            <div class="admin-item">
                <img src=CEO.jpeg alt="Admin 1" style="width:100px;height:100px;border-radius:50%;">
                <p>Darshini Baskaran</p>
                <p>Chief Executive Officer</p>
            </div>
            <div class="admin-item">
                <img src=COO.jpeg alt="Admin 2" style="width:100px;height:100px;border-radius:50%;">
                <p>Aabiya Lakshmi</p>
                <p>Chief Operating Officer</p>
            </div>
            <div class="admin-item">
                <img src=CFO.jpeg alt="Admin 3" style="width:100px;height:100px;border-radius:50%;">
                <p>Varshaa</p>
                <p>Chief Financial Officer</p>
            </div>
        </div>
    </div>
    <div id="contact" class="content">
        <h2>Contact Us</h2>
        <p>Address: EA Road,9K colony,Tamil Nadu, Chennai</p>
        <p>Phone:9089768451</p>
        <p>Email:culinarycruise@gmail.com</p>
    </div>
    <footer>
        <p>&copy;DEVELOPED BY theja sree g B(2400779))</p>
    </footer>
</body>
</html>

```

## OUTPUT:
![image](https://github.com/user-attachments/assets/77af65d3-5b86-4655-8d58-83f5de1be27f)
![image](https://github.com/user-attachments/assets/6c7d6244-6243-42ae-a452-4e831b49b58b)
![image](https://github.com/user-attachments/assets/f4038dd4-70ad-4366-ac06-4f1858134eb8)





## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
