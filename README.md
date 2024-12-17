# Ex.08 Design of Interactive Image Gallery
## Date:17.12.24

## AIM:
To design a web application for an inteactive image gallery with minimum five images.

## DESIGN STEPS:

### Step 1:
Clone the github repository and create Django admin interface.

### Step 2:
Change settings.py file to allow request from all hosts.

### Step 3:
Use CSS for positioning and styling.

### Step 4:
Write JavaScript program for implementing interactivity.

### Step 5:
Validate the HTML and CSS code.

### Step 6:
Publish the website in the given URL.

## PROGRAM :
```
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Interactive Photo Gallery</title>
    <style>
        body
         {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
            background-color: #b64bb9;
        }

        h1 
        {
            margin-top: 20px;
        }

        .gallery 
        
        {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 15px;
            padding: 20px;
        }

        .gallery img 
        {
            width: 300px;
            height: 200px;
            border: 2px solid #050000;
            border-radius: 12px;
            cursor: pointer;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .gallery img:hover 
        {
            transform: scale(1.1);
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

    </style>
</head>
<body>
    <h1><i>Interactive Photo Gallery</i></h1>
    <div class="gallery">
        <img src="travel1.jpg" alt="Image 1">
        <img src="travel2.jpg" alt="Image 2">
        <img src="travel3.jpg" alt="Image 3">
        <img src="travel4.jpg" alt="Image 4">
        <img src="travel5.jpg" alt="Image 5">
        <img src="travel6.jpg" alt="Image 6">
        <img src="travel7.jpg" alt="Image 7">
        <img src="travel8.jpg" alt="Image 8">
        <img src="travel9.jpg" alt="Image 9">
        <img src="travel10.jpg" alt="Image 10">
        <img src="travel12.jpg" alt="Image 11">
        <img src="travel13.jpg" alt="Image 12">
        <img src="travel14.jpg" alt="Image 13">
        <img src="travel15.jpg" alt="Image 14">
    </div>
    <footer class="bg-secondary text-white text-center py-3">
        <p>&copy 2024 Designed and Developed by Sukirthana</p>
    </footer>
</body>
</html>
```
## OUTPUT:

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
