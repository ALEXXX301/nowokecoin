# nowokecoin
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>No Woke Coin</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-image: url('path/to/your/image.png'); /* Asegúrate de que la ruta sea correcta */
            background-size: cover;
            background-position: center;
            text-align: center;
            color: white;
            font-family: Arial, sans-serif;
            flex-direction: column;
        }
        .links {
            display: flex;
            flex-direction: column;
            gap: 15px;
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 10px;
        }
        a {
            display: block;
            padding: 15px 25px;
            background: rgba(255, 255, 255, 0.2);
            color: white;
            text-decoration: none;
            font-size: 20px;
            border-radius: 5px;
        }
        a:hover {
            background: rgba(255, 255, 255, 0.5);
        }
    </style>
</head>
<body>
    <div class="links">
        <a href="#" id="link1" target="_blank">Enlace 1</a>
        <a href="#" id="link2" target="_blank">Enlace 2</a>
    </div>
    <script>
        document.getElementById('link1').href = prompt("Ingrese la URL para el primer enlace:");
        document.getElementById('link2').href = prompt("Ingrese la URL para el segundo enlace:");
    </script>
</body>
</html>
