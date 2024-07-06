Project_1
This project demonstrates a simple grid layout using HTML and CSS. It includes responsive design features to adapt to different screen sizes.

Preview

![Screenshot (1)](https://github.com/IT21117428/CSS-Grid-Project1/assets/87494020/36a4e025-9c5a-4f96-a604-a45ba08d293f)

Technologies Used

HTML
CSS (Grid Layout)
Google Fonts

Features

Grid Layout: Uses CSS Grid to create a structured layout.
Responsive Design: Adjusts the layout based on screen width (responsive design for 980px and 780px breakpoints).
Typography: Uses the Poppins font from Google Fonts.

Getting Started

To get a local copy up and running follow these simple steps:

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/project_1.git
Open index.html in your web browser.

Usage

Header: A centered header that introduces the project.
Grid Container: A grid layout with a main article and three sub-articles, each containing an image and a paragraph.
Responsive Design: The layout adjusts for screens narrower than 980px and 780px.

Code Overview

HTML

html
Copy code
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Project_1</title>
    <link rel="stylesheet" href="./style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@100..900&display=swap" rel="stylesheet">
</head>
<body>
    <header>Let's create our first project</header>
    <div class="grid-container">
        <article class="main-article">
            <img src="./images/1.png" alt="main-image">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit...</p>
        </article>
        <article>
            <img src="./images/2.webp" alt="image2">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit...</p>
        </article>
        <article>
            <img src="./images/3.webp" alt="image3">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit...</p>
        </article>
        <article>
            <img src="./images/4.jpg" alt="image4">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit...</p>
        </article>
    </div>
</body>
</html>

Contributing

Contributions are welcome! If you have any suggestions, or improvements, or find any issues, please create an issue or submit a pull request.

License

This project is licensed under the MIT License. See the LICENSE file for details.
