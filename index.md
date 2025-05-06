---
title: Automatizar o teste de carga do Azure com o GitHub Actions
permalink: index.html
layout: home
---

Os exercícios a seguir foram elaborados para fornecer uma experiência de aprendizado prática implementando ações e fluxos de trabalho do GitHub para automatizar a execução de um teste de carga do Teste de Carga do Azure. 

## Exercícios
<hr/>


{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %} {% for activity in labs  %}
* [{{ activity.lab.title }}]({{ site.github.url }}{{ activity.url }}) <br/> {{ activity.lab.description }} {% endfor %}
