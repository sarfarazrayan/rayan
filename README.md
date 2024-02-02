<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
    <script src='https://kit.fontawesome.com/a076d05399.js' crossorigin='anonymous'></script>
<style>
    * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Open-sans', sans-serif;
}

body {
    height: 100vh;
    background-color: black;
    background-image: url(https://images.pexels.com/photos/1421903/pexels-photo-1421903.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1);
    
    background-size: cover;
    background-position: center;
}

.logo {
    color: white;
    font-size: 2rem;
}

li {
    list-style: none;
}

a {
    text-decoration: none;
    color: white;
    font-size: 1rem;
}

a:hover {
    color: white;


}

header {
    margin-top: 20px;
    position: relative;
    padding: 0 2rem;

}

.navbar {
    width: 100%;
    height: 60px;
    max-width: 1200px;
    margin: 0 auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    
    
}

.navbar .logo a {
    font-size: 1.5rem;
    font-weight: bold;
}

.navbar .links {
  display: flex;
    gap: 5rem;
}
.links a::after{
    content:'';
    height: 3px;
    width: 0;
    background: orange;
    position: absolute;
    left: auto;
    display: flex;
    top: 45px;
    
}
.links a:hover::after{
    width: 30px;
    transition: 0.5s;
}

.container {
    display: flex;
    justify-items: center;
    align-items: center;
}

.content img {
    margin-top: 10rem;
    margin-left: 5rem;
    box-sizing: border-box;
    width: 100%;
    height: 100%;
    
    
    
}

.para {
    margin-left: 150px;
    margin-right: 10px;
    margin-top: 50px;
    color: white;
position: relative;


}

.heading {
    font-weight: bold;
    font-family: roboto;
    font-size: 3rem;

}

.about {
    font-family: arial;
    margin-top: 25px;
   
    font-size: 20px;
    width: 45rem;

}

.start {
   display: inline;
  margin-left: 39rem;
 box-sizing: border-box;
    width: 100px; 
    font-size: 20px;
    color: white;
    background-color: orange;
    border-radius: 10px;
    border-color: orange;
    padding: 15px;
    
}

.start:hover {
    background-color: blue;

    cursor: pointer;
    transition: 0.5s;
}

</style>
</head>
    


<body>

    <header>
        <div class="navbar">
            <div class="logo">Sketchfox</div>
            <ul class="links">
                <li><a href="#">Home &plus;</a></li>
                <li><a href="#">Pages &plus;</a></li>
                <li><a href="#">Services &plus;</a></li>
                <li><a href="#">Blog &plus;</a></li>
                <li><a href="#">Portfolio &plus;</a></li>
                <li><a href="#">Shop &plus;</a></li>
                <li><a href="#">Contact</a></li>
            </ul>

        </div>

    </header>
    <div class="container">

        <div class="content">
            <img src="Image-layer_2.5.png">
        </div>
        <div class="para">

            <div class="heading">

                Rank Your Site At Top From Others!
            </div>
            <div class="about">

                Seofy creates targeted SEO strategies, which maximize your website's potential, resulting in maximum
                online
                exposure. We drive traffic and customers to your site.
            </div>

        </div>
    </div>
    <div class="start">
        <a1 href="#">START NOW</a1>
    </div>
  





</body>

</html>
