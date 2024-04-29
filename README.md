# Ex.07 Software Product Company Website
## Date:24/04/2024

## AIM:
To develop a static company website to display the softwares and services provided by the company.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
START.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> HOME PAGE </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgb(214, 39, 0),rgba(147, 166, 227, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .logo {
                color:#1111c2;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(0, 13, 253);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgb(255, 255, 255);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(0, 0, 0);
            } 
            ::placeholder {
                color: rgb(0, 0, 0);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(0, 0, 0);
                border-radius: 10px;
                background:#ffffff;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(7, 6, 6);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: gray;
                background-color:#ffffff;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: rgb(0, 0, 0);
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: rgb(0, 0, 0);
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid#ffffff;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(0, 0, 0);
                border-radius: 30px;
                background-color:#ffffff;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid#ffffff;
                color:#ffffff;
                background-color: rgb(0, 0, 0);
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid#ffffff;
                padding: 13px 35px;
                letter-spacing: 1px;
                color: rgb(0, 0, 0);
                border-radius: 30px;
                background-color:#ffffff;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid#ffffff;
                color:#ffffff;
                background-color: rgb(0, 0, 0);
                transition: 0.5s;
                cursor: pointer;
            }
            footer {
                background-color:#ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/start.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="content">
            <div class="text">
                <h2>APPLE WEB WORLD</h2>
                <br>
                <p> DEVICE HUB </p>
                <br>
                <div>
                    <a href="#" class="login"> Log In </a>
                    <a href="#" class="signup"> Sign Up </a>
                </div>
            </div>
        </div>  
    </div>
    <footer>
        <center><big></big>Designed and Developed by Yendluri Chandana (212223100063) </center>
    </footer>
</body>
</html>
```

```
products.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgb(214, 39, 0),rgba(147, 166, 227, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: rgb(0, 21, 255);
                border-radius: 30px;
            }
            .logo {
                color:#0400ff;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: gray;
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: gray;
            } 
            ::placeholder {
                color: gray;
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: gray;
                border-radius: 10px;
                background:#ffffff;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: gray;
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: gray;
                background-color:#ffffff;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: gray;
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 300px;
                width: 140px;
                border: 2px solid gray;
                padding: 5px;
                
            }
            .image table td {
                color:#ffffff;
            }
            footer {
                background-color:#ffffff;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/start.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="200"> 
                <tr align="center">
                    <td> <img src="iphone 10.png"> </td>
                    <td> <img src="Iphone 8 plus.png"> </td>
                    <td> <img src="iphone 8.png"> </td>
                    <td> <img src="iphone 7.png"> </td>
                    <td> <img src="iphone 5.png"> </td>
                </tr>
                <tr align="center">
                    <th> Iphone x </th>
                    <th> Iphone 8 plus</th>
                    <th> Iphone 8</th>
                    <th> Iphone 7 </th>
                    <th> Iphone 5</th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Yendluri Chandana (212223100063) </center>
    </footer>
</body>
</html>
```
```
people.html

<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:linear-gradient(rgb(214, 39, 0),rgba(147, 166, 227, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: rgb(0, 0, 0);
               
                border-radius: 30px;
            }
            .logo {
                color:#1111c2;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(0, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(0, 0, 0, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(4, 3, 3);
            } 
            ::placeholder {
                color: rgb(11, 8, 8);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(255, 255, 255);
                border-radius: 10px;
                background:#984a4a;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(0, 0, 0);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(0, 0, 0);
                background-color:#010101;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: rgb(8, 6, 6);
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid rgb(5, 5, 5);
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color:#010101;
            }
            footer {
                background-color:#010101;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/start.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="200"> 
                <tr align="center">
                    <td> <img src="steve.png"> </td>
                    <td> <img src="cook.png"> </td>
                    <td> <img src="craig.png"> </td>
                    <td> <img src="tim.png"> </td>
                    <td> <img src="shaik.png"> </td>
                </tr>
                <tr align="center">
                    <th>Steves Jobs</th>
                    <th> Timothy Donald Cook </th>
                    <th> Craig Federighi </th>
                    <th> Tim Cook </th>
                    <th> Sabhi khan </th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by yendluri chandana (212223100063) </center>
    </footer>
</body>
</html>
```
```
people.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> people page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image:linear-gradient(rgb(214, 39, 0),rgba(147, 166, 227, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-people {
                border: 1px;
                padding: 10px;
                color: rgb(0, 0, 0);
               
                border-radius: 30px;
            }
            .logo {
                color:#1111c2;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(0, 0, 0);
            }
            form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(0, 0, 0, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(4, 3, 3);
            } 
            ::placeholder {
                color: rgb(11, 8, 8);
            }
            form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(255, 255, 255);
                border-radius: 10px;
                background:#984a4a;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(0, 0, 0);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(0, 0, 0);
                background-color:#010101;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .image {
                position: relative;
                border: 0;
                top: 70px;
                background: transparent;
            }
            .image table {
                border: 0;
                color: rgb(8, 6, 6);
                position: relative;
                left: 150px;
            }
            .image table img {
                height: 140px;
                width: 140px;
                border: 2px solid rgb(5, 5, 5);
                padding: 5px;
                border-radius: 50%;
            }
            .image table td {
                color:#010101;
            }
            footer {
                background-color:#010101;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/start.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/product.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html" class="bg-people"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="image">
            <table cellspacing="200"> 
                <tr align="center">
                    <td> <img src="steve.png"> </td>
                    <td> <img src="cook.png"> </td>
                    <td> <img src="craig.png"> </td>
                    <td> <img src="tim.png"> </td>
                    <td> <img src="shaik.png"> </td>
                </tr>
                <tr align="center">
                    <th>Steves Jobs</th>
                    <th> Timothy Donald Cook </th>
                    <th> Craig Federighi </th>
                    <th> Tim Cook </th>
                    <th> Sabhi khan </th>
                </tr>
                <tr align="center">
                    <td> CEO </td>
                    <td> CEO, Co-Founder </td>
                    <td> CTO, Co-Founder </td>
                    <td> Director </td>
                    <td> Asst. Director </td>
                </tr>
            </table>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by yendluri chandana(212223100063) </center>
    </footer>
</body>
</html>
```
```
contact.html
<html>
    <head>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title> Contact Us Page </title>
        <style type="text/css">
            * {
                margin: 0;
                padding: 0;
                font-family: Arial, Helvetica, sans-serif;
            }
            .banner {
                width: 100%;
                height: 100vh;
                background-image: linear-gradient(rgb(214, 39, 0),rgba(147, 166, 227, 0.75));
                background-size: cover;
                background-position: center;
            }
            .navbar {
                width: 85%;
                margin: auto;
                padding: 35px 0;
                display: flex;
                align-items: center;
                justify-content: space-between;
            }
            .bg-contact {
                border: 1px;
                padding: 10px;
                color: rgb(255, 255, 255);
                background-color:#ffffff;
                border-radius: 30px;
            }
            .logo {
                color:#1111c2;
                font-size: 40px;
                font-weight: 700;
                letter-spacing: 3px;
            }
            span {
                color: rgb(236, 229, 229);
            }
            .navbar form {
                width: 300px;
                height: 40px;
                display: flex;
                background: rgba(255, 255, 255, 0.2);
                padding: 1px 1px;
                font-size: 15px;
                border-radius: 10px;
                backdrop-filter: blur(4px) saturate(180%);
            }
            .navbar form input {
                background: transparent;
                flex: 1;
                border: 0;
                outline: none;
                padding: 12px 20px;
                font-size: 15px;
                color: rgb(255, 255, 255);
            } 
            ::placeholder {
                color: rgb(243, 243, 243);
            }
            .navbar form button {
                border: 0;
                outline: none;
                padding: 5px 20px;
                color: rgb(255, 255, 255);
                border-radius: 10px;
                background:#000000;
                cursor: pointer;
            }
            .navbar li {
                list-style: none;
                display: inline-block;
                margin: 0 20px;
                position: relative;
            }
            .navbar li a {
                text-decoration: none;
                color: rgb(0, 0, 0);
                text-transform: uppercase;
            }
            .navbar li:hover {
                border: 1px;
                padding: 10px;
                color: rgb(0, 0, 0);
                background-color:#000000;
                transition: 0.5s; 
                cursor: pointer;
                border-radius: 30px;
            }
            .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid rgb(0, 0, 0);
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid#000000;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: rgb(0, 0, 0);
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(0, 0, 0);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 15px;
                color: rgb(0, 0, 0);
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(0, 0, 0);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid rgb(0, 0, 0);
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 10px 20px;
                color: rgb(0, 0, 0);
                border-radius: 30px;
                background:#605858;
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(0, 0, 0);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: rgb(0, 0, 0);
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color:#000000;
                font-size: 20px;
            }
            footer {
                background-color:#000000;
                margin-top: auto;
            }
        </style>
    </head>
<body>
    <div class="banner">
        <br>
        <div class="navbar">
            <h1 class="logo">CodeHub</h1>
            <ul>
                <li><a href="http://127.0.0.1:8000/static/start.html"> Home </a></li>
                <li><a href="http://127.0.0.1:8000/static/products.html"> Products </a></li>
                <li><a href="http://127.0.0.1:8000/static/people.html"> People </a></li>
                <li><a href="http://127.0.0.1:8000/static/contact.html" class="bg-contact"> Contact </a></li>
            </ul>
            <form action="" method="get">
                <input type="text" placeholder="Enter to Search">
                <button type="submit"> Search </button>
            </form>
        </div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1> Contact Us </h1>
                        <input type="text" placeholder="Your Name">  <br>
                        <input type="email" placeholder="Your Email">
                        <br>
                        <textarea rows="4" cols="40" placeholder="Your Message"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> Contact Information </h2>
                <p> <span>Address</span> : srikalahasti,andhrapradesh,nagiri street </p>
                <p> <span>Email</span> : lakshmi34@gmail.com </p>
                <p> <span>Phone</span> : 7894561235 </p>
            </div>
        </div>
    </div>
    <footer>
        <center> Designed and Developed by Yendluri Chandana(212223100063) </center>
    </footer>
</body>
</html>
```

## OUTPUT:

![alt text](<Screenshot 2024-04-24 151552.png>)
![alt text](<Screenshot 2024-04-24 151633.png>)
![alt text](<Screenshot 2024-04-24 151712.png>)
![alt text](<Screenshot 2024-04-24 151739.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
