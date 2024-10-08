<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Tienda de productos ecológicos para un mundo más sostenible. Descubre nuestros productos amigables con el medio ambiente.">
    <title>Tienda de Productos Ecológicos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        /* Encabezado */
        header {
            background-color: #4CAF50;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            text-align: center;
            margin-top: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-size: 1.2em;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Banner principal */
        .banner {
            background-image: url('https://via.placeholder.com/1500x500'); /* Cambia la URL por una imagen de productos ecológicos */
            background-size: cover;
            background-position: center;
            height: 500px;
            color: white;
            text-align: center;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .banner h2 {
            font-size: 3em;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
        }

        /* Sección de productos */
        .productos {
            padding: 50px 10%;
            text-align: center;
        }

        .productos h2 {
            font-size: 2em;
            margin-bottom: 30px;
        }

        .productos-grid {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .producto {
            background-color: white;
            padding: 20px;
            margin: 15px;
            width: 250px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .producto img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }

        .producto h3 {
            font-size: 1.5em;
            margin: 10px 0;
        }

        .producto p {
            font-size: 1em;
            color: #777;
        }

        .producto a {
            display: inline-block;
            margin-top: 10px;
            padding: 10px 20px;
            background-color: #4CAF50;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }

        .producto a:hover {
            background-color: #45a049;
        }

        /* Sección sobre nosotros */
        .sobre-nosotros {
            background-color: #e8f5e9;
            padding: 50px 10%;
            text-align: center;
        }

        .sobre-nosotros h2 {
            font-size: 2em;
            margin-bottom: 20px;
        }

        .sobre-nosotros p {
            font-size: 1.2em;
            max-width: 800px;
            margin: 0 auto;
            color: #555;
        }

        /* Footer */
        footer {
            background-color: #4CAF50;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
        }

        footer a {
            color: white;
            text-decoration: underline;
        }

        footer a:hover {
            color: #ddd;
        }
    </style>
</head>
<body>

    <!-- Encabezado -->
    <header>
        <h1>Tienda de Productos Ecológicos</h1>
        <nav>
            <a href="#productos">Productos</a>
            <a href="#nosotros">Sobre Nosotros</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <!-- Banner principal -->
    <section class="banner">
        <h2>Productos ecológicos para un mundo mejor</h2>
    </section>

    <!-- Sección de productos -->
    <section id="productos" class="productos">
        <h2>Nuestros Productos</h2>
        <div class="productos-grid">
            <div class="producto">
                <img src="https://via.placeholder.com/250" alt="Producto 1">
                <h3>Botella Reutilizable</h3>
                <p>Botella de acero inoxidable que ayuda a reducir el uso de plásticos.</p>
                <a href="#">Comprar ahora</a>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/250" alt="Producto 2">
                <h3>Bolsas de Tela</h3>
                <p>Bolsas de algodón orgánico, perfectas para tus compras diarias.</p>
                <a href="#">Comprar ahora</a>
            </div>
            <div class="producto">
                <img src="https://via.placeholder.com/250" alt="Producto 3">
                <h3>Utensilios de Bambú</h3>
                <p>Set de cubiertos reutilizables, fabricados con bambú sostenible.</p>
                <a href="#">Comprar ahora</a>
            </div>
        </div>
    </section>

    <!-- Sección sobre nosotros -->
    <section id="nosotros" class="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>Somos una tienda comprometida con el medio ambiente. Nuestro objetivo es ofrecer productos que reduzcan el impacto ecológico y promuevan un estilo de vida más sostenible. Cada compra que haces ayuda a cuidar el planeta para las futuras generaciones.</p>
    </section>

    <!-- Footer -->
    <footer id="contacto">
        <p>Contacto: <a href="mailto:info@productos-ecologicos.com">info@productos-ecologicos.com</a></p>
        <p>© 2024 Tienda de Productos Ecológicos. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
