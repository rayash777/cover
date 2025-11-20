# Ex.06 Book Front Cover Page Design
## Date: 20.11.25

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
**bookcover.html**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Wings Of Fire - APJ</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet" />
  <link rel="stylesheet" href="bookcover.css" />
</head>
<body>
  <div class="column column-left">
    <div class="content">
      <h2>About the Book</h2>
      <p><em>Wings of Fire</em> is an autobiography of Dr. A.P.J. Abdul Kalam, former President of India. It captures his early life, struggles, and his remarkable journey through India's defense and space programs.</p>
      <p>The book serves as a source of inspiration to young Indians and is a testament to dedication, humility, and the power of dreams.</p>
    </div>
  </div>

  <div class="column column-center" id="book">
    <div class="book-info">
      <h1>WINGS OF FIRE</h1>
      <h3>By A. P. J. Abdul Kalam<br/>and Arun Tiwari</h3>
    </div>

  </div>

  <div class="column column-right">
    <div class="content">
      <h2>About Dr. APJ Abdul Kalam</h2>
      <p>Dr. A.P.J. Abdul Kalam was one of India’s most respected scientists and the 11th President of India. Known as the "Missile Man", he was instrumental in India's space and missile programs.</p>
      <p>He remained a passionate advocate for education and youth, and continues to inspire generations with his humility and visionary thoughts.</p>
    </div>
  </div>
</body>
</html>
```
**bookcover.css**
```css
body {
    margin: 0;
    padding: 0;
    display: flex;
    height: 100vh;
    font-family: 'Poppins', sans-serif; 
    color: white;
  }
  
  .column {
    flex: 1;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px;
    box-sizing: border-box;
    overflow-y: auto;
    text-align: left;
  }
  
  .column-left {
    background-color: #1e1e2f;
  }
  
  .column-right {
    background-color: #2f1e1e;
  }
  
  .column-center {
    background-image: url(king.png); 
    background-repeat: no-repeat;
    background-position: center;
    background-size: cover;
    flex-direction: column;
    background-color: #000; 
    text-align: center;
    min-height: 100%;
    position: relative;
  }
  
  .content {
    max-width: 400px;
  }
  
  h1 {
    font-size: 36px;
    margin-bottom: 10px;
    color: aqua;
    font-weight: 600;
  }
  
  h2 {
    font-size: 28px;
    margin-bottom: 15px;
    color: #fdd835;
  }
  
  h3 {
    font-size: 18px;
    font-weight: normal;
    color: #ffcc80;
    margin-top: 5px;
    font-style: italic;
  }
  
  .book-info {
    background-color: rgba(0, 0, 0, 0.7);
    padding: 20px 30px;
    border-radius: 10px;
    position: absolute;
    top: 20px; 
    left: 50%;
    transform: translateX(-50%); 
    width: 90%; 
  }
  
  .column-left, .column-right {
    background-color: rgba(0, 0, 0, 0.7);
    padding: 30px;
    border-radius: 10px;
  }
  
  h2, h3 {
    font-weight: 500;
  }
  
  p {
    font-size: 16px;
    line-height: 1.6;
    margin-bottom: 15px;
  }
```



## OUTPUT:
<img width="1280" height="749" alt="image" src="https://github.com/user-attachments/assets/6101d9e6-7985-4193-9542-36591e39f029" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
