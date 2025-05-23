# Ex.06 Book Front Cover Page Design
## Date:05/05/2025

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
~~~

        <!DOCTYPE html>
<html lang="en">
    <head>
        <meta name="viewport"
        content="width=device-width,initial-scale=1.0">
        <style>
        
        .bookpage{
            width: 400px;
            height: 600px;
            color:rgb(72, 7, 7);
            margin-left: auto;
            margin-right: auto;
            padding:20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url('123.jpeg.jpg');
            background-size: cover;
        }

        .EXPERTINSIGHT{
            color:#ffffff ;
            font-size: 20px;

        }

        .hrstyle{
            width: 100px;
        }

        .author{
            color: rgb(55, 26, 112);
            display: inline;
            position: absolute;
            color: rgb(35, 15, 70);
            top: 550px;

            font-family: Georgia, 'Times New Roman', Times, serif;
            font-size: 30px;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 30px;
            text-align: center;
            position: relative;
            top: 60px;
            color: white;
        }

        .id{
            width: 410px;
            position: relative;
            top: 210px;

        }

        .pub{
            font-size: large;
            position: relative;
            top: 170px;
            left: 300px;
        }
        .ed{
            color: rgb(195, 228, 63);
            font-size: medium;
            font-family: Verdana, Geneva, Tahoma, sans-serif;
            position: relative;
            top: 90px;

        }
        .subtitle{
            font-family: Tahoma;
            font-size: 20px;
            position: relative;
            top: 70px;
            color: white;
        }
        .mypic{
            position: relative;
            top: 70px;
            left: 280px;
            width: 100px;
            height: 100px;
           
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="EXPERTINSIGHT">
                <b>SEC INSIGHT</b>
            </div>
            
            <div class="booktitle">
                <h1><b>BASICS OF WEB DEVELOPMENT</b></h1>
            </div>
            <div class="subtitle">
            <b>Basic Guide For Beginners</b>
            </div>
            <div class="mypic">
                <img src="har.png.png" width="120" height="120" alt="Error">
            </div>
            
            <div class="author">
                <p><b>V.Harshini</b></p>
            </div>
            <div class="ed">
                <b>Author:</b>
            </div>
            
            
            
        </div>
    </body>
</html>
~~~


## OUTPUT:

![alt text](<Screenshot (119).png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
