<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        .box{
            width: 100px;
            height: 100px;
            background-color: orange;

            transition-duration: 2s;
        }
        .box:hover{
            width: 200px;
            height: 300px;
        }
        .box:active{
            background-color: red;
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
