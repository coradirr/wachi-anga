# wachi-anga<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coradir - Tienda de Ropa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
        }
        .product {
            background-color: #fff;
            border: 1px solid #ddd;
            margin: 20px 0;
            padding: 20px;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h2 {
            color: #333;
            font-size: 24px;
        }
        .product p {
            color: #666;
            font-size: 16px;
        }
        .product .price {
            color: #000;
            font-size: 20px;
            margin: 10px 0;
        }
        footer {
            background-color: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Coradir - Tienda de Ropa</h1>
    </header>
    <div class="container">
        <div class="product">
            <img src="ruta/de/la/imagen1.jpg" alt="Producto 1">
            <h2>Producto 1</h2>
            <p>Descripción breve del producto 1.</p>
            <p class="price">$19.99</p>
        </div>
        <div class="product">
            <img src="ruta/de/la/imagen2.jpg" alt="Producto 2">
            <h2>Producto 2</h2>
            <p>Descripción breve del producto 2.</p>
            <p class="price">$29.99</p>
        </div>
        <!-- Agrega más productos según sea necesario -->
    </div>
    <footer>
        <p>© 2024 Coradir. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
