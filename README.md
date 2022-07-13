<link rel="stylesheet" href="style.css">
<title>Calvary Youth Services</title>

<div class="slideshow">
    <h1>Calvary Youth Services</h1>
    <h2>A New Beginning</h2>
    {% capture p1 %}{% include topPG.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>

<div class="contactus flex-container">
    <div>
    {% capture p1 %}{% include contactus.md %}{% endcapture %}
    {{ p1 | markdownify }}
    </div>
    <form method="post" action="//formspree.io/coordinator@calvaryyouth.com.au">
        <div>
            <div>
                <span><input type="text" name="name" id="name" placeholder="Name"></span>
                <span><input type="email" name="email" id="email" placeholder="Email"></span>
            </div>
            <div><textarea name="message" id="message" placeholder="Message" rows="4"></textarea></div>
            <div><input type="submit" value="Send"></div>
        </div>
    </form>
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
    <a href="www.peelyouthservices.com.au">Peel Youth Services</a>

    {% capture p1 %}{% include usefulcontacts.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>

<div class="thanks">
    {% capture p1 %}{% include thanks.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>