---
Title: Home
Layout: default
---

<div class="content-right" markdown="1">
## Our amenities include:
- Sand Resistance Training
- Solar Endurance Tanning Beds
- Beach Volleyball Courts
- State of the Art Wave Pool

</div>

<div class="img-left" markdown="1">
# Surf Gym is a concept workout space that brings the maritime to your workout time.

## Join us for Marine Muscle themed classes like:

{% for class in site.classes %}
<h2>{{ class.title }}</h2>
<p>{{ class.content }}</p>
{% endfor %}

Want to know more about the classes we offer? Visit our [Marine Muscle]({{ "/classes/" | relative_url }}) page to register.

</div>

<div class="clearfix"></div>
