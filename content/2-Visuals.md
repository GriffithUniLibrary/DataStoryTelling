---
title: Visualisation
nav: Visualisation
---
{% include figure.html img="analytics-CC0.png" alt="DataToViz" caption="Visuals!" width="80%" %}
We now explore some examples of visualisations. Be aware there are so many possibilities out there for visualising your data. Think beyond the standard line or bar graphs!

### Visualise your thesis
[Visualise Your Thesis](https://library.unimelb.edu.au/research/visualise-your-thesis#resources) is an international competition run by the University of Melbourne that challenges Higher Degree by Research (HDR) students to summarise their research in an engaging, 60-second visual presentation using a supplied template, that encapsulates your research project. It gives you the opportunity to build essential digital communication skills so you can effectively communicate complex research to a general audience. Competition submissions are judged on their visual impact, and how well the content presents the research. The competition allows for multi-media, interactivity and interpretation and is suitable for all disciplines. The video here is from a 2019 winner, HDR student at UTS.
{% include video-embed.html youtubeid="Am-AvhPl0jA" caption="Visualise Your Thesis" %}

### Timelapse
- You can highlight that time lapses would work well for event set ups, constructing buildings, or use of infrastructure throughout a day. This Pea Shoot video is very peaceful and therapeutic. 
{% include video-embed.html youtubeid="w77zPAtVTuI" caption="Bean Time-Lapse" %}

- Google Earth Timelapse
[Google Earth Timelapse](https://earthengine.google.com/timelapse/) is a global, zoomable video that lets you see how the Earth has changed.

### Interactive graphs
There are many interesting interactive graphs available for you to 'feel'. Some of our pick are listed below. 
- [New York Times' swing history graph](http://www.nytimes.com/interactive/2012/10/15/us/politics/swing-history.html) really impressess audience.
{% comment %}
{% include figure.html img="Swing_State.png" alt="cat" caption="Swing history" width="70%" %} %}
{% endcomment %}

- [ABC 2020 US election story](https://www.abc.net.au/news/2020-11-02/us-election-trump-biden-states-polling/12822296) covers complex stories with data very clear way.
{% comment %}
{% include figure.html img="abc_Election.png" alt="cat" caption="ABC 2020 US election data storytelling" width="70%" %} 
{% endcomment %}
- This [word cloud](https://shiny.rstudio.com/gallery/word-cloud.html) is developed with R Shiny.
{% comment %}
{% include figure.html img="Word_Cloud.png" alt="cat" caption="Shakespeare's favourite words are...?" width="70%" %}
{% endcomment %}
- [Brisbane floods photo comparison](http://www.abc.net.au/news/specials/qld-floods/) presents how Brisbane was affected by 2011 floods by comparing photos. You can create this photo comparison by using a free tool introduced in HERE. 
  
### For R / Python users
If you are thinking of developing some visuals with R / Python, they will give you an idea together with coding :)
- [DataVizCatalogue](https://datavizcatalogue.com/)
{% comment %}
{% include figure.html img="DataVizCatalogue.png" alt="DataVizCatalogue" caption="DataVizZatalogue.com" width="50%" %}
- [from Data to Viz](https://www.data-to-viz.com/)
{% endcomment %}
{% comment %}
{% include figure.html img="DataToViz.png" alt="DataToViz" caption="dada-to-viz.com" width="60%" %}
{% endcomment %}
### Inspired by examples
- [Data vis Project](https://datavizproject.com/) gives you sooo many ideas about graph designs.
{% comment %}
{% include figure.html img="Data_Viz_Project.png" alt="DataToViz" caption="datavizproject.com" width="50%" %} 
{% endcomment %}
### ... and a little more
You can explore and learn coding-free publication quality visualiation tools from [Data visualisation basics](https://griffithunilibrary.github.io/data-vis-basics/) online tutorial.
{% include figure.html img="Data_visualisation_basics.png" alt="Data Visualisation Basics.png" caption="Data Visualisation Basics created by Griffith University Library 2021, CC BY 4.0" width="70%" %} 

If you want to create one by yourself, [Northwestern University Knight Lab](https://knightlab.northwestern.edu/) provides free tools for that under *'Storytelling Tools'* section.

## Make sure your point can be seen
There are a wide array of amazing and visually stunning visualisations to choose from. But ask yourself, does this visualisations clearly relay the message that I want my audience to take away, or do they get confused or take a different message away.
If the audience cannot clearly understand the point you are trying to relay, then the visualisation has failed. 
The following visualisation display this point, the first is impossible to get meaning from, and the message is improved with each following one. They visualise the indexed cumulative GDP for each country between 1800-2020 (i.e. the sum gdp of each country standardised across all countries). The dataset used is from Gapminder data from R for Reproducible Scientific Analysis (https://swcarpentry.github.io/r-novice-gapminder/) , licensed under a Creative Commons Attribution 4.0 International licence, CC BY 4.0. (https://creativecommons.org/licenses/by/4.0/) by The Carpentries. It was downloaded from https://raw.githubusercontent.com/swcarpentry/r-novice-gapminder/ghpages/_episodes_rmd/data/gapminder_data.csv. Let's attempt to demonstrate through the visualisations that wealth is very unevenly distributed across the globe.

{% include figure.html img="dognut_graph.png" alt="" width="80%" %}
Pie and donut charts can be tricky to interpret, our minds have difficulty converting angles to units of measurement. A bar graph may be better as the units of measurement are stacked next to each other, making direct comparisons possible. 
{% include figure.html img="bar_graph1.png" alt="" width="80%" %}
Now with the box plot we can directly compare between countries, there are far to many catagories (in this case the number of countries) which create clutter and our minds wander.
{% include figure.html img="bar_graph2.png" alt="" width="80%" %}
If we plot by region then suddenly we can very clearly see that Africa is the poorest region and Europe is the richest! But there is variation within regions. In Europe Switzerland is insanely rich, will Moldovia is definately not.

{% include figure.html img="map_1.png" alt="" width="80%" %}
A heatmap displays this data the best, you can see the general regional trends, but within these regions there is also wealth inequality.

## Simple techniques to make your point clear
There are a couple of simple techniques to make your point clearer. Here is a few:
- Headlines
- Callouts
- Highlight areas

What do they mean? Have a look at the video below!
{% include video-embed.html youtubeid="ctEeeE8yGEw" caption="3 techniques to make your point clear" %}


Are you inspired by looking at examples of beautiful visuals?
[Next section](https://griffithunilibrary.github.io/data-storytelling/content/3-Power-of-story.html) is about a narrative, which is another vital part of storytelling.




