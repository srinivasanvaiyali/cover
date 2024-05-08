# Ex.06 Book Front Cover Page Design
## Date: 08.05.2024

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
REG NO: 212222043008
DEVELOPED BY: SRINIVASAN V
DEPT : CSE

<!DOCTYPE html>
<html>

<head>
    <title>WEB APPLICATION DEVELOPMENT</title>
    <style>
        .bookpage {
            width: 600px;
            height: 700px;
            color:rgb(0, 0, 0);
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url("Background.jpg.jpeg");
            background-size: cover;
        }
        .background {
            width: 400px;
            height: 700px;
            background-image: url("PICS/SRINI BACKGROUND.jpeg");
            background-repeat: no-repeat;
            background-size: cover;
            
        }
     

        .insight{
            color:rgb(5, 16, 16);
            font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
            font-weight: 500;
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            font-size: medium;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            color:rgb(0, 0, 0);
            top:170px;
            left: 20px;
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(14, 3, 9);
            font-family: garamond;
            font-size: x-large;
            text-align: center;
            position: relative;
            top: 20px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color: #000000;
            font-family: 'Times New Roman', Times, serif;
            font-size: medium;
            position: relative;
            top:60px;
            left:150px;
        }
        .ed{
            color:rgb(0, 0, 0);
            font-size: medium;
            font-family: Georgia, 'Times New Roman', Times, serif;
            position:relative;
            top:100px;
        
        }
        .subtitle{
            color:rgb(0, 0, 0);
            font-family: 'Times New Roman', Times, serif;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: left;
            top: 135px;
            left: 200px;
            width: 90px;
            height: 100px;
            background-size:contain;
        }
    </style>
    <title>Book Cover Page</title>
</head>
<body class="bookpage">
        <div class="background">
            <div class="insight">
               <strong>DEPT OF CSE</strong> 
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(0, 0, 0)">
            </div>
            <div class="booktitle">
                <h1>WANDERLUST</h1></div>
            <div class="subtitle">
                 <strong>Travel with me</strong> 
            </div>
            <div class="subtitle">
                 <strong>LIMITED EDITION</strong><br><br><br><br><br><br><br><br>
            </div>

            <div class="mypic">
                <img src="C:\Users\Admin\Desktop\SRINI EX6\PICS\SRINI PASSPORT.jpeg" width="100" height="120" >
            </div>
            <div class="id">
                <hr style="color:rgb(0, 0, 0)">
            </div>
            <div class="author">
                <style>
                
                    mark {
                        background-color: #000000; 
                        color: rgb(0, 0, 0);
                    }
                    </style>
                    

               <p><b><strong>SRINIVASAN V<br>(212222043008)</strong></b></p>
            </div>
            <div class="pub">
            
                 <style>
                
                    mark {
                        background-color: #000000; 
                        color: black;
                    }
                    </style>
                    <div class="pub">
                       
                    
                <strong>SEC<br>CHENNAI</strong>
            
            </div>
           
        </div>
        </body>
        

</html>
```

## OUTPUT:

![ex6 srini output](https://github.com/srinivasanvaiyali/cover/assets/145117665/9ca3b824-239c-472e-a250-cae83f70e80b)



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
