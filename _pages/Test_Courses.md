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
  font-size: 15px;
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
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>
</head>
<body>

<h2>Animated Collapsibles</h2>

<p>A Collapsible:</p>
<button class="collapsible">Open Collapsible</button>
<div class="content">
<p> Abstract </p>
  <p>The verb you ‘to have’ in standard Mandarin is typically followed by a noun. You can also take a VP as its complement (‘you + VP’) in several varieties of Mandarin. However, the function associated with it is still under debate: ‘you + VP’ has been analyzed as expressing past tense, perfective aspect, perfect aspect, or realis mood. This paper assesses these analyses by conducting a corpus-based investigation of ‘you + VP’ on the PTT platform and by looking at different morphosyntactic environments in which it is used. The data favor analyzing ‘you + VP’ as expressing an assertive modality meaning (the situation is considered true in the real world by the speaker). This analysis corroborates with the high frequency of ‘you + VP’ in assertive environments (e.g., after factual verbs in embedded clauses, with attitudinal adverbs of truth value, among others). Conversely, taking ‘you + VP’ as indicating past tense or perfective aspect is challenged by the present data, and the perfect aspect analysis cannot explain all the environments in which ‘you + VP’ is used. This paper provides new insights regarding the morphosyntactic use of ‘you + VP’ and sheds light on the meaning this construction encodes.</p>
</div>

<p>Collapsible Set:</p>
<button class="collapsible">Open Section 1</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button class="collapsible">Open Section 2</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>
<button class="collapsible">Open Section 3</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
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