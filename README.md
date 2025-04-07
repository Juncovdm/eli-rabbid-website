<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eli Rabbid - Personalized Gifts & Decor</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background-color: #fdf8f5;
            color: #555;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #fff;
            padding: 20px;
            text-align: center;
            box-shadow: 0px 2px 10px rgba(0, 0, 0, 0.1);
        }
        .logo {
            width: 180px;
        }
        nav {
            margin-top: 10px;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #555;
            font-weight: 600;
        }
        .hero {
            background: url('https://via.placeholder.com/1200x500') no-repeat center center/cover;
            height: 400px;
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            text-align: center;
            font-size: 2rem;
            font-weight: bold;
        }
        .container {
            max-width: 1200px;
            margin: 40px auto;
            text-align: center;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 250px;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .button {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #ffb6c1;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0px -2px 10px rgba(0, 0, 0, 0.1);
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Eli Rabbid Logo" class="logo">
        <nav>
            <a href="#">Home</a>
            <a href="#products">Shop</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>
    </header><section class="hero">
    Beautiful Personalized Gifts & Decor for Children
</section>

<div class="container">
    <h2>Our Products</h2>
    <div class="products" id="products">
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 1">
            <h3>Product Name</h3>
            <p>Price: $XX.XX</p>
            <a href="#" class="button">View Product</a>
        </div>
        <div class="product">
            <img src="https://via.placeholder.com/250" alt="Product 2">
            <h3>Product Name</h3>
            <p>Price: $XX.XX</p>
            <a href="#" class="button">View Product</a>
        </div>
    </div>
</div>

<footer>
    &copy; 2025 Eli Rabbid. All Rights Reserved.
</footer>

</body>
</html>
