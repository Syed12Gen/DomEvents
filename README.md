# DomEvents

<!DOCTYPE html>

<html>
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title></title>
        <meta name="description" content="">
        <meta name="viewport" content="width=device-width, initial-scale=1">
        <link rel="stylesheet" href="">
        
    </head>
    <body>
        <h1> Welcome..!!</h1>
        <button> Click </button>
 
        <script src="app.js"></script>
    </body>
</html>

JS HERE;

const button = document.querySelector('button')
const h1 = document.querySelector('h1')
button.addEventListener('click', function(){
const r = Math.floor(Math.random()*255);
const g = Math.floor(Math.random()*255);
const b = Math.floor(Math.random()*255);
const newColor = `rgb(${r}, ${g}, ${b})`;
document.body.style.backgroundColor = newColor;
h1.innerText = newColor;


})
