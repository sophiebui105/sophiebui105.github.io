---
layout: default
title: "Home"
---

# Hi, I'm Sophie 👋

I'm a data analyst / aspiring data scientist with experience in:

- Predictive analytics (AF/AFL ECG project)
- Power BI dashboards and automation
- SQL & Python for data analysis

This site is my portfolio and blog.  
Use the navigation bar above to explore my projects and posts.

## Blog

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      <span> – {{ post.date | date: "%b %-d, %Y" }}</span>
    </li>
  {% endfor %}
</ul>
