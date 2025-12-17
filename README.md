<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Simple Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <h1>Hello World</h1>
    <button id="btn">Click me</button>

    <script src="script.js"></script>
</body>
</html>

//css
body {
    font-family: Arial, sans-serif;
    text-align: center;
    margin-top: 50px;
}

h1 {
    color: blue;
}

button {
    padding: 10px 20px;
    font-size: 16px;
    cursor: pointer;
}

//js
document.getElementById("btn").addEventListener("click", function () {
    alert("Button clicked!");
});
