+++
date = "2025-10-23T19:41:01+05:30"
title = "Network & Hierarchy Mapping with D3.js"
draft = false
image = "img/portfolio/lamiales_visual_20251024.png"
showonlyimage = false
weight = 1
tags = ['D3.js','Data Viz']
+++

Interactive taxonomy explorer built in D3.js to trace how the Lamiales order of flowering plants has been described over time.

<div class=Tags>
<span><a href="/tags/D3.js/">D3.js</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->
<hr>


<!--{{< lamiales-viz >}}-->

[View fullscreen](/projects/plant-taxonomy/index.html)

I studied botany before moving into data visualization and wanted to bridge both worlds. This D3.js build explores Lamiales — a massive order of flowering plants with 31,000+ species. Instead of overwhelming viewers, I used proportional sampling so families with more species earn more representation (think class weighting in ML). Tooltips surface the year and author of each described species, and a dual timeline toggle compares foundational 1700s discoveries with modern research still naming new taxa today.

**Interaction & insights**
- Responsive layout with hover tooltips for author/year and a toggle to flip between earliest vs. newest discoveries.
- Highlights biodiversity concentration and how discovery pace shifts over time.

**Tech stack**
- D3.js for force layout and SVG rendering, JSON data shaping for proportional sampling, and responsive styling for both desktop and mobile.

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
