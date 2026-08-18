# Scratch-
Intern 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Storefront</title>
    <style>
        * {
            box-sizing: border-box;
            font-family: system-ui, -apple-system, sans-serif;
        }
        body {
            background-color: #f4f5f7;
            margin: 0;
            padding: 2rem;
        }
        .header {
            text-align: center;
            margin-bottom: 2rem;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 1.5rem;
            max-width: 900px;
            margin: 0 auto;
        }
        .product-card {
            background: white;
            border-radius: 8px;
            padding: 1.5rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.08);
            text-align: center;
        }
        .product-card img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 6px;
        }
        .price {
            font-size: 1.25rem;
            font-weight: bold;
            color: #2b6cb0;
            margin: 0.5rem 0;
        }
        .add-btn {
            background-color: #2b6cb0;
            color: white;
            border: none;
            padding: 0.6rem 1rem;
            border-radius: 4px;
            cursor: pointer;
            width: 100%;
            font-weight: 600;
        }
        .add-btn:hover {
            background-color: #2c5282;
        }
    </style>https://turbo-space-garbanzo-xrwqpwvq45prh6qgp-8080.app.github.dev/
</head>
<body>

    <div class="header">
        <h1>Essential Gear Store</h1>
        <p>Featured Products</p>
    </div>

    <div class="product-grid">
        <!-- Product Item 1 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <h3>Classic Hoodie</h3>
            <p>Comfortable everyday cotton hoodie.</p>
            <div class="price">$45.00</div>
            <button class="add-btn">Add to Cart</button>
        </div>

        <!-- Product Item 2 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <h3>Training Sneakers</h3>
            <p>Lightweight performance footwear.</p>
            <div class="price">$85.00</div>
            <button class="add-btn">Add to Cart</button>
        </div>

        <!-- Product Item 3 -->
        <div class="product-card">
            <img src="https://via.placeholder.com/200" alt="Product Image">
            <h3>Water Bottle</h3>
            <p>Insulated 32oz stainless steel bottle.</p>
            <div class="price">$22.00</div>
            <button class="add-btn">Add to Cart</button>
        </div>
    </div>

</body>
</html>
