# Ex.06 Book Front Cover Page Design
## Date: 28/04/2025
## Name: Saravana Kumar S
## Reg no: 212224220090

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
<!DOCTYPE html>
<html>
    <head>
        <title>
            Front cover page
        </title>
        <style>
            .bookpage{
                height:700px;
                width:500px;
                margin-left:35%;
                background-image: url(back.jpg);
                padding:10px;
                background-size: cover;
            }
            .hr1{
                width:200px

            }
            .booktitle{
                margin-top: 30px;
                color:rgb(18, 3, 3);
                padding:5px;
                font-size: xx-large;
            }
            .subtitle{
                color:rgb(19, 16, 16);
                font-size: large;
            }
            .mypic{
                position: relative;
                top:90px;
                left:360px;
                height: 80px;
                width: 90px;
            }
            .hr2{
                padding-top: 130px;
            
            }
            *{
                color: rgb(34, 32, 32);
            }
            .ed{
                position:relative;
                top: 110px;
            }
            .author{
                font-family: 'Trebuchet MS';
                font-size: large;
                
            }
            .pb{
                position: relative;
                left:420px;
                top:-40px;
                font-size: x-large;
            }
        </style>
        <body>
            <div class="bookpage">
            <div style="color:rgb(37, 5, 5)">INSIGHT </div>
            <div class="hr1"><hr ></div>
            <div class="booktitle"><h1>Modern C for Absolute Beginners</h1></div>
            <div class="subtitle">A Friendly introduction for <br>C Programming Language</div>
            <div class="mypic"><img src="picture.png.jpg" height="140px" ></div>
            <div class="ed">SPECIAL EDITION</div>
            <div class="hr2"><hr ></div>
            <div class="author"> Bala B</div>
            <div class="pb"> <h2>SEC</h2></div>
        </div>
        </body>
    </head>
</html>
```

## OUTPUT:
![Screenshot 2025-04-27 150710](https://github.com/user-attachments/assets/5bf376b8-6401-4f9a-9ef4-45d2c1471c57)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
