---
title: App Icons
description: Icons I designed for several applications.
---

{% for app in site.data.apps %}
<h3>
    <a href="{{ app.url }}">
        {{ app.name }}
    </a>
</h3>
{{ app.desc }}
<br>
<br>
<img alt="app icon preview" src="/images/{{ app.name | replace: ' ', '-' }}-icon.webp" style="margin-bottom: 5em;">
{% endfor %}

i hang out in the [gnome app icon design matrix room](https://matrix.to/#/#appicondesign:gnome.org)

if you want to request an icon, you can find me there
