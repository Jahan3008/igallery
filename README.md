# Ex.08 Design of Interactive Image Gallery
## Date:17/12/2024

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
igalery.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BIGG BOSS IMAGE GALLERY</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="gallery-header">
        <h1>BIGG BOSS IMAGE GALLERY</h1>
        <p>Powerfull Contanstant</p>
    </header>
    <div class="gallery-container">
        <div class="gallery-item">
            <img src="Anshiths.jpg" alt="Anshi">
            <div class="overlay">
                <p>Anshitha</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Arun.jpg" alt="Arun">
            <div class="overlay">
                <p>Arun</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Dharsha.jpg" alt="Dhar">
            <div class="overlay">
                <p>Dharshaa</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="jack.jpg" alt="Jack">
            <div class="overlay">
                <p>Jack</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Jefery.jpg" alt="Jefery">
            <div class="overlay">
                <p>Jefery</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Soundeyy.jpg" alt="Soundeyy">
            <div class="overlay">
                <p>Soundeyy</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Muthu.jpg" alt="Muthu">
            <div class="overlay">
                <p>Muthu</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Pavi.jpg" alt="Pavi">
            <div class="overlay">
                <p>Pavi</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Tharshii.jpg" alt="Tharshii">
            <div class="overlay">
                <p>Tharshii</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="Vishuu.jpg" alt="Vishuu">
            <div class="overlay">
                <p>Vishuu</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="WhatsApp Image 2024-12-17 at 14.42.00_2ce7ac98.jpg" alt="Arnav">
            <div class="overlay">
                <p>Arnav</p>
            </div>
        </div>
        <div class="gallery-item">
            <img src="download.jpg" alt="Sethuu">
            <div class="overlay">
                <p>Sethuu</p>
            </div>
        </div>
    </div>
</body>
</html>

styles.css

body {
    margin: 0;
    font-family: 'Arial', sans-serif;
    background-image: url('featured1.jpg'); 
    background-size: cover; 
    background-position: center; 
    background-attachment: fixed; 
    color: #faf7f7;
}

.gallery-header {
    text-align: center;
    padding: 20px;
    background-color: rgba(50, 128, 224, 0.7); 
    border-bottom: 2px solid hsl(0, 0%, 99%);
}

.gallery-header h1 {
    margin: 0;
    font-size: 2.5em;
    color: hsl(300, 14%, 99%);
}

.gallery-header p {
    margin: 5px 0 0;
    font-size: 1.2em;
    color: hsl(348, 56%, 98%);
}


.gallery-container {
    display: grid;
    grid-template-columns: repeat(6, 1fr); 
    gap: 20px;
    padding: 20px;
    max-width: 1200px;
    margin: 0 auto;
}

/* Gallery Items */
.gallery-item {
    position: relative;
    overflow: hidden;
    aspect-ratio: 1 / 1; 
    border-radius: 50%; 
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease-in-out;
    border: 4px solid  hsl(346, 65%, 32%); 
}

.gallery-item img {
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 50%; 
    transition: transform 0.3s ease;
    border: 4px solid rgb(7, 139, 187); 
}

.gallery-item:hover img {
    transform: scale(1.1);
    border-color: hsl(346, 50%, 52%); 
}


.overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: rgba(0, 0, 0, 0.6);
    color: #71e710;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
    transition: opacity 0.3s ease;
    text-align: center;
    border-radius: 50%;
}

.gallery-item:hover .overlay {
    opacity: 1;
}

.overlay p {
    margin: 0;
    font-size: 1.5em;
    font-weight: bold;
}

```

## OUTPUT:
![alt text](<Screenshot 2024-12-17 205147.png>)
## RESULT:
The program for designing an interactive image gallery using HTML, CSS and JavaScript is executed successfully.
