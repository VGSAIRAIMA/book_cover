# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BOOKCOVER</title>
    <link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@700&family=Montserrat:wght@400&display=swap" rel="stylesheet">
    <style>
        .display{
            display: flex;
            justify-content: center;

        }
        .container{
            position: relative;
            width: 550px;
        }
        img{
            height: 700px;
            width: 600px;
        }
        .tagline{
            position:absolute;
            top: 10px;           
            left: 14%;
            margin: auto; 
            font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
            letter-spacing: 5px;
            color: rgb(217, 153, 81);
        }
        .title
        {
            display:inline-block;
            border:5px double rgb(218, 205, 104);;
            width:100%;
            font-family:'Times New Roman', Times, serif;
            font-size:xx-large;
            margin: 40px;
            display: block;
            margin-left: 50px;
            letter-spacing: 2px;
            text-shadow: 2px 2px 6px rgba(145, 72, 23, 0.7);
        }
        .name{
            position: absolute;
            top:200px;
        
            left:100px;
            font-size: large;
            font-family: Georgia, 'Times New Roman', Times, serif;
            color: rgb(213, 185, 86);
        }
        .author{
            position:absolute;
            top:400px;
            left:900px;
        }
        img{
            border-radius: 10px;
            border:5px solid rgb(111, 80, 13);
            l
        }

        
    </style>
</head>
<body>
    <div class="display">
        <div class="container">
            <img src="./bgi.jpg" style="width: 100%;">
            <div class="tagline"><p>***Exploring the Soul of Creativity***</p></div>
            <div style="position: absolute;top: 20px;left: 10px;color: rgb(205, 169, 26);">
                <center>
                    <h2 class="title">THE <br>SILENCE BETWEEN <br>STROKES</h2></center>
            </div>
            <div class="name" >
                <h3>BY: G.SAKTHIRANI<br>(M.F.A)</h3>
            <div class="authorimg">
                <img src="./img.jpg" style="width: 300px; height: 400px;object-fit: cover;">
            </div>
            </div>

        </div>
    </div>
```
</body>
</html>
## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
# OUTPUT:
![Alt text](image.png)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
