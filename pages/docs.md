---
layout: page
title: Docs
permalink: /docs/
weight: 5
---

# **docs**

Hi I am **{{ site.author.name }}** :wave:,<br>
测试页面
<div class="row">
<div class="col-lg-10 mx-auto mt-5 markdown-body">
    <!-- Elements -->
  <h1>Elements</h1>
<div class="list-group my-3">
  <a class="list-group-item active disabled text-white">Table of Contents</a>
  <a class="list-group-item list-group-item-action" href="https://icp.me/docs">Headers</a>
  <a class="list-group-item list-group-item-action" href="#emphasis">Emphasis</a>
  <a class="list-group-item list-group-item-action" href="#highlight">Highlight</a>
  <a class="list-group-item list-group-item-action" href="#blockquotes">Blockquotes</a>
</div>
     <!-- Highlight -->
  <h2 id="highlight"> Highlight</h2>
<mark class="px-2">I am highlighted text.</mark><details>
  <summary class="text-monospace">View Code...</summary><figure class="highlight">
    <pre><code class="language-liquid" data-lang="liquid">[I'm a link](https://www.google.com)</code></pre></figure>
</details>

 <!-- Line Breaks --> 
  <h2 id="line-breaks"> Line Breaks</h2>
<p>Here’s a line for us to start with.</p>

<p>This line is separated from the one above by two newlines, so it will be a <em>separate paragraph</em>.</p>

<details>

    <summary class="text-monospace">View Code...</summary><figure class="highlight"><pre><code class="language-liquid" data-lang="liquid">Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.</code></pre></figure></details>


   <!-- Links -->
<h2 id="links"> Links</h2>
<p><a href="https://www.google.com">I’m a link</a></p>
<details>
    <summary class="text-monospace">View Code...</summary><figure class="highlight"><pre><code class="language-liquid" data-lang="liquid">[I'm a link](https://www.google.com)</code></pre></figure>
</details>

  <!-- Code -->
<h2 id="code"> Code</h2>
<p>Inline <code class="language-plaintext highlighter-rouge">code</code> has <code class="language-plaintext highlighter-rouge">back-ticks around</code> it.</p>

<div class="language-plaintext highlighter-rouge"><div class="highlight"><pre class="highlight"><code>s = "Code Block Test";
print s;
</code></pre></div></div>

  <!-- List Group -->
<h2 id="list-group"> List Group</h2>
<div class="list-group my-3">
<a class="list-group-item active disabled text-white">Websites</a><a class="list-group-item list-group-item-action" href="https://www.google.com">Google</a><a class="list-group-item list-group-item-action" href="https://www.github.com">
GitHub</a>
</div>
    
  <!-- alert警告框 -->
  <h2 id="list-group"> alert警告框</h2>
<div class="alert alert-primary" role="alert">
 <a href="https://www.google.com"> A simple primary alert—check it out!I’m a link</a>
</div>
<div class="alert alert-secondary" role="alert">
   <a href="https://www.google.com">A simple secondary alert—check it out!</a>
</div>
<div class="alert alert-success" role="alert">
   <a href="https://www.google.com">A simple success alert—check it out!</a>
</div>
<div class="alert alert-danger" role="alert">
  <a href="https://www.google.com"> A simple danger alert—check it out!</a>
</div>
<div class="alert alert-warning" role="alert">
  <a href="https://www.google.com"> A simple warning alert—check it out!</a>
</div>
<div class="alert alert-info" role="alert">
  <a href="https://www.google.com"> A simple info alert—check it out!</a>
</div>
<div class="alert alert-light" role="alert">
  <a href="https://www.google.com"> A simple light alert—check it out!</a>
</div>
<div class="alert alert-dark" role="alert">
  <a href="https://www.google.com"> A simple dark alert—check it out!</a>
</div>
<!-- alert警告框链接 -->
<a class="btn btn-outline-primary" href="#" role="button">primary</a>
<a class="btn btn-outline-secondary" href="#" role="button">secondary</a>
<a class="btn btn-outline-success" href="#" role="button">success</a>
<a class="btn btn-outline-danger" href="#" role="button">danger</a>
<a class="btn btn-outline-warning" href="#" role="button">warning</a>
<a class="btn btn-outline-info" href="#" role="button">info</a>
<a class="btn btn-outline-light" href="#" role="button">light</a>
<a class="btn btn-outline-dark" href="#" role="button">dark</a>
</div>
