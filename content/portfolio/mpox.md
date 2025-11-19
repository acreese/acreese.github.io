+++
date = "2016-11-05T19:41:01+05:30"
title = "Automated Monkeypox Case Dashboard"
draft = false
image = "img/portfolio/laptop_mpox_dash_1.png"
showonlyimage = false
weight = 2
tags = ['Python', 'SQL', 'Tableau','Data Viz', 'ETL']
+++

Built a daily-updating public health dashboard during the 2022 monkeypox emergency to keep case counts fresh without manual effort. The pipeline ingests public health data, validates it, and pushes it straight to a Tableau-ready database so outbreaks can be monitored in near real time.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<span><a href="/tags/sql">SQL</a></span>
<span><a href="/tags/data-viz">Data Viz</a></span>
<!--<span><a href="/tags/etl">ETL</a></span>-->
</div>
<!--more-->
<hr>

#### What I built
- Automated ETL that pulls daily case data, standardizes geography/demographics, and runs light validation checks before loading into Amazon RDS PostgreSQL.
- Tableau dashboard with filters for region, date, and case characteristics plus time-series views for outbreak progression.

#### Impact
- Replaced manual spreadsheet updates with a timed Lambda workflow; data stayed current for briefings without human babysitting.
- Reduced refresh time to minutes and enabled stakeholders to self-serve trends by geography and demographic slices.

#### How it works
- **AWS Lambda** triggers Python ETL to extract public health APIs, transform, and validate records.
- **Amazon RDS PostgreSQL** hosts the cleaned dataset for visualization and ad hoc queries.
- **Tableau** connects to the database (production) with a manual publish fallback for Tableau Public.

#### Production note
Tableau Public can’t keep a live connection, so the public embed is republished manually. A Tableau Server/Power BI deployment keeps the production version on a live database connection with the same visuals and alerts for late data.

<div class='tableauPlaceholder' id='viz1661806693530' style='position: relative'><noscript><a href='https:&#47;&#47;alex-reese.com&#47;mpox'><img alt='Dark Dash (2) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;Monkeypox_dashboard&#47;DarkDash2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='Monkeypox_dashboard&#47;DarkDash2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;Monkeypox_dashboard&#47;DarkDash2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661806693530');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='827px';} else { vizElement.style.width='100%';vizElement.style.height='1927px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
