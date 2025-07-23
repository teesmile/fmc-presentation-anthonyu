---
theme: seriph

fonts:
  # basically the text
    sans: Robot
  # default
    weights: '400,600,800'
  # import italic fonts, default `false`
    italic: true
  # use with `font-serif` css class from UnoCSS
 

  
background: "#ffffff"  
title: Basics of Antimicrobial Stewardship in Hospitals
description: Slide Presentation on Antimicrobial Stewardship Practice in hospital settings
image: https://raw.githubusercontent.com/teesmile/fmc-presentation-anthonyu/master/images/newcover.png
info: |
  ## Pharmacist Interns Presentation.
class: text-center
drawings:
  persist: false
transition: slide-left
mdc: true
setup: |
  import DecoratedLayout from './components/DecoratedLayout.vue'
  <!-- Add shape components -->
  import CircleShape from './components/CircleShape.vue'
  import PillShape from './components/PillShape.vue'
head: |

  <style>
    /* Global Arial font with 700 weight */
    body, .slidev-layout {
      font-family: Arial, sans-serif !important;
      font-weight: 600 !important;
    }
    
    /* Override for specific elements */
    h1 {
      font-weight: 800 !important; /* Extra bold for headings */
    }
    .author-name {
      font-weight: 600 !important;
    }
  </style>
---
<style>
.gradient-text {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  line-height:1.2;
  font-weight: 900;
}

.background-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover; /* Ensures full coverage */
  z-index: 0;
  opacity: 1;
}

.content-wrapper {
  position: relative;
  z-index: 0;
  padding: 2rem;
  border-radius: 8px;
  display: inline-block;
  margin-top: 0%;
  transform: translateY(-30px);
}

.next-button {
  margin-top: 1.2rem;
  display: inline-block;

  padding: 0.5rem 0.5rem;
  background-color: rgba(3, 80, 105, 0.8);
  color: white !important;
  border-radius: 2px;
  transition: all 0.3s ease;
  
}
.author-name {
  color: #666;
  font-size: 0.75rem;
  font-style: italic;
}

.next-button:hover {
  background-color: rgb(3, 80, 105);
}
</style>

<!-- Full-size background image -->

<img src="./images/whitebg.png" class="background-image">

<!-- Content container -->
<div class="content-wrapper">

  # [Basics of Antimicrobial Stewardship in Hospitals]{.gradient-text}

<div @click="$slidev.nav.next" class="author-name next-button">
   Ugwuja Anthony C.  <carbon:arrow-right />
  </div>
</div>

<!-- Slides for background -->
---
src: ./pages/background.md
---

---
src: /pages/content1.md
---

---
src: ./pages/content2.md
---

<!-- Slides for month1 week4 -->

---
src: ./pages/content3.md
---

<!-- Slides for month2 week1 -->

---
src: ./pages/content4.md
---

---
src: ./pages/content5.md
---

<!-- Slides for month2 week3 -->

---
src: ./pages/content6.md


<!-- Slides for month2 week4 -->

<!-- ---
src: ./pages/mth2-wk4.md
--- -->

<!-- Slides for extra class week1 -->

<!-- ---
src: ./pages/extra-class1.md
--- -->

<!-- Slides for extra class week1 -->

<!-- ---
src: ./pages/extra-class2.md
--- -->


---
layout: center
transition: fade-out
class: flex items-center
---

# [Thanks For Listening!]{.gradient-text}

Questions and Discussions

<!-- CSS styling for .gradient-text class -->
<style>
    .gradient-text {
       background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
      font-size: 2em; 
      margin: 0;
      text-align: center;
    }
   
</style>



<!-- <img width="313" alt="Screenshot 2025-05-07 at 18 31 17" src="https://github.com/user-attachments/assets/166f3f4a-3ac3-4066-a014-54eced5482b7" /> -->


<!-- <img width="928" alt="Screenshot 2025-05-07 at 18 30 22" src="https://github.com/user-attachments/assets/35a14aa9-e250-4947-aaa7-33dce06a48f4" /> -->

