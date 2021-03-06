# Design of Responsive Website
## AIM:
To design a responsive website with two break points.

## DESIGN STEPS:
### Step 1: 
Requirement collection.
### Step 2:
Creating the layout using HTML and CSS.
### Step 3:
Updating the sample content.
### Step 4:
Choose the appropriate style and color scheme.
### Step 5:
Validate the layout in various browsers.
### Step 6:
Validate the HTML code.
### Step 7:
Create a database model and migrate the database.
### Step 8:
Retrieve data from database and display it in a dynamic webpage.
### Step 9:
Publish the website in the given URL.

## PROGRAM:
### responsepage.html
```
<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/css/bootstrap.min.css" integrity="sha384-B0vP5xmATw1+K9KRQjQERJvTumQW0nPEzvF6L/Z6nronJ3oUOFUFpCjEUQouq2+l" crossorigin="anonymous">

    <title>Silicon Private Limited</title>
  </head>
  <body>
    
        <div class="jumbotron jumbotron-fluid" style="background-color: aqua;">        
            <div class="container text-center">
            <h1>Silicon Private Limited</h1>
            <p class="lead">We manufacture high quality electronic products</p>
            </div>
        </div>      
        <div class="container text-center">
            <div class="row ">
                <div class="col-12 col-md-3 text-center">  
                   <a href="#">Home</a>
                </div>
                <div class="col-12 col-md-3 text-center">  
                   <a href="#">Products</a>   
                </div>     
                <div class="col-12 col-md-3 text-center">  
                   <a href="#">People</a>     
                </div>   
                <div class="col-12 col-md-3 text-center">  
                   <a href="#">Contact Us</a>     
                </div>                                        
            </div>
            <div class="row">
                    <div class="col-12 lead text-center m-3">
                        Our Premium Products
                    </div>
            </div>  
            <div class="row">
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/optical.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">OPTICAL LENCE</h5>
                    <p class="card-text">Price: Rs.2000</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/satahdd.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">1TB Laptop HDD</h5>
                    <p class="card-text">Price: Rs.5000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/watch.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">WATCH</h5>
                    <p class="card-text">Price: Rs.700.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/modem.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">WIFI DEVICE</h5>
                    <p class="card-text">Price: Rs.5000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/c1.jpg" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">4GB DDRA4 laptop memory</h5>
                    <p class="card-text">Price: Rs.2000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/battry.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">BATTRY</h5>
                    <p class="card-text">Price: Rs.5000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div> 

                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/microchip.jfif" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">MICRO CHIP</h5>
                    <p class="card-text">Price: Rs.5000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div> 
                <div class="card col-12 col-md-6 col-lg-3">
                <img class="card-img-top" src="/static/img/spray.png" alt="Card image cap">
                <div class="card-body">
                    <h5 class="card-title">spray</h5>
                    <p class="card-text">Price: Rs.5000.00</p>
                    <a href="#" class="btn btn-primary">More</a>
                </div>
                </div>                                  

            </div>  
            <div class="row">
                    <div class="col-12" style="background-color: aqua;">
                            Copyright © 2020 Silicon Private Limited, Developed by SUGANYA PARTHIBAN.
                    </div>
            </div>                      
        </div>
              

    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-Piv4xVNRyMGpqkS2by6br4gNJ7DXjqk09RmUpJ8jgGtD7zP9yug3goQfGII0yAns" crossorigin="anonymous"></script>

    <!-- Option 2: Separate Popper and Bootstrap JS -->
    <!--
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.0/dist/js/bootstrap.min.js" integrity="sha384-+YQ4JLhjyBLPDQt//I+STsc9iw4uQqACwlvpslubQzn4u2UU2UFM80nGisd026JF" crossorigin="anonymous"></script>
    -->
  </body>
</html>

```


## OUTPUT:
![output](./static/img/o1.png)

![output](./static/img/o2.png)

![output](./static/img/o3.png)

![output](./static/img/o4.png)

![output](./static/img/o5.png)

## validation report


![output](./static/img/v1.png)

## RESULT:
Thus a website is designed for the chip manufacturing company and is hosted in the URL http://suganya.student.saveetha.in:8000/responsivepage . HTML code is validated.