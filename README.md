
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pedido Especial</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            position: relative;
        }
        h1 {
            font-size: 60px;
            color: red;
            text-shadow: 2px 2px 4px darkred;
        }
        .hearts {
            font-size: 30px;
            color: red;
            position: absolute;
        }
        .top-left { top: -50px; left: -50px; }
        .top-right { top: -50px; right: -50px; }
        .bottom-left { bottom: -50px; left: -50px; }
        .bottom-right { bottom: -50px; right: -50px; }
    </style>
</head>
<body>
    <div class="container">
        <div class="hearts top-left">❤️❤️❤️</div>
        <div class="hearts top-right">❤️❤️❤️</div>
        <h1>Eu te amo!<br>Quer namorar comigo?</h1>
        <div class="hearts bottom-left">❤️❤️❤️</div>
        <div class="hearts bottom-right">❤️❤️❤️</div>
    </div>
</body>
</html>
