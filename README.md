<!DOCTYPE html>

<html lang="en">

<head>

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Multiplication Table</title>

</head>

<body>

<h1>Multiplication Table</h1>

<div id="result"></div>

<script>

const number = 7; 

document.write("<h2>Multiplication Table of " + number + ":</h2>");

for (let i = 1; i <= 10; i++) {

const result = number * i;

document.write(number + " * " + i + " = " + result + "<br>");

}

</script>

</body>

</html>
