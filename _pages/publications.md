---
title: "Artificial Intelligence and Machine Learning Group - Publications"
layout: gridlay
excerpt: "AIML Group -- Publications."
sitemap: false
permalink: /publications/
---


## Publications

(See also [Google Scholar](https://scholar.google.com/citations?user=RdA9uxYAAAAJ))

{% assign number_printed = 0 %}
{% for publi in site.data.publist %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if publi.highlight == 1 %}

{% if even_odd == 0 %}
<div class="row 1000px">
{% endif %}

<div class="col-sm-6 clearfix">
 <div class="well">
  <pubtit>{{ publi.title }}</pubtit>
  <em>{{ publi.authors }}</em> <br>
  <strong><a href="{{ publi.link.url }}">{{ publi.link.display }}</a></strong> <br>
  <img src="{{ site.url }}{{ site.baseurl }}/images/pubpic/{{ publi.image }}" class="img-responsive" width="100%" style="float: left" />
  <p>{{ publi.description }}</p>  
  <p class="text-danger"><strong> {{ publi.news1 }}</strong></p>
  <p> {{ publi.news2 }}</p>
 </div>
</div>

{% assign number_printed = number_printed | plus: 1 %}

{% if even_odd == 1 %}
</div>
{% endif %}

{% endif %}
{% endfor %}

{% assign even_odd = number_printed | modulo: 2 %}
{% if even_odd == 1 %}
</div>
{% endif %}

<p> &nbsp; </p>


#### 2026

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2026 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2025

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2025 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2024

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2024 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2023

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2023 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2022

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2022 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2021

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2021 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2020

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2020 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2019

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2019 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2018

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2018 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2017

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2017 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2016

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2016 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2015

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2015 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2014

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2014 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2013

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2013 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2012

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2012 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2011

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2011 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2010

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2010 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2009

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2009 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2008

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2008 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2007

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2007 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2006

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2006 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2005

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2005 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2004

{% for publi in site.data.publist %}
{% if {{publi.year}} == 2004 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}

#### 2003 - 2000

{% for publi in site.data.publist %}
{% if {{publi.year}} <= 2003 %}
  - {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a> <br>
  {% if {{publi.haslocal}} == 1 %}[<a href ="{{ site.url }}{{ site.baseurl }}/files/{{publi.local}}">local copy</a>]{% endif %} {% if {{publi.hascode}} == 1 %}[<a href="{{publi.code}}">code</a>]{% endif %} {% if {{publi.hasppt}} == 1 %}[<a href="{{publi.ppt}}">ppt</a>]{% endif %} {% if {{publi.poster}} == 1 %}[<a href="{{publi.poster}}">poster</a>]{% endif %} {% if {{publi.hasvideo}} == 1 %}[<a href="{{publi.video}}">video</a>]
  {% endif %} 
  
{% endif %}
{% endfor %}
