+++
draft = false
image = "/img/portfolio/cluster_viz_cover.png"
showonlyimage = false
date = "2016-11-05T19:50:47+05:30"
title = "COVID Authorship Community Detection with Machine Learning"
weight = 4
tags = ['Python','Machine Learning', 'Data Viz']
+++

Applied unsupervised machine learning to analyze a network of 260,000+ COVID-19 research authors, identifying collaboration communities using advanced graph algorithms. Compared Infomap clustering and GraphSAGE node embeddings to reveal patterns in scientific collaboration during the pandemic.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/machine-learning/">Machine Learning</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
<span>GraphSAGE</span>
<span>Infomap</span>
<span>t-SNE</span>
</div>
<!--more-->

[GitHub Repository](https://github.com/acreese/covid_coauthorship_community_detection) | Full methodology and code

## Project Overview

This project analyzed scientific collaboration patterns among COVID-19 researchers by building and analyzing a network graph of 260,000+ authors and 2 million+ co-authorship connections from 173,000 publications. I compared two sophisticated community detection approaches to understand how research communities organized during the pandemic.

**Data Source:** LitCovid and PubMed Knowledge Graph datasets

**Technical Skills Demonstrated:**
- Large-scale data processing and ETL with Python (Pandas, NetworkX, StellarGraph)
- Unsupervised machine learning (GraphSAGE node embeddings)
- Graph theory and network analysis (Infomap clustering algorithm)
- Dimensionality reduction and visualization (t-SNE, DBSCAN)
- Working with complex scientific datasets

**Methodology:**
1. **Data Engineering**: Transformed publication data into network graph structure (260,637 nodes, 2M+ edges)
2. **Community Detection**: Applied Infomap algorithm identifying 23,825 research communities (0.871 modularity score)
3. **Machine Learning**: Implemented unsupervised GraphSAGE to generate 50-dimensional node embeddings
4. **Visualization**: Used t-SNE to reduce embeddings to 2D for interactive exploration

**Key Finding**: The two algorithms revealed different organizational patterns—Infomap identified tight collaboration clusters while GraphSAGE showed broader relationship structures, demonstrating how algorithm choice impacts analytical insights.

![t-SNE visualization of GraphSAGE embeddings colored by Infomap communities](/img/portfolio/cluster_viz.png)

*Visualization showing GraphSAGE node positioning colored by Infomap community membership*

![Infomap community size distribution](/img/portfolio/infomap_community_size_plot.png)

![Example research community structure](/img/portfolio/infomap_sample_community.png)

