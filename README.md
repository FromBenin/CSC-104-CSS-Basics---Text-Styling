index.html
<!--The doctype tag is used to specify the version of HTML being used-->
<!DOCTYPE html>
<!-- The html tag is the root element of an HTML page -->
<html lang="en">
<!-- The head tag contains information about the HTML document -->
<head>
    <!-- The meta tag provides information for the browser and search engines -->
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- The link tag is used to link external stylesheets -->
    <link rel="stylesheet" href="style.css">
    <!-- The title tag is used to give a title to a webpage -->
    <title>Week 4 Assignment: CSS Styling</title>
</head>
<!-- The body tag contains the main content of a webpage -->
<body>
    <!-- The header tag is used to add content to the top of a webpage-->
    <header>
        <h1>Welcome to CSC104</h1>
    </header>
    <!-- The nav tag is used to add a navigation bar to a webpage -->
    <nav>
        <!-- The a tag is used to add links to a webpage -->
        <a href="#">Home</a> |
        <a href="#">About</a> |
        <a href="#">Courses</a> |
        <a href="#">Contact Us</a>
    </nav>
    <!-- The p tag is used to add paragraphs to a webpage -->
    <p>This is my second webpage created for the CSC104 course at UAT.</p>
    <!-- The img tag is used to display an image in the webpage -->
    <img src="nature.jpg" alt="A beautiful scenery of nature">
    &nbsp;
    <p>The Images I used for this webpage are taken from <a href="https://pexels.com">Pexels.com</a></p>
    <!-- The footer tag is used to add items at the bottom of a webpage -->
    <footer>
        <!-- &copy; is used to display the copyright symbol -->
        &copy; Nosa Erhabor<br>
        <!-- The br tag is used to add line breaks -->
        - June 2025<br>
        University of Advanced Technology<br>
    </footer>
</body>
</html>

style.css
body {
    background-color: lemonchiffon;
    background-image: url('background.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    text-align: center;
}

h1 {
    color: #40516b;
    font-family: 'Courier New', Courier, monospace;
}

h2 {
    color: #e7ac3f;
    font-family: 'Courier New', Courier, monospace;
}

nav a {
    color: #e7ac3f;
    text-decoration: none;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
nav a:hover {
    color: #74541a;
    text-decoration: underline;
}

img {
    width: 70%;
    height: auto;
    border: 2px solid #40516b;
    border-radius: 15px;
}

p {
    color: beige;
    font-family: 'Courier New', Courier, monospace;
}
p a {
    color: coral;
    font-family: 'Courier New', Courier, monospace;
    text-decoration: none;
}
a:hover {
    color: rgb(255, 73, 7);
    text-decoration: underline;
}

footer {
    background-color: black;
    color: #16a581;
    text-align: center;
    font-size: 16px;
    font-family: Arial, Helvetica, sans-serif;
}

![Screenshot 2025-06-04 152914](https://github.com/user-attachments/assets/ec4217b2-a52b-49fb-b54d-1722ff55ae90)
![Screenshot 2025-06-04 152940](https://github.com/user-attachments/assets/ff552f7f-08e0-4782-98a3-1a2b9100ab84)
![Screenshot 2025-06-04 152852](https://github.com/user-attachments/assets/9fb6798d-1905-4229-a064-7d152cee1eac)
