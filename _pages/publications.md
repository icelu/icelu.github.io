---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Please find the most updated versions of the list of publications on [Google Scholar](https://scholar.google.com/citations?user=GzDlXfUAAAAJ).

{% if author.googlescholar %}
  You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Preprints

   <ul>{% for post in site.preprints reversed %}
      {% include archive-single.html %}
   {% endfor %}</ul>

## Peer-reviewed journal

   <ul>{% for post in site.publications reversed %}
     {% include archive-single.html %}
   {% endfor %}</ul>
