---
layout: default
title: Home
---

# 🐫 Benvenuto su AlpacaData

**Blog tecnico su Artificial Intelligence, Business Intelligence e Analytics**

## 📋 Menu
- [Progetti](/progetti.html)
- [Tutorial](/tutorial.html)  
- [Blog](/blog.html)

## 📝 Ultimi articoli
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

## 🚀 Servizi
- **AI & Machine Learning**: Modelli predittivi, NLP
- **Business Intelligence**: Dashboard, reporting
- **Data Analytics**: Analisi dati, visualizzazioni

---
*© 2024 AlpacaData* 
