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
  line-height: 1.2;
  font-weight: 900;
  font-size: 2.5rem; /* Fixed size */
  margin-bottom: 1.8rem;
  display: block; /* Prevents layout shift */
}

.background-image {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
  z-index: 1; /* Behind content */
  opacity: 1;
}

.content-wrapper {
  position: relative;
  z-index: 1;
  padding: 3rem;
  width: 100%;
  height: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
}

.next-button {
  margin-top: 0rem;
  padding: 0.4rem 0.4rem;
  background-color: rgba(3, 80, 105, 0.8);
  color: white !important;
  border-radius: 4px;
  transition: all 0.3s ease;
  /* width: fit-content; */
  font-size: 0.5rem;
  margin: 0 auto;
  cursor: pointer;
}

.next-button:hover {
  background-color: rgb(3, 80, 105);
  transform: translateX(4px);
}

.author-name {
  display: flex;
  align-items: center;
  gap: 0.11rem;
  color: white;
  font-size: 0.5rem;
  
}
</style>

<img src="./images/whitebg.png" class="background-image">

<div class="content-wrapper">
  <h1 class="gradient-text">Basics of Antimicrobial Stewardship in Hospitals</h1>
  
  <div @click="$slidev.nav.next" class="next-button">
    <span class="author-name italic">Ugwuja Anthony C.<carbon:arrow-right /></span>
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


<!-- <img width="313" alt="Screenshot 2025-05-07 at 18 31 17" src="https://github.com/user-attachments/assets/166f3f4a-3ac3-4066-a014-54eced5482b7" /> -->


<!-- <img width="928" alt="Screenshot 2025-05-07 at 18 30 22" src="https://github.com/user-attachments/assets/35a14aa9-e250-4947-aaa7-33dce06a48f4" /> -->

