# Ex.06 Book Front Cover Page Design
# Date:04/12/2024
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
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
<header>
    <title>
        Money Book</title>
</header>
<style>
      body {
            font-family: Arial, sans-serif;
            background-color: white;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

    .container {
            text-align: center;
            border: 2px solid green;
            padding: 20px;
            width: 35%;
            position: relative;
        }

        .container::before,
        .container::after {
            content: '';
            position: absolute;
            top: 0;
            bottom: 0;
            width: 10px;
            background-color: green;
        }

        .container::before {
            left: -10px;
        }

        .container::after {
            right: -10px;
        }
    .txt {
        text-align: center;
        font-size: 47px;
        font-weight: lighter;
        font-style: italic;
        
    }

    .txt1 {
        text-align: center;
        font-size: 50px;
        font-weight: bold;
        color: green;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        
    }
    .txt2 {
        text-align: center;
        font-size: 80px;
        font-weight: bold;
        color: green;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        
    }

      .center {
        display: block;
        margin-left: 28%;
    }
    .author {
        font-size:20px;
        font-weight: bold;
            margin-bottom: 20px;
        }
    .nor {
        text-align: center;
        font-size: 30px;
        font-weight: lighter;
margin-left: 20%;
    }

    .txt3 {
        text-align: center;
        font-size: 60px;
    }
</style>


<body>
  
            <div class="container">
               
                <div class="txt">The</div>
                <div class=" txt1"> Psychology </div>
                <div class="txt">of </div>
                <div class=" txt2">Money</div>
                <div class="graphic"></div>
                {% load  static %}
                <img src={% static 'images/money_logo.jpg'%} width="210px" height="230px"><br><br>
                
                <div class="subtitle">Timeless Lessons on Wealth, Greed,<br> AND Happiness</div><br>
                <div class="author" >Morgan Housel</div>
                <div style="margin-left: -5px;">&quot;Everyone should own a copy"</div>
                <div style="margin-left:370px ;">----NANESHVARAN</div>
                <a href="https://www.amazon.in/Psychology-Money-Morgan-Housel/dp/9390166268" style="margin-left: 50px;">Touch for Book</a> 
        
    </div>







</body>

</html>
```
# OUTPUT:
![ouput06(web)](https://github.com/user-attachments/assets/a93cb5b8-aa79-4e86-8cff-83b663ec27c8)


# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
