<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biryani Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        .navbar {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: brown;
            padding: 10px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 14px 20px;
            text-align: center;
        }
        .navbar a:hover {
            background-color: orange;
            color: black;
        }
        .content {
            padding: 20px;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            justify-content: center;
        }
        .gallery-item {
            text-align: center;
            max-width: 200px;
        }
        .gallery img {
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="navbar" id="biryani">
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </div>
    <div id="home" class="content">
        <h1>Welcome to Biryani Gallery</h1>
        <p>This is the home section of our biryani-themed website with a navigation bar.</p>
    </div>
    <div id="gallery" class="content">
        <h1>Biryani Gallery</h1>
        <div class="gallery">
            <div class="gallery-item">
                <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS0PD3APm2Xl728wKMGwpNc_cPj8xO1UKAIuQ&s" alt="Chicken Biryani">
                <p>Chicken Biryani</p>
            </div>
            <div class="gallery-item">
                <img src="https://www.indianhealthyrecipes.com/wp-content/uploads/2023/02/paneer-curry-recipe.jpg" alt="Paneer">
                <p>Paneer</p>
            </div>
            <div class="gallery-item">
                <img src="https://www.shutterstock.com/shutterstock/photos/2402928707/display_1500/stock-photo-food-after-main-food-salaad-on-plate-2402928707.jpg" alt="Salad">
                <p>Salad</p>
            </div>
            <div class="gallery-item">
                <img src="https://www.allrecipes.com/thmb/q-IfK20zxeyp1DgKWhrVp6CQ43w=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/AR-89268-triple-dipped-fried-chicken-beauty-4x3-3961ac838ddd41958e7cb9f49376cd68.jpg" alt="Chicken">
                <p>Chicken</p>
            </div>
        </div>
    </div>
    <div id="contact" class="content">
        <h1>Contact Us</h1>
        <p>Email: contact@biryanigallery.com</p>
        <p>Phone: (123) 456-7890</p>
    </div>
</body>
</html>
