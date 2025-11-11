+++
date = "2016-11-05T19:41:01+05:30"
title = "Project Management Course Development Dashboards"
draft = false
image = "img/portfolio/GTPE_dual_screen_dash.png"
showonlyimage = false
weight = 1
tags = ['Python','Tableau','ETL','Data Viz']
+++

Designed and implemented a complete analytics solution for Georgia Tech Professional Education's course development pipeline, integrating ClickUp project data via Python APIs with custom business logic to enable data-driven intake decisions for 30+ course requests.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<!--<span><a href="/tags/etl/">ETL</a></span>-->
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->
<hr>

#### Project Overview

[Georgia Tech Professional Education (GTPE)](https://pe.gatech.edu/) develops credentials and courses for online Master's degree programs and custom courses requested by external organizations. The organization lacked a structured system for evaluating, prioritizing, and tracking these course development requests, making it difficult for leadership to make informed intake decisions.

**Business Challenge:**
With 30+ course requests in various stages, executives needed visibility into projected business value, resource requirements, and development risks across the portfolio. External requestors also needed transparency into their course's development progress.

**My Role:**
I led the end-to-end development of this analytics solution, from data flow diagramming through ETL pipeline implementation to dual-audience dashboard design. This work established GTPE's first systematic approach to course portfolio management.

**Technical Implementation:**

**Python ETL Pipeline:**
- Built automated data pipeline using Python to extract data from ClickUp API
- Implemented complex transformation logic to normalize inconsistent project data across different course types
- Applied course-specific business rules requiring unique handling for various program formats
- Performed extensive data pivoting and restructuring for analysis
- Integrated supplementary HR data and business logic from external files to enrich project context
- Automated daily data refresh to keep dashboards current

**Tableau Dashboards:**
- **Executive Intake Dashboard**: Prioritization tool showing business value scores, resource needs, and risk assessments for all pending course requests
- **External Requestor Dashboard**: Progress tracking interface providing transparency to course sponsors

**Business Impact:**
The dashboards transformed GTPE's course intake process by:
- Enabling executives to make evidence-based intake decisions using standardized evaluation criteria
- Providing transparency to external partners on development timelines and milestones
- Consolidating fragmented project information from ClickUp into a cohesive portfolio view
- Eliminating manual status report creation through automated dashboard updates

*Dashboards below display sample data for information security*

#### Executive Intake Dashboard

<div class='tableauPlaceholder' id='viz1661534822370' style='position: relative'><noscript><a href='#'><img alt='Course request Dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GT&#47;GTPE-CourseRequestSummary&#47;CourserequestDashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GTPE-CourseRequestSummary&#47;CourserequestDashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GT&#47;GTPE-CourseRequestSummary&#47;CourserequestDashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661534822370');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='4727px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


<br></br>
#### External Requestor Dashboard

<div class='tableauPlaceholder' id='viz1661807736853' style='position: relative'><noscript><a href='#'><img alt='Dashboard 2 (5) ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GT&#47;GTPECourseDevelopment&#47;Dashboard25&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='GTPECourseDevelopment&#47;Dashboard25' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;GT&#47;GTPECourseDevelopment&#47;Dashboard25&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661807736853');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='1027px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='1027px';} else { vizElement.style.width='100%';vizElement.style.height='5027px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>
