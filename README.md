<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyectos de Matriz LED</title>
    <!-- Agrega el ícono de la pestaña del navegador -->
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
                <li><a href="file:///C:/Users/esteban%20laiseca%20hoyo/OneDrive/Escritorio/TRABAJO%20DE%20MATRIZ%20LED/MATRIZ%20LED%20PROYECTOS/JOYSTICK%20GAME.html">joystick game</a></li>
            </ul>   
        </div>
    </nav>

    <section id="Introduction">
        <h2>INTRODUCTION</h2>
        <p>In this website we are going to collect the information to undertake in the activities realized with the Matriz LED 8x8, in which we makes a pair of circuits with differents functionalities, the first one shows a mensaje that says “te amo” in a consecutive form and the second one consisted in the construction of a snake, that is based in increment the size of a snake getting points that spawn in randomly mode along the map. For the first circuit we use a lot of materials, among they stand out mostly the Matriz LED and the male/female cables, about the operation of the first circuit, it's very simple, because we only need to create the code un Chat GPT, that order to the matriz what lights turn on to form letters and with the sucesión of those create a simple mensaje. Talking about the snake game that presents more difficulty than the last one, that's because the joystick was implemented into the circuit. When we finished the functional part of the circuit, we created a box that works to get a better presentation and helps the circuit to look like a recreational device. In both activities we has some difficulties, because the matriz led had a that we can't identificate, preventing that the first activity was realized in totally normally, the same error appear in the second activity, in conclusión this page is dedicated to show the results of the activities realized with the matriz LED in informatic.</p>
    </section>

    <section id="Operation">
        <h2>OPERATION</h2>
        <p>First, the connections between the LED matrix and the Arduino were made both to supply it with electrical power and to transmit the information from the computer to the Arduino so that it gives the orders to the matrix, then the GND (ground pole) of the matrix was connected to the GND of the Arduino, this is done in order to avoid damaging any additional parts that are being used, since the role of the ground pole is to receive the energy avoiding it from damaging other parts of the circuit, the DIN of the matrix was connected to pin 12 of the Arduino so that it passes the information of what the LED matrix has to do, the CS of the matrix was connected to pin 10 with a similar objective to the previous one and finally the CLK of the matrix to pin 11 of the Arduino so that the two devices are synchronized.</p>
    </section>

    <section id="materials">
    <h2>MATERIALS</h2>
    <h2>Very few materials were used for this project:</h2> <!-- Este es el subtítulo añadido -->
    <p>- 5 male/female cables</p>

<p>- An Arduino with its respective cable to connect it to the computer</p>

<p>- the LED matrix.</p> <!-- Etiqueta de texto añadida -->
</section>

    </section>

    <section id="step by step">
        <h2>STEP BY STEP</h2>
        <p>First, the connections between the LED matrix and the Arduino were made, then the GND (ground) of the matrix was connected to the GND of the Arduino, the DIN of the matrix was connected to pin 12 of the Arduino, the CS of the matrix was connected to pin 10 and finally the CLK of the matrix to pin 11 of the Arduino.</p>

<p>Later, the code was integrated that gave the order to the LED matrix to write "I LOVE YOU", so that each letter appears consecutively to the previous one.</p>
    </section>

    <section id="Knowledge acquired">
        <h2>KNOWLEDGE ACQUIRED</h2>
        <p>At the end of this process we discovered a couple of new concepts when using the 8x8 matrix, among them is "VCC" which means (direct current voltage) which provides electrical power without any type of alteration, followed by this is the "DIN" which establishes a connection with the interface, the "CS" connection that sends the information to the matrix and finally the "CLK" which synchronizes the two devices.</p>
    </section>

 <section id="References">
        <h2>REFERENCES</h2>
        <p> 
<br>Carmenate, J. G. (2020, November 3). Matriz de LED 8x8 con Arduino y driver MAX7219. Programarfacil Arduino y Home Assistant. https://programarfacil.com/blog/arduino-blog/matriz-led-arduino-max7219/</br>

<br>Cómo funciona la toma de tierra GND: cómo conectarla correctamente. (2021, June 8). Descubrearduino.com. https://descubrearduino.com/gnd/</br>

<br>Profesor, L. E. D. (2021, December 14). Diferencia entre voltaje constante (VC) y corriente constante (CC). Ledbox News; Profesor LED. https://blog.ledbox.es/diferencia-entre-voltaje-constante-vc-y-corriente-constante-cc/</br>

<br>Secuenciales, S. (n.d.). Ingeniería de sistemas industriales Curso 2019-2020. Cartagena99.com. Retrieved August 5, 2024, from https://www.cartagena99.com/recursos/alumnos/apuntes/Apuntes%20secuenciales.pdf</br></p>
    </section>

    <section id="video de solución">
        <h2>VIDEO DE SOLUCIÓN</h2>
     
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video de YouTube</title>
</head>
<body>
    <div style="max-width: 605px; min-width: 325px;">
        <iframe width="560" height="315" src="" 
        title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; 
        clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
</body>

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
