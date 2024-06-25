---
permalink: /
title: "About"
excerpt: "Welcome to my personal academic website!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br>
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
  background-color: #eeeeee;
  color: #e06666;
  border-left: solid #777 4px;
  border-radius: 4px;
  font-size: 18px;
}
</style>

<body>
<button class="collapsible"><b>News</b></button>
<div class="content">
<br>
<p><b>2024/06/25</b><br>The manuscript entitled "A decade of language processing research: Which place for linguistic diversity?" is now available online in <i>Glossa Psycholinguistics</i> <a href="https://doi.org/10.5070/G60111432" target="_blank">here</a>!
</p>
<p><b>2024/05/09</b><br>The manuscript entitled "It costs to exist: Acceptability judgments of the temporal concord of the auxiliary verbs <i>you</i> and <i>hui</i> in Taiwan Mandarin" is now available online in <i>Journal of Psycholinguistic Research</i> <a href="https://doi.org/10.1007/s10936-024-10086-5" target="_blank">here</a>!
</p>
<p><b>Upcoming presentations</b></p>
<p>
- <b>2024/07/12-14</b>: "<i>Existing in the future depends on who you are and what you do: Acceptability judgments of ‘you (to have) + VP’ in Taiwan Mandarin</i>", oral presentation at the Japanese Society for Language Sciences 25th Annual International Conference, Shizuoka, Japan
<br>
- <b>2024/09/03-04</b>: "<i>Quantitative explorations of regional grammatical variations: The case of you ‘to have’ in Taiwan Mandarin</i>", poster presentation at the Crosslinguistic Perspectives on Processing and Learning Conference, Zurich, Switzerland
<br>
- <b>2024/09/05-07</b>: "<i>Judging past time reference across languages: A Competition Model perspective</i>", poster presentation at the 30th AMLaP Architectures and Mechanisms for Language Processing Conference, Edinburgh, Scotland
<br>
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

<br>

### Short bio

I am currently a postdoctoral researcher at the Institute of Linguistics of Academia Sinica, Taiwan. I work on my own project entitled "On the expression of temporal reference with modal information from a morphosyntactic and psycho-/neuro-linguistic perspective: The case of ‘<i>you</i> (to have) + VP’ in Taiwan Mandarin".

I graduated from the PhD program of the department of English of National Taiwan Normal University (Linguistic track). During my PhD studies, I was also the manager of the [Neurolinguistics Lab](https://sites.google.com/view/neurolinguisticslabntnu) of National Taiwan Normal University, where I supervized behavioral, ERP and fMRI experiments about a great variety of language-related topics, such as language relativity, classifier processing or conceptual categorization.

### Research interests

My research interests combine two disciplines: linguistics and language processing.

* On the linguistic side, I am interested in the syntax and semantics of the expression of TIME from a functional syntax and user-based perspective. Particularly, I aim at understanding how temporal relations are expressed with grammatical markers in Mandarin Chinese (and its variety spoken in Taiwan), which is said to be a tenseless language.
* On the psycholinguistic and neurolinguistic side, I have mainly worked in sentence processing with a focus on the processing of temporality (tense, aspect, modality) in grammar. 

I aim at bridging linguistic analyses with their brain processing patterns in order to establish a neurolinguistic and crosslinguistic model of the processing of temporality at the sentence level. Although I have mainly conducted my research on Mandarin Chinese, I also wish to expand my research to other languages, especially languages which are underrepresented in the language processing domain.

<br>
My research interests lie in the following  topics (click on the image for more details):


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
    "Project1 Project2 Project 3"; 
  justify-content: center; 
  justify-items: stretch; 
  align-items: stretch; 
}

</style>



<div class="container">
<div class="Project1">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/projects/1-Mandarin_Syntax_Semantics_Corpus_Experiments_Temporal/">
      <img src="./../images/Project1.png" width="200" height="200">
    </a>
    <div class="desc">
<b>Temporal reference in (Taiwan) Mandarin: Syntax and semantics, Corpus and experiments</b></div>
  </div>
</div>

<div class="Project2">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/projects/2-Crosslinguistic_Processing">
      <img src="./../images/Project2.png" width="250" height="250">
    </a>
    <div class="desc"><b>Crosslinguistic language processing: Linguistic and cognitive diversities of the mind</b></div>
  </div>
</div>

<div class="Project3">
  <div class="gallery">
    <a target="_blank" href="https://aymeric-collart.github.io/projects/3-Applied_language_processing/">
      <img src="./../images/Project3.png" width="200" height="200">
    </a>
    <div class="desc"><b>Applied language processing: Interpreting, and language learning and teaching</b></div>
  </div>
</div>

<br>
<font size="1">Last update: 2024/05/09</font>
