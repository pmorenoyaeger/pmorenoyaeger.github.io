---
layout: page
title: "How volcanoes respond to glaciation?"
description: NSF Project Ice Forcing in Arc Magma Plumbing Systems (IF-AMPS)
img: assets/img/DSC_0074.JPG
importance: 1
category: work
related_publications: true
---

The relationship between ice and volcanoes has been investigated for decades. Lava and tephra can melt ice that its released as vapour water into the atmosphere. Now, how does ice impact a volcano during a glacial cycle? Has ice the capacity to prevent eruptions to occur? If so, when ice retreats, do erupts resume? I started working on these questions with my former advisor, [Dr. Brad S. Singer](https://geoscience.wisc.edu/people/singer-bradley-s/), during my Master's and PhD in Geoscience. To investigate the research questions, I integrated the <sup>40</sup>Ar/<sup>39</sup>Ar and <sup>14</sup>C dating techniques with 3He and <sup>36</sup>Cl surface exposure ages as we are interested in exploring how volcanoes reacted before, during and after glaciation. I then performed dozens of thousands of whole-rock, glass and mineral composition measurements to constrain how the magma plumbing system was evolving through time. Our findings show that volcanoes do erupt during glaciation but less, and some of them change their composition due to the stress load produced by the ice, whereas others do not. This research led to several press interviews. Please take a look at the references below if you are interested in this. 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/DSC_1256.JPG" title="Brad and Pablo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/helo.jpeg" title="Helo" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/IMG_20200329_144535.jpg" title="Lago" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Left: [Dr. Brad S. Singer](https://geoscience.wisc.edu/people/singer-bradley-s/) and I on the southern flank of Villarrica volcano in 2023. We are standing on a pāhoehoe lava flow that we successfully dated using cosmogenic <sup>3</sup>He, yielding an age of 600 ± 200 years, and which we named Lavas de Catricheo.

    Middle: [Dr. Brad S. Singer](https://geoscience.wisc.edu/people/singer-bradley-s/) and a helicopter pilot with the majestic Osorno volcano in the background. My colleague Jack Stalla is currently working on constraining the eruptive history of this volcano.

    Right: Lago Panguipulli and the town of Choshuenco in the background. This photograph was taken on the flanks of the Choshuenco cones, which we dated using the <sup>40</sup>Ar/<sup>39</sup>Ar method to between 11.5 and 8 ka.</div>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/Figure 9.png" title="Model of how Mocho-Choshuenco might have responded to glaciation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This figure was published in the Journal of Geophysical Research Solid Earth (Moreno-Yaeger et al., 2025). It is a model of how Mocho-Choshuenco volcano in the southern Andes might have reacted to glaciation. 
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">

    <!-- Large image on left -->
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/EPMA.jpg" title="Electron Probe Microanalyzer" class="img-fluid rounded z-depth-1" %}
    </div>

    <!-- Right column -->
    <div class="col-sm-4">

        <!-- Figure 2 -->
        <div class="mt-3 mt-md-0">
            {% include figure.liquid path="assets/img/Subofitic.jpg" title="Subophitic texture" class="img-fluid rounded z-depth-1" %}
        </div>

        <!-- Video -->
        <div class="mt-3">
            <video autoplay loop muted playsinline class="img-fluid rounded z-depth-1">
                <source src="/assets/img/Lasering.mp4" type="video/mp4">
            </video>
        </div>

    </div>

</div>

<div class="caption">
Left: Electron Probe Microanalyzer (EPMA) at the University of Wisconsin–Madison used to analyze volcanic minerals and glasses. Top right: Subophitic texture formed by clinopyroxene and plagioclase. Bottom right: NGX lasering plagioclase to then measure its <sup>40</sup>Ar and <sup>39</sup>Ar content and constrain its age.
</div>

    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
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
