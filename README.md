<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ukaenthiran's Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ff2d2d;
        }
        header {
            background-color: #c7ff33;
            text-align: center;
            padding: 20px;
            font-size: 24px;
            font-weight: bold;
        }
        nav {
            background-color: #d70040;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .section {
            background: white;
            padding: 20px;
            margin: 15px 0;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        .btn {
            display: block;
            width: 150px;
            margin: 10px auto;
            padding: 10px;
            text-align: center;
            background: black;
            color: white;
            text-decoration: none;
            border-radius: 5px;
        }
        footer {
            text-align: center;
            padding: 10px;
            background: black;
            color: white;
        }
    </style>
</head>
<body>

<header>
    Ukaenthiran K<br>
    <small>BCA Student</small>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
</nav>

<div class="container">
    <div class="section" id="about">
        <h2>About Me</h2>
        <p>I am Ukaenthiran, currently pursuing a Bachelor of Computer Applications (BCA) at Prince Shri Venkateswara Arts and Science College.</p>
    </div>

    <div class="section" id="education">
        <h2>Education</h2>
        <p>Bachelor of Computer Applications (BCA)</p>
    </div>

    <div class="section" id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>Data Structures</li>
            <li>C++</li>
        </ul>
    </div>

    <div class="section" id="projects">
        <h2>Projects</h2>
        <p><a href="#">Bank Account Program in Python</a></p>
    </div>

    <div class="section" id="resume">
        <h2>Resume</h2>
        <a href="#" class="btn">Download CV</a>
    </div>
</div>

<footer>
    © 2025 Ukaenthiran K
</footer>

</body>
</html>
