---
layout: page
title: My Journey at Yale
---



This is a test


<body>
<style>

body {
  font: 10px sans-serif;
  background: #222;
  background-color: #222;
}

text {
  fill: #fff
}

.axis path,
.axis line {
  fill: none;
  stroke: #fff;
  shape-rendering: crispEdges;
}

.dot {
  stroke: #fff;
}


.overlay {
  pointer-events: none;
}

.hidden{
  display:none;
}

.interact{
  fill: #aaa;
}

.interacttext{
  fill: #000;
}

.colorselect{
  fill: #aaa;
}

.colortext{
  fill: #000;
}

.labelselect{
  fill: #aaa;
}

.labeltext{
  fill: #000;
}

</style>
<script src="d3.min.js"></script>
<script src='data.js'></script>
<script src='darkviz.js'></script>


<div class="container" id="dataviz">
</div>
<div class="container" id="hud">
</div>
</body>