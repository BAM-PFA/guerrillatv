---
layout: section
title: paper archives
permalink: /paper-archives
---
We can have a section talk about the archival papers with some examples.

<!-- <div class="container-fluid"> -->
  <div class="row">
    <div class="col text-center">
      <image style="width: 50%" src="{{ site.baseurl }}/assets/images/worlds-largest.jpg"/>
    </div>
  </div>
<!-- </div> -->

{% include sections/last_post.html last_post=site.paper-archives.last%}
{% include sections/items_except_last.html items=site.paper-archives%}
