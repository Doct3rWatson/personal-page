---
layout: page
title: Interactive Database of Spectroscopically Confirmed Gravitational Lens Systems
description: Post-doc project for AGEL survey.
img: assets/img/3_interactive_plotonly.png
importance: 2
category: work
citation: true
---


## The AGEL Survey
My first post-doc was with the [AGEL survey team](https://sites.google.com/view/agelsurvey/home?authuser=0). One of the first projects I undertook was creating a plot of spectroscopically confirmed source and deflector redshifts for gravitational lensing systems since the first discovery of one such source in 1979 [Weyman et. al 1979](https://ui.adsabs.harvard.edu/abs/1979ApJ...233L..43W/abstract). 

## The Interactive Lensing Database
I decided to get a bit extra and see if I could make the plot more interactive. Rather than a movie, I wanted users to be able to just move a slider and have greater control over seeing the number of new discoveries grow. I wanted to be able to zoom in to check out regions that had lots of points in more details. I wanted to be able to easily find the papers associated with these targets. So I build a plot that did all of that. Available [on my github](https://doct3rwatson.github.io/Lensing-DB-redshifts/) and linked on the AGEL website. Along with this, I compiled an ADS library of papers to link to each system. This is available as the [AGEL+ Lens Database library on ADS](https://ui.adsabs.harvard.edu/public-libraries/HB5WWHhdSf6FlHyOPV6DYg).


<div style="position:relative; width:200vh; height:100vh; overflow:hidden;">
  <iframe
    src="https://doct3rwatson.github.io/Lensing-DB-redshifts/"
    style="
      position:absolute; top:0; left:0;
      width:1800px; height:1400px;   /* native page size */
      transform:scale(0.75);
      transform-origin:0 0;
      border:0;
    "
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>




## Animated Figure
Before jumping to the interactive version, I started by creating a simple animation that steps through each year, progressively adding more points to the plot as more systems were discovered (with lots of help from large-scale surveys). 

<div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/image_animation_v08.20.2025.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>


