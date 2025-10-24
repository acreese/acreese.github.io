+++
date = "2025-10-23T19:41:01+05:30"
title = "Visualizing Plant Taxonomy with D3.js"
draft = false
image = "img/portfolio/lamiales_visual_20251024.png"
showonlyimage = false
weight = 1
tags = ['D3.js','Data Viz']
+++

My recent adventures in D3.js

<div class=Tags>
<span><a href="/tags/D3.js/">D3.js</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->
<hr>


<!--{{< lamiales-viz >}}-->

[View fullscreen](/projects/plant-taxonomy/index.html)

I studied botany before moving into data visualization and wanted to create something that bridged both worlds. This D3.js visualization explores Lamiales — a massive order of flowering plants with over 31,000 species. Rather than showing everything, I used proportional sampling to represent biodiversity fairly: families with more species get more representation. The outer ring of nodes represents this sampling of species and a tooltip shows the year it was described and the author to do so. A dual timeline toggle at the left lets users you explore and compare the earliest descrdibed species (from founadtional botanical work by Linnaeus and early explorers) with the most recently described species representing cutting-edge modern discoveries from researchers still naming new taxa today.

<br>

<style>
  .viz-container {
    width: 100vw;
    position: relative;
    left: 50%;
    right: 50%;
    margin-left: -50vw;
    margin-right: -50vw;
    max-width: 100vw;
  }
  .viz-container iframe {
    width: 100%;
    height: 1650px;
    border: none;
  }
  
  /* Responsive: smaller on mobile */
  @media (max-width: 768px) {
    .viz-container iframe {
      height: 500px;
    }
  }
</style>

<div class="viz-container">
  <iframe 
    src="/projects/plant-taxonomy/index.html" 
    width="100%" 
    height="700px" 
    frameborder="0"
    title="Lamiales Taxonomy Visualization">
  </iframe>
</div>
