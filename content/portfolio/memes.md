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

Built a lightweight meme sentiment explorer with collaborator Liz Seeley to practice multilingual NLP and dashboarding. The project ingests 57,000+ meme instances across 82 languages, scores sentiment with lexicons, and lets you slice the results in Tableau without taking itself too seriously.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/sql/">SQL</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<!--<span><a href="/tags/etl/">ETL</a></span>
<span><a href="/tags/nlp/">NLP</a></span>-->
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->
<hr>

#### What I built
- MySQL schema and Python ETL that standardize meme text from the Library of Congress collection.
- Language detection and sentiment scoring with multilingual lexicons covering 80+ languages.
- Tableau dashboard to filter by language, meme base image, and sentiment trends.

#### Notes
- Early grad-school experiment—kept simple but reproducible in notebooks.
- Repo and docs: [GitHub](https://github.com/acreese/meme-generator_data-wrangling)

![English, Spanish, and Russian memes](/img/portfolio/meme_samples.png)

<div class='tableauPlaceholder' id='viz1661783922251' style='position: relative'><noscript><a href='#'><img alt='Identifying sentiment in multilingual memesdata source: Library of Congress; analysis by Alexander Reese &amp; Elizabeth Seeley ' src='https://public.tableau.com/static/images/Me/MemeGeneratorLanguageandSentiment/FinalDraftDashboard2/1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MemeGeneratorLanguageandSentiment/FinalDraftDashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https://public.tableau.com/static/images/Me/MemeGeneratorLanguageandSentiment/FinalDashboard2/1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661783922251');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='2177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                  vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

![Database diagram](/img/portfolio/meme_database_diagram.jpeg)
