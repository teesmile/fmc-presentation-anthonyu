---
layout: center
transition: fade-out
class: flex items-center
---

<div class="w-full flex justify-center items-center gap-4">
  <!-- Text Content -->
  <div class="text-center">
    <h1 class="gradient-text mb-2">What is AMR?</h1>
  </div>
  
  <!-- Image Container -->
  <div class="w-[20%]">
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
layout: default
---
<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: bold;
  display: inline-block;
  font-size: 2rem;
  margin-bottom: 1.5rem;
}
</style>

## [Antimicrobial Resistance]{.gradient-heading}

<br>
<v-clicks>

- Antimicrobial Resistance (AMR) occurs when bacteria, viruses, fungi and parasites 

  no longer respond to antimicrobial medicines (WHO).

- 1.27 million deaths directly attributed to drug‑resistant infections in 2019; 
  
  ~5 million deaths associated overall (Murray et al., 2022).

- In Nigeria alone, ≈263,000 AMR‑related deaths in 2019 surpassing malaria and 

  respiratory infections locally (Murray et al., 2022).

- Why does it matter?

</v-clicks>

---
layout: default
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

## [Resistance Mechanisms]{.gradient-heading}

<v-clicks>

<div class="w-[90%]">
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
---

## [Key Drivers of AMR]{.gradient-heading}

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />


<div class="mt-3% grid grid-cols-2 gap-3 h-full">
  <!-- Upper Left -->
  <div class=" p-4 rounded-lg">
    <v-click>
      <div class="text-3xl">⚖️</div>
      <h2>Overuse & Misuse</h2>
      <p class="text-sm">~30% of hospital antimicrobial prescriptions are unnecessary, fueling resistance and C. difficile infections (CDC, 2019).</p>
    </v-click>
  </div>

  <!-- Upper Right -->
  <div class=" p-4 rounded-lg">
    <v-click at="2">
      <div class="text-3xl">🐄</div>
      <h2>Agricultural Use</h2>
      <p class="text-sm">70% of global antibiotic consumption is in livestock for growth promotion and disease prevention (O’Neill Review, 2016).</p>
    </v-click>
  </div>
  <!-- Lower Left -->
  <div class=" p-4 rounded-lg">
    <v-click at="3">
      <div class="text-3xl">🏥</div>
      <h2>Infection Control</h2>
      <p class="text-sm">Inadequate hand hygiene, environmental cleaning, and isolation allow resistant organisms to spread in hospitals (WHO, 2021).</p>
    </v-click>
  </div>

  <!-- Lower Right -->
  <div class=" p-4 rounded-lg">
    <v-click at="4">
      <div class="text-3xl">💊</div>
      <h2>Innovation Gap</h2>
      <p class="text-sm">Insufficient development of novel antimicrobials; resistance outpaces new drug approvals (WHO, 2021)
</p>
    </v-click>
  </div>
</div>

