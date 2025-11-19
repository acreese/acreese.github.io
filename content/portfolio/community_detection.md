+++
draft = false
image = "/img/portfolio/cluster_viz_cover.png"
showonlyimage = false
date = "2016-11-05T19:50:47+05:30"
title = "COVID Authorship Community Detection with Machine Learning"
weight = 4
tags = ['Python','Machine Learning', 'Data Viz']
+++

Early grad-school experiment: mapped COVID-19 co-authorship to see how different clustering methods reveal the research network. Built a large collaboration graph, compared Infomap clusters to GraphSAGE embeddings, and visualized the differences.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/machine-learning/">Machine Learning</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
<span>GraphSAGE</span>
<span>Infomap</span>
<span>t-SNE</span>
</div>
<!--more-->
<hr>

#### What I explored
- Parsed LitCovid data into a co-author network of ~300K authors and 2M+ edges using Pandas and NetworkX.
- Ran **Infomap** for community labels and **GraphSAGE** embeddings + t-SNE/DBSCAN to see where methods align or diverge.
- Visualized clusters to compare tight algorithmic communities versus looser embedding neighborhoods.

#### Takeaways
- The two methods surface different shapes of the network—useful reminder to test multiple approaches before interpreting clusters.
- Notebooks keep everything reproducible; see the [GitHub repo](https://github.com/acreese/covid_coauthorship_community_detection).

![Clustering visualization](/img/portfolio/cluster_viz.png)

![t-SNE-enabled visualization of GraphSAGE embeddings with Informap colorization](/img/portfolio/graphsage_clusters_infomap_colors.png)
