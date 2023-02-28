<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="stilo.css">
</head>
<body>
    
        <div class="calculator">
        
          <div class="buttons">
                     
                <div class="num-container">
                    <input type="text" id="display" placeholder="0">
                </div>
                <div class="num-container">
                    <button class="function" id="clear" onclick="resetear()">C</button>
                    <button class="number" id="eight" onclick="numeros(8)">8</button>
                    <button class="number" id="nine" onclick="numeros(9)">9</button>
                    <button class="operator" id="multiply" onclick="numeros('*')">x</button>
                </div>
                <div class="num-container">
                    <button class="number" id="seven" onclick="numeros(7)">7</button>
                    <button class="number" id="eight" onclick="numeros(8)">8</button>
                    <button class="number" id="nine" onclick="numeros(9)">9</button>
                    <button class="operator" id="multiply" onclick="numeros('*')">x</button>
                </div>
                <div class="num-container">
                    <button class="number" id="four" onclick="numeros(4)">4</button>
                    <button class="number" id="five" onclick="numeros(5)">5</button>
                    <button class="number" id="six" onclick="numeros(6)">6</button>
                    <button class="operator" id="subtract" onclick="numeros('-')">-</button>
                </div>
                <div class="num-container">
                    <button class="number" id="one" onclick="numeros(1)">1</button>
                    <button class="number" id="two" onclick="numeros(2)">2</button>
                    <button class="number" id="three" onclick="numeros(3)">3</button>
                    <button class="operator" id="add"onclick="numeros('+')">+</button>
                </div>
                <div class="num-container">
                    
                    <button class="operator" id="decimal"onclick="numeros(00)">00</button>
                    <button class="operator" id="zero" onclick="numeros(0)">0</button>
                    <button class="operator" id="decimal"onclick="numeros('.')">.</button>
                    <button class="operator" id="equals" onclick="operacion()">=</button>
                </div>
            </div>
        </div>
    
    </body>
    <script src="main.js"></script>
    </html>
