---
title: Marine Muscle Classes
theme: default
permalink: /classes/
---
# Marine Muscle Classes

Many of our exercise courses offer three levels of expertise: beginner, intermediate, and intense, so you can decide on the right fit. Find out more about our classes below. Go ahead and register to get the workout started!

## Our current class offerings:
{% for class in site.classes %}
<h2>{{ class.title }}</h2>
<p>{{ class.content }}</p>
{% endfor %}

**and more to come!**

_Have a recommendation? [Tell us all about it!](https://surfgym.com/suggestions)_
