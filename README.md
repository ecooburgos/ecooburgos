<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ecooburgos - Estudio y Coordinación de Obras en Burgos">
    <title>Ecooburgos - Construcción y Coordinación</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        body {
            background-color: #f8f9fa;
            color: #333;
        }
        header {
            background: linear-gradient(135deg, #007bff, #6610f2);
            color: white;
            padding: 20px;
            text-align: center;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
        }
        nav ul {
            list-style: none;
            padding: 0;
            text-align: center;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: 600;
        }
        .banner {
            background: url('banner.jpg') no-repeat center center/cover;
            height: 70vh;
            display: flex;
            align-items: center;
            justify-content: center;
            flex-direction: column;
            text-align: center;
            color: white;
            padding: 20px;
        }
        .banner h2 {
            font-size: 3em;
            animation: fadeIn 2s ease-in-out;
        }
        .cta-btn {
            display: inline-block;
            margin-top: 20px;
            padding: 12px 25px;
            background: #ff6600;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            border-radius: 10px;
            transition: 0.3s;
        }
        .cta-btn:hover {
            background: #cc5500;
        }
        section {
            padding: 60px 20px;
            text-align: center;
        }
        .service-list {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
        }
        .service {
            background: white;
            padding: 30px;
            border-radius: 12px;
            box-shadow: 0px 5px 15px rgba(0,0,0,0.1);
            width: 280px;
            transition: transform 0.3s;
        }
        .service:hover {
            transform: translateY(-10px);
        }
        .service i {
            font-size: 2em;
            color: #007bff;
            margin-bottom: 10px;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }
        .gallery img {
            width: 300px;
            border-radius: 10px;
            transition: 0.3s;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
        .contact-info p {
            font-size: 1.2em;
            margin-bottom: 10px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Ecooburgos</h1>
        <nav>
            <ul>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <section class="banner">
        <h2>Construcción sostenible y de calidad</h2>
        <p>Más de 20 años de experiencia en proyectos de construcción y coordinación en Burgos.</p>
        <a href="#contacto" class="cta-btn">¡Contáctanos ahora!</a>
    </section>
    <section id="nosotros">
        <h2>Quiénes somos</h2>
        <p>Somos un equipo especializado en la coordinación y ejecución de proyectos de construcción en Burgos.</p>
    </section>
    <section id="servicios">
        <h2>Servicios</h2>
        <div class="service-list">
            <div class="service">
                <i class="fas fa-hard-hat"></i>
                <h3>Asesoramiento</h3>
                <p>Te ayudamos en cada fase de tu proyecto de construcción.</p>
            </div>
            <div class="service">
                <i class="fas fa-project-diagram"></i>
                <h3>Coordinación</h3>
                <p>Gestionamos todas las partes de la obra para garantizar calidad.</p>
            </div>
        </div>
    </section>
    <section id="proyectos">
        <h2>Proyectos Realizados</h2>
        <div class="gallery">
            <img src="proyecto1.jpg" alt="Proyecto 1">
            <img src="proyecto2.jpg" alt="Proyecto 2">
        </div>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes alguna consulta? ¡Estamos para ayudarte!</p>
        <div class="contact-info">
            <p><i class="fas fa-phone"></i> <strong>Teléfono:</strong> +34 123 456 789</p>
            <p><i class="fas fa-envelope"></i> <strong>Email:</strong> contacto@ecooburgos.es</p>
            <p><i class="fab fa-whatsapp"></i> <strong>WhatsApp:</strong> <a href="https://wa.me/34123456789" target="_blank">Chatear ahora</a></p>
        </div>
    </section>
    <footer>
        <p>&copy; 2025 Ecooburgos. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
