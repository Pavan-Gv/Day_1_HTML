# Table code
```
Developed by : G Venkata Pavan Kumar
Reg. No : 212221240013
```
### Assignment 1: Table 
HTML CODE:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    
</head>
<body>

<table border="1" width="100%">
    <tbody>
        <tr>
            <th colspan="2">My Day</th>
        </tr>
        <tr>
            <td >
                <ol>1. Wake up Early</ol>
                <ol>
                    <ul>
                        <li>5AM</li>
                        <li>walk</li>
                        <li>jog</li>
                    </ul>
                </ol>
            </td>
            <td rowspan="3">
                <table border="1" align="center">
                    <tr>
                        <th colspan="2">Things to watch</th>
                    </tr>
                    <tr>
                        <td >
                            <img src="images\row1.jpeg" width="100" height="100"></img>
                        </td>
                        <td>
                            <img src="images\row2.jpeg" width="100" height="100"></img>
                        </td>
                    </tr>
                    <tr>
                        <td>
                            <img src="images\row3.jpeg" width="100" height="100"></img>
                        </td>
                        <td>
                            <img src="images\row4.jpeg" width="100" height="100"></img>
                        </td>   
                    </tr>
                </table>
            </td>
        </tr>
       
        <tr>
            <td>
                <ol>2. Breakfast</ol>
                <ol>
                    <ul>
                        <li>8AM</li>
                        <li>eggs</li>
                        <li>coffee</li>
                    </ul>
                </ol>
            </td>
        </tr>
        <tr>
            <td>
                <ol>3.Go to Saveetha</ol>
                <ol>
                    <ul>
                        <li>8AM</li>
                        <li>go to college</li>
                        <li>to be continued</li>
                    </ul>
                </ol>
            </td>
        </tr>
    </tbody>
</table>

</body>
</html>

```
### Output:
![Screenshot 2024-07-03 214027](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/e998810e-593b-4f33-98f6-fbbc77cd4585)


### Assignment 2: College Website
#### index.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo" height="100" width="100">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Welcome to Saveetha Engineering College</h2>
        <p>College Name is a prestigious institution offering a diverse range of programs in Arts, Science, and Commerce. Our mission is to provide quality education and foster a love for learning in our students.</p>
    </div>
</body>
</html>

```
#### gallery.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo" height="100" width="100">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Gallery</h2>
        <img src="images/gallery1.jpeg" alt="Gallery Image 1" height="200" width="300">
        <img src="images/gallery2.png" alt="Gallery Image 2" height="200" width="300"><br>
        
        <img src="images/gallery3.png" alt="Gallery Image 3" height="200" width="300">
        <img src="images/gallery4.png" alt="Gallery Image 4" height="200" width="300">
    </div>
</body>
</html>

```
#### acedamics.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academics - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo" height="100" width="100">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Academic Departments</h2>
        <ul>
            <li>Arts
                <ul>
                    <li><a href="courses/english.html">English</a></li>
                    <li><a href="courses/sociology.html">Sociology</a></li>
                </ul>
            </li>
            <li>Science
                <ul>
                    <li><a href="courses/computer-science.html">Computer Science</a></li>
                    <li><a href="courses/mathematics.html">Mathematics</a></li>
                </ul>
            </li>
            <li>Commerce
                <ul>
                    <li><a href="courses/economics.html">Economics</a></li>
                    <li><a href="courses/business-management.html">Business Management</a></li>
                </ul>
            </li>
        </ul>
    </div>
</body>
</html>

```
#### admission.html:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admission - Saveetha Engineering College</title>
    <link rel="stylesheet" href="styles/style.css">
</head>
<body>
    <header>
        <img src="images/logo.png" alt="College Logo" height="100" width="100">
        <h1>Saveetha Engineering College</h1>
    </header>
    <nav>
        <a href="index.html">Home</a>
        <a href="academics.html">Academics</a>
        <a href="admission.html">Admission</a>
        <a href="gallery.html">Gallery</a>
    </nav>
    <div class="container">
        <h2>Admission Form</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name"><br><br>
            <label for="dob">Date of Birth:</label>
            <input type="date" id="dob" name="dob"><br><br>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email"><br><br>
            <label for="course">Course:</label>
            <select id="course" name="course">
                <option value="computer-science">Computer Science</option>
                <option value="mathematics">Mathematics</option>
                <option value="english">English</option>
                <option value="sociology">Sociology</option>
                <option value="economics">Economics</option>
                <option value="business-management">Business Management</option>
            </select><br><br>
            <input type="submit" value="Submit">
        </form>
    </div>
</body>
</html>

```

### Outputs:

**Index.html**:

![image](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/3c61e861-e5bb-47d9-85db-27eee2a88abb)

**Acedamics.html**:

![image](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/c52efe03-f088-4cec-b738-e9ff67a6f410)

**Admissions.html**:

![image](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/ba67e602-3827-4d27-965b-5776f2d534fa)

**Gallery.html**:

![image](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/733863df-3ade-4201-aa66-db4c2dbf33fe)


### CSS Project:
#### Index
```HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css\styles.css">
</head>
<body>
    <div class="banner">
        <br />
        <div class="navbar">
            <div class="logo">TECHBLITZz... </div>
          <ul>
            <li><a href="index.html"> Home </a></li>
            <li><a href="services.html"> services </a></li>
            <li><a href="people.html"> People </a></li>
            <li><a href="contact.html"> Contact </a></li>
          </ul>
          <form action="" method="get">
            <input type="text" placeholder="Enter to Search" /><br>
            <button id="search" type="submit">Search</button>
          </form>
        </div>
        <div class="content">
          <div class="text">
                Navigate your Way to Innovation
            <br>
            <br>
            <br>
            <div class="cont">
                TechBlitzz is a cutting-edge company dedicated to providing comprehensive technical solutions across various domains. Our mission is to simplify the complexities of technology for businesses and individuals alike, ensuring seamless integration and optimal performance. From IT support and network solutions to software development and cybersecurity, TechBlitzz leverages expertise and innovation to meet the evolving needs of our clients.
            </div>
  
            <br />
          </div>
        </div>
      </div>
    </div>
<footer>
    <center>Developed by | Pavan GV | </center>
</footer>
</body>
</html>
```

#### people:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css\styles.css">
</head>
<body>
    <div class="banner">
        <br />
        <div class="navbar">
            <div class="logo">TECHBLITZz... </div>
          <ul>
            <li><a href="index.html"> Home </a></li>
            <li><a href="services.html"> services </a></li>
            <li><a href="people.html"> People </a></li>
            <li><a href="contact.html"> Contact </a></li>
          </ul>
          <form action="" method="get">
            <input type="text" placeholder="Enter to Search" /><br>
            <button id="search" type="submit">Search</button>
          </form>
        </div>
        <div class="content">
          <div class="text">
                Navigate your Way to Innovation
            <br>
            <br>
            <br>
            <div class="cont">
                TechBlitzz is a cutting-edge company dedicated to providing comprehensive technical solutions across various domains. Our mission is to simplify the complexities of technology for businesses and individuals alike, ensuring seamless integration and optimal performance. From IT support and network solutions to software development and cybersecurity, TechBlitzz leverages expertise and innovation to meet the evolving needs of our clients.
            </div>
  
            <br />
          </div>
        </div>
      </div>
    </div>
<footer>
    <center>Developed by | Pavan GV | </center>
</footer>
</body>
</html>
```
#### css file:
```html
* {
    margin: 0;
    padding: 0;
    
  }
  .banner{
    width: 100%;
    height: 95vh;
    background-color: aliceblue;
  }
  .navbar {
    width: 85%;
    margin: auto;
    padding: 40px 0;
    display: flex;
    align-items: center;
    justify-content: space-between;
  }
  .logo {
    height: 50px;
    font-size: 50px;
    font-family:'sans-serif';
    color: #305017;

  }
  form {
    width: 200px;
    height: 40px;
    display: flex;
    background: rgba(255, 255, 255, 0.2);
    padding: 1px 1px;
    font-size: 15px;
    border-radius: 10px;
    backdrop-filter: blur(4px) saturate(180%);
  }
  form input {
    background: rgb(226, 226, 226);
    flex: 1;
    border: 0;
    border-radius: 10%;
    outline: none;
    padding: 12px 20px;
    font-size: 15px;
  }
  ::placeholder {
    color: black;
  }
  form button {
    border: 0;
    outline: none;
    padding: 5px 20px;
    color: white;
    border-radius: 10px;
    background: #59b18e;
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
    color: black;
    text-transform: uppercase;
  }
  
  .content {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
  }
  .text{
    color: #305017;
    font-weight: 700;
    font-size: 30px;
    letter-spacing: 3px;
    font-family:'sans-seri';
  }
  
  
  footer {
    border: 1px;
    padding: 5px;
    font-family: 'sans-serif';
    transition: 0.5s;
    background: #000000;
    color: #9cdcc8;
    box-shadow: 0 0 20px #305017;
  }
  .cont{
    font-family:'Times New Roman', Times, serif;
    font-size: 20px;
    color: #000000;
  }
```

### Output:
![image](https://github.com/Pavan-Gv/Day_1_HTML/assets/94827772/df49c8bc-9b90-481e-bbe1-f086c717e4d0)
