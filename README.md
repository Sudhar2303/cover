# Ex.06 Book Front Cover Page Design
## Date: 28/10/2023

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
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
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
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(023.jpg);
            background-size: cover;
            position: relative;
        }

        .insight {
            color: white;
        }

        .booktitle {
            color: rgb(255, 0, 0);
            font-family: 'Chiller';
            font-size: 30px;
            text-align: center;
            position: relative;
            top: 30px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            text-align: center; /* Center the subtitle text */
            position: relative;
            top: 40px;
        }

        .author 
        {
            font-family: 'Times New Roman', Times, serif;
            position: absolute;
            bottom: 10px;
            right: 10px;
            font-size: 25px;
        }

        .mypic {
            position: relative;
            top: 280px; 
            left: 295px;
            width: 150px;
            height: 150px;
            border-radius: 50%; 
            background-size: cover;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
        <div class="booktitle">
            <h1>THE  WITCH  STORY</h1>
        </div>
        <div class="author" style="color: rgb(218, 202, 202);">
            SUDHARSANAN 
        </div>
        <div class="mypic">
            <img src="06.jpg" width="100" height="100" alt="">
        </div>
    </div>
</body>
</html> 
```

## OUTPUT:
![Alt text](<Screenshot (313).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
