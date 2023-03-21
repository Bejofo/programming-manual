# HTML/CSS
HTML (Hypertext Markup Language) is a markup language used for creating the structure and content of web pages. It provides a way to add headings, paragraphs, images, links, and other elements to a web page. HTML was first developed in 1990 by Tim Berners-Lee, a British computer scientist who is also credited with inventing the World Wide Web.

CSS (Cascading Style Sheets) is a stylesheet language used for describing the presentation of web pages, including layout, colors, fonts, and other design aspects. CSS was developed in 1996 by Håkon Wium Lie, a Norwegian web pioneer. CSS allows developers to separate the design elements of a web page from its content, making it easier to maintain and update.

<img style="float: right; width:30%; height:50%; object-fit:contain;" src="https://miro.medium.com/v2/resize:fit:792/1*lJ32Bl-lHWmNMUSiSq17gQ.png">

# Nerd stuff
Together, HTML and CSS are the backbone of the web. They provide the basic tools for creating and designing web pages, and they continue to evolve to meet the needs of modern web design. 

HTML and CSS lacks functionality. They need to be used with other technologies like JavaScript to create dynamic and interactive web pages that engage users and provide a rich user experience.

# Ecosystem
To get started, simply create a HTML file (ex. index.html) and a CSS file (ex. style.css) on your computer.

To apply the style in your CSS file, reference the CSS file in your HTML file.
```
<link rel="stylesheet" href="style.css">
```


# Examples
To make "Hello, World!" be displayed on your browser

In your HTML file,
```
<html>
  <head></head>
  <body>
    <h1>Hello, World!</h1>
  </body>
<html>
```
To change your "Hello, World!" text color to blue

In your CSS file
```
h1 {
  color: blue;
}
```
Then reference the CSS file in your HTML file
```
<html>
  <head>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <h1>Hello, World!</h1>
  </body>
<html>
```

# Stats
CSS is used by 97.1% of all the websites.

Stats from https://w3techs.com/technologies/details/ce-css#:~:text=CSS%20is%20used%20by%2097.1%25%20of%20all%20the%20websites.
