# Demo
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Media Queries</title>
    <style>
        body {
            background-color: red;
        }

        @media only screen and (max-width: 455px) {
         body {
            background-color: blue;
        }
        .boxes{
        flex-direction: column;
    }
    }

    .Box {
        
        width:344px;
        height:344px;
        margin:3px;
        padding:3px;
        background-color: rgb(168, 131, 131);
    }

   
    .boxes{
        display: flex;
        
    }
    
    </style>
    
</head>

<body>
    <div>
        Hello You interacting with Human.
    </div>
    <div class="boxes">
    <div class="Box box1"></div>
    <div class="Box box2"></div>
    <div class="Box box3"></div>
</div>
</body>

</html>
