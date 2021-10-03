<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!--<link rel="stylesheet" href="Practice.css" --->
    <title>Practice one</title>
    <style>
        *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'poppins' sans-serif;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #0e1538;

}
.box::before{
    content: '';
    position: absolute;
    width: 150px;
    height: 140%;
    background: linear-gradient(#00ccff, #d400d4);
    animation: animate 4s linear infinite;
}
.box::after{
    content: '';
    position: absolute; 
    background: #0e1538;
    inset: 14px;
    background: #0e1538;
    border-radius: 10px;
}
.box{
    position: relative;
    width: 300px;
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    background: rgb(0, 0, 0, 0.5);
    overflow: hidden;
    border-radius: 20px;
   
}
@keyframes animate {
    0%{
        transform: rotate(0deg);
    }100%{
        transform: rotate(360deg);
    }
}
.box h2{
    position: relative;
    color: #fff;
    font-size: 10em;
    z-index: 10;
}

    </style>
</head>
<body>
    <div class="box">
        <h2>02</h2>
    </div>
  
</body>
</html>
