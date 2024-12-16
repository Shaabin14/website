# Ex.07 Restaurant Website
# Date: 28.10.2024
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
index.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="
        width=device-width, initial-scale=1">
        <!--google fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
         <!--font awesome-->
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
         <!-- connect style.css -->
          <link rel="stylesheet" type="text/css" href="style.css">
        <title>Shaabin Restaurant</title>
    </head>
    <body>
        <!--hero section begin-->
        <div id="hero">
            <div id="hero_content">
                <h1>Shaabin's Restaurant</h1>
                <h2>Best Quality and Tasty Food Point</h2>
                <a href="menu.html">Menu</a>
            </div>
        </div>
        <!--hero section End-->
        <!--header section begin-->
        <div id="header">
            <nav id="navbar">
                <h1>Shaabin's Restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="Administration.html">Administration</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                <div id="phone">
                    <a href="tel:+1234567890">+1234567890</a>
                </div>
            </nav>
            <div id="mobile_menu">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#Administration">Administration</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li> 
                </ul>
            </div>
        </div>
        <!--Header Section End -->
                  <!--Footer Section Begin -->
                  <div id="footer">
                    <div>
                        <h5>Copyright &copy;2024 | <a href="">Shaabinrestaurantwebtech</a></h5>
                    </div>
                    <div id="top">
                        <a href="#hero"><i class="fa fa-chevron-circle-up"></i></a>
                    </div>
                  </div>
                  <!--Footer Section End -->
    </body>
</html>

```
menu.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="
        width=device-width, initial-scale=1">
        <!--google fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
         <!--font awesome-->
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
         <!-- connect style.css -->
          <link rel="stylesheet" type="text/css" href="style.css">
        <title>Shaabin Restaurant</title>
    </head>
    <body>
         <!--header section begin-->
         <div id="header">
            <nav id="navbar">
                <h1>Shaabin's Restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="Administration.html">Administration</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                <div id="phone">
                    <a href="tel:+1234567890">+1234567890</a>
                </div>
            </nav>
            <div id="mobile_menu">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#Administration">Administration</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li> 
                </ul>
            </div>
        </div>
        <!--Header Section End -->
         <!--Menu Section begin-->
        <div id="menu">
            <h1 id="section">Menu</h1>
            <div id="menu_row">
                <div id="menu_col">
                    <h2>Breakfast</h2>
                    <div class="box">
                        <div id="image">
                            <img src="images/breakfast.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 01</h3>
                            <h4>10$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/breakfast2.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 02</h3>
                            <h4>30$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/breakfast3.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 03</h3>
                            <h4>20$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/breakfast4.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 04</h3>
                            <h4>40$</h4>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Lunch</h2>
                    <div class="box">
                        <div id="image">
                            <img src="images/lunch.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 01</h3>
                            <h4>100$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/lunch2.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 02</h3>
                            <h4>300$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/lunch3.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 03</h3>
                            <h4>200$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/lunch4.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 04</h3>
                            <h4>400$</h4>
                        </div>
                    </div>
                </div>
                <div id="menu_col">
                    <h2>Dinner</h2>
                    <div class="box">
                        <div id="image">
                            <img src="images/dinner.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 01</h3>
                            <h4>1000$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/dinner2.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 02</h3>
                            <h4>3000$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/dinner3.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 03</h3>
                            <h4>2000$</h4>
                        </div>
                    </div>
                    <div class="box">
                        <div id="image">
                            <img src="images/dinner4.jpg">
                        </div>
                        <div>
                            <h3>Tasty Dish 04</h3>
                            <h4>4000$</h4>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        </body>
        </html>
                    <!--Menu Section End -->
```
administration.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="
        width=device-width, initial-scale=1">
        <!--google fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
         <!--font awesome-->
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
         <!-- connect style.css -->
          <link rel="stylesheet" type="text/css" href="style.css">
        <title>Shaabin Restaurant</title>
    </head>
    <body>
         <!--header section begin-->
         <div id="header">
            <nav id="navbar">
                <h1>Shaabin's Restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="Administration.html">Administration</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                <div id="phone">
                    <a href="tel:+1234567890">+1234567890</a>
                </div>
            </nav>
            <div id="mobile_menu">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#Administration">Administration</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li> 
                </ul>
            </div>
        </div>
        <!--Header Section End -->
                    <!--Administration Section Begin -->
                    <div id="Administration">
                        <h1 id="section">Administration</h1>
                        <div id="Administration_row">
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/yuga.webp">
                                </div>
                                <div>
                                    <h4>Chef Yuga</h4>
                                    <h4>Executive Chef</h4>
                                    <h4>(Overall Head Chef)</h4>
                                </div>
                            </div>
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/cutie.webp">
                                </div>
                                <div>
                                    <h4>Chef Cutie</h4>
                                    <h4>Garde Manger</h4>
                                    <h4>(Pantry Chef)</h4>
                                </div>
                            </div>
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/sam.jpeg">
                                </div>
                                <div>
                                    <h4>Chef Sam</h4>
                                    <h4> Chef de Cuisine</h4>
                                    <h4>(Head Chef)</h4>
                                </div>
                            </div>
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/sweety.webp">
                                </div>
                                <div>
                                    <h4>Chef Sweety</h4>
                                    <h4> Chef De Partie</h4>
                                    <h4> (Station Chef)</h4>
                                </div>
                            </div>
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/veega.jpeg">
                                </div>
                                <div>
                                    <h4>Chef Veera</h4>
                                    <h4> Sous Chef </h4>
                                    <h4>(Deputy Head Chef)</h4>
                                </div>
                            </div>
                            <div class="Administration_col">
                                <div id="img">
                                    <img src="images/beauty.webp">
                                </div>
                                <div>
                                    <h4>Chef Beauty</h4>
                                    <h4> Commis Chef</h4>
                                    <h4>(Junior Chef)</h4>
                                </div>
                            </div>
                        </div>
                    </div>
                    </body>
                    </html>
                  <!--Administration Section Ends -->
```
about.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="
        width=device-width, initial-scale=1">
        <!--google fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
         <!--font awesome-->
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
         <!-- connect style.css -->
          <link rel="stylesheet" type="text/css" href="style.css">
        <title>Shaabin Restaurant</title>
    </head>
    <body>
         <!--header section begin-->
         <div id="header">
            <nav id="navbar">
                <h1>Shaabin's Restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="Administration.html">Administration</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                <div id="phone">
                    <a href="tel:+1234567890">+1234567890</a>
                </div>
            </nav>
            <div id="mobile_menu">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#Administration">Administration</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li> 
                </ul>
            </div>
        </div>
        <!--Header Section End -->
          <!--About Section Begin -->
          <div id="about">
            <h1 id="section">About</h1>
            <div id="about_row">
                <div class="about_col">
                    <h1>About Us</h1>
                    <p>
                        Where it matters, they add author and creator information, too. (For example, brands who rely on multiple authors across their site have dedicated bios for each of them.)
                        They answer the questions, “Why does your business exist, and who does it exist to serve?”                             
                        And that's exactly what your About page should do.
                        Sure, write one because it's standard practice, but also make sure you write an effective About Us page that will help build trust with your customers and demonstrate why your brand is an authority on what you sell.
                        Don't let your About Us page become an afterthought  it's a foundational website page, and should be created and written strategically. 
                    </p>
                </div>
                <div class="about_col">
                    <div id="about_img">
                    <img src="images/aboutus.jpg">
                    </div>
                </div>
            </div>
          </div>
          </body>
          </html>
          <!--About Section End -->
```
contact.html
```
<!DOCTYPE html>
<html>
    <head>
        <meta charset="utf-8">
        <meta name="viewport" content="
        width=device-width, initial-scale=1">
        <!--google fonts-->
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Poppins&display=swap" rel="stylesheet">
         <!--font awesome-->
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
         <!-- connect style.css -->
          <link rel="stylesheet" type="text/css" href="style.css">
        <title>Shaabin Restaurant</title>
    </head>
    <body>
         <!--header section begin-->
         <div id="header">
            <nav id="navbar">
                <h1>Shaabin's Restaurant</h1>
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="menu.html">Menu</a></li>
                    <li><a href="Administration.html">Administration</a></li>
                    <li><a href="about.html">About</a></li>
                    <li><a href="contact.html">Contact</a></li>
                </ul>
                <div id="phone">
                    <a href="tel:+1234567890">+1234567890</a>
                </div>
            </nav>
            <div id="mobile_menu">
                <ul>
                    <li><a href="index.html">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#Administration">Administration</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li> 
                </ul>
            </div>
        </div>
        <!--Header Section End -->
         <!--Contact Section Begin -->
         <div id="contact">
            <h1 id="section">Contact</h1>
            <div id="contact_row">
                <div class="contact_col">
                    <div>
                        <p>
                            <i class="fa fa-map-marker"></i>
                            Mannivakkam,Chengalpattu District,Chennai
                        </p>
                        <p>
                            <a href="mailto: restaurantwebtech@gmail.com">
                                <i class="fa fa-envelope"></i>
                                restaurantwebtech@gmail.com
                            </a>
                        </p>
                        <p>
                            <a href="tel:+1234567890">
                            <i class="fa fa-phone-square"></i>
                            +1234567890
                        </a>
                        </p>
                        <h3>Follow Us</h3>
                        <p id="social">
                            <a href=""><i class="fa fa-facebook-official fa-2x"></i></a>
                            <a href=""><i class="fa fa-instagram fa-2x"></i></a>
                            <a href=""><i class="fa fa-twitter-square fa-2x"></i></a>
                            <a href=""><i class="fa fa-youtube-square fa-2x"></i></a>
                        </p>
                    </div>
                </div>
                <div class="contact_col">
                     <form>
                        <h2>Get in touch</h2>
                        <input type="text" placeholder="Name">
                        <input type="email" placeholder="Email">
                        <input type="text" placeholder="Subject">
                        <textarea rows="6" placeholder="Type Message"></textarea>
                        <button>Send Message</button>
                     </form>
                </div>
            </div>
          </div>
          </body>
          </html>
          <!--Contact Section End -->
```
css
```
*{
    margin: 0;
    padding: 0;
}
html{
    font-size:100%;
    scroll-behavior: smooth;
}
body{
    font-family: "Poppins", sans-serif;
    overflow-x: hidden;
}
#hero{
    position:relative;
    width:100vw;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
}
#hero::before{
     content:"";
     position:absolute;
     top:0;
     Left:0;
     width:100%;
     height:100%;
     background-image:url(images/res.jpg);
     background-position:center;
     background-repeat:no-repeat;
     background-attachment:fixed;
     filter:brightness(50%);
}
#hero_content{
    position:absolute;
}
#hero_content h1{
    color: #fff;
    font-size:2.8rem;
    text-shadow:2px 2px 2px #000;
}
#hero_content h2{
    color: #fff;
    font-size:2rem;
    font-family:cursive;
    margin-top:1rem;
    margin-bottom:4rem;
    text-shadow:2px 2px 2px #000;
}
#hero_content a{
    color: #fff;
    padding:3px 20px 3px 20px;
    border:1px solid orange;
    background: rgb(0,0,0,0.6);
    font-size:1.5rem;
    text-decoration:none;
    border-radius: 25px;
}
#hero_content a:hover{
    background: navy;
}
#header{
    position:fixed;
    top:0;
    width:100vw;
    height:70px;
    line-height:70px;
}
#navbar{
    display:flex;
    justify-content:space-around;
    background: rgb(0,0,0,0.5);
}
#navbar h1{
    color: orange;
    font-size:1.8rem;
    text-shadow:2px 2px 2px #000;
    font-family:cursive;
}
#navbar ul{
    display:flex;
}
#navbar ul li{
    List-style: none;
    padding:3px 15px 3px 15px;
}
#navbar ul li:hover,#phone a:hover,#mobile_menu ul li:hover{
    background: navy;
    cursor:pointer;
}
#navbar ul li a{
    text-decoration:none;
    color: #fff;
    font-size:1.1rem;
}
#phone a{
    text-decoration:none;
    color: #fff;
    font-size:1.1rem;
    padding:3px 15px 3px 15px;
    border:1px solid orange;
}
#mobile_menu{
    display:none;
    height:20px;
    Line-height:20px;
    background-color:magenta;
}
#mobile_menu ul{
    display:flex;
    justify-content:center;
}
#mobile_menu ul li{
    List-style:none;
    padding:0 5px 0 5px;
}
#mobile_menu ul li a{
    text-decoration:none;
    color: #fff;
}
@media screen and(max-width : 768px){
    #header{
        position:absolute;
    }
    #mobile_menu{
        display:block;
    }
    #navbar ul{
        display: none;
    }
    html{
        font-size:95%;
    }
    #menu_row{
        flex-wrap:wrap;
        padding:0 10px 0 10px;
    }
}
@media screen and(max-width : 360px){
    html{
        font-size1;70%;
    }
}
#menu{
    padding:15px 0 15px 0;
}
#section{
    padding:25px 0 25px 0;
    text-align:center;
    font-size:2rem;
    font-family:verdana;
}
#menu_row,#about row{
    display:flex;
    padding:0 100px 0 100px;
}
#menu_col{
    box-shadow:2px 2px 2px #bbb;
    border:1px solid #bbb;
    background-color: #fff;
    margin:8px;
    padding:10px;
    flex:1;
}
#menu_col h2{
    background-color:red;
    color: #fff;
    text-align:center;
    padding:5px;
    font-family:cursive;
}
#image{
    width:150px;
    height:150px;
    border-radius:50%;
    padding:5px;
    border:2px solid orange;
}
#image img{
    width:100%;
    height:100%;
    border-radius:50%;
    object-fit:cover;
}
.box{
    display:flex;
    flex-direction:column;
    align-items:center;
    text-align:center;
    margin:5px;
}
#Administration{
    padding:25px 0 25px 0;
}
#Administration_row{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
}
.Administration_col{
    text-align:center;
    padding:10px;
    margin:5px;
}
#img{
    width:200px;
    height:250px;
    margin:auto;
}
#img img{
    width:100%;
    height:100%;
    object-fit:cover;
}
.box{
    display:flex;
    flex-direction:column;
    align-items:center;
    text-align:center;
    margin:5px;
}
#about{
    padding:25px 0 25px 0;
}
#about_row{
    display:flex;
    justify-content:center;
    align-items:center;
    flex-wrap:wrap;
    padding:0 100px 0 100px;
}
.about_col{
     flex:1;
}
#about_img{
    width:300px;
    height:300px;
    border-radius:50%;
    margin:auto;
    background-repeat: no-repeat;
}
#about_img img{
    width:100%;
    height:100%;
    border-radius:50%;
    object-fit:fill;
}
.about_col h1{
    text-align:center;
    font-family:cursive;
}
.about_col p{
    text-align:justify;
    font-weight:bold;
}
#contact{
    padding:25px 0 25px 0;
}
#contact_row{
    display:flex;
    justify-content:center;
    align-items:center;
    padding:0 100px 0 100px;
    flex-wrap:wrap;
}
.contact_col{
    display:flex;
    flex-direction:column;
    align-items:center;
    flex:1;
}
.contact_col p,h3{
    font-weight:bold;
    color: #292929;
    margin:10px;
}
.contact_col p a{
    text-decoration:none;
    color: #292929;
}
#social a{
    color:magenta;
    margin:3px;
}
.contact_col form{
    display:flex;
    flex-direction:column;
    background-color:magenta;
    width:70%;
    padding:20px 40px 20px 20px;
}
.contact_col form h2{
    text-align:center;
    font-family:cursive;
}
.contact_col form input{
    width:100%;
    height:17pt;
    padding:5px;
    margin:5px;
}
.contact_col form textarea{
    width:100%;
    padding:5px;
    margin:5px;
}
.contact_col form button{
    margin:auto;
    padding:10px;
    color: #fff;
    background-color:orange;
    border:1px solid orange;
    cursor:pointer;
}
#footer{
    background-color: #292929;
    padding:20px;
    position:relative;
}
#footer h5{
    text-align:center;
    color:orange;
}
#footer h5 a{
    color: #fff;
    text-decoration:none;
}
#top{
    position:absolute;
    bottom:12px;
    right:12px;
}
#top a{
    color: #fff;
    font-size:1.2rem;
}
```
# OUTPUT:
![IMG7](https://github.com/user-attachments/assets/b955506d-4e15-44f0-ae83-9c7c066ba084)

![web85](https://github.com/user-attachments/assets/28dba68a-502e-47b7-bc27-b1bf4fdd553d)


![IMG8](https://github.com/user-attachments/assets/cf4d3d4b-016c-4bf3-a410-717105931d49)

![IMG9](https://github.com/user-attachments/assets/d0da90ac-a520-4529-b1db-e27c29de91be)

![IMG10](https://github.com/user-attachments/assets/5d5992ff-0104-4c77-a0c5-0db4e8957509)

# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
