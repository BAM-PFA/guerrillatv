---
layout: section
title: paper archives
permalink: /paper-archives
---

<!-- <div class="container-fluid"> -->
<div class="row my-2">
  <div class="col-sm-7">
    <p>Say something intelligent about the paper collection.</p>
  </div>
  <div class="col-sm-5 text-right">
    <image style="width: 80%" src="{{ site.baseurl }}/assets/images/booth.gif"/>
  </div>
</div>
<!-- </div> -->

<div class="row">
  <div class="col-sm-12 text-center">
    <image style="width: 100%" src="{{ site.baseurl }}/assets/images/worlds-largest.jpg"/>
  </div>
</div>

{% include sections/last_post.html last_post=site.paper-archives.last%}
{% include sections/items_except_last.html items=site.paper-archives%}
