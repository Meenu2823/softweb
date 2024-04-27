# Ex.07 Software Product Company Website
## Date:27.04.24

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
### home.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            text-align: center;
            color: wheat;
            font-size: 15px;
            padding: 15px;
            font-weight: bold;
        }
        a:hover{
            color: lightskyblue;
        }
        #h{
            color: goldenrod;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            padding: 10px;
            text-align: left;
        }
        h6{
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        i{
            font-size: 30px;
            color: gold;
        }
    </style>
</head>
<body style="background-image: url(bg1.jpg);background-repeat: no-repeat;background-size:cover;">
    <div class="d-flex align-items-center" style="background-color: black;">
          <img src="D.png" alt="" style="width: 150px;height: 150px;border-radius: 50%;">
          <h1 id="h"><b>DREAM<br>DEVELOPERS</b></h1>
          <a href="home.html" style="padding-left: 200px;">HOME</a>
          <a href="people.html">PEOPLE</a>
          <a href="product.html">PRODUCTS</a>
          <a href="contact.html">CONTACT</a>
          <div style="padding-left: 240px;">
          <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Enter to Search" aria-label="Search">
                <button class="btn btn-primary" type="submit">Search</button>
              </form>
            </div>
           </div>
        </nav>
    </div>
    <div class="my-5 d-flex align-items-center">
         <div style="width: 70%;padding-right: 20%;padding-left: 10%;">
            <h1 style="color: bisque;font-size: 50px;">A Software Agency shaping ideas into Products</h1>
            <h4 style="color:gold;">"People who are really serious about software should make their own hardware" - Alan Kay.</h4>
            <button class="btn btn-primary" type="submit">Join Us</button>
         </div>
         <div class="card text-center mb-3 bg-dark" style="width: 18rem;color: bisque;">
            <div class="card-header" style="background-color: darkgoldenrod;">
                Login Here
            </div>
            <div class="card-body">
                User Name <p><input type="text" name="uname" id=""></p><br>
                Password <p><input type="password" name="pwd" id=""></p><br>
              <a href="#" class="btn btn-primary">Login</a>
              <p>Don't you have an account <b style="color: goldenrod;">Sign Up</b> here</p>
            </div>
            <div class="card-footer">
                <p class="card-text">Log in with</p>
                <i class="bi bi-facebook"></i>
                <i class="bi bi-google" ></i>
                <i class="bi bi-instagram"></i>
            </div>
          </div>
    </div>
    <div class="fixed-bottom" style="background-color: lightskyblue;color: navy;">
        <h6>Designed & Developed by MEENU.S © 2024</h6>
    </div>
</body>
</html>
~~~
### people.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            text-align: center;
            color: wheat;
            font-size: 15px;
            padding: 15px;
            font-weight: bold;
        }
        a:hover{
            color: lightskyblue;
        }
        #h{
            color: goldenrod;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            padding: 10px;
            text-align: left;
        }
        h6{
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        h5{
            font-size: 20px;
            color: bisque;
            text-align: center;
        }
        p{
            font-size: 15px;
            color: bisque;
            text-align: center;
        }
    </style>
</head>
<body style="background-image: url(bg1.jpg);background-repeat: no-repeat;background-size:cover;">
    <div class="d-flex align-items-center" style="background-color: black;">
          <img src="D.png" alt="" style="width: 150px;height: 150px;border-radius: 50%;">
          <h1 id="h"><b>DREAM<br>DEVELOPERS</b></h1>
          <a href="home.html" style="padding-left: 200px;">HOME</a>
          <a href="people.html">PEOPLE</a>
          <a href="product.html">PRODUCTS</a>
          <a href="contact.html">CONTACT</a>
          <div style="padding-left: 240px;">
          <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Enter to Search" aria-label="Search">
                <button class="btn btn-primary" type="submit">Search</button>
              </form>
            </div>
           </div>
        </nav>
    </div>
    <div class="my-5 d-flex align-items-center">
        <div style="padding: 7%;">
          <img src="profile.jpg" style="width: 200px;height: 200px;border-radius: 50%;">
          <h5><b>MEENU.S</b></h5>
          <p>Chairman,CEO</p>
        </div>
        <div style="padding: 5%;padding-left: 0%;">
          <img src="President.jpg" style="width: 200px;height: 200px;border-radius: 50%;">
          <h5><b>John Joseph</b></h5>
          <p>President of Board</p>
        </div>
        <div style="padding: 5%;padding-left: 0%;">
            <img src="VP.jpg" style="width: 200px;height: 200px;border-radius: 50%;">
            <h5><b>Angelina</b></h5>
            <p>Vice-President of Board</p>
        </div>
        <div style="padding: 5%;padding-left: 0%;">
            <img src="Non-executive director.jpg" style="width: 200px;height: 200px;border-radius: 50%;">
            <h5><b>Ram</b></h5>
            <p>Non-executive director</p>
        </div>
        <div style="padding: 5%;padding-left: 0%;">
            <img src="CFO.jpg" style="width: 200px;height: 200px;border-radius: 50%;">
            <h5><b>Kavya Haris</b></h5>
            <p>Chief Financial Officer(CFO)</p>
        </div>
    </div>
    <div class="fixed-bottom" style="background-color: lightskyblue;color: navy;">
        <h6>Designed & Developed by MEENU.S © 2024</h6>
    </div>
</body>
</html>
~~~
### product.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            text-align: center;
            color: wheat;
            font-size: 15px;
            padding: 15px;
            font-weight: bold;
        }
        a:hover{
            color: lightskyblue;
        }
        #h{
            color: goldenrod;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            padding: 10px;
            text-align: left;
        }
        h6{
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        
    </style>
</head>
<body style="background-image: url(bg1.jpg);background-repeat: no-repeat;background-size:cover;">
    <div class="d-flex align-items-center" style="background-color: black;">
          <img src="D.png" alt="" style="width: 150px;height: 150px;border-radius: 50%;">
          <h1 id="h"><b>DREAM<br>DEVELOPERS</b></h1>
          <a href="home.html" style="padding-left: 200px;">HOME</a>
          <a href="people.html">PEOPLE</a>
          <a href="product.html">PRODUCTS</a>
          <a href="contact.html">CONTACT</a>
          <div style="padding-left: 240px;">
          <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Enter to Search" aria-label="Search">
                <button class="btn btn-primary" type="submit">Search</button>
              </form>
            </div>
           </div>
        </nav>
    </div>
    <div class="my-5 d-flex align-items-center">
        <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="CSD.png" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text"><b>Custom software development</b> allows companies to ensure that their software
             solutions meet their needs and deliver the best results, whether by introducing automation into
             their working processes or validating and developing an idea for a new product that will give
             them a competitive edge in the market.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="WD.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text"><b>Web development</b> services contain the full range of activities necessary
              to build a web solution, be it a simple website or a complex, unique solution. Web development 
              includes everything from creating the code to hosting, optimising and maintaining web pages.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="MAD.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text">From a business standpoint, <b>Mobile Application Development</b> is often seen 
                as a way to reach new customers or markets. For example, mobile apps can be used by retailers 
                to provide customers with a better version of the brand's website and improve the in-store 
                shopping experience.</p>
            </div>
          </div>
          <div class="card" style="width: 18rem;margin: 5%;margin-top: 0%;">
            <img src="Cloud.jpg" class="card-img-top" alt="">
            <div class="card-body">
              <p class="card-text">The process of developing software applications that are designed to run 
                in the cloud is known as <b>Cloud Software Development</b>. It involves using cloud computing 
                services and platforms to develop, test and manage software applications.</p>
            </div>
          </div>
    </div>
    <div class="fixed-bottom" style="background-color: lightskyblue;color: navy;">
        <h6>Designed & Developed by MEENU.S © 2024</h6>
    </div>
</body>
</html>
~~~
### contact.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" 
    integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            text-decoration: none;
            text-align: center;
            color: wheat;
            font-size: 15px;
            padding: 15px;
            font-weight: bold;
        }
        a:hover{
            color: lightskyblue;
        }
        #h{
            color: goldenrod;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            padding: 10px;
            text-align: left;
        }
        h6{
            text-align: center;
            font-family: 'Times New Roman', Times, serif;
        }
        i{
            font-size: 30px;
            color: gold;
        }
        input{
            border-radius: 5px;
            width: 30rem;
            margin: 2.5%;
            align-self: center;
        }
        #ta{
            border-radius: 15px;
            margin: 2.5%;
        }
        #ch{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 25px;
            color: black;
        }
        #ci{
            color: black;
            font-size: 20px;
            font-weight: bold;
        }
    </style>
</head>
<body style="background-image: url(bg1.jpg);background-repeat: no-repeat;background-size:cover;">
    <div class="d-flex align-items-center" style="background-color: black;">
          <img src="D.png" alt="" style="width: 150px;height: 150px;border-radius: 50%;">
          <h1 id="h"><b>DREAM<br>DEVELOPERS</b></h1>
          <a href="home.html" style="padding-left: 200px;">HOME</a>
          <a href="people.html">PEOPLE</a>
          <a href="product.html">PRODUCTS</a>
          <a href="contact.html">CONTACT</a>
          <div style="padding-left: 240px;">
          <nav class="navbar bg-body-tertiary">
            <div class="container-fluid">
              <form class="d-flex" role="search">
                <input class="form-control me-2" type="search" placeholder="Enter to Search" aria-label="Search">
                <button class="btn btn-primary" type="submit">Search</button>
              </form>
            </div>
           </div>
        </nav>
    </div>
    <div class="my-5 d-flex align-items-center">
        <div class="card" style="width: 36rem;margin: 5%;border-radius: 5%;background-color: darkgoldenrod;">
            <div class="card-header" id="ch"><b>Contact Us</b></div>
            <div class="card-body">
                <input type="text" placeholder="Your Name" ><br>
                <input type="email" placeholder="Your Email">
                <textarea name="" id="ta" cols="62" rows="5" placeholder="Your Message"></textarea>
            </div>
        </div>
        <div class="card" style="width: 30rem;margin: 5%;border-radius: 5%;background-color: darkgoldenrod;">
            <div class="card-header" id="ch"><b>Contact Information</b></div>
            <div class="card-body">
                <i class="bi bi-geo-alt-fill" style="color: black;"></i>
                <span id="ci"> : 123 Main Street,Tiruvallur,Chennai </span><br>
                <i class="bi bi-envelope-at-fill" style="color: black;"></i>
                <span id="ci"> : dd@gmail.com </span><br>
                <i class="bi bi-telephone-fill" style="color: black;"></i>
                <span id="ci"> : 044-0804 </span><br>
            </div>
        </div>
    </div>
    <div class="fixed-bottom" style="background-color: lightskyblue;color: navy;">
        <h6>Designed & Developed by MEENU.S © 2024</h6>
    </div>
</body>
</html>
~~~
## OUTPUT:

![image](https://github.com/Meenu2823/softweb/assets/139416219/2e558e50-8bbc-44f3-8eea-38b271d4eaee)
![image](https://github.com/Meenu2823/softweb/assets/139416219/f61decaa-4678-4f41-9659-70906e6b56cc)
![image](https://github.com/Meenu2823/softweb/assets/139416219/3e3a814c-d1ff-4ab9-9d04-144d2249ecd8)
![image](https://github.com/Meenu2823/softweb/assets/139416219/525c39ac-4d53-445c-81f9-046d524f6826)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
