!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Componentes Eletrônicos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f8f9fa;
            margin: 0;
            padding: 0;
        }

        h1 {
            color: #333;
            margin-top: 20px;
        }

        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 20px;
        }

        .item {
            width: 250px;
            text-align: center;
            background-color: #fff;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            padding: 15px;
        }

        .item img {
            width: 100%;
            height: auto;
            border-radius: 10px;
        }

        .item h2 {
            font-size: 18px;
            margin: 10px 0;
            color: #555;
        }

        .item p {
            font-size: 14px;
            color: #666;
        }
    </style>
</head>
<body>
    <h1>Componentes Eletrônicos</h1>
    <p>Aprenda sobre os principais componentes utilizados em projetos eletrônicos e suas funcionalidades.</p>

    <div class="container">
        <!-- Protoboard -->
        <div class="item">
            <img src="https://cdn.sparkfun.com//assets/parts/1/1/9/2/15622-01.jpg" alt="Protoboard">
            <h2>Protoboard</h2>
            <p>Um protoboard é usado para montar circuitos eletrônicos sem a necessidade de solda. Ele facilita experimentos e prototipagem rápida.</p>
        </div>

        <!-- Resistores -->
        <div class="item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Resistors.jpg" alt="Resistores">
            <h2>Resistores</h2>
            <p>Os resistores limitam a corrente elétrica e ajustam os níveis de tensão em circuitos eletrônicos. Cada cor na sua faixa representa seu valor de resistência.</p>
        </div>

        <!-- LEDs -->
        <div class="item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/80/Leds.jpg" alt="LEDs">
            <h2>LEDs</h2>
            <p>LEDs (Diodos Emissores de Luz) convertem energia elétrica em luz e são usados em indicadores, iluminação e displays.</p>
        </div>

        <!-- Cabos Jumper -->
        <div class="item">
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/94/Jump_wire.jpg" alt="Cabos Jumper">
            <h2>Cabos Jumper</h2>
            <p>Cabos jumper conectam diferentes partes de um circuito em protoboards ou entre dispositivos eletrônicos.</p>
        </div>

        <!-- Cabo de Impressora -->
        <div class="item">
            <img src="https://cdn.pixabay.com/photo/2016/06/14/09/01/usb-1457645_960_720.jpg" alt="Cabo de Impressora">
            <h2>Cabo de Impressora</h2>
            <p>O cabo de impressora (USB-B) conecta dispositivos como impressoras e placas Arduino a computadores para transferência de dados e energia.</p>
        </div>
