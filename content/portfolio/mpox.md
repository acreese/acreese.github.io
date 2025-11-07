+++
date = "2016-11-05T19:41:01+05:30"
title = "Automated Monkeypox Case Dashboard"
draft = false
image = "img/portfolio/laptop_mpox_dash_1.png"
showonlyimage = false
weight = 1.5
tags = ['Python', 'SQL', 'Tableau','Data Viz', 'ETL']
+++

Developed an automated public health dashboard during the 2022 monkeypox outbreak to provide real-time case tracking. Built a fully automated ETL pipeline using AWS Lambda and Python to extract daily case data, transform it for analysis, and load it into a PostgreSQL database, eliminating manual data updates and ensuring stakeholders had access to current outbreak information.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<span><a href="/tags/sql">SQL</a></span>
<span><a href="/tags/data-viz">Data Viz</a></span>
<!--<span><a href="/tags/etl">ETL</a></span>-->
</div>
<!--more-->
<hr>

#### Project Overview

This dashboard was developed during the 2022 monkeypox public health emergency to provide accessible, up-to-date case tracking. The system demonstrates end-to-end data engineering and visualization skills, combining cloud infrastructure, automated data pipelines, and interactive dashboards.

**Technical Architecture:**
- **AWS Lambda** function scheduled to run daily ETL processes
- **Python** scripts for data extraction from public health APIs, data transformation, and validation
- **Amazon RDS PostgreSQL** database for structured data storage
- **Tableau** for interactive visualization and analysis
- Fully automated pipeline requiring no manual intervention

**Key Features:**
- Daily automated updates of case counts by geography and demographics
- Time-series analysis showing outbreak progression
- Interactive filtering by region, date range, and case characteristics
- Designed for both public health professionals and general public access

*Note: Tableau Public does not support live server connections, so updates to this public version must be published manually. The production version updates automatically.*

<div class='tableauPlaceholder' id='viz1661806693530' style='position: relative'><noscript><a href='https:&#47;&#47;alex-reese.com&#47;mpox'><img alt='Dark Dash (2) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;Monkeypox_dashboard&#47;DarkDash2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Monkeypox_dashboard&#47;DarkDash2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;Monkeypox_dashboard&#47;DarkDash2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661806693530');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1927px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
