---
layout: post
title:  Four More Years
description: Raw footage from <i>Four More Years</i>
date:   1972-08-20
image: /assets/images/fmy-038.jpg
---

This tape consists of approximately 33 minutes of raw footage from the TVTV shooting of <i>Four More Years</i> (1972) during the 1972 Republican National Convention.
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>

<script>
  function load_iframe (vid,img) {
    var iframe = $("#"+vid);
    var image = $("#"+img)
    <!-- alert(event); -->
    image.addClass("fade-out");
    iframe.attr("src", iframe.data("src"));
    iframe.addClass("iframe-loaded");
    <!-- iframe.attr("width", "100"); -->
  }
</script>

<!-- <button  onclick="load_iframe('video1frame')">hello</button> -->
<div class="row">
  <div class="col-md-4 col-sm-6 col-xs-12">
    <div class="iframe-div-container" onclick="load_iframe('video1frame','image1')" style="cursor: pointer;">
      <iframe class="iframe-overlaid" id="video1frame" frameborder="0" data-src="https://drive.google.com/file/d/1-EDQeDRvceC9KRA-ullNywgK679fZLVV/preview"></iframe>
      <image class="iframe-img" id="image1" src="{{ site.baseurl }}/assets/images/kovic.jpg"/>
    </div>
    <p>Here is some info</p>
  </div>
  <div class="col-md-4 col-sm-6 col-xs-12">
    <div class="iframe-div-container" onclick="load_iframe('video2frame','image2')" style="cursor: pointer;">
      <iframe class="iframe-overlaid" id="video2frame" frameborder="0" data-src="https://drive.google.com/file/d/1-EDQeDRvceC9KRA-ullNywgK679fZLVV/preview"></iframe>
      <image class="iframe-img" id="image2" src="{{ site.baseurl }}/assets/images/kovic.jpg"/>
    </div>
    <p>Here is some info</p>
  </div>
  <div class="col-md-4 col-sm-6 col-xs-12">
    <div class="iframe-div-container" onclick="load_iframe('video3frame','image3')" style="cursor: pointer;">
      <iframe class="iframe-overlaid" id="video3frame" frameborder="0" data-src="https://drive.google.com/file/d/1-EDQeDRvceC9KRA-ullNywgK679fZLVV/preview"></iframe>
      <image class="iframe-img" id="image3" src="{{ site.baseurl }}/assets/images/kovic.jpg"/>
    </div>
    <p>Here is some info</p>
  </div>
</div>


<!--
<div class="row my-2">
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
</div>
<div class="row my-2">
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
  <div class="col-4">
    <div class="iframe-container mx-auto">
      {% include drive_player.html id="1-EDQeDRvceC9KRA-ullNywgK679fZLVV" %}
      <p>This is some info.</p>
    </div>
  </div>
</div>
-->
