---
title: News
nav:
  order: 5
  tooltip: Lab news and updates
---


{% capture col1 %}
###  {% include icon.html icon="fa-solid fa-newspaper" %} News and updates

{% assign sorted_news = site.data.news | sort: "date" | reverse %}
    {% for post in sorted_news %}
    
  <div class="news-card">
    <div class="news-header">
        <span class="news-title">{{ post.title }}</span>
        <span class="news-date">{% include icon.html icon="fa-regular fa-calendar" %} {{ post.date | date: "%B %d, %Y" }} </span>
    </div>
    <div class="news-description">
        {{ post.description }} 
            {% if post.url %}
            <a href="{{ post.url }}" target="_blank">More...</a>
            {% endif %}
    </div>
  </div>

    {% endfor %}  

{% endcapture %}

{% include cols.html col1=col1 %}