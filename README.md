# Pagina-Web
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Primera Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 20px;
            background-color: white;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenidos a Mi Página Web</h1>
    </header>
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#sobre-mi">Sobre Mí</a>
        <a href="#contacto">Contacto</a>
    </nav>
    <section id="inicio">
        <h2>Inicio</h2>
        <p>Esta es la página de inicio de mi sitio web.</p>
    </section>
    <section id="sobre-mi">
        <h2>Sobre Mí</h2>
        <p>Información sobre mí y lo que hago.</p>
    </section>
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Puedes contactarme en: email@ejemplo.com</p>
    </section>
</body>
</html>