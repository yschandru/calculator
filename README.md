# calculator
<html>
    <head> CALCULATOR</head>
    <body>
        <h2> enter first number</h2><br>
        <input type="text" id="n1" name="n1"/><br>
        <h2> enter second number </h2><br>
        <input type="text" id="n2" name="n2"/><br>
        <button value="add" onclick="addition()">add
        <button value="sub" onclick="substraction()">sub
        <button value="mul" onclick="multiplication()">mul
        <button value="div" onclick="division()">div
        </button>
        </button>
        </button>
        </button>
        <h2> total sum</h2>
        <input type="text" id="result" name="result"/>
        <script>
            function addition()
            {
                const a=parseInt(document.getElementById("n1").value);
                const b=parseInt(document.getElementById("n2").value);
                const c=a+b;
                document.getElementById("result").value=c;
            }
            function substraction()
            {
                const a=parseInt(document.getElementById("n1").value);
                const b=parseInt(document.getElementById("n2").value);
                const c=a-b;
                document.getElementById("result").value=c;
            }function multiplication()
            {
                const a=parseInt(document.getElementById("n1").value);
                const b=parseInt(document.getElementById("n2").value);
                const c=a*b;
                document.getElementById("result").value=c;
            }function division()
            {
                const a=parseInt(document.getElementById("n1").value);
                const b=parseInt(document.getElementById("n2").value);
                const c=a/b;
                document.getElementById("result").value=c;
            }
            
        </script>

    </body>
</html>
