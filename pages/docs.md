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
<div class="col-lg-10 mx-auto mt-8 markdown-body">
        <!-- 关闭警告框 -->
          <h2>警告框</h2>
   <div class="alert alert-danger" role="alert">
  测试页面!
</div>
    
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
<div class="list-group">
  <a href="#" class="list-group-item list-group-item-action">A simple default list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-primary">A simple primary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-secondary">A simple secondary list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-success">A simple success list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-danger">A simple danger list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-warning">A simple warning list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-info">A simple info list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-light">A simple light list group item</a>
  <a href="#" class="list-group-item list-group-item-action list-group-item-dark">A simple dark list group item</a>
</div>

<!-- alert警告框链接 -->
  <h2 id="list-group"> 警告框链接</h2>
<a class="btn btn-outline-primary" href="#" role="button">primary</a>
<a class="btn btn-outline-secondary" href="#" role="button">secondary</a>
<a class="btn btn-outline-success" href="#" role="button">success</a>
<a class="btn btn-outline-danger" href="#" role="button">danger</a>
<a class="btn btn-outline-warning" href="#" role="button">warning</a>
<a class="btn btn-outline-info" href="#" role="button">info</a>
<a class="btn btn-outline-light" href="#" role="button">light</a>
<a class="btn btn-outline-dark" href="#" role="button">dark</a>
<!-- 小图标 -->
  <div class="my-3 p-3 bg-body rounded shadow-sm">
    <h6 class="border-bottom pb-2 mb-0">Suggestions</h6>
    <div class="d-flex text-muted pt-3">
      <svg class="bd-placeholder-img flex-shrink-0 me-2 rounded" width="32" height="32" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 32x32" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#007bff"/><text x="50%" y="50%" fill="#007bff" dy=".3em">32x32</text></svg>
            <i class="bi bi-cup-hot-fill"></i>
      <div class="pb-3 mb-0 small lh-sm border-bottom w-100">
        <div class="d-flex justify-content-between">
          <strong class="text-gray-dark">Full Name</strong>
          <a href="#">Follow</a>
        </div>
        <span class="d-block">@username</span>
      </div>
    </div>

    <div class="d-flex text-muted pt-3">
      <svg class="bd-placeholder-img flex-shrink-0 me-2 rounded" width="32" height="32" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Placeholder: 32x32" preserveAspectRatio="xMidYMid slice" focusable="false"><title>Placeholder</title><rect width="100%" height="100%" fill="#007bff"/><text x="50%" y="50%" fill="#007bff" dy=".3em">32x32</text></svg>
      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-cup-hot-fill" viewBox="0 0 16 16">
  <path fill-rule="evenodd" d="M.5 6a.5.5 0 0 0-.488.608l1.652 7.434A2.5 2.5 0 0 0 4.104 16h5.792a2.5 2.5 0 0 0 2.44-1.958l.131-.59a3 3 0 0 0 1.3-5.854l.221-.99A.5.5 0 0 0 13.5 6H.5ZM13 12.5a2.01 2.01 0 0 1-.316-.025l.867-3.898A2.001 2.001 0 0 1 13 12.5Z"/>
  <path d="m4.4.8-.003.004-.014.019a4.167 4.167 0 0 0-.204.31 2.327 2.327 0 0 0-.141.267c-.026.06-.034.092-.037.103v.004a.593.593 0 0 0 .091.248c.075.133.178.272.308.445l.01.012c.118.158.26.347.37.543.112.2.22.455.22.745 0 .188-.065.368-.119.494a3.31 3.31 0 0 1-.202.388 5.444 5.444 0 0 1-.253.382l-.018.025-.005.008-.002.002A.5.5 0 0 1 3.6 4.2l.003-.004.014-.019a4.149 4.149 0 0 0 .204-.31 2.06 2.06 0 0 0 .141-.267c.026-.06.034-.092.037-.103a.593.593 0 0 0-.09-.252A4.334 4.334 0 0 0 3.6 2.8l-.01-.012a5.099 5.099 0 0 1-.37-.543A1.53 1.53 0 0 1 3 1.5c0-.188.065-.368.119-.494.059-.138.134-.274.202-.388a5.446 5.446 0 0 1 .253-.382l.025-.035A.5.5 0 0 1 4.4.8Zm3 0-.003.004-.014.019a4.167 4.167 0 0 0-.204.31 2.327 2.327 0 0 0-.141.267c-.026.06-.034.092-.037.103v.004a.593.593 0 0 0 .091.248c.075.133.178.272.308.445l.01.012c.118.158.26.347.37.543.112.2.22.455.22.745 0 .188-.065.368-.119.494a3.31 3.31 0 0 1-.202.388 5.444 5.444 0 0 1-.253.382l-.018.025-.005.008-.002.002A.5.5 0 0 1 6.6 4.2l.003-.004.014-.019a4.149 4.149 0 0 0 .204-.31 2.06 2.06 0 0 0 .141-.267c.026-.06.034-.092.037-.103a.593.593 0 0 0-.09-.252A4.334 4.334 0 0 0 6.6 2.8l-.01-.012a5.099 5.099 0 0 1-.37-.543A1.53 1.53 0 0 1 6 1.5c0-.188.065-.368.119-.494.059-.138.134-.274.202-.388a5.446 5.446 0 0 1 .253-.382l.025-.035A.5.5 0 0 1 7.4.8Zm3 0-.003.004-.014.019a4.077 4.077 0 0 0-.204.31 2.337 2.337 0 0 0-.141.267c-.026.06-.034.092-.037.103v.004a.593.593 0 0 0 .091.248c.075.133.178.272.308.445l.01.012c.118.158.26.347.37.543.112.2.22.455.22.745 0 .188-.065.368-.119.494a3.198 3.198 0 0 1-.202.388 5.385 5.385 0 0 1-.252.382l-.019.025-.005.008-.002.002A.5.5 0 0 1 9.6 4.2l.003-.004.014-.019a4.149 4.149 0 0 0 .204-.31 2.06 2.06 0 0 0 .141-.267c.026-.06.034-.092.037-.103a.593.593 0 0 0-.09-.252A4.334 4.334 0 0 0 9.6 2.8l-.01-.012a5.099 5.099 0 0 1-.37-.543A1.53 1.53 0 0 1 9 1.5c0-.188.065-.368.119-.494.059-.138.134-.274.202-.388a5.446 5.446 0 0 1 .253-.382l.025-.035A.5.5 0 0 1 10.4.8Z"/>
</svg>

      <div class="pb-3 mb-0 small lh-sm border-bottom w-100">
        <div class="d-flex justify-content-between">
          <strong class="text-gray-dark">Full Name</strong>
          <a href="#">Follow</a>
        </div>
        <span class="d-block">@username</span>
      </div>
    </div>
    <small class="d-block text-end mt-3">
      <a href="#">All suggestions</a>
    </small>
  </div>
  

</div>
  
  </div>
  
