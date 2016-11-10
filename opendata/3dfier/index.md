---
layout: page
title: Open datasets created with 3dfier
permalink: /opendata/3dfier/
---

A few Dutch cities that we reconstructed with [3dfier](https://github.com/tudelft3d/3dfier) by combining the [BGT](http://www.kadaster.nl/bgt) and the [AHN3 datasets](https://www.pdok.nl/nl/ahn3-downloads).


- - -

<div class="row">
{% for i in site.data.data-3dfier %}
  <div class="col-sm-4 col-md-3">
    <div class="thumbnail">
      <img src="{{ i.image | prepend: site.baseurl }}"/>
      <div class="caption">
        <h3>{{ i.name }}
        <br />
        <small>
        {% if i.citygml %}
          <a href="{{ i.citygml | prepend: "/download/3dfier/" | prepend: site.baseurl }}">[CityGML]</a> 
        {% endif %}
        {% if i.obj %}
          <a href="{{ i.obj | prepend: "/download/3dfier/" | prepend: site.baseurl  }}">[OBJ]</a> 
        {% endif %}
        </small>
        </h3>
        <p>{{ i.description }}</p>
      </div>
    </div>
  </div>
{% endfor %}
</div>
