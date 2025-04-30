# practica4dennis
<!DOCTYPE html>
<html lang=”es”>
<head>
    <meta charset=”UTF-8”>
    <meta name=”viewport” content=”width=device-width, initial-scale=1.0”>
    <title>Tienda en Línea – Producto</title>
    <style>
        Body {
            Font-family: Arial, sans-serif;
            Margin: 0;
            Padding: 0;
            Background-color: #f4f4f4;
        }
        Header {
            Background-color: #333;
            Color: white;
            Padding: 20px;
            Text-align: center;
        }
        .container {
            Width: 80%;
            Margin: 0 auto;
            Display: flex;
            Justify-content: space-between;
            Padding: 20px;
        }
        .product-info {
            Width: 60%;
        }
        .product-info h1 {
            Font-size: 2em;
            Margin-bottom: 10px;
        }
        .product-info p {
            Font-size: 1.2em;
            Line-height: 1.6;
        }
        .product-details {
            Margin-top: 20px;
        }
        .product-details label {
            Font-weight: bold;
        }
        .product-details p {
            Font-size: 1.1em;
        }
        .price {
            Font-size: 1.5em;
            Color: #d9534f;
            Margin-top: 20px;
        }
        .buy-button {
            Background-color: #5bc0de;
            Color: white;
            Padding: 15px 25px;
            Text-align: center;
            Font-size: 1.2em;
            Border: none;
            Cursor: pointer;
            Margin-top: 20px;
        }
        .buy-button:hover {
            Background-color: #31b0d5;
        }
        .product-image {
            Width: 35%;
            Text-align: center;
        }
        .product-image img {
            Width: 100%;
            Max-width: 300px;
            Border-radius: 10px;
        }
    </style>
</head>
<body>

<header>
    <h1>Tienda en Línea</h1>
    <p>Compra el mejor producto ahora mismo</p>
</header>

<div class=”container”>
    <!—Información del producto 
    <div class=”product-info”>
        <h1>Producto XYZ</h1>
        <p>¡El producto ideal para ti! El Producto XYZ es perfecto para todas tus necesidades. Diseñado con materiales de alta calidad y pensado para ofrecerte lo mejor en rendimiento y estilo.</p>
        
        <div class=”product-details”>
            <div>
                <label for=”size”>Tamaño:</label>
                <p id=”size”>M (Mediano)</p>
            </div>
            <div>
                <label for=”texture”>Textura:</label>
                <p id=”texture”>Suave y cómoda, ideal para uso diario.</p>
            </div>
            <div>
                <label for=”price”>Precio:</label>
                <p id=”price”>$49.99 USD</p>
            </div>
        </div>

        <div class=”price”>
            <p>¡Aprovecha nuestra oferta especial!</p>
            <p><strong>Solo por hoy: $49.99 USD</strong></p>
        </div>

        <button class=”buy-button”>Comprar Ahora</button>
    </div>

    <!—Imagen del producto 
    <div class=”product-image”>
        <img src=https://via.placeholder.com/300 alt=”Producto XYZ”>
    </div>
</div>

</body>
</html>
