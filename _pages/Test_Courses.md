---
permalink: /test_courses/
title: "Tests"
---

This is where the courses I teach will be listed.

<style>
.dropbtn {
  color: white;
  padding: 16px;
  font-size: 16px;
  border: none;
  cursor: pointer;
}

.dropbtn:hover, .dropbtn:focus {
  background-color: #2980B9;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  overflow: auto;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
  transition: 3s ease-out;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  transition: 3s ease-out;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}

</style>

<div class="dropdown">
  <button onclick="myFunction()" class="dropbtn">Expressing the existence of an event with ‘you (to have) + VP’ in Taiwan Mandarin: A corpus-based investigation. (Collart & Su, 2022)</button>
  <div id="myDropdown" class="dropdown-content">
    <p>The verb you ‘to have’ in standard Mandarin is typically followed by a noun. You can also take a VP as its complement (‘you + VP’) in several varieties of Mandarin. However, the function associated with it is still under debate: ‘you + VP’ has been analyzed as expressing past tense, perfective aspect, perfect aspect, or realis mood. This paper assesses these analyses by conducting a corpus-based investigation of ‘you + VP’ on the PTT platform and by looking at different morphosyntactic environments in which it is used. The data favor analyzing ‘you + VP’ as expressing an assertive modality meaning (the situation is considered true in the real world by the speaker). This analysis corroborates with the high frequency of ‘you + VP’ in assertive environments (e.g., after factual verbs in embedded clauses, with attitudinal adverbs of truth value, among others). Conversely, taking ‘you + VP’ as indicating past tense or perfective aspect is challenged by the present data, and the perfect aspect analysis cannot explain all the environments in which ‘you + VP’ is used. This paper provides new insights regarding the morphosyntactic use of ‘you + VP’ and sheds light on the meaning this construction encodes.</p>
    <a href="https://doi.org/10.1075/consl.21046.col" target="_blank">Link to the article</a>
  </div>
</div>

And a lot of text to add here as well.

<script>
function myFunction() {
  document.getElementById("myDropdown").classList.toggle("show");
}

// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>