<link rel="stylesheet" href="style.css">
<title>Calvary Youth Services</title>

<div class="slideshow">
    <h2>Calvary Youth Services</h2>
    <h3>A New Beginning</h3>
    {% capture p1 %}{% include topPG.md %}{% endcapture %}
    {{ p1 | markdownify }}
    ![background image](/assets/calvary_home_front.jpg)
</div>

<div class="contactus flex-container">
    <div>
    {% capture p1 %}{% include contactus.md %}{% endcapture %}
    {{ p1 | markdownify }}
    </div>
    <div>
        <h2> </h2>
        <form method="post" action="//formspree.io/coordinator@calvaryyouth.com.au">
                <div>
                    <span><input type="text" name="name" id="name" placeholder="Name"></span>
                    <span><input type="email" name="email" id="email" placeholder="Email"></span>
                </div>
                <div><textarea name="message" id="message" placeholder="Message" rows="4">What to include in the message</textarea></div>
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