# Ex.06 Book Front Cover Page Design
# Date:9/11/23
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
~~~
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
            color: red;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(web.webp);
            background-size: cover;
            position: relative;
        }

        .insight {
            color: white;
        }

        .booktitle {
            font-family: 'Algerian', cursive;
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

        .author {
		font-family: 'Algerian', cursive;
            position: absolute;
            bottom: 10px;
            right: 10px;
            color: red;
            font-size: 25px;
        }
    </style>
    <title>Book Cover Page</title>
</head>

<body>
    <div class="bookpage">
	<div class="insight">SEC INSIGHT</div>
        <div class="booktitle">
            <h1>WEB Developer</h1>
        </div>
        <div class="author">
           Selva KumarA
        </div>
    </div>
</body>
</html>
~~~

## OUTPUT:
![WhatsApp Image 2023-11-16 at 10 49 21](https://github.com/Selvakumar525/cover/assets/120643262/a97b6976-eb7d-4688-b653-532c1a255dfe)
![image](https://github.com/Selvakumar525/cover/assets/120643262/7cb311af-3358-49fb-bd5c-3a3311121e33)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
