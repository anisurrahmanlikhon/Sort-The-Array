
<html>
<body>
<title>Sort The Array</title>
<center>
<h1>Sort The Array</h1>

<button onclick="myFunction()">Descending Order</button><br><br>


<button onclick="myFunction1()">Ascending Order</button>
<br><br>

<p id="demo"></p>

<script>
var points = [40, 100, 1, 5, 25, 10,200,250,150];
document.getElementById("demo").innerHTML = points;

function myFunction1() {
  points.sort(function(a, b){return b-a});
  document.getElementById("demo").innerHTML = points;
}
</script>

<script>
var points = [40, 100, 1, 5, 25, 10,200,250,150];
document.getElementById("demo").innerHTML = points;

function myFunction() {
  points.sort(function(a, b){return a-b});
  document.getElementById("demo").innerHTML = points;
}
</script>
</center>

</body>
</html>

