---
title: "Courses"
permalink: /courses/
author_profile: true
---

Page with the courses I intend to teach.

<style>

div.gallery {
  border: 1px solid #ccc;
}

div.gallery:hover {
  border: 1px solid #777;
}

div.gallery img {
  width: 100%;
  height: auto;
}

div.desc {
  padding: 12px;
  text-align: center;
}

* {
  box-sizing: border-box;
}

.container {
  display: grid; 
  grid-auto-rows: 1fr; 
  grid-template-columns: 32% 32% 32%; 
  grid-template-rows: auto auto auto; 
  gap: 15px 15px; 
  grid-template-areas: 
    "Course1
	Course2
	Course3"; 
  justify-content: center; 
  justify-items: stretch; 
  align-items: stretch; 
}

</style>



<div class="container">
<div class="Course1">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/courses/1-Course1/">
      <img src="./../images/Book_chapter.jpg" width="200" height="200">
    </a>
    <div class="desc">
<b>Course 1</b></div>
  </div>
</div>

<div class="Course2">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/courses/2-Course2">
      <img src="./../images/Book_chapter.jpg" width="250" height="250">
    </a>
    <div class="desc"><b>Course 2</b></div>
  </div>
</div>

<div class="Course3">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/courses/3-Course3/">
      <img src="./../images/Book_chapter.jpg" width="200" height="200">
    </a>
    <div class="desc"><b>Course 3</b></div>
  </div>
</div>