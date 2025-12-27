<!DOCTYPE html>
<html lang="en">
<head>
    *{
    margin: 0;
    padding: 0;
    border: border-box;
    font-family: Arial;
}
.navbar {
    height: 60px;
    background-color:#0f1111;
    color: whitesmoke;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.logo {
    background-image: url('./Assets/amazon_logo.png');
    background-size: cover;
    height: 50px;
    width: 100%;
}
.nav-logo {
    height: 50px;
    width: 100px;
}
.border {
    border: 2px solid transparent;
}
.border:hover{
    border: 2px solid whitesmoke;
}
.p1 {
    color: #cccccc;
    font-size: 0.85rem;
    margin-left: 15px;
}
.p2 {
    font-size: 1rem;
    margin-left: 3px;
}
.add-icon {
    display: flex;
    align-items: center;
}
.nav-address:hover {
    border: 2px solid whitesmoke;
}
.nav-searchbar {
    display: flex;
    justify-content: space-evenly;
    background-color: orange;
    width: 660px;
    height: 40px;
    border-radius: 5px;
}
.search-selectbar {
    background-color: #f3f3f3;
    width: 50px;
    text-align: center;
    border-top-left-radius: 5px;
    border-bottom-left-radius: 5px;
    border: none;
}
.inputbar{
    width: 100%;
    font-size: 1rem;
    border: none;
}
.search-icon {
    width: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 1.2rem;
    background-color: #febd68;
    border-top-right-radius: 5px;
    border-bottom-right-radius: 5px;
    color: #0f1111;
}
span {
    font-size: 0.7rem;
}
.Nav-Return{
    font-size: 0.85rem;
    font-weight: 700;
}
.nav-searchbar:hover{
    border: 2px solid orange;
}
.nav-cart i{
font-size: 40px;
}
.nav-cart {
    font-size: 0.85rem;
    font-weight: 700;
}
.nav-cart:hover {
    border: 2px solid whitesmoke;
}
.panel {
    height: 40px;
    background-color: #222f3d;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
    color: whitesmoke;
    
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
.hero-image {
    background-image: url("./Assets/hero_image.jpg");
    height: 350px;
    background-size: cover;
    display: flex;
    justify-content: center;
    align-items: flex-end;
}
.hero-message{
    background-color: whitesmoke;
    color: black;
    height: 40px;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 0.85rem;
    bottom: 25px;
    position: relative;
    width: 80%;
    margin-bottom: 25px;
}
.hero-message a {
    color: #007185;
}
.shop-section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-evenly;
    background-color: #E2E7E6;
}
.box {
    height: 400px;
    /* border: 2px solid black; */
    width: 23%;
    background-color: whitesmoke;
    padding: 20px 0px 15px;
    margin-top: 20px;
}
.box-image {
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
    color:#007185 ;
}
.footpanel-1 {
    background-color: #37475a;
    color: whitesmoke;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 0.85rem;
}
footer {
    margin-top: 15px;
}
.footpanel-2 {
    background-color: #222f3d;
    color: whitesmoke;
    height: 300px;
    display: flex;
    justify-content: space-evenly;
}
ul {
    margin-top: 20px;
}
ul a{
    display: block;
    font-size: 0.85rem;
    margin-top  : 10px;
    color: #dddddd;
}
.footpanel-3{
    background-color: #222f3d;
    color: white;
    border-top: 0.5px solid white;
    height: 70px;
    display: flex;
    justify-content: center;


}
.logo{
    background-image: url('./Assets/amazon_logo.png');
    background-size: cover;
    height: 50px;
    width: 100px;
}
.footpanel-4 {
    background-color: #0f1111;
    color: whitesmoke;
    font-size: 0.7rem;
    text-align: center;
    height: 80px;
}
.pages {
    
    padding-top: 25px;

}
.copyright {
        padding-top: 5px;
        


}

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon Website Clone </title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <div class="navbar">
         <div class="nav-logo border" >
            <div class="logo"> </div>
         </div>
         <div class="nav-address border">
            <p class="p1">Deliver to</p>
            <div class="add-icon">
            <i class="fa-solid fa-location-dot"></i>
                <p class="p2">Pakistan</p>
            </div>
         </div>
         <div class="nav-searchbar">
            <select class="search-selectbar">
                <option>All</option>
            </select>
            <input placeholder="Search Amazon" class="inputbar ">
            <div class="search-icon">
                <i class="fa fa-search" aria-hidden="true"></i>
            </div>
         </div>
         <div class="Nav-Signin border">
            <p><span>Hello, Sign in </span></p>
            <p class="Nav-Account">Account & Lists</p>
         </div>
         <div class="Nav-Return border">
            <p><span>Returns</span></p>
            <p class="Nav-Dropdown"> & Orders</p>
         </div>
         <div class="nav-cart border">
     <i class="fa fa-shopping-cart" aria-hidden="true"></i>
     Cart
         </div>
         </div>     

         <div class="panel">
            <div class="panel-all">
                <i class="fa fa-bars" aria-hidden="true"></i>
                All
            </div>
              <div class="panel-ops">
                <p>Today's Deals</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards </p>
                <p>Sell</p>
            </div>
            <div class="panel-deals">
                shop Deals In Electronics
            </div>
        </div>
    </header>
    <div class="hero-image">
        <div class="hero-message">
            <p>You are on amazon.com .You Can Also Shop On Amazon Pakistan For Millions Of Products With Fast Local Delivery. <a>Click Here to go to amazon.in</a></p>
        </div>
    </div>
     <div class="shop-section">
        <div class="Box1 box" >
            <div class="box-content">
                <h2>Health & Personal Care</h2>
            <div class="box-image" style="background-image: url(./Assets/box1_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box2 box">
            <div class="box-content">
                <h2>Cloth Section</h2>
            <div class="box-image" style="background-image: url(./Assets/box2_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box3 box">
            <div class="box-content">
                <h2>Furniture Section</h2>
            <div class="box-image" style="background-image: url(./Assets/box3_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box4 box">
            <div class="box-content">
                <h2>Electronics Section</h2>
            <div class="box-image" style="background-image: url(./Assets/box4_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box1 box" >
            <div class="box-content">
                <h2>Makeup Section</h2>
            <div class="box-image" style="background-image: url(./Assets/box5_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box2 box">
            <div class="box-content">
                <h2>pet care</h2>
            <div class="box-image" style="background-image: url(./Assets/box6_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box3 box">
            <div class="box-content">
                <h2>New Arrival In Toys  </h2>
            <div class="box-image" style="background-image: url(./Assets/box7_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
        <div class="Box4 box">
            <div class="box-content">
                <h2>Discover Fashion & Trends</h2>
            <div class="box-image" style="background-image: url(./Assets/box8_image.jpg);"></div>
              <p>See More</p>   
            </div>
        </div>
     </div>
    <footer>
        <div class="footpanel-1">
        Back To Top
        </div>
        <div class="footpanel-2">
            <ul>
                <p>Get To Know us </p>
                <a> Careers</a>
                <a> Blog</a>
                <a> About Amazon</a>
                <a> Investor Relations</a>
                <a> Amazon Devices</a>
                <a> Amazon Science</a>
            </ul>
             <ul>
                <p>Get To Know us </p>
                <a> Careers</a>
                <a> Blog</a>
                <a> About Amazon</a>
                <a> Investor Relations</a>
                <a> Amazon Devices</a>
                <a> Amazon Science</a>
            </ul>
             <ul>
                <p>Get To Know us </p>
                <a> Careers</a>
                <a> Blog</a>
                <a> About Amazon</a>
                <a> Investor Relations</a>
                <a> Amazon Devices</a>
                <a> Amazon Science</a>
            </ul>
             <ul>
                <p>Get To Know us </p>
                <a> Careers</a>
                <a> Blog</a>
                <a> About Amazon</a>
                <a> Investor Relations</a>
                <a> Amazon Devices</a>
                <a> Amazon Science</a>
            </ul>
        </div>


        <div class="footpanel-3">
            <div class="logo"></div>
            </div>
            <div class="footpanel-4">
                <div class="pages">
                    <a>Condition Of Use</a>
                    <a>Privacy Notes</a> 
                    <a>Your Add privacy Choices</a>
                </div>
                <div class="copy-right">
                    @1996-2025,Amazon.com, Inc.Or its Affiliates
                </div>
            </div>
        </div>
    </footer>
    
</body>

</html># Amazon-website-UI-clone-using-HTML-CSS-
    I'm [Muhammad Fahad Khan], a passionate [Web Developer] with a focus on [Front End Developer].
