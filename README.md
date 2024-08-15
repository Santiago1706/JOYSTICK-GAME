<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyectos de Matriz LED</title>
    <link rel="icon" type="image/png" href="https://ideogram.ai/assets/progressive-image/balanced/response/7Clo_RpLTMSB0eSO0hzyAw">
    <style>
        /* Estilos CSS */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000000;
            background-image: url('https://i.pinimg.com/474x/f1/45/05/f1450577ee5ec66dee6ec938b6b186ee.jpg');
            background-size: cover;
            background-position: top;
            color: #FFFFFF;
        }
        header {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            padding: 30px 0;
            text-align: center;
            margin-bottom: 20px; /* Margen inferior agregado */
        }
        .logo img {
            width: 200px; /* Tamaño del logo 1 */
            display: block;
            margin: 0 auto; /* Centrar horizontalmente */
        }
        nav {
            background-color: transparent; /* Color transparente */
            padding: 10px 0;
            text-align: center;
            padding-bottom: 10px; /* Aumento del padding inferior */
        }
        nav a {
            display: inline-block; /* Modificado para mostrar en línea */
            color: #FFFFFF; /* Cambiado a color blanco */
            text-decoration: none;
            margin: 10px; /* Se cambió margin-top y margin-bottom a margin */
            padding: 10px;
            border-radius: 5px;
            background-color: transparent; /* Color transparente */
            border: 2px solid #FFFFFF; /* Agregar borde blanco */
            transition: background-color 0.3s ease;
        }
        nav a:hover {
            background-color: #93C0EE;
        }
        section {
            padding: 30px;
            margin: 20px;
            background-color: rgba(255, 255, 255, 0.9); /* Fondo blanco semitransparente */
            border-radius: 10px;
            box-shadow: 0 5px 10px rgba(0, 0, 0, 0.1);
        }
        section h2,
        section p {
            color: #000000; /* Cambiar color del texto a negro */
        }
        footer {
            background-color: rgba(0, 0, 0, 0.5); /* Fondo semitransparente */
            color: #FFFFFF; /* Cambiado a color blanco */
            padding: 20px 0;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        /* Estilos para el menú */
        .Menu {
            padding-bottom: 22px;
            width: 100%;
            margin: 0 auto;
            text-align: center;
        }
        .Menu ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex; /* Cambiado a flex para hacer el menú horizontal */
            justify-content: center; /* Centrar los elementos */
        }
        /* Estilos para la galería de imágenes */
        .galery {
            display: flex;
            height: 20rem;
            gap: 1rem;
        }
        .galery > div {
            flex: 1;
            border-radius: 1rem;
            background-position: center;
            background-repeat: no-repeat;
            background-size: auto 100%;
            transition: all .8s cubic-bezier(.25, .04, .45, 1.4);
        }
        .galery > div:hover {
            flex: 5;
        }
        /* Estilos para el contenedor de video */
        .video-container {
            display: flex;
            justify-content: center; /* Centra el video horizontalmente */
            align-items: center;     /* Centra el video verticalmente (opcional) */
            padding: 20px 0;
        }
        .video-container iframe {
            border: none;
            width: 80%;   /* Ajusta el ancho del iframe a un porcentaje del contenedor */
            height: 450px; /* Ajusta la altura del iframe a un valor fijo */
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="https://colegiodivinosalvadorcali.edu.co/images/fixed/ESCUDO%20OFICIAl.png" alt="Logo 1">
        </div>
        <h1>Joystick Game</h1>
    </header>

    <nav>
        <div class="Menu">
            <ul>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/PROYECTOS%20DE%20MATRIZ%20LED%20PAGINA%20PRINCIPAL.html">Página Principal</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/PANTALLA%20DE%20LETRAS.html">Pantalla de Letras</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/JUEGO%20DE%20JOYSTICK.html">Juego con Joystick</a></li>
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/JOYSTICK%20GAME.html">Joystick Game</a></li>
            </ul>   
        </div>
    </nav>

    <section id="Introduction">
        <h2>INTRODUCTION</h2>
        <p>In this website, we are going to collect information about the activities realized with the Matriz LED 8x8. We created two circuits with different functionalities: the first one displays a message that says "te amo" in a consecutive form, and the second one is a snake game where the snake increases in size as it consumes points that spawn randomly on the map. The first circuit uses several materials, mainly the LED matrix and male/female cables. Its operation is simple as we only need to create the code in Chat GPT that instructs the matrix on which lights to turn on to form letters and create a simple message. The snake game, however, was more challenging due to the implementation of a joystick into the circuit. After completing the functional part of the circuit, we built a box for better presentation and to give the circuit a recreational device appearance. We faced some difficulties with the LED matrix, particularly with an issue we couldn't identify, which affected the first activity, although it was less problematic in the second. In conclusion, this page is dedicated to showing the results of the activities realized with the LED matrix in informatics.</p>
    </section>

    <section id="Operation">
        <h2>OPERATION</h2>
        <p>First, the connections between the LED matrix and the Arduino were made both to supply it with electrical power and to transmit the information from the computer to the Arduino so that it gives orders to the matrix. Then, the GND (ground) of the matrix was connected to the GND of the Arduino, to avoid damaging any additional parts being used. The DIN of the matrix was connected to pin 12 of the Arduino to pass the information on what the LED matrix has to do. The CS of the matrix was connected to pin 10 with a similar objective, and finally, the CLK of the matrix was connected to pin 11 of the Arduino to synchronize the two devices.</p>
    </section>

    <section id="materials">
        <h2>MATERIALS</h2>
        <h3>Very few materials were used for this project:</h3>
        <ul>
            <li>5 male/female cables</li>
            <li>An Arduino with its respective cable to connect it to the computer</li>
            <li>The LED matrix</li>
        </ul>
    </section>

    <section id="step by step">
        <h2>STEP BY STEP</h2>
        <p>First, the connections between the LED matrix and the Arduino were made. Then, the GND (ground) of the matrix was connected to the GND of the Arduino, the DIN of the matrix was connected to pin 12 of the Arduino, the CS of the matrix was connected to pin 10, and the CLK of the matrix was connected to pin 11.</p>
    </section>

    <section id="final product">
        <h2>Final Product</h2>
        <div class="video-container">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/jki3DkQ19DM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </section>

    <!-- Nueva sección de galería de imágenes -->
    <section class="galery">
        <div style="background-image: url('https://www.google.com/url?sa=i&url=https%3A%2F%2Felectronicacaribe.com%2Fproduct%2Fmodulo-matriz-led-8x8-max7219-para-arduino%2F&psig=AOvVaw1SBz-XuTREydK01FptvGPK&ust=1723644716280000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCOCxlIuT8ocDFQAAAAAdAAAAABAE');"></div>
        <div style="background-image: url('https://robotuno.com/wp-content/uploads/2022/05/esquema-Fritzing-snake-game_bb.webp');"></div>
        <div style="background-image: url('https://i.ytimg.com/vi/P9ZiFsZbwew/maxresdefault.jpg');"></div>
        <div style="background-image: url('');"></div>
        <div style="background-image: url('');"></div>
    </section>

    <footer>
        <p>&copy; 2024 - Combita y Laiseca - Matriz LED - C.D.S</p>
    </footer>
</body>
</html>
