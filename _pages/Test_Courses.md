---
permalink: /test_courses/
title: "Tests"
---

This is where the courses I teach will be listed.

<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  border-radius: 4px
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
  transform: translateY(-50%);
}

.active:after {
  content: "\2212";
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.4s ease-out;
  background-color: #eeeeee;
  color: #e06666;
  border-left: solid #bcbcbc 4px;
  border-radius: 4px;
  padding:0.7em;
  font-size: 18px;
  margin-left:1em;
}
</style>



NEW

<body>
<button class="collapsible">News!</button>
<div class="content">

<p><b>New! (2024/03/31)</b><br>The abstract "<i>Existing in the future depends on who you are and what you do: Acceptability judgments of ‘you (to have) + VP’ in Taiwan Mandarin</i>" has been accepted for an oral presentation at the The Japanese Society for Language Sciences 25th Annual International Conference!<br>
</p>
<p><b>New! (2024/04/06)</b><br>The manuscript entitled "A decade of language processing research: Which place for linguistic diversity?" has been accepted for publication in <i>Glossa Psycholinguistics</i>!
</p>
<p><b>New! (2024/05/09)</b><br>The manuscript entitled "It costs to exist: Acceptability judgments of the temporal concord of the auxiliary verbs <i>you</i> and <i>hui</i> in Taiwan Mandarin" is now available online in <i>Journal of Psycholinguistic Research</i> <a href="https://doi.org/10.1007/s10936-024-10086-5" target="_blank">here</a>!
</p>

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
</body>

Old
<div style='background-color:#eeeeee; color: #e06666; border-left: solid #bcbcbc 4px; border-radius: 4px; padding:0.7em;'>
<div style='margin-left:1em;'><b>New! (2024/03/31)</b><br>The abstract "<i>Existing in the future depends on who you are and what you do: Acceptability judgments of ‘you (to have) + VP’ in Taiwan Mandarin</i>" has been accepted for an oral presentation at the The Japanese Society for Language Sciences 25th Annual International Conference!<br>
</div>
<div style='margin-left:1em;margin-top:1em'><b>New! (2024/04/06)</b><br>The manuscript entitled "A decade of language processing research: Which place for linguistic diversity?" has been accepted for publication in <i>Glossa Psycholinguistics</i>!
</div>
<div style='margin-left:1em;margin-top:1em'><b>New! (2024/05/09)</b><br>The manuscript entitled "It costs to exist: Acceptability judgments of the temporal concord of the auxiliary verbs <i>you</i> and <i>hui</i> in Taiwan Mandarin" is now available online in <i>Journal of Psycholinguistic Research</i> <a href="https://doi.org/10.1007/s10936-024-10086-5" target="_blank">here</a>!
</div>
</div>





