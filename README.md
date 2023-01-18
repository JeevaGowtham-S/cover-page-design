# cover-page-design

## HTML CSS code:
```
<!DOCTYPE html>
<html>
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style type="text/css">

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/6.jpg);
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
            top:300px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
        
        }
        .id {
            width:400;
            position: relative;
            top:300px;
            
        }
        .publisher{
            font-size: medium;
            position: relative;
            top:270px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:200px;

        }
        .subtitle{
            font-family:Tahoma;
            position: relative;
            top:30px;
        }
        .photo{
            position: relative;
            top:100px;
            background-image: url("/static/images/4.png");
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
            <div class="photo"><p></p></div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <b> <p>Jeeva Gowtham</p></b>
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


# OUTPUT:
![output](./images/cov.png)