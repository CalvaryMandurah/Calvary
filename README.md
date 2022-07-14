<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<title>Calvary Youth Services</title>

<h2>Calvary Youth Services</h2>
<h3>A New Beginning</h3>
<div height="100%"> scroll down for more<div>
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
    <div>
        <h3>Application Form</h3>
        <form method="post" action="//formspree.io/coordinator@calvaryyouth.com.au">
            <div>
                <span><input type="text" name="name" id="name" placeholder="Name"></span>
                <span><input type="email" name="email" id="email" placeholder="Email"></span>
            </div>
            <div><textarea name="message" id="message" placeholder="Message"
                    rows="4">What to include in the message</textarea></div>
            <div><input type="submit" value="Send"></div>
        </form>
    </div>
</div>
<iframe frameborder="0"
    src="https://www.google.com/maps/embed/v1/place?q=calvary+youth+services+mandurah&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8">
</iframe>

<div class="aboutus">
    {% capture p1 %}{% include aboutus.md %}{% endcapture %}
    {{ p1 | markdownify }}
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