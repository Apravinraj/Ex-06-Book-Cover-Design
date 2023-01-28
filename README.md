Ex-06-Book-Cover-Design
AIM:
To develop a website to display the cover page design of a book

Design Steps:
Step 1:
Clone the Github respository and create a Django admin interface.

Step 2:
Write HTML and CSS Code for designing book cover page and execute them.

Code:
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>
        .bookpage{
            width: 420px;
            height: 700px;
            background-color:cyan;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image:
            background-size: cover;
        }
            
        .insight{
            color: blue;
        }
        
        .hrstyle{
            width:100px;
        }
        .author{
            color: blue;
            display: inline;
            position: relative;
            color: black;
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
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:blue;
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
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 5000px;
            height: 200px;
            background-size: cover;
        }
        </style>
        <title>COVER PAGE DESIGN</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: blue;">
            </div>
            <div class="booktitle" style="color: red;">
                <h1>Fundamentals of Web Application Development</h1></div>
            <div class="subtitle" style="color:red;"><b>
                HTML and CSS Combined with Django Architecture</b>
            </div>
            <div class="mypic" >
                <img src="web.jpeg" width="60" height="100" alt="" style="vertical-align:bottom;margin:50px 55px">
            </div>
            <div class="id">
                <hr style="color: pink;">
            </div>
            <div class="author">
               <p><b>A pravin raj</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Seventh Edition</b>
            </div>
            
        </div>
    </body>
</html>
Output:

![Screenshot (32)](https://user-images.githubusercontent.com/118707879/215278949-8baa6b44-1e7d-4691-a1ed-126ac318ce0a.png)


Result:
The program for designing book cover page using HTML and CSS is executed.
