<!DOCTYPE html>
<html lang="en">
    <style>
        body {
   
   color: #FFF;
   background: #848584;
   background: linear-gradient(to left, rgb(46, 248, 147), rgb(248, 135, 5)); 
}
    </style>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Jogo Da Velha/Unis/</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
    <h1>Bora Jogar</h1>
    <div class='game'></div>

    <script src="js/Jogo_da_velha.js"></script>
    <script>
        tic_tac_toe.init( document.querySelector('.game') );
        tic_tac_toe.start();
    </script>
    
</body>
</html>
