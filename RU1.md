---
layout: default
title: "RU1"
---
<body>
    <!-- ciao -->
</body>

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}
