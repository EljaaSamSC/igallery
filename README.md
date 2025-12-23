# Ex.08 Design of Interactive Image Gallery
## Date:23/12/25

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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Village Life Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f1ee;
      color: #333;
      margin: 0;
      padding: 0;
    }

    h1 {
      text-align: center;
      color: #6b4226;
      margin: 20px 0;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
      padding: 20px;
      max-width: 1200px;
      margin: 0 auto;
    }

    .gallery img {
      width: 100%;
      height: 250px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 8px 16px rgba(0,0,0,0.3);
    }

    footer {
      text-align: center;
      margin: 20px 0;
      color: #888;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <h1>🌾 Village Life Gallery 🌾</h1>c
  <div class="gallery">
    <img src="c:\Users\sridh\Downloads\nat1.jpg" alt="Village Hut">
    <img src="c:\Users\sridh\Downloads\nat2.jpg" alt="Farm Field">
    <img src="c:\Users\sridh\Downloads\nat3.jpeg" alt="Sunset over Village">
    <img src="c:\Users\sridh\Downloads\nat4.jpeg" alt="Village Pathway">
    <img src="c:\Users\sridh\Downloads\nat5.jpeg" alt="Children Playing">
    <img src="c:\Users\sridh\Downloads\nat6.jpeg" alt="Village Market">
    <img src="c:\Users\sridh\Downloads\nat7.jpeg" alt="Rural Life">
    <img src="c:\Users\sridh\Downloads\nat8.jpeg" alt="Village Landscape">
    
  </div>

  <footer>© 2025 Village Life Gallery | Nature & Rural Beauty</footer>
</body >
</html>
```
## OUTPUT:
<img width="1133" height="623" alt="{ACA83676-0E4C-4F82-B835-93F918028678}" src="https://github.com/user-attachments/assets/2a47eb20-730b-41e1-bbc5-d3cb4e5e5919" />

## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
