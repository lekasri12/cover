# Ex.06 Book Front Cover Page Design
## Date: 16/04/2024

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
          <meta charset="UTF-8"
          name="viewport"
          content="width=device-width, initial-scale=1.0">
          <style>
         


         .bookpage{
              width: 400px;
              height: 600px;
              color:white;
              margin-left: auto;
              margin-right: auto;
              padding: 20px;
              position: relative;

              font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
              background-image: url(background.jpeg);
              background-size: cover;
              }
             .insight{
                color:pink;
              }

             .hrstyle{
             width:100px;
             }
             .author{
             display: inline;
             position: relative;
             color:rgb(255, 247, 247);
             top:300px;

             font-family:Georgia;
             font-size: medium;
             }
             .booktitle{
             font-family: 'Courier New',Courier,monospace;
             font-size: larger;
             text-align: center;
             position: relative;
             top: 30px;
             color:white;
           
             }
             .id {
             width:400px;
             position: relative;
             top:300px;
             }
             .pub{
             font-size: medium;
             position: relative;
             top:265px;
             left:330px;
            
             }
             .ed{
             color: yellow;
             font-size: medium;
             font-family: Verdana;
             position:relative;
             top:200px;
             }
             .subtitle{
             font-family:Tahoma;
             font-size: large;
             position: relative;
             top:40px;
             color:yellow;
             }
             .mypic{
             position: relative;
             top: 250px;
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
                SEC SERIES
             </div>
             <div class="hrstyle">
                <hr style="color: yellow;">
             </div>
             <div class="booktitle">
             <h1>HACKING</h1>
             </div>
             <div class="subtitle">
             <b>DARK SIDE OF INTERNET</b>
             </div>
             <div class ="mypic">
               <img src="leka.jpg" width="130" height="145" alt="">
             </div>
             <div class="id">
             <hr style="color: lightgreen;">
             </div>
             <div class="author">
             <p><b>  LEKASRI G</b></p>
             </div>
             <div class="pub">
                SEC
             </div>
             <div class="ed">
             <b>Limited edition</b>
          </div>
     </body>
</html>
```


## OUTPUT:
![alt text](<Screenshot 2024-04-16 095657.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
