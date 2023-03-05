---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: 
permalink: /blogs/
---
<div class="uk-cover-container" >
  <div class="uk-section uk-section-small">
    <div class="uk-container uk-position-relative uk-text-center">
<div class="uk-child-width-1-2@s uk-child-width-1-3@m" uk-grid="masonry: true">
{% for post in site.posts %}


    {% include blogcard.html image=page.featured-image alt=page.featured-image-alt %}

{% endfor %}
</div>
</div>
</div>
</div>