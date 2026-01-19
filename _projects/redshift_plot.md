---
layout: page
title: Interactive Database of Spectroscopically Confirmed Gravitational Lens Systems
description: Post-doc project for AGEL survey.
img: assets/img/3_interactive_lensing_database.png
importance: 2
category: work
citation: true
---

<div style="position:relative; width:200vh; height:100vh; overflow:hidden;">
  <iframe
    src="https://doct3rwatson.github.io/lensing-db-dashboard/"
    style="
      position:absolute; top:0; left:0;
      width:1600px; height:1400px;   /* native page size */
      transform:scale(0.75);
      transform-origin:0 0;
      border:0;
    "
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>

<hr>


## The AGEL Survey
My first post-doc was with the [AGEL survey team](https://sites.google.com/view/agelsurvey/home?authuser=0). One of the first projects I undertook was creating a plot of spectroscopically confirmed source and deflector redshifts for gravitational lensing systems since the first discovery of one such source in 1979 [Weyman et. al 1979](https://ui.adsabs.harvard.edu/abs/1979ApJ...233L..43W/abstract). Along with this, I compiled an ADS library of papers to link to each system. This is available as the [AGEL+ Lens Database library on ADS](https://ui.adsabs.harvard.edu/public-libraries/HB5WWHhdSf6FlHyOPV6DYg). 

## Animated Redshift Figure
Before jumping to the interactive version, I started by creating a simple animation that steps through each year, progressively adding more points to the plot as more systems were discovered (with lots of help from large-scale surveys). 

<div class="col-sm mt-3 mt-md-0">
    {% include video.liquid path="assets/video/image_animation_v08.20.2025.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true %}
</div>


## Interactive Redshift Plot
I decided to get a bit extra and see if I could make the plot more interactive. Rather than a movie, I wanted users to be able to just move a slider and have greater control over seeing the number of new discoveries grow. I wanted to be able to zoom in to check out regions that had lots of points in more details. I wanted to be able to easily find the papers associated with these targets. 

<div style="position:relative; width:200vh; height:100vh; overflow:hidden;">
  <iframe
    src="https://doct3rwatson.github.io/Lensing-DB-redshifts/"
    style="
      position:absolute; top:0; left:0;
      width:1600px; height:1400px;   /* native page size */
      transform:scale(0.75);
      transform-origin:0 0;
      border:0;
    "
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>

This version is still available [on my github](https://doct3rwatson.github.io/Lensing-DB-redshifts/) and linked on the AGEL website. 

## The Interactive Lensing Database
Then my advisor asked, "What if it was like an all-sky map?" So changed everything I'd done and built an interactive dashboard showing the evolution of spectroscopically confirmed gravitational lensing systems throughout the years, keeping most of the functionality of the redshift plot. You can click on individual points to view more information and get a link to the associated paper. You can scroll to zoom in and out, and pan around to explore all the points. Some funcionalities were added/upgraded, such as the collapsible "How to Use" info panel, and the ability to click on items in the legend to highlight specific groups of points. 

Available [on my github](https://doct3rwatson.github.io/lensing-db-dashboard/) and linked on the AGEL website. 


<div style="position:relative; width:200vh; height:100vh; overflow:hidden;">
  <iframe
    src="https://doct3rwatson.github.io/lensing-db-dashboard/"
    style="
      position:absolute; top:0; left:0;
      width:1600px; height:1400px;   /* native page size */
      transform:scale(0.75);
      transform-origin:0 0;
      border:0;
    "
    loading="lazy"
    allowfullscreen>
  </iframe>
</div>


