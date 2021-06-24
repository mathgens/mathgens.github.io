---
title: Home
---
# Mathgens
This website has math problem generators.

<ul>
      {% for p in site.pages %}
        <li>
          <a href="{{site.url}}{{ p.url }}">{{ p.title }}</a>
        </li>
      {% endfor %}
</ul>
