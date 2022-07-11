<div class="slideshow">
    <h1>Calvary Youth Services</h1>
    <h2>A New Beginning</h2>
    {% capture p1 %}{% include _include/topPG.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="contactus flex-container">
    {% capture p1 %}{% include _include/contactus.md %}{% endcapture %}
    {{ p1 | markdownify }}
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
<div class="map">
    <iframe frameborder="0"
        src="https://www.google.com/maps/embed/v1/place?q=calvary+youth+services+mandurah&key=AIzaSyBFw0Qbyq9zTFTd-tUY6dZWTgaQzuU17R8">
    </iframe>
</div>
<div class="aboutus">
    {% capture p1 %}{% include _include/aboutus.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="programs">
    {% capture p1 %}{% include _include/programs.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="faqs">
    {% capture p1 %}{% include _include/faqs.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="usefulcontacts">
    {% capture p1 %}{% include _include/usefulcontacts.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="thanks">
    {% capture p1 %}{% include _include/thanks.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>