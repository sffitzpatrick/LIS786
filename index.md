---
Title: Home
Layout: default
---
<div class="content-left" markdown="1">
# Surf Gym is a concept workout space that brings the maritime to your workout time.

## Our amenities include:
{% for amenity in site.amenities %}
<h2>{{ amenity.title}}</h2>
<p>{{ amenity.content}}</p>
{% endfor %}


</div>

<div class="img-right" markdown="1">
## Join us for Marine Muscle themed classes like:

Mantis Shrimp Boxing
![boxing](/assets/images/boxing.jpg)

Hot Vent Yoga
![beach yoga](/assets/images/beach_yoga.jpg)

Whale Weight Training
![weights](/assets/images/weights.jpg)

Shark Surfing
![shark waves](/assets/images/shark_waves.jpg)


</div>

Want to know more about the classes we offer? Visit our [Marine Muscle]({{ "/classes/" | relative_url }}) page to register.

<div class="clearfix"></div>
