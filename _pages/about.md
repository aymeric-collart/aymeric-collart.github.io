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
<p><b>Important news!</b><br>We are organizing the "<i>The 2025 conference on the Mosaic of East Asian Language Processing:
Exploring Taiwan's diversity and beyond</i>". More information on the website of the conference <a href="https://sites.google.com/view/mealp-2025/home" target="_blank">here</a>!
<br>
<p><b>2024/06/25</b><br>The manuscript entitled "A decade of language processing research: Which place for linguistic diversity?" is now available online in <i>Glossa Psycholinguistics</i> <a href="https://doi.org/10.5070/G60111432" target="_blank">here</a>!
</p>
<p><b>2024/05/09</b><br>The manuscript entitled "It costs to exist: Acceptability judgments of the temporal concord of the auxiliary verbs <i>you</i> and <i>hui</i> in Taiwan Mandarin" is now available online in <i>Journal of Psycholinguistic Research</i> <a href="https://doi.org/10.1007/s10936-024-10086-5" target="_blank">here</a>!
</p>
<p><b>Upcoming presentation(s)</b></p>
<p>
- <b>2025/04/17-19</b>: "<i>¡¥Computer or smartphone, as you please¡¦: On the device effect in web-based acceptability judgment experiments</i>", poster presentation at the 5th International Conference on Theoretical East Asian Psycholinguistics (ICTEAP-5), Tokyo, Japan
<br>
- <b>2025/05/07-09</b>: "<i>In the clouds and on the ground: Taiwan as a laboratory to expand the typological pool of psycholinguistic research</i>", oral presentation at the Linguistic data and language comparison in light of the ¡¥quantitative turn¡¦ and ¡¥big data¡¦ ¡V a workshop and symposium, Bern, Switzerland
<br>
- <b>2025/05/12-14</b>: "<i>A tale of the lab and the field: An opportunity for Formosan language research</i>", oral presentation at the 5th World Congress of Taiwan Studies (Taiwan in a changing world: Past, present, and future), Taipei, Taiwan
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

I am currently a postdoctoral researcher at the Institute of Linguistics of Academia Sinica, Taiwan. I am working on my own 2-year project entitled "Paving the way for 'field psycholinguistics' of Formosan languages: Case studies in Truku Seediq, Bunun and Tsou", with a grant from the Academia Sinica postdoctoral scholar program. 
<br>
Previously, I worked on another 2-year postdoctoral project (2022-2024), "On the expression of temporal reference with modal information from a morphosyntactic and psycho-/neuro-linguistic perspective: The case of '<i>you</i> (to have) + VP' in Taiwan Mandarin", where I examined this grammatical construction in the variety of Mandarin spoken in Taiwan using a wide range of techniques: corpus-driven observations, morphosyntactic/semantic/discursive analyses, behavioral methods (acceptability judgments, self-paced reading), neuroimaging methods (EEG/ERP).
<br>
I graduated from the PhD program of the department of English of National Taiwan Normal University (Linguistic track) in June 2022. During my PhD studies, I was also the manager of the <a href="https://sites.google.com/view/neurolinguisticslabntnu" target="_blank">Neurolinguistics Lab</a> of National Taiwan Normal University, where I supervized behavioral, ERP and fMRI experiments about a great variety of language-related topics, such as language relativity, classifier processing or conceptual categorization.

### Research interests

My research interests combine two disciplines: linguistics and cognitive science (including language processing). My main area of research can be summarized as follows:
<br>
<center>
<img src="https://aymeric-collart.github.io/images/GeneralResearch.jpg" alt="drawing" width="75%"/>
</center>
<br>
* On the linguistic side, I am interested in the syntax and semantics of the expression of time reference from a functional syntax and user-based perspective. Particularly, I aim at understanding how temporal relations are expressed with grammatical markers in tenseless languages, with a focus on Mandarin Chinese (and its variety spoken in Taiwan).
* On the cognitive science side, I have mainly worked in sentence processing using psycholinguistic and neurolinguistic techniques with a focus on the processing of temporality (tense, aspect, mood and modality) in grammar. 

I aim at bridging linguistic analyses with their brain processing patterns in order to establish a neurolinguistic and crosslinguistic model of the processing of temporality at the sentence level. Although I have mainly focused on Mandarin Chinese so far, I wish to expand my research to other languages, especially languages which are underrepresented in the language processing domain.

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
<font size="1">Last update: 2025/01/15</font>
