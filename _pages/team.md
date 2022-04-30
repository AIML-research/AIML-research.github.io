---
title: "Artificial Intelligence and Machine Learning Group - Team"
layout: gridlay
excerpt: "AIML group: Team members"
sitemap: false
permalink: /team/
---

### Faculty

{% assign number_printed = 0 %}
{% for member in site.data.faculty %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i>
  - E-mail: {{ member.email }}
  
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### Secretariat
{% assign number_printed = 0 %}
{% for member in site.data.secretary %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }} </i> <br>
  - E-mail: {{ member.email }}
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


### PhDs
{% assign number_printed = 0 %}
{% for member in site.data.phds %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="30%" style="float: left" />
  <h4> <a href=" {{ member.website }} ">{{ member.name }}</a> </h4>
  <i>{{ member.info }} </i>
  - E-mail: <a href="mailto: {{ member.email }} ">{{ member.email }}  </a>
  - Project:{% if member.has_project_web == 1 %} <a href=" {{ member.project_web }} "> {% endif %} {{ member.project }} </a>  
<!---  - Research interests: {{ member.interest }} -->
  <ul style="overflow: hidden">

  {% if member.number_educ == 1 %}
  <li> {{ member.education1 }} </li>
  {% endif %}

  {% if member.number_educ == 2 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  {% endif %}

  {% if member.number_educ == 3 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  {% endif %}

  {% if member.number_educ == 4 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  {% endif %}

  {% if member.number_educ == 5 %}
  <li> {{ member.education1 }} </li>
  <li> {{ member.education2 }} </li>
  <li> {{ member.education3 }} </li>
  <li> {{ member.education4 }} </li>
  <li> {{ member.education5 }} </li>
  {% endif %}

  </ul>
  
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}


### Master and Bachelor students

- <b> Viktoria Andres </b>, BSc , <a href ="https://git.imp.fu-berlin.de/viktoa98/bachelor-thesis-about-counterfactuals-in-time-series-classification/-/tree/master"> "Generating Counterfactual Explanations for Electrocardiography Classification with Native Guide" </a>, WiSe21/22 
- <b> Florian Mies </b>, MSc, "Generative replay", SoSe22


### HiWi students

- <b> Viktoria Andres </b>, BSc , Student assistant, project: <a href ="https://aiml-research.github.io/projects/hephaestus/">Hephaestus </a>, WiSe21/22 
- <b> Anton Kriese </b>, MSc, Student assistant, WiSe21/22


### Former members

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">  
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> {{ member.info }}</i> <br>
  {{ member.topic }}
  <ul style="overflow: hidden">

  </ul>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

### Former visitors

  - <b> Srijanani Saiegiridar </b> (Visiting BSc student), 01/01/2020-31/7/2020, Sastra Deemed University, India. Research topic: Fair clustering.  
  - <b> Bahman Askari </b> (Erasmus MSc student), WiSe18/19-SS19, University of Camerino, Italy. Research topic: demand prediction. Related publication <a href = "https://doi.org/10.1109/COMPSAC48688.2020.000-7"> SSMLS@COMPSAC 2020 </a>.  
  - <b> Wenbin Zhang </b> (Visiting PhD student), WiSe17/18-SS18, University of Maryland, USA. Research topic: Online fairness. Related publication <a href="https://www.ijcai.org/proceedings/2019/0205.pdf"> IJCAI 2019 </a>.
  
### Former Master and Bachelor students

#### Leibniz University Hannover (LUH), Germany
- <b> Philipp Naumann </b>, MSc, ''Evolutionary Instance Tweaking'', WiSe20/21.
- <b> Leonard Zucht </b>, MSc, ''Application of Amortized Fairness in Sequential Group Recommendations Using Collaborative Filtering'', WiSe19/20.
- <b> Philip Ossenkopp </b>, BSc, ''Dealing with Concept Drifts via Weightless Neural Networks'', WiSe19/20.
- <b> Niels Nuthmann </b>, BSc, ''Detecting tendon failure from acoustic emission data with machine learning methods'' - in cooperation with Prof. Marx (Institut für Massivbau), SoSe19.
- <b> Wazed Ali </b>, MSc, ''Sentiment Analysis using Deep Learning'', WoSe18/19.
- <b> Christopher Blake </b>, MSc, ''Knowledge Production and Control of a Black Box Using Machine Learning'', WS18/19. Related publication: <a href ="https://aiml-research.github.io/files/18.ICBK.pdf">ICBK 2018 </a>.
- <b> Theresa Tholsti </b>, BSc, ''Stability of high dimensional stream clustering'', SoSe18.
- <b> Kersten Nicksch </b>, BSc, ''Multicriteria recommendations with implicit criteria'', SoSe18.
- <b> Simon Wingert </b>, MSc, ''Augmentation on image data for deep learning'', SoSe18.
- <b> Alvaro Alvaro Veizaga Campero </b>, MSc, ''Sentiment Analysis with Deep Learning'', SoSe18.
- <b> Ruben Hohndorf </b>, MSc, ''Data stream clustering", SoSe18.
- <b> Bin Li </b>, MSc, ''Anomaly detection in sensor streams'', SoSe18.
- <b> Monseh Haghaieghshenasfard </b>, Research project, Taxi Fare Prediction, SoSe18.
- <b> Al Kafi Khan </b>, Research project, ''Predictive Maintenance'', SoSe 17.
- <b> Amit Tyagi </b>, MSc project, “Outlier detection in data streams", SoSe 17.
- Rajib Das, MSc, “Mining opinionated product features from Amazon reviews", SoSe 17.
- <b> Alvaro Alvaro Veizaga Campero </b>, Research project, “Lexicon-based approaches for sentiment analysis in Twitter", SoSe 17. Related publication: <a href ="https://aiml-research.github.io/files/18.WIMS.pdf"> WIMS 2018 </a>.
- <b> Lijun Lyu </b>, Research project, “Wikipedia Entity Enrichment from News Streams", SoSe 17.
- <b> Nrithya Muniswamy & Nidhi Chachra </b>, Research project, “Implicit network mining from archive collections", SoSe 17.
- <b> Sudhir Kumar Sah </b>, MSc, “Topic extraction from archive collections", WiSe 16/17.

#### Ludwig Maximilians University (LMU) Munich, Germany
- <b> Omar Backhoff </b>, MSc, “Scalable Online-Offline Stream Clustering in Apache Spark”, TUM Munich, 2017. <a href ="https://aiml-research.github.io/files/16.ICDM.IoT.pdf">Related publication </a>
- <b> Daniel Basaran </b>, MSc, “On the effect of duplicated reviews on performance statistics of recommender systems”, LMU Munich, 2016. <a href ="https://aiml-research.github.io/files/17.SDM.pdf">Related publication </a>
- <b> Benedikt Böhm </b>, Project work, “Building blocks for multicriteria recommendation systems”, LMU Munich, 2016.
- <b> Yulia Bobkova </b>, BSc, Interaktive Bestimmung charakterstischer Punktmengen durch Kombination von Clusterings”, LMU Munich, 2016. <a href ="https://aiml-research.github.io/files/16.PKDD.pdf">Related publication </a>
- <b> Hossain Mahmud </b>, MSc, “Ensemble Learning in Data Streams”, TUM Munich, 2016.
- <b> Sebastian Wagner </b>,BSc, “Ageing-based Multinomial Naive Bayes Classifiers over Data Streams”, LMU Munich, 2015. <a href ="https://aiml-research.github.io/files/15.ECMLPKDD.pdf">Related publication </a>
- <b> Annina Oelschläger </b>, BSc, “Adaptive Ageing of Multinomial Naive Bayes Classifiers over Opinionated Data Streams”, LMU Munich, 2015.
- <b> Tabea Schmidt </b>, “High Dimensional Stream Clustering”, LMU Munich, 2015.
- <b> Michael Stockerl </b>, MSc, "Find Templates for Scans and Pictures of Paper Documents", LMU Munich, 2014. <a href ="https://aiml-research.github.io/files/15.SSDBM(a).pdf">Related publication </a>
- <b> Michael Stockerl </b>, Project work, "Distributed Computation of User Similarities", LMU Munich, 2014.
- <b> Claudia Lauschke </b>, MSc, "Topic extraction and evolution monitoring in social streams", LMU Munich, 2014. <a href ="https://aiml-research.github.io/files/12.BASNA.pdf">Related publication </a>
- <b> Katharina Rausch </b>, MSc, "Exploring Subspace Clustering for Recommendations", LMU Munich, 2013. <a href ="https://aiml-research.github.io/files/14.SSDBM.pdf">Related publication </a>
- <b> Michalis Petropoulos </b>, BSc, “gRecs: A Group Recommendation System”, LMU Munich, 2013. <a href ="https://aiml-research.github.io/files/13.TLDKS.pdf">Related publication </a>
- <b> Charlotte Prieß </b>, BSc, “Domain-specific sentiment analysis in Twitter using Bayesian classifiers”, LMU Munich, 2012.
- <b> Alina Sinelnikova </b>, BSc, “Sentiment analysis in the Twitter stream”, LMU Munich, 2012. <a href ="https://aiml-research.github.io/files/12.GfKl_a.pdf"> Related publication </a>
- <b> Alexander Velkov </b>, Diploma thesis, "Incremental Data Bubbles for Non-Vector Data in Arbitrary Metric Space", LMU Munich, 2011.
- <b> Kumar Subramanim </b>, Diploma thesis, "Community Detection in Social Networks using Density Based Clustering Algorithms", LMU Munich, 2011. <a href ="https://aiml-research.github.io/files/11.BASNA.pdf">Related publication </a>
- <b> Claudia Lauschke </b>, BSc, "User Profile Monitoring in Twitter", LMU Munich, 2011.
- <b> Veselin Georgiev </b>, Project work, "Web Profile Monitoring", Projektarbeit, LMU Munich, 2011.

#### University of Piraeus, Greece
- <b> Georgios Tzoumis </b>, MSc, “Data warehousing for news portals”, University of Piraeus, 2006.
- <b> Marios Mpartzokas </b>, BSc, "Comparing complex patterns: a study on collections of documents", University of Piraeus, 2006.
- <b> Anastasia Tzeveleka </b>, BSc, "Duck-miner: A Tool for Discovering and Handling Knowledge from Large DBs", University of Piraeus, 2005.
