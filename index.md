---
title: Implement HTTP operations in a Blazor web app
permalink: index.html
layout: home
---

The following exercises are designed to provide you with a hands-on learning experience implementing HTTP operations, and rendering the results, in an ASP.NET Core Blazor web app. Learn how to gather needed information from a documented API, implement HTTP clients, and perform data operation through an API. 

## Exercises
<hr/>


{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %}
{% for activity in labs  %}
* [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) <br/> {{ activity.lab.description }}
{% endfor %}

