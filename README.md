# Ex.06 Book Front Cover Page Design
## Date:02-12-2024

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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width: 400px;
                height: 600px;
                color: rgb(245, 48, 18);
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url("BACKIMAGE.jpg");
                background-size: cover;
            }
            .insight{
                color: rgb(176, 132, 20);

            }
            .hrstyle{
                width: 100px;
            }
            .author{
                display: inline;
                position: relative;
                color: red;
                top: 200px;

                font-family: Georgia;
                font-size: medium;
            }
            .booktitle{
                color:rgb(231, 238, 33);
                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            
            }
            .id{
                width: 400px;
                position: relative;
                top: 210px;

            }
            .pub{
                font-size: medium;
                position: relative;
                top: 165px;
                left: 330px;
            }
            .ed{
                color: rgb(205, 183, 183);
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 115px;

            }
            .subtitle{
                color:rgb(143, 213, 39);
                font-family: 'Tahoma';
                font-size: large;
                position: relative;
                top: 40px;
            }
            .mypic{
                position: relative;
                top: 170px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;
            }
        </style>
        <title>Book Cover Page</title>

    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                EXPERT INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: rgb(110, 146, 182);">
            </div>
            <div class="booktitle">
                <h1>
                    <font size="5">
                    "A COMPREHENSIVE GUIDE to Web Devlopment Wonders"
                </font></h1>
            </div>
            <br>
            <br>
            <br>

            <div class="subtitle">
                with HTML,CSS and JS.
            </div>
            <div class="mypic">
                <img src=IMAGE.PNG width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
                <p><b>YUGESH M</b></p>
            </div>
            <div class="pub">
                <font size="5">
                SEC
            </font>
            </div>
            <div class="ed">
                <b>SECOND Edition</b>
            </div>
        </div>

    </body>
</html>


```

## OUTPUT:
![alt text](<Screenshot (80).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
