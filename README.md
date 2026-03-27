# xd
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Google Drive</title>
    <link rel="icon" href="https://ssl.gstatic.com/docs/doclist/images/drive_2022q3_32dp.png">
    <style>
        /* Esto elimina todos los bordes y barras de desplazamiento raras */
        body, html { 
            margin: 0; 
            padding: 0; 
            height: 100%; 
            width: 100%;
            overflow: hidden; 
            background-color: #000; /* Fondo negro por si el juego es oscuro */
        }
        /* Esto obliga al juego/proxy a ocupar exactamente el 100% de la pantalla visible */
        iframe { 
            position: absolute;
            top: 0;
            left: 0;
            width: 100%; 
            height: 100%; 
            border: none;
        }
    </style>
</head>
<body>
    <iframe src="https://maddoxcloud.com/app/google-chrome/run"></iframe>
</body>
</html>
