<html>
<head>
  <title>My Calculator</title>
</head>
<body>
  <h3>Calculator</h3>
  <label for="num1">First value:</label>
  <input type=number id="num1"><br><br>
  <label for="num2">Second value:</label>
  <input type=number id="num2"><br><br>
  <button onclick="addnum();">Add</button>
  <button onclick="subnum();">Subtract</button>
  <button onclick="mulnum();">Multiply</button>

  <script>
    function addNum() {
      var y = document.getElementById("num1").value;
      var z = document.getElementById("num2").value;
      window.alert(y+z);
    }
    function subNum() {
      var y = document.getElementById("num1").value;
      var z = document.getElementById("num2").value;
      window.alert(Number(y)-Number(z));
    }
    function mulNum() {
      var y = document.getElementById("num1").value;
      var z = document.getElementById("num2").value;
      window.alert(Number(y)*Number(z));
    }
  </script>
</body>
</html>
