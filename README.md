# Ex.06 Book Front Cover Page Design
## Date:

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
~~~
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .book-cover {
            position: relative;
            width: 600px;
            height: 800px;
            border: 2px solid #000;
            overflow: hidden;
        }

        .overlay {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(to bottom, rgba(0, 0, 50, 0.7), rgba(255, 255, 255, 0.9));
        }

        .content {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: #000;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            box-sizing: border-box;
        }

        .title {
            font-size: 36px;
            font-weight: bold;
            color: #123466;
            margin-bottom: 10px;
        }

        .subtitle {
            font-size: 18px;
            font-weight: 300;
            color: #555;
            margin-bottom: 50px;
        }

        .bottom-section {
            position: absolute;
            bottom: 20px;
            width: 100%;
            display: flex;
            justify-content: space-between;
            align-items: flex-end;
            padding: 0 20px;
            box-sizing: border-box;
        }

        .edition-author {
            text-align: left;
        }

        .edition {
            font-size: 16px;
            font-weight: bold;
            color: #000;
        }

        .author {
            font-size: 16px;
            color: #000;
        }

        .profile-sec {
            text-align: center;
        }

        .author-photo {
            width: 100px;
            height: 100px;
            border-radius: 10px;
            border: 2px solid #123466;
        }

        .institution {
            font-size: 18px;
            font-weight: bold;
            color: #000;
            margin-top: 10px;
        }
    </style>
</head>
<body>
    <div class="book-cover">
        <div class="overlay"></div>
        <div class="content">
            <h1 class="title">The Web Design Blueprint</h1>
            <p class="subtitle">Crafting Exceptional Digital Experiences with Design Excellence</p>
            <div class="bottom-section">
                <div class="edition-author">
                    <p class="edition">Tenth Edition</p>
                    <p class="author">SHREEDHAR KUMAR K J</p>
                </div>
                <div class="profile-sec">
                    <img src="c:\Users\admin\OneDrive\Pictures\my pic\24901118_shreedhar_kumar-removebg.png" alt="Author's Photo" class="author-photo">
                    <p class="institution">SEC</p>
                </div>
            </div>
        </div>
    </div>
</body>
</html>
~~~

## OUTPUT:
![image](https://github.com/user-attachments/assets/3535c6ca-dd23-45aa-945d-90d4d601f6bc)
![Screenshot (133)](https://github.com/user-attachments/assets/3f9b1a87-60be-45a1-8947-2a3c1ce87ef5)
## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
