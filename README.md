<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Ecooburgos - Estudio y Coordinación de Obras en Burgos">
    <title>Ecooburgos - Construcción y Coordinación</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="logo">
            <h1>Ecooburgos</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#nosotros">Nosotros</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio">
        <div class="banner">
            <h2>Construcción sostenible y de calidad</h2>
            <p>Más de 20 años de experiencia en proyectos de construcción y coordinación en Burgos.</p>
            <a href="#contacto" class="cta-btn">¡Contáctanos ahora!</a>
        </div>
    </section>

    <section id="nosotros">
        <h2>Quiénes somos</h2>
        <p>Somos un equipo especializado en la coordinación y ejecución de proyectos de construcción en Burgos, con más de 20 años de experiencia.</p>
    </section>

    <section id="servicios">
        <h2>Servicios</h2>
        <div class="service-list">
            <div class="service">
                <h3>Asesoramiento en Construcción</h3>
                <p>Ofrecemos asesoramiento integral para la ejecución de obras de todo tipo.</p>
            </div>
            <div class="service">
                <h3>Coordinación de Proyectos</h3>
                <p>Nos encargamos de coordinar todas las fases de tu proyecto de construcción.</p>
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
            <p><strong>Teléfono:</strong> +34 123 456 789</p>
            <p><strong>Email:</strong> contacto@ecooburgos.es</p>
            <p><strong>WhatsApp:</strong> <a href="https://wa.me/34123456789" target="_blank">Haz clic aquí para chatear</a></p>
        </div>
        <form>
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Ecooburgos. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
