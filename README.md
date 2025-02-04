<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adrenalina Biker</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            background-color: #111;
            color: #eee;
        }

        header {
            background-color: #222;
            padding: 20px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo img {
            max-height: 50px;
        }

        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        nav li {
            margin-left: 20px;
        }

        nav a {
            color: #eee;
            text-decoration: none;
        }

        .cta button {
            background-color: #f00;
            color: #fff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .hero {
            background-image: url("moto-futurista.jpg");
            background-size: cover;
            background-position: center;
            height: 500px;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .hero-content {
            text-align: center;
            color: #fff;
        }

        .hero h1 {
            font-size: 4em;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 1.2em;
            margin-bottom: 30px;
        }

        .hero button {
            background-color: #f00;
            color: #fff;
            padding: 15px 30px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .featured-products {
            padding: 40px;
            text-align: center;
        }

        .featured-products h2 {
            margin-bottom: 30px;
        }

        .product-gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .product {
            width: 300px;
            background-color: #222;
            padding: 20px;
            border-radius: 10px;
        }

        .product img {
            width: 100%;
            border-radius: 5px;
            margin-bottom: 10px;
        }

        .about-us,
        .testimonials,
        .contact {
            padding: 40px;
        }

        footer {
            background-color: #222;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="Adrenalina Biker Logo">
        </div>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Productos</a></li>
                <li><a href="#">Sobre nosotros</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
        <div class="cta">
            <button>Compra ahora</button>
        </div>
    </header>

    <section class="hero">
        <div class="hero-content">
            <h1>Adrenalina Biker: Tu pasión por las motos comienza aquí</h1>
            <p>Encuentra los mejores accesorios y la comunidad biker que estabas buscando</p>
            <button>Descubre nuestros productos</button>
        </div>
    </section>

    <section class="featured-products">
        <h2>Nuestros productos estrella</h2>
        <div class="product-gallery">
            <div class="product">
                <img src="casco.jpg" alt="Casco">
                <h3>Casco de alta gama</h3>
                <p>Descripción breve del producto</p>
            </div>
            <div class="product">
                <img src="guantes.jpg" alt="Guantes">
                <h3>Guantes de cuero</h3>
                <p>Descripción breve del producto</p>
            </div>
            <div class="product">
                <img src="escape.jpg" alt="Escape">
                <h3>Escape deportivo</h3>
                <p>Descripción breve del producto</p>
            </div>
        </div>
    </section>

    <section class="about-us">
        <h2>Somos Adrenalina Biker</h2>
        <p>En Adrenalina Biker, no solo encontrarás los mejores accesorios para tu moto ⚙️, sino también un espacio donde compartir tu pasión por el motociclismo. Somos un equipo de entusiastas que entendemos la emoción y la libertad que se siente sobre dos ruedas , y queremos transmitirte esa misma adrenalina. ¡Únete a nuestra comunidad de bikers! ️</p>
    </section>

    <section class="testimonials">
        <h2>Lo que dicen nuestros clientes</h2>
        <div class="testimonial">
            <p>"Los mejores accesorios que he encontrado. ¡Recomendado!"</p>
            <p>- Juan Pérez</p>
        </div>
        <div class="testimonial">
            <p>"Excelente servicio y productos de alta calidad."</p>
            <p>- María Gómez</p>
        </div>
    </section>

    <section class="contact">
        <h2>Visítanos o contáctanos</h2>
        <p>Dirección: [Tu dirección]</p>
        <p>Teléfono: [Tu teléfono]</p>
        <p>Correo electrónico: [Tu correo electrónico]</p>
    </section>

    <footer>
        <p>&copy; 2023 Adrenalina Biker. Todos los derechos reservados.</p>
    </footer>
<script src="https://cdn.botpress.cloud/webchat/v2.2/inject.js"></script>
<script src="https://files.bpcontent.cloud/2025/02/04/04/20250204044814-U5MEMA25.js"></script>
  
</body>

</html>
