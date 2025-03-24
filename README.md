# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨


SOLUTION

HTML FILE

<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Metadata -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Introduction to CSS - Linking and Styling">
    <title>Introduction to CSS</title>

    <!-- 🔗 Linking the external CSS file -->
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- 🌟 Main Header styled with element selector -->
    <h1>Welcome to CSS Styling</h1>

    <!-- 👤 Paragraph styled using a class selector -->
    <p class="intro-text">
        This is an example of a paragraph styled using a class selector. It demonstrates padding, margin, font, and color.
    </p>

    <!-- 🖼️ Image styled using an ID selector -->
    <img id="styled-image" src="https://images.pexels.com/photos/1103970/pexels-photo-1103970.jpeg" alt="Sample" width="300">

    <!-- 🎯 Additional styled section -->
    <div class="highlight-box">
        This box is styled using margin, padding, border, and background color.
    </div>
</body>
</html>




CSS FILE

/* 🔹 Element Selector: Applies style to all h1 tags */
h1 {
    color: darkblue;
    font-family: 'Georgia', serif;
    text-align: center;
    margin-bottom: 20px;
}

/* 🔹 Class Selector: Targets paragraph with class="intro-text" */
.intro-text {
    font-family: 'Arial', sans-serif;
    color: #333;
    background-color: #f9f9f9;
    padding: 15px;
    margin: 20px auto;
    width: 80%;
    border-left: 5px solid #4CAF50;
    line-height: 1.6;
}

/* 🔹 ID Selector: Targets image with id="styled-image" */
#styled-image {
    display: block;
    margin: 30px auto;
    border: 5px solid #ccc;
    padding: 10px;
    border-radius: 10px;
}

/* 🔹 Another Class Selector: Styled box */
.highlight-box {
    background-color: #e3f2fd;
    padding: 20px;
    margin: 40px auto;
    border: 2px dashed #2196F3;
    width: 75%;
    font-family: 'Verdana', sans-serif;
    font-size: 16px;
    color: #0d47a1;
}
