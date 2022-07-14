<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<title>Calvary Youth Services</title>

<h2 style="left:50%; transform:translate(-50%, -25ch); color:white;">Calvary Youth Services</h2>
<h3 style="left:50%; transform:translate(0%, -25ch); color:white;">A New Beginning</h3>
<h2>Scroll down for more<h2>
<!-- <div class="slideshow">
    <div class="slide">
        <div class="numbertext">1 / 3</div>
        <img src="https://github.com/ahaybale/Calvary/blob/main/assets/calvary_home_front.jpg?raw=true">
        <div class="text">The entrance to Calvary home</div>
    </div>
    <div class="slide">
        <div class="numbertext">2 / 3</div>
        <img src="https://github.com/ahaybale/Calvary/blob/main/assets/calvary_home_front.jpg?raw=true">
        <div class="text">Caption Text</div>
    </div>
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
    <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
    </div>
</div> -->

<div class="toppg">
    {% capture p1 %}{% include topPG.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="contactus flex-container">
    <div>
        {% capture p1 %}{% include contactus.md %}{% endcapture %}
        {{ p1 | markdownify }}
    </div>
    <div style="width:50%">
        <h3>Application Form</h3>
        <form action="https://formspree.io/f/xknylaqe" method="POST">
            <label>Name<input type="Name" name="Name"></label>
            <label>Email<input type="email" name="email"></label>
            <label>Message<textarea name="message" placeholder="text here"></textarea></label>
            <button type="submit">Send</button>
        </form>
    </div>
</div>
<iframe frameborder="0"
    src="https://www.google.com/maps/embed/v1/place?q=calvary+youth+services+mandurah&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8">
</iframe>

<div class="aboutus">
    {% capture p1 %}{% include aboutus.md %}{% endcapture %}
    {{ p1 | markdownify }}
    <img src="https://github.com/ahaybale/Calvary/blob/main/assets/calvary_logo.jpg?raw=true" style="transform(-5ch,0px)">

</div>

<div class="programs">
    {% capture p1 %}{% include programs.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>

<div class="faqs">
    {% capture p1 %}{% include faqs.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>

<div class="usefulcontacts">
    {% capture p1 %}{% include usefulcontacts.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>

<div class="thanks">
    {% capture p1 %}{% include thanks.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>