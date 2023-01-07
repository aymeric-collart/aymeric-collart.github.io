---
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---


<iframe src="/files/CV_AymericCollart_October2022.pdf" width="100%" height="500" frameborder="no" border="0" marginwidth="0" marginheight="0"></iframe>
The PDF copy of my CV can be downloaded [here](/files/CV_AymericCollart_October2022.pdf).



<section class="cd-timeline js-cd-timeline">
  <div class="container max-width-lg cd-timeline__container">
    <div class="cd-timeline__block">
      <div class="cd-timeline__img cd-timeline__img--picture">
        <img src="assets/img/cd-icon-picture.svg" alt="Picture">
      </div> <!-- cd-timeline__img -->

      <div class="cd-timeline__content text-component">
        <h2>Title of section 1</h2>
        <p class="color-contrast-medium">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, optio, dolorum provident rerum aut hic quasi placeat iure tempora laudantium ipsa ad debitis unde? Iste voluptatibus minus veritatis qui ut.</p>

        <div class="flex justify-between items-center">
          <span class="cd-timeline__date">Jan 14</span>
          <a href="#0" class="btn btn--subtle">Read more</a>
        </div>
      </div> <!-- cd-timeline__content -->
    </div> <!-- cd-timeline__block -->

    <div class="cd-timeline__block">
      <!-- ... -->
    </div> <!-- cd-timeline__block -->
  </div>
</section> <!-- cd-timeline -->

.cd-timeline {
  overflow: hidden;
  padding: var(--space-lg) 0;
}

.cd-timeline__container {
  position: relative;
  padding: var(--space-md) 0;

  &::before { // this is the timeline vertical line
    content: '';
    position: absolute;
    top: 0;
    left: 18px;
    height: 100%;
    width: 4px;
    background: var(--cd-color-2);
  }
}

.cd-timeline__block {
  display: flex;

  @include breakpoint(md) {
    &:nth-child(even) {
      flex-direction: row-reverse; // for even blocks -> lay out content from right to left
    }
  }
}

.cd-timeline__img {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-shrink: 0;

  @include breakpoint(md) {
      order: 1; // flex order -> place the image after cd-timeline__content
   }
}

.cd-timeline__content {
   flex-grow: 1; // expand element so that it takes up all the available space inside its parent

   @include breakpoint(md) {
      width: 45%;
      flex-grow: 0; // prevent element from growing inside its parent
   }
}

.cd-timeline {
  overflow: hidden;
  padding: var(--space-lg) 0;
}

.cd-timeline__container {
  position: relative;
  padding: var(--space-md) 0;

  &::before { // this is the timeline vertical line
    content: '';
    position: absolute;
    top: 0;
    left: 18px;
    height: 100%;
    width: 4px;
    background: var(--cd-color-2);
  }
}

function VerticalTimeline( element ) {
   this.element = element;
   this.blocks = this.element.getElementsByClassName("cd-timeline__block");
   this.images = this.element.getElementsByClassName("cd-timeline__img");
   this.contents = this.element.getElementsByClassName("cd-timeline__content");
   // ..
};

VerticalTimeline.prototype.showBlocks = function() {
   var self = this;
   for( var i = 0; i < this.blocks.length; i++) {
      (function(i){
         if( self.contents[i].classList.contains("cd-timeline__content--hidden") && self.blocks[i].getBoundingClientRect().top <= window.innerHeight*self.offset ) {
            // add bounce-in animation
            self.images[i].classList.add("cd-timeline__img--bounce-in");
            self.contents[i].classList.add("cd-timeline__content--bounce-in");
            self.images[i].classList.remove("cd-timeline__img--hidden");
            self.contents[i].classList.remove("cd-timeline__content--hidden");
         }
      })(i);
   }
};