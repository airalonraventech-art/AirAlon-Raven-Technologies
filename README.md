<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AirAlon Raven Technologies</title>
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Orbitron:700|Montserrat:400,700&display=swap">
    <style>
        body {
            margin: 0;
            background: #0a0a0a;
            font-family: 'Montserrat', Arial, sans-serif;
            color: #fff;
        }
        header {
            text-align: center;
            padding-top: 2rem;
            padding-bottom: 2rem;
            background: linear-gradient(to bottom, #191919 90%, transparent 100%);
        }
        .logo-img {
            max-width: 340px;
            width: 95%;
            border-radius: 18px;
            box-shadow: 0 0 35px #d1003f85;
            margin-bottom: 1rem;
        }
        h1 {
            font-family: 'Orbitron', Arial, sans-serif;
            font-size: 2.7rem;
            color: #ff0035;
            text-shadow: 0 0 16px #ff0035aa;
            letter-spacing: 2px;
        }
        .lema {
            font-size: 1.1rem;
            font-weight: 700;
            margin-top: .5rem;
            margin-bottom: 0;
            color: #fff;
            text-shadow: 0 0 10px #d1003fcc;
        }
        nav {
            margin: 2rem 0 .5rem 0;
            text-align: center;
        }
        nav a {
            color: #fff;
            background: #d1003fcc;
            border-radius: 6px;
            padding: 7px 18px;
            text-decoration: none;
            margin: 0 8px;
            font-weight: 700;
            box-shadow: 0 0 10px #d1003f88;
            transition: background .3s;
        }
        nav a:hover {
            background: #ff0035;
        }
        section {
            max-width: 700px;
            margin: 2rem auto;
            background: rgba(30, 0, 18, 0.70);
            border-radius: 14px;
            box-shadow: 0 0 30px #d1003f30;
            padding: 2rem 1.5rem;
        }
        .frase-principal {
            font-size: 1.4rem;
            color: #ff0035;
            text-align: center;
            margin-bottom: 1.6rem;
            text-shadow: 0 0 10px #d1003faa;
        }
        .titulo-section {
            color: #ff0035;
            font-family: 'Orbitron', Arial, sans-serif;
            margin-bottom: 1rem;
            font-size: 1.4rem;
        }
        .servicios-lista {
            list-style: none;
            padding-left: 0;
        }
        .servicios-lista li:before {
            content: '• ';
            color: #ff0035;
        }
        .servicios-lista li {
            font-size: 1.1rem;
            padding-bottom: 7px;
            margin-left: 0;
        }
        .contacto-info {
            font-size: 1.1rem;
            margin-top: .8rem;
        }
        .contacto-info a {
            color: #ff0035;
            text-decoration: underline;
            margin-right: 15px;
        }
        .redes-sociales {
            text-align: right;
            margin-top: 8px;
        }
        .redes-sociales a {
            color: #ff0035;
            font-size: 1.5rem;
            margin-left: 10px;
            vertical-align: middle;
        }
        .footer {
            text-align: center;
            font-size: 0.9rem;
            color: #ccc;
            padding: 1rem 0 2rem 0;
            letter-spacing: .5px;
        }
        /* Whatsapp botón flotante */
        .wa-float {
            position: fixed;
            bottom: 28px;
            right: 28px;
            background: #25D366;
            color: #fff;
            border-radius: 50%;
            width: 60px;
            height: 60px;
            display: flex;
            box-shadow: 0 0 18px #25D36690;
            z-index: 99;
            justify-content: center;
            align-items: center;
            transition: box-shadow .4s;
        }
        .wa-float:hover {
            box-shadow: 0 0 34px #25D366cc;
            background: #128C7E;
        }
        .wa-icon {
            font-size: 2.2rem;
        }
        @media (max-width: 600px) {
            .logo-img {max-width:90vw;}
            section {padding: 1.2rem .6rem;}
            nav a {padding: 5px 10px;font-size:1rem;}
        }
    </style>
    <!-- Iconos para WhatsApp y Facebook -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <!-- Logo imagen proporcionada -->
        <img src="logo.jpg" alt="Logo AirAlon Raven Technologies" class="logo-img" />
        <h1>AirAlon Raven Technologies</h1>
        <p class="lema">Filipenses 4:13 &mdash; “Todo lo puedo en Cristo que me fortalece”</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="inicio">
        <div class="frase-principal">¿Tenés una PC en la oscuridad del olvido?<br>
            <span style="color: #fff;">Nosotros la reparamos y le hacemos su soporte.</span>
        </div>
        <hr style="border: 1px solid #ff0035; margin-bottom:2rem;">
        <div>
            <span class="titulo-section">Sobre Nosotros</span>
            <p>Somos una mini empresa apasionada por la tecnología y el servicio al cliente.
            Especializados en soporte de computadoras y soluciones informáticas, ponemos a tu disposición profesionalismo, honestidad y valores cristianos: <b>“Todo lo puedo en Cristo que me fortalece”</b>.</p>
        </div>
    </section>

    <section id="servicios">
        <span class="titulo-section">Servicios</span>
        <ul class="servicios-lista">
            <li>Soporte técnico especializado de PC</li>
            <li>Reparación de computadoras</li>
            <li>Mantenimiento preventivo y correctivo</li>
            <li>Instalación y actualización de software</li>
            <li>Asesoría en tecnología para empresas y hogares</li>
        </ul>
    </section>

    <section id="contacto">
        <span class="titulo-section">Contacto</span>
        <div class="contacto-info">
            <b>WhatsApp:</b> <a href="https://wa.me/50660938800" target="_blank">+506 6093 8800</a><br>
            <b>Email:</b> <a href="mailto:soporte@airalonraven.com">soporte@airalonraven.com</a><br>
        </div>
        <div class="redes-sociales">
            <a href="https://www.facebook.com/share/1AnaoJ9GVp/" target="_blank" title="Ir a Facebook"><i class="fab fa-facebook"></i> Facebook</a>
        </div>
    </section>

    <div class="footer">
        &copy; 2026 AirAlon Raven Technologies &mdash; Todos los derechos reservados.
    </div>

    <!-- Botón WhatsApp flotante -->
    <a class="wa-float" href="https://wa.me/50660938800" target="_blank" title="¿Necesitas soporte?">
        <i class="fab fa-whatsapp wa-icon"></i>
    </a>
</body>
</html>
