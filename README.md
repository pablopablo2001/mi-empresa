<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Empresa</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f7;
            color: #333;
        }
        header {
            background-color: #000;
            color: #fff;
            padding: 20px 0;
            text-align: center;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        .section {
            padding: 40px 0;
        }
        .section-title {
            text-align: center;
            font-size: 2.5em;
            margin-bottom: 20px;
        }
        .about, .projects, .contact {
            text-align: center;
        }
        .about p, .contact p {
            font-size: 1.2em;
            line-height: 1.6;
            margin-bottom: 20px;
        }
        .projects .project-list {
            list-style: none;
            padding: 0;
        }
        .projects .project-list li {
            margin-bottom: 15px;
            font-size: 1.2em;
        }
        .contact form {
            max-width: 600px;
            margin: 0 auto;
        }
        .contact form input, .contact form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .contact form button {
            padding: 10px 20px;
            background-color: #000;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        .contact form button:hover {
            background-color: #333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Mi Empresa</h1>
    </header>
    <div class="container">
        <section class="section about">
            <h2 class="section-title">Sobre Nosotros</h2>
            <p>Somos una empresa dedicada a ofrecer soluciones innovadoras en el campo de [tu industria]. Nuestro equipo de expertos trabaja con pasión y dedicación para entregar resultados excepcionales.</p>
        </section>
        <section class="section projects">
            <h2 class="section-title">Proyectos</h2>
            <ul class="project-list">
                <li>Proyecto 1: Descripción breve del proyecto 1.</li>
                <li>Proyecto 2: Descripción breve del proyecto 2.</li>
                <li>Proyecto 3: Descripción breve del proyecto 3.</li>
            </ul>
        </section>
        <section class="section contact">
            <h2 class="section-title">Contactar con Nosotros</h2>
            <p>Introduce aquí tus datos para darte información:</p>
            <form action="#" method="post">
                <input type="text" name="name" placeholder="Nombre" required>
                <input type="email" name="email" placeholder="Correo Electrónico" required>
                <textarea name="message" placeholder="Mensaje" rows="5" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </div>
</body>
</html>
