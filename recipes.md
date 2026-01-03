---
layout: page
title: Family Recipes
---

<table class="table table-hover">
  <thead>
  </thead>
  <tbody>
  {% for recipe in site.recipes %}
    <tr>
      <td class="title"><a href="{{ recipe.url | prepend: site.baseurl }}">{{ recipe.title }}</a></td>
    </tr>
  {% endfor %}
  </tbody>
</table>
