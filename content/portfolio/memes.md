+++
image = "/img/portfolio/meme_dash_4.png"
showonlyimage = false
draft = false
date = "2022-08-29T19:53:42+05:30"
title = "Meme Generator Natural Language Processing and Sentiment Analysis"
weight = 4
tags = ["Python","SQL","Tableau",'ETL','NLP','Data Viz']
categories = ['Data Viz']
+++

Data wrangling using Python and SQL meme text, images, and 82 language sentiment lexicons into a realational MySQL database for language and sentiment analysis. Visualization with Tableau.

<div class=Tags>
<span><a href="/tags/python/">Python</a></span>
<span><a href="/tags/sql/">SQL</a></span>
<span><a href="/tags/tableau/">Tableau</a></span>
<span><a href="/tags/etl/">ETL</a></span>
<span><a href="/tags/nlp/">NLP</a></span>
<span><a href="/tags/data-viz/">Data Viz</a></span>
</div>
<!--more-->

See this project's: [GitHub Repository](https://github.com/acreese/meme-generator_data-wrangling) and documentation

![English, Spanish, and Russian memes](/img/portfolio/meme_samples.png)


<div class='tableauPlaceholder' id='viz1661783922251' style='position: relative'><noscript><a href='#'><img alt='Identifying sentiment in multilingual memesdata source: Library of Congress; analysis by Alexander Reese &amp; Elizabeth Seeley ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MemeGeneratorLanguageandSentiment&#47;FinalDraftDashboard2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MemeGeneratorLanguageandSentiment&#47;FinalDraftDashboard2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MemeGeneratorLanguageandSentiment&#47;FinalDraftDashboard2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1661783922251');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1000px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='2177px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

<br></br>

### Project Summary

Working with the Python `langid` library and sentiment lexicons in 81 languages developed by the SUNY Data Science Lab, my partner, Liz Seeley, and I created a relational database of 57,000 meme instances based on over 800 basememes. In this process, we were able to probabilistically identify the language of each meme and analyze their captions for positive and negative words to which we assigned positive (+1) and negative (-1) scores, respectively. With an SQL query, we were able to calculate an overall sentiment score for each meme and basememe both within and across languages.


![Database diagram](/img/portfolio/meme_database_diagram.jpeg)

![Data wrangling flow](/img/portfolio/meme_database_flow.jpeg)


