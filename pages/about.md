---
layout: page
title: About
permalink: /about/
weight: 6
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
<div class="card">
  <div class="card-header">
    Quote
  </div>
  <div class="card-body">
    <blockquote class="blockquote mb-0">
      <p>A well-known quote, contained in a blockquote element.</p>
      <footer class="blockquote-footer">Someone famous in <cite title="Source Title">Source Title</cite></footer>
    </blockquote>
  </div>
</div>
<hr class="my-5">
<!-- alert警告框 -->
  <h2 id="list-group"> alert警告框</h2>
<div class="list-group">
  <div class="list-group-item list-group-item-action list-group-item-default">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-primary">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-secondary">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-success">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-danger">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-warning">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-info">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-light">A simple default list group item</div>
  <div class="list-group-item list-group-item-action list-group-item-dark">A simple default list group item</div>
  
  <a href="#" class="list-group-item list-group-item-action list-group-item-primary">A simple primary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-secondary">A simple secondary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-success">A simple success list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-danger">A simple danger list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-warning">A simple warning list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-info">A simple info list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-light">A simple light list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-dark">A simple dark list group item</a>
</div>
<hr class="my-5">
<div class="row">
{% include about/guestbook.html %}
</div>
