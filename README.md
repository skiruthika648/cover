# Ex.06 Book Front Cover Page Design
## Date:28/10/23

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Clone the GitHub repository.

### Step 2:
Create a Django Admin interface.

### Step 3:
Write the HTML code with relevant CSS properties.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the HTML code.

### Step 6:
Publish the website in the given URL.

## PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        *{
            font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        }
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh; 
            margin: 0; 
            background-color:darkgray;
        }

        .cover{
            display: flex;
            height: 98vh;
            width: 30%;    
            justify-content: center;
            align-items: center;
            border-color: black;
            box-shadow: rgba(0, 0, 0, 0.35) 0px 5px 15px;
            overflow: hidden;
            background-image: url(galaxy.jpg);
            background-repeat: no-repeat;
        }
        
        .title{
            position: absolute;
            color:beige;
            top: 150px;
            font-size: 18px;
        }

        .text1{
            position: absolute;
            color: darkcyan;
            top: 15px;
            left: 560px;
        }

        .line1{
            position: absolute;
            top: 60px;
            left: 540px;
        }

        .edition{
            position:absolute;
            top: 550px;
            left: 560px;
            color:orange;
        }

        .line2{
            position: absolute;
            top: 600px;
            left: 540px;
        }

        .author{
            position: absolute;
            top: 610px;
            left: 560px;
            color:cornflowerblue;
        }

        .image img{
            height: 100px;
            width: 90px;
            position: absolute;
            top: 560px;
            left: 870px;
        }
                
    </style>
</head>
<body>
    <div class="cover">
        <div class="title">
            <h1>AFTER THE LAST SKY</h1>
        </div>
        <div class="text1">
            <h3>EXPERT INSIGHT</h3>
        </div>
        <hr class="line1" width="210px">
        <div class="edition">
            <h3>FIRST EDITION</h3>
        </div>
        <div class="author">
            <h3>KIRUTHIKA </h3>
        </div>
        <hr class="line2" width="170px">
        <div class="image">
            <img src="kiruthika.jpg">
        </div>
    </div>
</body>
</html>
```


## OUTPUT:
![image](https://github.com/skiruthika648/cover/assets/128348968/ba2362c4-5f0d-4d0e-bc90-0f263b411736)
![image](https://github.com/skiruthika648/cover/assets/128348968/1cae4b12-9eb8-440e-81a9-e8c5be91b0da)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
