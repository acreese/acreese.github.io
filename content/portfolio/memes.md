+++
image = "/img/portfolio/meme_dash_4.png"
showonlyimage = false
draft = false
date = "2022-08-29T19:53:42+05:30"
title = "Meme Generator Natural Language Processing and Sentiment Analysis"
weight = 5
tags = ["Python","SQL","Tableau",'ETL','NLP','Data Viz']
categories = ['Data Viz']
+++

Designed and built a multilingual sentiment analysis system to analyze 57,000+ internet meme instances across 82 languages. Developed a relational MySQL database schema and Python ETL pipeline to process text, apply NLP techniques for language detection, and calculate sentiment scores. Created interactive Tableau dashboards to visualize sentiment patterns across meme types and languages.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/sql/">SQL</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<!--<span><a href="/tags/etl/">ETL</a></span>
<span><a href="/tags/nlp/">NLP</a></span>-->
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->

See this project's: [GitHub Repository](https://github.com/acreese/meme-generator_data-wrangling) and documentation

![English, Spanish, and Russian memes](/img/portfolio/meme_samples.png)


<div class='tableauPlaceholder' id='viz1661783922251' style='position: relative'><noscript><a href='#'><img alt='Identifying sentiment in multilingual memesdata source: Library of Congress; analysis by Alexander Reese &amp; Elizabeth Seeley ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MemeGeneratorLanguageandSentiment&#47;FinalDraftDashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MemeGeneratorLanguageandSentiment&#47;FinalDraftDashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MemeGeneratorLanguageandSentiment&#47;FinalDashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661783922251');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='2177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br></br>

### Project Summary

This project demonstrates skills in database design, ETL pipeline development, natural language processing, and multilingual data analysis. Working with collaborator Liz Seeley, I designed a relational database schema to organize 57,000 meme instances derived from 800+ base memes, then built Python scripts to extract text, identify languages using the `langid` library, and calculate sentiment scores using SUNY Data Science Lab's lexicons covering 81 languages.

**Technical Approach:**
- Designed normalized MySQL database structure for meme text, images, and sentiment data
- Developed Python ETL pipeline to process and load data from Library of Congress sources
- Implemented NLP workflow: language detection → sentiment lexicon matching → score calculation
- Created SQL queries to aggregate sentiment scores across meme types and languages
- Built interactive Tableau dashboards to explore sentiment patterns and language distributions


![Database diagram](/img/portfolio/meme_database_diagram.jpeg)

![Data wrangling flow](/img/portfolio/meme_database_flow.jpeg)


