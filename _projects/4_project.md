---
layout: page
title: "Integrating geochemical thermodynamic modelling with geophysics"
description: 
img: assets/img/ldm.jpg
importance: 3
category: work
---

Silicic systems are known to generate the most explosive eruptions in the world due to their high volatile content. Many silicic eruptions occur in continental arcs, which are heavily populated (e.g., the Andean Arc, the Cascades). Understanding how these eruptions occur is then key for understanding and mitigating volcanic hazards. By coupling magma compositions with thermodynamic modelling, I explore what mechanisms can trigger a silicic eruption. I am currently working on these questions with Dr. Basil Tikoff and Dr. Claire Ruggles as a Postdoctoral Researcher. My objective is to systematically explore the composition and physical parameters of the magmas that are injected into the Laguna del Maule Volcanic Field in the Andes. This system is currently experiencing the highest uplifting rates of any volcanic system in the world. I am performing thermodynamic modelling using the MELTS algorithm that combines a suite of intensive magma properties to compare magma chamber compositional changes with available geophysical data.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/lgm.jpg" title="Laguna del Maule" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The Laguna del Maule volcanic field is the fastest-inflating volcanic system in the world.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/Old_volcano.jpg" title="Old volcano" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/columnar.jpg" title="Columnar basalts" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The area around Laguna del Maule is comprised by several Pleistocene eroded volcanoes such as the Campanario volcano (left image). Some of the eruptive products in the area show specific textures that could be related with lava-ice contact features (right image).
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
