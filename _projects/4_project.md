---
layout: page
title: Development of a Remineralizing and Antiomicrobial Composite using K18-Isobornyl Acrylate and Nanohydroxyapatite
description: another without an image
img:
importance: 3
category: fun
---

Dental caries are the the most prominent type of chronic disease involving permanent teeth, affecting an estimated 2 billion people globally. Dental amalgam restorations have been considered to the gold standard in treating caries since the 19th century. In recent years, global organizations such as the International Association for Dental Research (IADR) have called for research on its alternatives to phase out their use due to limitations in patient safety, environmental waste management, aesthetics, and thermal properties. Ongoing efforts in researching and developign amalgam free dental restorations have yet to attain similar rates of clinical longevity. Failures in amalgam free dental restorations, notably resin-based composites, are attributed to bulk fracture, polymerization shrinkage, and marginal gap formation. These shortcomings in resin composites contribute to the proliferation of secondary caries, highlighting the need to develop increasingly robust restoration materials which exhibit traits including but not limited to: increased stiffness, fracture toughness, decreased polymerization shrinkage and stress, and critically, decreased rates of secondary caries.

Prevention of secondary decay is achieved primarily through 2 means: preventing biofilm colonization on tooth surfaces or enhancing remineralization capacity of the host tooth structure. Previous attempts at denying biofilm colonization has involved the use of releasable agents such as fluoride, chlorhexidine, antibiotics, etc. This method of prevention suffers from continued reliance on leachable ions, experiencing exponential decrease in efficacy over time. Since then, developments in the use of contact killing agents such as quaternary ammonium compounds (QACs) or silanes (QAS) achieve similar effects through imbuing contact inhibition surface they are bound to, notably without the need for ion release. In dental applications they have been covalently bound to filler particles that make up the dispersed phase of resin-based composites. This effect is achieved through the long, lipohilic alkyl chain on QACs which penetrate bacterial membranes.

While QACs and nanohydroxyapatite have been validated across several platforms, neither had been evaluated in combination prior this work. The project here address a comparative gap, specifically with a new formulation of QACs (K18 quaternary ammonium silane) by combining two well tested components into a single composite (K18 IBOA and nHA). It was hypothesized that co-incorporating K18-IBOA and nHA into a Bis-GMA resin base will produce a composite with permanent antimicrobial and remineralizing properties without compromising mechanical performance, esthetics, or polymerization shrinkage relative to commercial controls. Beyond composites, the platform is intended as a foundation for translation into cements, liners, and pulp-capping agents later on.

Every project has a beautiful feature showcase page.
It's easy to include images in a flexible 3-column grid format.
Make your photos 1/3, 2/3, or full width.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
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
