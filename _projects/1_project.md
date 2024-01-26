---
layout: page
title: Dancing with Literature: The Social Networks of Shows and Intellectual Circuits in Spain (1911-1933)
description: Digital Social Networks
img: assets/img/12.jpg
importance: 1
category: work
related_publications: true
---

As part of my doctoral dissertation, “Dancing with Literature” explores the personal connections among literary figures such as Ramón Gómez de la Serna or Federico García Lorca,  choreographers like Antonia Mercé, set designers like Salvador Bartolozzi, and musicians such as Manuel de Falla. The main objective is to demonstrate that the worlds of dance and literature were intricately connected through personal relationships. This connection explains phenomena like dance librettos being written by authors like María Martínez Sierra and textual choreographic pieces by Ramón Gómez de la Serna. To visualize these digital social networks and analyze the intellectual circuit, I use gephi.org. The initial database focuses on participants in events such as the Concurso del Cante Jondo, literary gatherings at Café del Pombo and, together with 20 premiered dance pieces. This database will be amplified with the correspondence, dance and theater companies of the time like Teatro del Arte by Gregorio Martínez Sierra or Ballet Espagnols by Antonia Mercé. In short,  this project aims to illustrate and analyze the social networks shaping the cultural landscape of early 20th-century Spain.

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: Dancing with Literature: The Social Networks of Shows and Intellectual Circuits in Spain (1911-1933)
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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
