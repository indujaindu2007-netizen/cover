# Ex.05 Book Cover Page Design
## Date:15-12-2025

## AIM:
To design a book back cover page using HTML and CSS.

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
cover.html
<html>
<head>
    <title>About My Book</title>
    <link href="styles.css" rel="stylesheet">
</head>
<body>

<div class="box">

    <h2>ABOUT MY BOOK</h2>
    <hr>

    <p>
        This book <span class="highlight">"Internet & Web Browsers"</span> provides a simple understanding 
        of the Internet and web browsers. The Internet is a global network that connects millions of 
        computers and allows users to share information quickly. It supports communication through 
        emails, websites, videos, and social media. A web browser is a software application used 
        to open and view these websites on the Internet. Popular browsers include Google Chrome, 
        Firefox, Safari, and Microsoft Edge.
    </p>

    <div class="quote">
        "The Internet is the bridge to information, and the web browser is the doorway that lets us cross it."
    </div>

    <div class="author">
        <img src="myimg.jpg" class="authorimg">
        <div class="authorinfo">
            <b>Induja R</b>
            <p>Induja is a passionate learner and technology enthusiast who enjoys exploring computers 
            and the Internet. Dedicated to sharing knowledge clearly, they aim to make complex topics 
            easy to understand for all readers.</p>
        </div>
    </div>

    <div class="bottom"><br>
        SEC Publishers
        <br>
        Printed in India
        <h4 style="text-align:right;">Price: Rs 399</h4>
    </div>
</div>
</body>
<footer>
    <p>Induja R(25001726)</p>
</footer>
</html>

styles.css

body
{
    background-color: cornsilk;
}

.box
{
    width: 500px;
    background-image: url('newimg.jpg');
    color:rgb(75, 3, 29);
    font-family: Georgia, 'Times New Roman', Times, serif;
    background-size: cover;
    background-position: center;
    border: inset 5px rebeccapurple;
    border-radius: 12px;
    padding: 30px;
    margin: 40px auto;
}
hr
{
    height: 5px;
    background-color: black;
}
h2
{
    color:navy;
    text-align: center;
    font-size: 25px;
}

.highlight
{
    background-color:darksalmon;
    font-weight: bold;
}

.quote
{
    background-color:coral ; ;
    padding: 15px;
    border-left: 5px solid brown;
    text-align: center;
    font-style: italic;
    margin: 20px ;
    border-radius: 5px;
}

.author
{
    display: flex;
    gap: 15px;
    background-color:khaki;
    padding: 15px;
    border: dotted 3px;
    border-radius: 10px;
    margin-top: 20px;
}

.authorimg
{
    width: 110px;
    height: 150px;
    border: inset 2px;
    border-radius: 5px;
    object-fit: cover;
}

.authorinfo
{
    flex: 1;
    background-color: lightgoldenrodyellow;
    color: darkred;
    padding: 10px;
    border-radius: 8px;
}

.bottom
{
    margin-top: 30px;
    background-color: darkkhaki;
    color: rgb(232, 63, 63);
    padding: 12px 20px;
    border-top: 50px;
    border-radius: 6px;
    font-weight: bold;
    display: flex;
    justify-content: space-between;
}
footer
{
    background-color:blue;
    text-align: center;
    color: white;
    height: 25px;
    font-size: larger;
}
```

## OUTPUT:


## RESULT:
The program for designing book back cover page using HTML and CSS is completed successfully.
