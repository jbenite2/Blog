---
title: 'Posts'
layout: 'posts'
---

<style>
  /* Style the timeline */
  ol.timeline {
    list-style: none;
    position: relative;
  }

  /* Add a line to connect the items on the timeline */
  ol.timeline:before {
    content: '';
    position: absolute;
    top: 0;
    bottom: 0;
    left: 50%;
    width: 2px;
    margin-left: -1.5px;
    background-color: #ddd;
  }

  /* Style the items on the timeline */
  ol.timeline > li {
    position: relative;
    margin: 20px 0;
    padding-left: 50px;
  }

  /* Add an arrow to the left of the items on the timeline */
  ol.timeline > li:before {
    content: '';
    position: absolute;
    top: 5px;
    left: 0;
    width: 12px;
    height: 12px;
    border: 3px solid #ddd;
    border-radius: 50%;
    background-color: white;
  }
</style>

<ol class="timeline">
  <li>MATLAB</li>
  <li>C</li>
  <li>C++</li>
  <li>Linux</li>
  <li>Python</li>
  <li><a href="/posts/html/">HTML</a></li>
  <li>CSS</li>
  <li>MySQL</li>
  <li>JavaScript</li>
  <li>React</li>
</ol>
