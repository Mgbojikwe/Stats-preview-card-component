# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Very dark blue (main background): hsl(233, 47%, 7%)/*used*/
- Dark desaturated blue (card background): hsl(244, 38%, 16%)/*used*/
- Soft violet (accent): hsl(277, 64%, 61%)

### Neutral

- White (main heading, stats): hsl(0, 0%, 100%) /*used*/
- Slightly transparent white (main paragraph): hsla(0, 0%, 100%, 0.75)
- Slightly transparent white (stat headings): hsla(0, 0%, 100%, 0.6)

## Typography

### Body Copy

- Font size: 15px /*used*/

### Font

- Family: [Inter](https://fonts.google.com/specimen/Inter)
- Weights: 400, 700

- Family: [Lexend Deca](https://fonts.google.com/specimen/Lexend+Deca)
- Weights: 400


* {
    box-sizing: border-box;
}
body {
    background-color: hsl(233, 47%, 7%);
    color: white;
    font-size: 15px;
    margin: 0;
}
.flex-container {
    background-color: hsl(244, 38%, 16%);
    border-radius: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin: 45px 20px;
    overflow: hidden;
    
}
img {
    
    width: 100%;
}
.flex-text {
    text-align: center;
}
.flex-picture {

}
h2 { 
    font-family: 'Inter', sans-serif; 
    color: hsl(0, 0%, 100%);
}
p {font-family: 'Lexend Deca', sans-serif;}

......................

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
    <link rel="stylesheet" href="myworkstylesheet.css">
    <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png"> 

    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&family=Lexend+Deca&display=swap" rel="stylesheet">
    
    <title>Frontend Mentor | Stats preview card component</title>
    <style>
        .attribution { font-size: 11px; text-align: center; }
        .attribution a { color: hsl(228, 45%, 44%); }
    </style>
</head>
<body>
<div class="flex-container">
  
    <div class="flex-picture">
        <img src="images/image-header-mobile.jpg" alt="image for mobile" width="100%" height="100%">
    </div>

    <div class="flex-text">
            <h2>Get insights that help your business grow.</h2>
            <p>Discover the benefits of data analytics and make better decisions regarding revenue, customer 
                experience, and overall efficiency.</p>
            <div>
                <p>10k+<br>companies</p>
                <p>314<br>templates</p>
                <p>12M+<br>queries</p>
            </div>
    </div>

</div>

<footer class="attribution">
        Challenge by <a href="https://www.frontendmentor.io?ref=challenge" target="_blank">Frontend Mentor</a>. 
        Coded by <a href="#">Your Name Here</a>.
</footer>

</body>
</html>