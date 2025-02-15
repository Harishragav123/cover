# EX 06 Book Front Cover Page Design

## DATE:17/10/2023

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
        <meta name="viewport" 
        content="width=device-width, initial-scale=1.0">
        <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }

        .bookpage {
            width: 400px;
            height: 600px;
            color: rgb(0, 255, 60);
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(Slide2.PNG);
            background-size: cover;
        }
        .insight{
            color: rgb(0, 255, 60);
        }
        .hrstyle{
            width:100px;
        }
        .author{
            display: inline;
            position: relative;
            color: rgb(0, 255, 60);
            top:190px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: 19px;
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
            color: rgb(0, 255, 60);
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
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">EXPERT INSIGHT</div>
            <div class="hrstyle"><hr style="color: rgb(0, 255, 60);"></div>
            <div class="booktitle"><h1>WHITE AND BLACK HAT HACKING BASICS TO PROFESSIONAL</h1></div>
            <div class="subtitle">METHODOLOGY TO UNETHICAL HACKING</div>
            <div class="mypic"><img src="my image.png" width="130" height="145" alt=""></div>
            <div class="id"><hr style="color: rgb(0, 255, 60);"></div>
            <div class="author"><p><b>BY SRIRAM</b></p></div>
            <div class="pub">OPEN >>></div>
            <div class="ed"><b>Special Edition</b></div>
        </div>
    </bodY>
</html>
```
## OUTPUT:
![Screenshot 2023-11-20 125106](https://github.com/Harishragav123/cover/assets/135584731/0670c696-d1d2-4070-b2f5-8d67f5a7f6b3)
![Screenshot 2023-11-20 125155](https://github.com/Harishragav123/cover/assets/135584731/dab586dc-3b86-4b3d-a4fe-9ddce4e11eb4)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
