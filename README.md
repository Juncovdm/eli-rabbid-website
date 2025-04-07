<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eli Rabbid - Personalized Gifts & Decor</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #fceff5;
            color: #555;
            text-align: center;
            padding: 20px;
        }
        header {
            background-color: #ffe4e1;
            padding: 20px;
            border-radius: 10px;
        }
        .logo {
            width: 150px;
        }
        .products {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .product {
            background: white;
            padding: 15px;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            width: 200px;
        }
        .product img {
            width: 100%;
            border-radius: 10px;
        }
        .add-product {
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ffb6c1;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo.jpg" alt="Eli Rabbid Logo" class="logo">
        <h1>Welcome to Eli Rabbid</h1>
        <p>Beautiful personalized gifts & decor for children</p>
    </header><div class="products" id="product-list">
    <!-- Sample products will go here -->
</div>

<button class="add-product" onclick="addProduct()">Add New Product</button>

<script>
    function addProduct() {
        const productList = document.getElementById('product-list');
        const product = document.createElement('div');
        product.className = 'product';
        product.innerHTML = `
            <img src="https://via.placeholder.com/200" alt="New Product">
            <h3>New Product</h3>
            <p>Price: $00.00</p>
        `;
        productList.appendChild(product);
    }
</script>

</body>
</html>
