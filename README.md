<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amor</title>
    <style>
        body {
            background-color: #161616;
        }
    
        img {
            width: 300px; /* Largura da imagem */
            height: auto; /* Altura automática para manter a proporção */
            transition: transform 0.5s ease; /* Transição para suavizar a animação */
        }
    
        /* Animação de batimento cardíaco */
        img:hover {
            animation: heartbeat 0.47s infinite; /* Inicia a animação ao passar o mouse */
        }
    
        /* Keyframes para a animação de batimento cardíaco */
        @keyframes heartbeat {
            50% {
                transform: scale(1); /* Escala normal */
            }
            75% {
                transform: scale(1.1); /* Escala aumentada */
            }
            100% {
                transform: scale(1); /* Retorna à escala normal */
            }
        }
    </style>
</head>
<body>
    <center>
        <h1 style="color: aliceblue; font-style: oblique;"> Ola Rebecca</h1>
        <p style="color: aliceblue; font-style: italic;">Terminei</p>
        <p style="color: aliceblue;font-style: italic;">É pouco, mas deu trabalho</p>
        <p style="color: aliceblue;font-style: italic;"></p>
        <p style="color: aliceblue;font-style: italic;">Espero Que Goste sz</p>
        <!-- Envolve a imagem em uma tag <a> para criar um link -->
        <a href="http://127.0.0.1:3000/pedido/Amor 2.html" style="background-color: #161616;">
            <img src="https://www.pngall.com/wp-content/uploads/4/Heart-Symbol-PNG-Free-Image.png">
        </a>
        <p style="color: aliceblue; font-style: italic;">Meu Coração Quando Falo Com Vc</p>
    </center>
</body>
</html>
