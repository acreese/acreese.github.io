+++
date = "2024-09-16T11:50:00+00:00"
title = "Quarterly Sales Churn Tableau Dashboard"
draft = false
image = "img/portfolio/churn_quarterly_tableau.png"
showonlyimage = false
weight = 3
tags = ['Tableau','Data Viz']
+++

Tableau exploration of acquisition, retention, and churn to spot at-risk segments before they slip away.

<div class=Tags>
<span><a href="/tags/tableau/">Tableau</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->
<hr>

#### What question it answers
Which segments drive churn and where should retention spend go?

#### What I built
- Cohort-based Tableau dashboard tracking logo churn %, revenue churn, and replacement rate by segment, size, and state.
- State map and segment filters to quickly isolate hotspots and compare acquisition vs. churn within the same view.

#### Findings from the sample data
- Midwest SMB churn was trending up while replacement lagged new acquisition.
- Larger enterprise cohorts showed steadier retention but slower replacement when churn occurred.

#### Methods & cadence
- Cohorting, segment filtering, state-level mapping, and quarterly refresh cadence to mirror leadership reporting.

<div class='tableauPlaceholder' id='viz1729184170602' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 (2) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Qa&#47;QarterlyCustomerChurnAnalysis&#47;Dashboard12&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='QarterlyCustomerChurnAnalysis&#47;Dashboard12' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Qa&#47;QarterlyCustomerChurnAnalysis&#47;Dashboard12&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1729184170602');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1927px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>