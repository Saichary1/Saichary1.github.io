---
layout: home
title: "Welcome to My Portfolio"
author_profile: true
---

## About Me  
Hello! I’m **Saikumar Chary**, a passionate **[Oracle Fusion HCM Consultant]**.  
This is my personal blog and portfolio where I share my projects and thoughts.

## Projects  
- **Project 1** – Description of project 1.  
- **Project 2** – Description of project 2.  
- **Project 3** – Description of project 3.  

## Blog  
Here are my latest blog posts:  
{% for post in site.posts limit:3 %}  
- [{{ post.title }}]({{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}  
{% endfor %}
