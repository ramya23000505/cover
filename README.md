# Ex.06 Book Front Cover Page Design
## Date: 23.04.24

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style type="text/css">
            .bookcover {
                width: 400px;
                height: 640px;
                color:black (221, 39, 39);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:Verdana, Geneva, Tahoma, sans-serif;
                background-image: url(book.png );
                background-size: cover;
            }
            .insight {
                color:white;
            }
            .hr1 {
                width: 131px;
                color:black (221, 39, 39);
            }
            .h1 {
                font-size: larger;
                font-family: Arial, Helvetica, sans-serif;
                text-align: center;
                position: relative;
                top: 30px;
                color:white;
            }
            .para {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                position: relative;
                width: 100px;
                top: 40px; 
                color:white; 
            }
            .pic {
                position: relative;
                top: 100px;
                right: 8px;
                width: 1px;
                height: 3px;
                background-size: cover;
                color:black (221, 39, 39);
            }
            .hr2 {
                position: relative;
                width: 400px;
                top: 120px;
                color:white;
            }
            .name {
                font-size: medium;
                font-family: Arial, Helvetica, sans-serif;
                display: inline;
                position: relative;
                color:white;
                right: 5px;
                top: 140px;
            }
            .hr3 {
                position: relative;
                width: 130px;
                top: 110px;
                left: 280px;
                color:white;
            }
            
            .pub {
                font-size: small;
                position: relative;
                top: 145px;
                left: 330px; 
                color:white;
            }
            .sav {
                font-size: small;
                position: relative;
                top: 130px;
                left: 300px;
                color:white;
            }
        </style>
        <title> Book Front Cover Page  </title>
    </head>
    <body>
        <div class="bookcover">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hr1">
                <hr>
            </div>
            <div class="h1">
                <h1> WORLD OF TALES </h1>
            </div>
            <div class="para">
                <p> "World of Tales" typically refers to a vast collection of folklore and fairy tales from various cultures worldwide </p>
            </div>
            <div class="name">
                <p><b>RAMYA R</b></p>
            </div>
            <div class="pub">
                <h5>Published by</h5>
            </div>
            <div class="pic">
                <img src="pic1.jpg" alt="" style="height: 100px">
            </div>
            <div class="sav">
                <h7>@saveetha.ac.in <h7>
            </div>
            <div class="edition">
                <b> THIRD EDITION</b>
            </div>
            <div class="hr3">
                <hr>
            </div>
        </div>
    </body>
</html>
```
## OUTPUT:
![Screenshot 2024-04-23 215536](https://github.com/ramya23000505/cover/assets/149370791/094c7983-cad6-4bc3-9ee6-09d978401b93)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
