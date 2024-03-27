# EX01 Developing a Simple Webserver
## Date:

## AIM:
To develop a simple webserver to serve html pages.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Serving the HTML pages.

### Step 5:
Testing the webserver.

## PROGRAM:
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>

<body>
    <style>
        .icon {
            color: red;
            font-size: 25px;
            padding: 1%;
        }

        .icon:hover {
            color: gray;
        }

        a {
            padding: 10px;
            font-family: 'Courier New';
            color: rgb(123, 192, 201);
            text-decoration: dotted;
            font-size: 20px;

        }

        a:hover {
            color: red;
        }
    </style>
    <div style="height: 100%; background-color: #615b5b;">


        <div style="display: flex; height: 30%; background-color:rgb(18, 18, 26);">
            <div style="width: 9%; padding-top :2%">
                <img style="width: 100%;" src="gaming.png" alt="">
                
            </div>
            <div style="width: 60%; padding:5%; padding-left: 2%">
                <a href=""><b>HOME</b></a>
                <a href=""><b>GAME</b></a>
                <a href=""><b>CAR GAME</b></a>
                <a href=""><b>DRIVING</b></a>
                <a href=""><b>ABOUT</b></a>
            </div>
            <div style="width: 20%; padding-top: 5%;">
                <input style="height: 30px;
                width: 80%;
                background-image : url(search.png);
                background-size: contain;
                background-repeat : no-repeat;
                border-radius : 15px;
                padding-left : 40px; " type="text" name="search" >

            </div>
        </div>

        <div style="display:flex; height: 30px;">

            <div style="width: 100%; padding-top:0%;">
                <div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0"
                            class="active" aria-current="true" aria-label="Slide 1"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"
                            aria-label="Slide 2"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"
                            aria-label="Slide 3"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="3"
                            aria-label="Slide 4"></button>
                        <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="4"
                            aria-label="Slide 5"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                            <img src="p.png" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="game.png" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="third.png" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="123.png" class="d-block w-100" alt="...">
                        </div>
                        <div class="carousel-item">
                            <img src="four.png" class="d-block w-100" alt="...">
                        </div>
                    </div>
                    <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators"
                        data-bs-slide="prev">
                        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Previous</span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators"
                        data-bs-slide="next">
                        <span class="carousel-control-next-icon" aria-hidden="true"></span>
                        <span class="visually-hidden">Next</span>
                    </button>
                </div>
            </div>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
</body>

</html>

## OUTPUT:
![Screenshot 2024-03-27 131105](https://github.com/jayaseelan2006/simplewebserver/assets/151389443/8f3dfc8b-2f8d-4421-b34e-cb57959f1eb8)



## RESULT:
The program for implementing simple webserver is executed successfully.
