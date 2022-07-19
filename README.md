<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<div class="scroller">Scroll down for more</div>

<div class="toppg">
    {% capture p1 %}{% include topPG.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="whatsnew">
    {% capture p1 %}{% include whatsnew.md %}{% endcapture %}
    {{ p1 | markdownify }}
</div>
<div class="contactus flex-container">
    <div>
        {% capture p1 %}{% include contactus.md %}{% endcapture %}
        {{ p1 | markdownify }}
    </div>
    <div style="width:50%">
        <h3>Application Form </h3>
        <form   action="https://formspree.io/f/mzbolqka" method="POST">
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
    <img src="https://github.com/CalvaryMandurah/Calvary/blob/main/assets/calvary_logo.jpg?raw=true">

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
