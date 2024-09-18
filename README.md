<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Productos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            display: flex;
            justify-content: space-between;
            margin-bottom: 20px;
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 150px;
            border-radius: 5px;
        }
        .product-details {
            flex: 1;
            margin-left: 20px;
        }
        .product-title {
            font-size: 1.5em;
            margin-bottom: 10px;
        }
        .product-price {
            color: #4CAF50;
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        .add-to-cart {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .add-to-cart:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>
    <header>
        <h1>Tienda Online de Productos</h1>
    </header>

    <div class="container">
        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Producto 1">
            <div class="product-details">
                <h2 class="product-title">Producto 1</h2>
                <p>Descripción del producto 1. Es un producto excelente.</p>
                <p class="product-price">$19.99</p>
                <button class="add-to-cart">Añadir al carrito</button>
            </div>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Producto 2">
            <div class="product-details">
                <h2 class="product-title">Producto 2</h2>
                <p>Descripción del producto 2. Este producto es increíble.</p>
                <p class="product-price">$29.99</p>
                <button class="add-to-cart">Añadir al carrito</button>
            </div>
        </div>

        <div class="product">
            <img src="https://via.placeholder.com/150" alt="Producto 3">
            <div class="product-details">
                <h2 class="product-title">Producto 3</h2>
                <p>Descripción del producto 3. No te lo pierdas.</p>
                <p class="product-price">$39.99</p>
                <button class="add-to-cart">Añadir al carrito</button>
            </div>
        </div>
    </div>
</body>
</html>

