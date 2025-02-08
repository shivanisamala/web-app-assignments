# web-app-assignments
<!DOCTYPE html>

<html>
    <head>
        <script>
            function add() {
                x = parseInt(document.getElementById("num1").value);
                y = parseInt(document.getElementById("num2").value);

                let res = x + y;
                document.getElementById("res").value = res;

            }
            function sub() {
                x = parseInt(document.getElementById("num1").value);
                y = parseInt(document.getElementById("num2").value);

                let res = x - y;
                document.getElementById("res").value = res;

            }
            function mul() {
                x = parseInt(document.getElementById("num1").value);
                y = parseInt(document.getElementById("num2").value);

                let res = x * y;
                document.getElementById("res").value = res;

            }
            function div() {
                x = parseInt(document.getElementById("num1").value);
                y = parseInt(document.getElementById("num2").value);

                let res = x / y;
                document.getElementById("res").value = res;

            }
        </script>
        <style>
            input{
                width: 300px;
                font-size: 20px;
            }
            button{
                width: 230px;
                font-size: 20px;
            }
            .button_div{
                margin-top: 10px;
            }
            #container{
                padding: 10px;
                margin: 10px;
            }
        </style>
    </head>

    <body>
        <div id="container">
            <div class="input_div">
                <input placeholder="Enter the value of X" id="num1"/>
                <input placeholder="Enter the value of Y" id="num2"/>
                <input placeholder="Result will appear here" id="res" disabled/>
            </div>

            <div class="button_div">
                <button onclick="add();">Addition (X + Y)</button>
                <button onclick="sub();">Subtraction (X - Y)</button>
                <button onclick="mul();">Multiplication (X * Y)</button>
                <button onclick="div();">Division (X / Y)</button>
            </div>            
        </div>

    </body>
</html>
