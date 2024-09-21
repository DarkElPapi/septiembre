<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Feliz 21 de Septiembre!</title>

    <!-- Estilos CSS dentro del archivo HTML -->
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f7f0c0;
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
        }

        .girasol {
            position: relative;
            width: 150px;
            height: 150px;
            margin: 20px auto;
            animation: girar 5s infinite linear;
        }

        .pétalos {
            position: absolute;
            width: 100%;
            height: 100%;
            background: radial-gradient(circle, yellow 50%, transparent 51%);
            clip-path: polygon(50% 0%, 60% 25%, 100% 25%, 70% 50%, 100% 75%, 60% 75%, 50% 100%, 40% 75%, 0% 75%, 30% 50%, 0% 25%, 40% 25%);
        }

        .centro {
            position: absolute;
            width: 50px;
            height: 50px;
            background-color: brown;
            border-radius: 50%;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }

        @keyframes girar {
            from {
                transform: rotate(0deg);
            }
            to {
                transform: rotate(360deg);
            }
        }

        h1 {
            color: #ffcc00;
            font-size: 2rem;
            margin: 20px 0;
        }

        p {
            color: #444;
            font-size: 1.4rem;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="girasol">
            <div class="pétalos"></div>
            <div class="centro"></div>
        </div>
        <h1>¡Feliz día mi niñita! ❤️</h1>
        <p>Te Amo Mika : )</p>
    </div>

    <!-- JavaScript dentro del archivo HTML -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            console.log('¡El girasol está celebrando con Mika!');
        });
    </script>
</body>
</html>
