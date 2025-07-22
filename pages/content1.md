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

## [Antimicrobial Resistance]{.gradient-heading}

<v-clicks>

- **Antimicrobial Resistance (AMR)** occurs when bacteria, viruses, fungi and parasites no longer respond to antimicrobial medicines (WHO).
<br>
- **1.27 million deaths** directly attributed to drug-resistant infections in 2019; **~5 million deaths** associated overall (Murray et al., 2022).
<br>
- In **Nigeria alone**, ≈263,000 AMR-related deaths in 2019 surpassing malaria and respiratory infections locally (Murray et al., 2022).
<br>
- **Why does it matter?**

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
class: px-6
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
  font-size: 2rem;
  margin-bottom: 0;
}

.driver-card h2 {
  color: rgb(9, 131, 172); /* Theme color */
  font-weight: 600;
  font-size: 1.5rem;
  margin: 0.2rem 0;
}

.driver-card p {
  font-size: 1.1rem;
  line-height: 1.8;
  font-weight: 500;
  opacity: 0.9;
}

.emoji-icon {
  font-size: 1.5rem;
  margin-bottom: 0.2rem;
}
</style>

<div class="mt-2 grid grid-cols-2 gap-2 h-full">
  <!-- Upper Left -->
  <div class="driver-card p-3 rounded-lg">
    <v-click>
      <div class="emoji-icon">⚖️</div>
      <h2>Overuse & Misuse</h2>
      <p>~30% of hospital antimicrobial prescriptions are unnecessary, fueling resistance and C. difficile infections (CDC, 2019).</p>
    </v-click>
  </div>

  <!-- Upper Right -->
  <div class="driver-card p-5 rounded-lg">
    <v-click at="2">
      <div class="emoji-icon">🐄</div>
      <h2>Agricultural Use</h2>
      <p>70% of global antibiotic consumption is in livestock for growth promotion and disease prevention (O’Neill Review, 2016).</p>
    </v-click>
  </div>

  <!-- Lower Left -->
  <div class="driver-card p-5 rounded-lg">
    <v-click at="3">
      <div class="emoji-icon">🏥</div>
      <h2>Infection Control</h2>
      <p>Inadequate hand hygiene, environmental cleaning, and isolation allow resistant organisms to spread in hospitals (WHO, 2021).</p>
    </v-click>
  </div>

  <!-- Lower Right -->
  <div class="driver-card p-5 rounded-lg">
    <v-click at="4">
      <div class="emoji-icon">💊</div>
      <h2>Innovation Gap</h2>
      <p>Insufficient development of novel antimicrobials; resistance outpaces new drug approvals (WHO, 2021)</p>
    </v-click>
  </div>
</div>