# iamge-gallery
<!DOCTYPE html>
<html>

<head>
    
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <header>

<h1>SACHIN GALLERY</h1>

<p>Immersive Visual Experience</p>

</header>


    <div class="gallery">

        <img src="images/a1.jpg" alt="">
        <img src="images/a2.jpg" alt="">
        <img src="images/a3.jpg" alt="">
        <img src="images/a4.jpg" alt="">
        <img src="images/a5.jpg" alt="">
        <img src="images/a6.jpg" alt="">
        <img src="images/a7.jpg" alt="">
        <img src="images/c1.jpg" alt="">
        <img src="images/c2.jpg" alt="">
        <img src="images/c3.jpg" alt="">
        <img src="images/c4.jpg" alt="">
        <img src="images/c5.jpg" alt="">
        <img src="images/n1.jpg" alt="">
        <img src="images/n2.jpg" alt="">
        <img src="images/n3.jpg" alt="">
        <img src="images/n4.jpg" alt="">




    </div>
    <div id="lightbox">

    <span id="close">&times;</span>

    <button id="prev">❮</button>

    <img id="lightbox-img">

    <button id="next">❯</button>

</div>

<div class="buttons">

<button onclick="filterImages('nature')">Nature</button>

<button onclick="filterImages('animals')">Animals</button>

<button onclick="filterImages('city')">City</button>

<button onclick="filterImages('all')">All</button>

</div>

<div class="gallery">

<img src=" images/a1.jpg" class="animals">
<img src="images/a2.jpg" class="animals">
<img src="images/a3.jpg" class="animals">
<img src="images/a4.jpg" class="animals">
<img src="images/a5.jpg" class="animals">
<img src="images/a6.jpg" class="animals">
<img src="images/a7.jpg" class="animals">

<img src="images/n1.jpg" class="nature">
<img src="images/n2.jpg" class="nature">
<img src="images/n3.jpg" class="nature">
<img src="images/n4.jpg" class="nature">

<img src="images/c1.jpg" class="city">
<img src="images/c2.jpg" class="city">
<img src="images/c3.jpg" class="city">
<img src="images/c4.jpg" class="city">
<img src="images/c5.jpg" class="city">
</div>
    <script src="script.js"></script>

</body>

</html>
