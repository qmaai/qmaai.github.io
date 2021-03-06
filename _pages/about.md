---
permalink: /
title: "Gary Qiurui Ma"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style type="text/css">
  body{
    margin: 0;
    }
</style>
<hr style="border:1.5px solid gray">
I am a final year Computer Science and Business Student at Hong Kong University of Science and Technology, where I am very fortunate to be advised by [Prof. Tong Zhang](http://tongzhang-ml.org/).

In 2019, I spent a fantastic year at the [Strategic Reasoning Group](https://strategicreasoning.org/), University of Michigan Ann Arbor, where I was so thankful to be supervised by [Prof. Michael Wellman](http://strategicreasoning.org/michael-p-wellman/). My sincere gratitude also goes to [Prof. Tilman Borgers](http://www-personal.umich.edu/~tborgers/), whose most enlighting lectures sparked my interest in Game Theory. 

[comment]: #I also had a summer supervised by [Prof. Sankararaman](http://web.cs.ucla.edu/~sriram/) in UCLA and a semester in [Sensetime HK](https://www.sensetime.com/en) where [Sirui Xie](https://siruixie.com/) guided me onto the path of research.

# Research
<hr style="border:1.5px solid gray">
After exploration of Reinforcement Learing (RL) and Stochastic Control, I have found myself deeply attracted to the intersection of Game Theory and Computer Science. I was drawn to the field initially because of its power in combining the potential of RL with a solid framework of Equilibrium concepts into a multiagent system. Now I am interested in the theories of convergence to equilibrium concepts. My current work attempts to answer the following two questions:
1. Why and when do certain no-external-regret algorithms converge to Correlated Equilibriums or even Nash Equilibrium in some games, instead of a more general Coarse Correlated Equilibrium?
2. Is Nash Equilibrium identifiable through sampling in unknown stochastic games without a minimax oracle?


# Papers
<hr style="border:1.5px solid gray">
<h6>* indicates equal contribution. </h6>
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.publications reversed %}
      {% include archive-single.html %}
  {% endfor %}
</tbody>
</table>

# Projects
<hr style="border:1.5px solid gray">
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.talks reversed %}
      {% include archive-single-talk.html %}
  {% endfor %}
</tbody>
</table>

# Research and Work Experience
<hr style="border:1.5px solid gray">
<table style="width:100%;border:0px;border-spacing:0px;border-collapse:separate;margin-right:auto;margin-left:auto;">
<tbody>
  {% for post in site.portfolio reversed %}
      {% include archive-single-cv.html %}
  {% endfor %}
</tbody>
</table>



# Awards
<hr style="border:1.5px solid gray">
* HKSAR Government Scholarship (2018-2020) 
* UCLA CSST Scholarship and Best Presentation Award (2019)
* HKUST One Million Dollar International Entrepreneurship Competition Grand Finals Winning Award (2018)
* HSBC/HKU Hong Kong Business Case Competition Championship (2018)
* HKSAR Government Scholarship Fund - Talent Development Scholarship (2016)
* Dean List (2016-2020)
