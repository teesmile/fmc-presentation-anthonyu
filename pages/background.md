---
layout: center
class: px-8 py-6 text-center
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Team Members]{.gradient-heading}

<div class="flex flex-col items-center space-y-4 mt-4">

<!-- Row 1 (2 members) -->
<div class="flex justify-center space-x-8">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍⚕️</div>
    <div class="font-bold">Pharm. Mrs.<br> Bara'atu</div>
    <div class="text-sm text-gray-600">Supervisor</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍💻</div>
    <div class="font-bold">Pharm. Anthony</div>
    <div class="text-sm text-gray-600">Presenter</div>
  </div>
</div>

<!-- Row 2 (3 members) -->
<div class="flex justify-center space-x-8">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🔬</div>
    <div class="font-bold">Pharm Mrs.<br> Nenzarmwa</div>
    <div class="text-sm text-gray-600">Microbiology</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🏫</div>
    <div class="font-bold">Dr. F. Bello</div>
    <div class="text-sm text-gray-600">Pharmacist</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍🔬</div>
    <div class="font-bold">Dr. I. Yusuf</div>
    <div class="text-sm text-gray-600">Data Analyst</div>
  </div>
</div>

<!-- Row 3 (4 members) -->
<div class="flex justify-center space-x-6">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍💻</div>
    <div class="font-bold">Nurse G. Okafor</div>
    <div class="text-sm text-gray-600">Infection Control</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍💻</div>
    <div class="font-bold">Dr. E. Nwachukwu</div>
    <div class="text-sm text-gray-600">Administrator</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🏫</div>
    <div class="font-bold">Dr. Z. Abdul</div>
    <div class="text-sm text-gray-600">Education</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍🏫</div>
    <div class="font-bold">Dr. O. Adeleke</div>
    <div class="text-sm text-gray-600">Quality Assurance</div>
  </div>
</div>

</div>

---
layout: center
class: px-10 py-6
background: linear-gradient(-45deg, rgba(11, 104, 134, 0.08), rgba(9, 131, 172, 0.08))
---

<style>
.toc-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
  font-size: 2.8rem;
  margin-bottom: 1.5rem;
}

.toc-container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.5rem;
  width: 90%;
}

.toc-item {
  font-size: 1.1rem;
  margin-bottom: 0.8rem;
  position: relative;
  padding-left: 1.5rem;
  cursor: pointer;
  transition: all 0.2s ease;
}

.toc-item:hover {
  color: rgb(11, 104, 134);
  transform: translateX(3px);
}

.toc-item::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0.5rem;
  width: 0.6rem;
  height: 0.6rem;
  background: rgb(9, 131, 172);
  border-radius: 50%;
  transition: all 0.2s ease;
}

.toc-item:hover::before {
  background: rgb(11, 104, 134);
  transform: scale(1.2);
}

.toc-divider {
  border-left: 2px solid rgba(9, 131, 172, 0.3);
  height: 1.2rem;
  margin: 0.3rem 0 0.3rem 0.8rem;
}
</style>

<CircleShape position="top:15%; left:-5%; size:60px; color:rgba(3, 80, 105, 0.4)" />
<PillShape position="bottom:2%; right:2%; width:8%; height:16px; color:rgba(33,150,243,0.06)" />

# [Contents]{.toc-heading}

<div class="toc-container">

<!-- Left Column -->
<div>
<div class="toc-item" @click="$slidev.nav.go(2)">1. Team Members</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(4)">2. Introduction</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(7)">3. Principles of Antimicrobial Stewardship</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(5)">4. Nigeria Statistics</div>
</div>

<!-- Right Column -->
<div>
<div class="toc-item" @click="$slidev.nav.go(6)">5. Front-End Strategies</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(7)">6. Back-End Approaches</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(8)">7. Implementation Barriers</div>
<div class="toc-divider"></div>
<div class="toc-item" @click="$slidev.nav.go(9)">8. Case Studies</div>
</div>

</div>

---
layout: center
transition: fade-out
setup: |
  import DecoratedLayout from './components/DecoratedLayout.vue'
  import CircleShape from './components/CircleShape.vue'
  import PillShape from './components/PillShape.vue'
---

# [INTRODUCTION ]{.gradient-text}

<style>
    .gradient-text {
     background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
      font-size: 2em; 
    }
</style>


---
layout: center
class: px-10 py-8
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
text: white
---



<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<div class="space-y-8 text-lg">

<v-clicks>

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<h2 class="text-2xl font-bold mb-4" style="color: rgb(11, 104, 134);">What is Antimicrobial?</h2>
<p style="font-size: 1.5rem; line-height: 2;">Antimicrobials are agents that either kill microorganisms (biocidal effect) or inhibit their growth (biostatic effect).</p>
</div>


</v-clicks>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
p {
  margin-bottom: 1rem;
}
</style>

---
layout: default
class: px-8 py-6
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style>
/* Enhanced heading */
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 2.5rem;
  margin: 0 0 1.5rem 0;
  line-height: 1.3;
}

/* Bullet list container */
ul {
  list-style: none;
  padding-left: 0;
  margin: 0;
  font-size: 1.4rem;
  line-height: 1.6;
}

/* Bullet points */
li {
  position: relative;
  padding-left: 1.75rem;
  margin-bottom: 1rem;
}

li::before {
  content: "•";
  color: rgb(9, 131, 172); /* Your theme color */
  font-size: 1.8rem;
  position: absolute;
  left: 0;
  top: -0.1rem;
}

/* Slide content container */
.slidev-page {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
}

/* Text emphasis */
strong {
  font-weight: 600;
}
</style>

## [Antimicrobial Resistance (AMR)]{.gradient-heading}

<v-clicks>

- **Antimicrobial Resistance (AMR)** occurs when bacteria, viruses, fungi and parasites no longer respond to antimicrobial medicines (WHO).
<br>
- **1.27 million deaths** directly attributed to drug-resistant infections in 2019; **~5 million deaths** associated overall (Murray et al., 2022).
<br>
- In **Nigeria alone**, ≈263,000 AMR-related deaths in 2019 surpassing malaria and respiratory infections locally (Murray et al., 2022).
<br>


</v-clicks>

---
layout: default
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

## [Resistance Mechanisms]{.gradient-heading}

<v-clicks>

<div class="w-[84%] ml-[6%]">
    <img 
      src="/images/AMRmech.png" 
      class="w-full h-auto" 
      style="mix-blend-mode: multiply; filter: drop-shadow(0 2px 8px rgba(0,0,0,0.1))"
    >
  </div>

</v-clicks>

<style>
  img {
  image-rendering: -webkit-optimize-contrast;
  image-rendering: crisp-edges;
}
</style>

---
layout: default
class: px-6 py-8
---

## [Key Drivers of AMR]{.gradient-heading}

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 3rem;
  margin-bottom: 1rem;
}

.driver-container {
  display: flex;
  flex-direction: column;
  height: 50vh;
}

.driver-row {
  display: flex;
  flex: 1;
  gap: 0.1rem;
}

.driver-card {
  flex: 1;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;
  padding: 1rem;
}

.driver-card h2 {
  color: rgb(9, 131, 172);
  font-weight: 600;
  font-size: 1.8rem;
  text-align: center;
  margin: 0.5rem 0;
}

.emoji-icon {
  font-size: 2.5rem;
  margin-bottom: 0.5rem;
}
</style>

<div class="driver-container">
  <!-- Top Row -->
  <div class="driver-row">
    <!-- Upper Left -->
    <div class="driver-card">
      <v-click>
        <div class="emoji-icon">⚖️</div>
        <h2>Overuse & Misuse</h2>
        <!-- <p>~30% of hospital antimicrobial prescriptions are unnecessary, fueling resistance and C. difficile infections (CDC, 2019).</p> -->
      </v-click>
    </div>

    
   <div class="driver-card">
      <v-click at="2">
        <div class="emoji-icon">🐄</div>
        <h2>Agricultural Use</h2>
        <!-- <p>70% of global antibiotic consumption is in livestock for growth promotion and disease prevention (O'Neill Review, 2016).</p> -->
      </v-click>
    </div>
  </div>


  <div class="driver-row">
 
  <div class="driver-card">
      <v-click at="3">
        <div class="emoji-icon">🏥</div>
        <h2>Infection Control</h2>
        <!-- <p>Inadequate hand hygiene, environmental cleaning, and isolation allow resistant organisms to spread in hospitals (WHO, 2021).</p> -->
      </v-click>
    </div>

    
  <div class="driver-card">
      <v-click at="4">
        <div class="emoji-icon">💊</div>
        <h2>Innovation Gap</h2>
        <!-- <p>Insufficient development of novel antimicrobials; resistance outpaces new drug approvals (WHO, 2021)</p> -->
      </v-click>
    </div>
  </div>
</div>


---
layout: center
transition: fade-out
class: flex items-center
---

<div class="w-full flex justify-center items-center gap-1">
  <!-- Text Content -->
  <div class="text-center">
    <h1 class="gradient-text mb-2">What is Antimicrobial Stewardship (AMS)?</h1>
  </div>
  
  <!-- Image Container -->
  <div class="w-[25%]">
    <img 
      src="/images/question.png" 
      class="w-full h-auto" 
      style="mix-blend-mode: multiply; filter: drop-shadow(0 2px 8px rgba(0,0,0,0.1))"
    >
  </div>
</div>


<style>
.gradient-text {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
  font-size: 2.5em;
  line-height:1.2;
  font-weight: 900;
}

/* Remove white edges from transparent PNG */
img {
  image-rendering: -webkit-optimize-contrast;
  image-rendering: crisp-edges;
}
</style>

---
layout: center
class: px-10 py-8
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
text: white
---



<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<div class="space-y-8 text-lg">

<v-clicks>

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<h2 class="text-2xl font-bold mb-4" style="color: rgb(11, 104, 134);">Antimicrobial Stewardship (AMS)</h2>
<p style="font-size: 1.5rem; line-height: 2;">Antimicrobial stewardship (AMS) is a coordinated program that seeks to promote appropriate use of all anti-microbials, including antibiotics, antivirals, and antifungals.</p>
</div>

</v-clicks>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
p {
  margin-bottom: 1rem;
}
</style>

---
layout: center
class: px-10 py-2
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
text: white
---


<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Principles of Antimicrobial Stewardship]{.gradient-heading}

<br>

<div class="grid grid-cols-2 gap-6 mt-4" style="font-size: 1.2rem;">

<!-- Column 1 -->
<div class="space-y-6">
<div v-click="1" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(11, 104, 134);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Appropriate Use of Antimicrobials</h3>
  
</div>

<div v-click="3" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(9, 131, 172);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Policy and Guideline Development</h3>
  
</div>

<div v-click="5" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(70, 160, 180);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Multidisciplinary Collaboration</h3>
  
</div>
</div>

<!-- Column 2 -->
<div class="space-y-6">
<div v-click="2" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(9, 131, 172);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Education and Awareness</h3>
  
</div>

<div v-click="4" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(70, 160, 180);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Audit and Feedback Mechanisms</h3>

</div>

<div v-click="6" class="p-5 rounded-lg border-l-4 cursor-pointer hover:bg-opacity-20 transition-all" 
     style="background-color: rgba(255,255,255,0.1); border-left-color: rgb(11, 104, 134);">
  <h3 class="font-bold mb-2" style="color: rgb(11, 60, 90);">Surveillance and Monitoring</h3>
 
</div>
</div>

</div>

<style>
.slidev-vclick-target {
  transition: opacity 400ms ease;
}
.slidev-vclick-hidden {
  opacity: 0;
  pointer-events: none;
}
</style>

---
layout: two-column
class: px-10 py-8
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<!-- Left Column - Text Content -->

<div class="col-left" style="width: 50%; padding-right: 2rem;">

## [Why AMS Matters in the Hospitals]{.gradient-heading}

<v-clicks>

- **4.95 million deaths/year** globally linked to Antimicrobial Resistance (AMR) (Lancet 2022)
- **50–70% of hospitalized patients** receive antimicrobials (WHO)
- Increasing local AMR rates leading to **hard‑to‑treat infections**
- **Resource constraints**: ICU beds, lab diagnostics
- **Economic pressure**: Costs of last‑line drugs and extended stays
- Alignment with **Nigeria's AMR National Action Plan 2024–2028**

</v-clicks>
</div>



<!-- Right Column - Image -->
<div class="flex items-center justify-center">
  <img src="/images/stats.png" class="w-full h-auto object-contain rounded-lg">
</div>



<style>
.col-left {
  float: left;
}
.col-right {
  float: right;
}
.two-columns {
  display: flex;
  gap: 2rem;
}
.slidev-vclick-target {
  transition: opacity 400ms ease;
}
.slidev-vclick-hidden {
  opacity: 0;
  pointer-events: none;
}
ul {
  margin-top: 1rem;
  line-height: 1.6;
}
li {
  padding-left: 0.5rem;
}
</style>

