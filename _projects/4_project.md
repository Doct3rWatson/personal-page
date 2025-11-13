---
layout: page
title: Spectroscopically Confirmed Gravitational Lens Systems | Interactive Database
description: Post-doc project for AGEL survey.
img: assets/img/3_interactive_plotonly.png
importance: 2
category: work
---


## The AGEL Survey
My first post-doc was with the <a href="https://sites.google.com/view/agelsurvey/home?authuser=0">AGEL survey team</a>. One of the first projects I undertook was creating a plot of spectroscopically confirmed source and deflector redshifts for gravitational lensing systems since the first discovery of one such source in 1979 (<a href="https://ui.adsabs.harvard.edu/abs/1979ApJ...233L..43W/abstract">Weyman et. al 1979</a>). I started by creating a simple animation (<a href="https://sites.google.com/view/agelsurvey/research/visualizations?authuser=0">available on the AGEL website</a>) that steps through each year, progressively adding more points to the plot as more systems were discovered (with lots of help from large scale surveys). 


## The Interactive Lensing Database
I decided to get a bit extra and see if I could make the plot more interactive. Rather than a movie, I wanted users to be able to just move a slider and have greater control over seeing the number of new discoveries grow. I wanted to be able to zoom in to check out regions that had lots of points in more details. I wanted to be able to easily find the papers associated with these targets. So I build a plot that did all of that. Available <a href="https://doct3rwatson.github.io/Lensing-DB-redshifts/">on my github</a> and linked on the AGEL website. Along with this, I compiled an ADS library of papers to link to each system. This is available as the <a href="https://ui.adsabs.harvard.edu/public-libraries/HB5WWHhdSf6FlHyOPV6DYg">AGEL+ Lens Database library on ADS</a>.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3_interactive_still.png" title="interactive still" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Screenshot of interactive plot. 
</div>



