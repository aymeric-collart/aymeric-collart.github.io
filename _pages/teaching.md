---
permalink: /teaching/
title: "Teaching"
---


------

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
  float: left;
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
  grid-auto-rows: 1fr 1fr 1fr; 
  grid-template-columns: auto; 
  grid-template-rows: auto; 
  gap: 45px; 
  grid-template-areas: 
    "Course1 Course2 Course3"; 
  justify-content: center; 
  justify-items: stretch; 
  align-items: stretch; 
}

.collapsible {
background-color: #777;
color: white;
cursor: pointer;
padding: 18px;
width: 100%;
border: none;
text-align: left;
outline: none;
border-radius: 4px;
font-size: 22px;
}

.active, .collapsible:hover {
background-color: #555;
}

.collapsible:after {
content: '\002B';
color: white;
font-weight: bold;
float: right;
margin-left: 5px;
}

.active:after {
content: "\2212";
}

.content {
padding: 0 18px;
max-height: 0;
overflow: hidden;
transition: max-height 0.4s ease-out;
background-color: #ffffff;
color: #000000;
border-left: solid #777 4px;
border-radius: 4px;
font-size: 18px;
}

</style>

## Academic year 2025-2026

<body>
<button class="collapsible"><b>Fall semester</b></button>
<div class="content">
<br>

<div class="container">
<div class="Course1">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/CHU0387">
      <img src="./../images/Project3.png" width="200" height="200">
    </a>
    <div class="desc">
<b>CHU0387 - Language, Society and Literature with Corpus and Modern Technology</b></div>
  </div>
</div>

<div class="Course2">
  <div class="gallery">
    <a target="_blank" href="https://moodle3.ntnu.edu.tw/course/view.php?id=52328">
      <img src="./../images/Project3.png" width="250" height="250">
    </a>
    <div class="desc"><b>CHU0386 - Language, Culture and Cognition (only Moodle)</b></div>
  </div>
</div>

<div class="Course3">
  <div class="gallery">
    <a target="_blank" href="https://moodle3.ntnu.edu.tw/course/view.php?id=52327">
      <img src="./../images/Project3.png" width="250" height="250">
    </a>
    <div class="desc"><b>CHU0385 - First Approach to Linguistics (only Moodle)</b></div>
  </div>
</div>
</body>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
coll[i].addEventListener("click", function() {
this.classList.toggle("active");
var content = this.nextElementSibling;
if (content.style.maxHeight){
content.style.maxHeight = null;
} else {
content.style.maxHeight = content.scrollHeight + "px";
} 
});
}
</script>
