<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mobile QR-CODE</title>
    <link rel="icon" href="./images/favicon-32x32.png">
    <style>
.divcontainer{
            width: 1100px;
            background-color: hsl(212, 45%, 89%);
            height: 500px;
            position: absolute;
            top: 50px;
            left: 60px;
}
.grid {
    display: grid;
    background-color: white;
    grid-template-rows: 190px;
    position: relative;
    top: 80px;
    left: 460px;
    right: 100px;
    width: 155px;
    padding-left: 10px;
    padding-top: 10px;
    padding-right: 10px;
    border-radius: 10px;
    
}

        .text1 {
            color: black;
            font-weight: 700;
            font-size: 14px;
            text-align: center;
            
        }

        .text2 {
            color: darkgray;
            text-align: center;
            font-size: 10px;
            
        }

        img {
            border-radius: 10px;
        }
        @media (max-width: 710px) {
        .divcontainer{
            width: 100%;
            background-color: hsl(212, 45%, 89%);
            height: 500px;
            position: static;
            
            
            
            
            
          

        }
        .grid {
            display: grid;
            background-color: white;
            grid-template-rows: 190px;
            position: relative;
            top: 80px;
            left: 30%;
            right: 100px;
            width: 155px;
            padding-left: 10px;
            padding-top: 10px;
            padding-right: 10px;
            border-radius: 10px;
    

        }
    }

    </style>
</head>
<body>
    <div class="divcontainer">
        
            <div class="grid">
                <a href="https://www.frontendmentor.io" target="_blank">
                    <img src="./images/image-qr-code.png" width="152px" height="180px">
                    </a>
                
                    <p class="text1">Improve your front-end skills by building projects</p>
                    <p class="text2">Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>




            </div>

    
    </div>
   
            
</body>
</html>
