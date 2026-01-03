---
layout: page
title: Posts
---

<table class="table table-hover">
  <thead>
  </thead>
  <tbody>
  {% for post in site.posts %}
    <tr>
      <td class="light" style="width: 1%; white-space: nowrap;">{{ post.date | date: "%b %d, %Y" }}</td>
      <td class="title"><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></td>
    </tr>
  {% endfor %}
  </tbody>
</table>
