# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the Github repository and create a Django admin interface.

### Step 2:
Write HTML and CSS code for designing book cover page and execute them.

## Code:
```
<!DOCTYPE html>
<html lang="en">
   <head>
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>

       .bookpage{
           width: 400px;
           height: 600px;
           background-color: #3d3a3a;
           color:white;
           margin-left: auto;
           margin-right: auto;
           padding: 20px;
           font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
           background-image: url(/static/images/back.jpg);
           background-size: cover;
       }
           

       .toptext{
           color:white;

       }

       
       .tophr{
           width:140px;
       }
       .author{
           color: white;
           display: inline;
           position: relative;
           color:lightblue;
           top:190px;
           
           font-family:Georgia;
           font-size: medium;
       }
       .booktitle{
           font-family: 'Courier New', Courier, monospace;
           font-size: larger;
           text-align: center;
           position: relative;
           top: 30px;
       
       }
       .id {
           width:400px;
           position: relative;
           top:180px;
           
       }
       .publisher{
           font-size: medium;
           position: relative;
           top:155px;
           left:330px;
       }
       .edition{
           color:red;
           font-size: medium;
           font-family: Verdana;
           position:relative;
           top:85px;

       }
       .subtitle{
           font-family:Tahoma;
           font-size: large;
           position: relative;
           top:40px;
       }
       .photo{
           position: relative;
           top: 135px;
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
           <div class="toptext">
               EXPERT INSIGHT
           </div>
           <div class="tophr">
               <hr style="color: red;">
           </div>
           <div class="booktitle">
               <h1>Responsive Web Design With HTML5 and CSS</h1></div>
           <div class="subtitle">
               Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
           </div>
           <div class="photo">
               <img src="/static/images/prema.jpg" width="130" height="145" alt="">
           </div>
           <div class="id">
               <hr style="color: orange;">
           </div>
           <div class="author">
              <p><b>S.premalath</b></p>
           </div>
           <div class="publisher">
               PACKT
           </div>
           <div class="edition">
               <b>First Edition</b>
           </div>
           
       </div>
   </body>
</html>
```
## Output:

![cover book](https://user-images.githubusercontent.com/119475721/215325016-4c586f98-beb1-4ca0-afdc-e0668f5b5352.JPEG)



## HTML Validation:




![cover](https://user-images.githubusercontent.com/119475721/215325066-e4945502-00c8-4eee-bfad-bd1ba6b2c222.JPEG)



## Result:

The program for desiging book cover page using HTML and CSS is executed successfully.
