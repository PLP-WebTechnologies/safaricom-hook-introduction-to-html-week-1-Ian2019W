[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/TUGW0SrP)
# Welcome to the HTML5 Basics Assignment repository! 

This assignment is designed to help you build foundational knowledge of HTML5, understand its structure, and practice creating web page content using semantic elements.

## Learning Objectives

By completing this assignment, you will:

  Understand the structure and purpose of HTML5 in web development.
  Learn to create basic web page content using core HTML5 elements.
  Explore semantic HTML elements and their benefits for readability and SEO.
  Gain a basic understanding of accessibility and SEO best practices in HTML.
  
## Assignment Content
  1. HTML5 Basics
Learn the structure of an HTML document (e.g., <!DOCTYPE html>, <html>, <head>, <body>).
Explore core elements such as headings, paragraphs, lists, links, and images.
  2. Semantic HTML
Introduction to semantic tags like <header>, <footer>, <nav>, <section>, and <article>.
Learn how semantic elements improve content readability and support SEO.
  3. Accessibility and SEO Basics
Understand the importance of accessible HTML and SEO-friendly practices.
Use attributes like alt, title, and semantic structures to improve usability.

## Activities

Creating a Simple Webpage: Design a basic webpage that includes text, images, and links.
Use common HTML tags like h1, p, a, img, and ul or ol.
Structure a webpage with semantic tags such as header, footer, nav, section, and article.
Ensure the content is well-organized for readability and SEO.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Simple Webpage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }
        header, footer {
            background-color: #f4f4f4;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 10px;
        }
        section {
            margin: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to My Simple Webpage</h1>
    </header>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <section id="home">
        <article>
            <h2>Introduction</h2>
            <p>This is my first HTML webpage, just completed it for my Day 1 assighnment submission.</p>
            <img src="download.jpeg" alt="Software engineer ">
        </article>
    </section>
    <section id="about">
        <article>
            <h2>About Me</h2>
            <p>Im a PLP student just trying his best to learn and understand programming so that maybe one day i'll become one of the best Software engineers in the world.</p>
        </article>
    </section>
    <section id="contact">
        <article>
            <h2>Contact Information</h2>
            <p>If you would like to get in touch, please use the contact information below.</p>
            <ul>
                <li>Email: <a href="wangunyuian@gmail.com">wangunyuian@gmail.com</a></li>
                <li>Phone: +254 702 684 414</li>
            </ul>
        </article>
    </section>
    <footer>
        <p>&copy; 2024 My Simple Webpage. All rights reserved.</p>
    </footer>
</body>
</html>

