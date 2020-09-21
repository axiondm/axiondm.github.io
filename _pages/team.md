---
title: "AxionDM - Team"
layout: gridlay
excerpt: "AxionDM: Team members"
sitemap: false
permalink: /team/
---

# Group Members

 <!-- **We are  looking for new PhD students, Postdocs, and Master students to join the team** [(see openings)]({{ site.url }}{{ site.baseurl }}/vacancies) **!** -->

<div class="row">

  <div class="col-sm-4 clearfix">
  <h4>Senior members</h4>
  Stefano Bonetti

  Jan Conrad

  Jon Gudmundsson

  David Marsh

  Frank Wilczek

  Hiranya Peiris (PI)
  </div>

  <div class="col-sm-4 clearfix">
  <h4>Postdocs</h4>
  Tom Edwards

  Matthew Lawson

  Alexander Millar

  Keir Rogers
  </div>

  <div class="col-sm-4 clearfix">
  <h4>PhD students</h4>
  Alexandre Adler

  Konstantina Dachlythra

  Katherine Dunne

  Eike Müller
  </div>

</div>


<div class="row">
<div class="col-sm-4 clearfix">
<h4>Associate Members</h4>

Alexander Balatsky (Nordita)

Matthias Geilhufe (Nordita)

</div>
<div class="col-sm-4 clearfix">
  <h4></h4>

Ariel Goobar

Tim Linden

</div>

<div class="col-sm-4 clearfix">
  <h4></h4>

Bart Olsthoorn (Nordita)

Andreas Rydh
</div>

</div>


# External and International partners

<div class="row">
<div class="col-sm-4 clearfix">
<h4>Arizona State University</h4>

Nate Newman

<h4>Chalmers</h4>

Leonid Kuzmin

<h4> MIT </h4>

Sid Morampudi

<h4> Stanford University </h4>

Sebastian Baum
</div>

<div class="col-sm-4 clearfix">

<h4> UC Berkeley </h4>

Karl Van Bibber

Alexander Droster

Vishal Gajjar

Al Kenany

Samantha Lewis

<h4>  UC Berkeley / LBNL </h4>

Sinead Griffin

</div>

<div class="col-sm-4 clearfix">

<h4> UC Davis </h4>

Valentin Taufour

<h4> University of Michigan </h4>

Josh Foster

Ben Safdi

</div>

</div>

<!--
Alexander Balatsky (Nordita)

Matthias Geilhufe (Nordita)

Ariel Goobar

Tim Linden

Bart Olsthoorn (Nordita)

Andreas Rydh

</div>

<div class="col-sm-4 clearfix"></div>
<div class="col-sm-4 clearfix"></div>
</div>

## Senior members

Stefano Bonetti

Jan Conrad

Jon Gudmundsson

David Marsh

Frank Wilczek

Hiranya Peiris (PI)

## Postdocs / Researchers

Tom Edwards

Matthew Lawson

Alexander Millar

Keir Rogers

## PhD students

Alexandre Adler

Konstantina Dachlythra

Katherine Dunne

Eike Müller

## Associate members

Alexander Balatsky (Nordita)

Matthias Geilhufe (Nordita)

Ariel Goobar

Tim Linden

Bart Olsthoorn (Nordita)

Andreas Rydh

## External and International partners


#### Arizona State University:

Nate Newman

#### Chalmers / Nizhny Novgorod State Technical University:

Leonid Kuzmin

#### MIT

Sid Morampudi

#### Stanford University

Sebastian Baum

#### UC Berkeley:

Karl Van Bibber

Alexander Droster

Vishal Gajjar

Al Kenany

Samantha Lewis

#### UC Berkeley / LBNL:

Sinead Griffin

#### UC Davis:

Valentin Taufour

#### University of Michigan:

Josh Foster

Ben Safdi
 -->

<!--

Jump to [staff](#staff), [master and bachelor students](#master-and-bachelor-students), [alumni](#alumni), [administrative support](#administrative-support), [lab visitors](#lab-visitors).

## Staff
{% assign number_printed = 0 %}
{% for member in site.data.team_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
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




## Master and Bachelor Students
{% assign number_printed = 0 %}
{% for member in site.data.students %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <h4>{{ member.name }}</h4>
  <i>{{ member.info }}<br>email: <{{ member.email }}></i>
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


## Alumni

{% assign number_printed = 0 %}
{% for member in site.data.alumni_members %}

{% assign even_odd = number_printed | modulo: 2 %}

{% if even_odd == 0 %}
<div class="row">
{% endif %}

<div class="col-sm-6 clearfix">
  <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" class="img-responsive" width="25%" style="float: left" />
  <h4>{{ member.name }}</h4>
  <i>{{ member.duration }} <br> Role: {{ member.info }}</i>
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

## Former visitors, BSc/ MSc students
<div class="row">

<div class="col-sm-4 clearfix">
<h4>Visitors</h4>
{% for member in site.data.alumni_visitors %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Master students</h4>
{% for member in site.data.alumni_msc %}
{{ member.name }}
{% endfor %}
</div>

<div class="col-sm-4 clearfix">
<h4>Bachelor Students</h4>
{% for member in site.data.alumni_bsc %}
{{ member.name }}
{% endfor %}
</div>

</div>


## Administrative Support
<a href="mailto:Rijsewijk@Physics.LeidenUniv.nl">Ellie van Rijsewijk</a> is helping us (and other groups) with administration.
 -->