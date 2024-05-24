# Amazon_clone

## The Cloning of the amazon website is performed using basic static understanding of HTML & CSS Configurations setup.

HTML Code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="amazon cloning.css">

</head>
<body>
    <header>
    <div class="navbar">
        <div class="nav-logo border" >
            <div class="logo"></div>
        </div>
        <div class="nav-address border" >
            <p class="add-first">Deliver to</p>
            <div class="add-icon">
                <i class="fa-solid fa-location-dot"></i>
                <p class="add-second">India</p>
            </div>
        </div>
        <div class="nav-search">
            <select class="search-select">
                <option>All</option>
            </select>
            <input placeholder="Search Amazon" class="search-input">
            <div class="search-icon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
   
    
       <div class="nav-second border">
            Hello, sign in
            
        </div>
        <p class="nav-second border">Account and Lists</p>
        <div class="nav-return border">
            <p><span>Returns</span></p>
        <p class="nav-second">& orders</p>
        </div>
        <div class="nav-cart border">
        <i class="fa-solid fa-cart-shopping"></i>  
        Cart
        </div>
    </div>
    <div class="panel">
        <div class="panel-all">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div class="panel-ops">
            <p> Today's Deals</p>
            <p>Customer Service</p>
            <p> Registry</p>
                <p>Gift Cards</p>
                <p>Sell</p>
        </div>
        <div class="panel-deals">
            Shop deals in Electronics
        </div>
    </div>
    </header>
   <div class="hero-section">
<div class="hero-message">
<p>You are on Amazon.com. You can also shop on Amazon India for millions of products with fast delivery.</p> 
</div>
</div>

<div class="shop-section">
    <div class="box">
        <div class="box-content">
        <h2>Groceries</h2>
        <div class="box-img" style="background-image:url('im1.jpg');"></div>
        <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Gadgets</h2>
            <div class="box-img" style="background-image:url('im2.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Kid's Toys</h2>
            <div class="box-img" style="background-image:url('im3.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Bags</h2>
            <div class="box-img" style="background-image:url('im6.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
    <div class="box">
        <div class="box-content">
        <h2>Clothes</h2>
        <div class="box-img" style="background-image:url('im5.jpg');"></div>
        <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Bedsheets</h2>
            <div class="box-img" style="background-image:url('im4.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Tiffins & Containers</h2>
            <div class="box-img" style="background-image:url('im7.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
    <div class="box">
            <div class="box-content">
            <h2>Shoes</h2>
            <div class="box-img" style="background-image:url('im8.jpg');"></div>
            <p>See More</p>
        </div>
    </div>
</div>


<footer>
    <div class="foot-panel1">
        Back to Top
    </div>
    <div class="foot-panel2">
        <ul>
        <p>Get to Know Us</p>
         <a>About Us</a>
         <a>Careers</a>
         <a>Press Releases</a>
         <a>Amazon Sciences</a>
        </ul>
        <ul>
            <p>Get to Know Us</p>
             <a>About Us</a>
             <a>Careers</a>
             <a>Press Releases</a>
             <a>Amazon Sciences</a>
            </ul>
            <ul>
                <p>Get to Know Us</p>
                 <a>About Us</a>
                 <a>Careers</a>
                 <a>Press Releases</a>
                 <a>Amazon Sciences</a>
                </ul>
                <ul>
                    <p>Get to Know Us</p>
                     <a>About Us</a>
                     <a>Careers</a>
                     <a>Press Releases</a>
                     <a>Amazon Sciences</a>
                    </ul>
    </div>
    <div class="foot-panel3">
        <div class="logo"></div>
    </div>

    <div class="foot-panel4">
        <div class="pages">
<a>Conditions of Use</a>
<a>Privacy Notice</a>
<a>Your Ads Privacy Choices</a>

        </div>
        <div class="copyright">
            © 1996-2024, Amazon.com, Inc. or its affiliates
        </div>
    </div>
</footer>
</body>
</html>


CSS Code

* {
    margin: 0;
    font-family: Arial;
    border: border-box;
}

.navbar {
    height: 60px;
    background-color: #0f1111;
    color: white;
    display: flex;
    align-items: center;
}

.nav-logo {
    height: 50px;
    width: 100px;
}

.logo {
    background-image: url('amazon\ logo.png'); /* Update the path to your logo image */
    background-size: contain; /* Adjust the size as needed */
    background-repeat: no-repeat;
    height: 50px;
    width: 100px;
    background-color: rgba(0, 0, 0, 0); /* Set background color to transparent */
}


.border {
    border: 1.5px solid transparent;
}

.border:hover {
    border: 1.5px solid white;
}

/** box 2**/
.add-first {
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}

.add-second {
    font-size: 1rem;
    margin-left: 3px;
}

.add-icon {
    display: flex;
    align-items: center;
}

/** box 3**/
.nav-search {
    display: flex;
    justify-content: space-evenly;
    background-color: pink;
    width: 620px;
    height: 40px;
    border-radius: 4px;
    justify-content: space-evenly;
}

.search-select {
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    border: none;
}

.search-input {
    width: 100%;
    font-size: 1rem;
    border: none;
}

.search-icon {
    width: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: rgba(250, 169, 28, 0.953);
    border-top-left-radius: 4px;
    border-bottom-left-radius: 4px;
    color: #0f1111;
}

.nav-search:hover {
    border: 2px solid orange;
}

/** box 4 **/
span {
    font-size: 0.7em;
}

.nav-second {
    font-size: 0.8rem;
    font-weight: 700;
    margin-right: 10px; /* Added spacing */
}

/** box 6 **/
.nav-cart i {
    font-size: 30px;
}

.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}

.panel {
    height: 40px;
    background: #222f3d;
    display: flex;
    color: white;
    align-items: center;
    justify-content: space-evenly;
}

.panel-ops p {
    display: inline;
    margin-left: 15px;
}

.panel-ops {
    width: 70%;
    font-size: 0.85rem;
}

.panel-deals {
    font-size: 0.9rem;
    font-weight: 700;
}

/** hero section**/
.hero-section {
    background-image: url(hero-section.jpg);
    height: 400px;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}

.hero-message {
    background-color: white;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    width: 80%;
    margin-bottom: 25px;
}

/** shop-section**/

.shop-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #e2e7e6;
}

.box {
    height: 400px;
    border: 2px solid black;
    width: 23%;
    background-color: white;
    padding: 20px 0px 15px;
    margin-top: 15px;
}

.box-img {
    height: 300px;
    background-size: cover;
    margin-top: 1rem;
    margin-bottom: 1rem;
}

.box-content {
    margin-left: 1rem;
    margin-right: 1rem;
}

.box-content p {
    color: #007185;
}

/** footer **/

.footer {
    margin-top: 15px;
}

.foot-panel1 {
    background-color: #37475a;
    color: white;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}

.foot-panel2 {
    background-color: #222f3d;
    color: white;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
}

ul {
    margin-top: 20px;
}

ul a {
    display: block;
    font-size: 0.85rem;
    margin-top: 10px;
    color: #dddddd;
}

.foot-panel3 {
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;
}

.logo {
    background-image: url(amazon\ logo.png);
    background-size: cover;
    height: 50px;
    width: 100px;
}

.foot-panel4 {
    background-color: #0f1111;
    color: white;
    height: 100px;
    font-size: 0.7rem;
    text-align: center;
}

.pages {
    font-size: 0.7rem;
    text-align: center;
    padding-top: 25px;
}

.copyright {
    padding-top: 5px;
}

/* Slide in animation for navbar */
@keyframes slideInNav {
    from {
        opacity: 0;
        transform: translateY(-100%);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Fade in animation for nav-second */
@keyframes fadeInNavSecond {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}

/* Blink animation for nav-cart */
@keyframes blink {
    0% {
        opacity: 1;
    }
    50% {
        opacity: 0;
    }
    100% {
        opacity: 1;
    }
}

/* Rotate animation for footer logo */
@keyframes rotate {
    0% {
        transform: rotate(0deg);
    }
    100% {
        transform: rotate(360deg);
    }
}

/* Add animations to respective elements */
.navbar {
    animation: slideInNav 0.5s ease-in-out forwards;
}

.nav-second {
    animation: fadeInNavSecond 0.5s ease-in-out forwards;
}

.nav-cart {
    animation: blink 1.5s infinite;
}

.footer .foot-panel3 .logo {
    animation: rotate 4s linear infinite;
}






