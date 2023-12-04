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
<div class="col-lg-10 mx-auto mt-10 markdown-body">
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

 <!-- 下拉链接 --> 
 <div class="accordion" id="accordionExample">
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingOne">
      <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#collapseOne" aria-expanded="true" aria-controls="collapseOne">
        Accordion Item #1
      </button>
    </h2>
    <div id="collapseOne" class="accordion-collapse collapse show" aria-labelledby="headingOne" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingTwo">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseTwo" aria-expanded="false" aria-controls="collapseTwo">
        Accordion Item #2
      </button>
    </h2>
    <div id="collapseTwo" class="accordion-collapse collapse" aria-labelledby="headingTwo" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
  <div class="accordion-item">
    <h2 class="accordion-header" id="headingThree">
      <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#collapseThree" aria-expanded="false" aria-controls="collapseThree">
        Accordion Item #3
      </button>
    </h2>
    <div id="collapseThree" class="accordion-collapse collapse" aria-labelledby="headingThree" data-bs-parent="#accordionExample">
      <div class="accordion-body">
        <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
      </div>
    </div>
  </div>
</div>


   <!-- Links -->
<h2 id="links"> Links</h2>
<p><a href="https://www.google.com">I’m a link</a></p>
<a href="#" class="text-decoration-none">This link has its text decoration removed</a>

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
<hr class="my-5">
<!-- text-bg-primary p-3 -->
<div class="text-bg-light p-3">Light with contrasting</div>
<div class="text-bg-primary p-3">Primary with contrasting color</div>
<div class="text-bg-secondary p-3">Secondary with contrasting color</div>
<div class="text-bg-success p-3">Success with contrasting color</div>
<div class="text-bg-danger p-3">Danger with contrasting color</div>
<div class="text-bg-warning p-3">Warning with contrasting color</div>
<div class="text-bg-info p-3">Info with contrasting color</div>
<div class="text-bg-dark p-3">Dark with contrasting color</div>
<hr class="my-5">
<div class="vstack gap-2 col-md-5 my-5 mx-auto">
  <button type="button" class="btn btn-secondary">Save changes</button>
  <button type="button" class="btn btn-outline-secondary">Cancel</button>
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
  
