---
layout: center
class: px-8 py-6 text-center
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Team Members]{.gradient-heading}

<div class="flex flex-col items-center space-y-4 mt-4">

<!-- Row 1 (2 members) -->
<div class="flex justify-center space-x-8">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍⚕️</div>
    <div class="font-bold">Pharm. Nenzarmwa Makan</div>
    <div class="text-sm text-gray-600">Preceptor</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍💻</div>
    <div class="font-bold">Pharm. Ugwuja Anthony</div>
    <div class="text-sm text-gray-600">Presenter</div>
  </div>
</div>

<!-- Row 2 (3 members) -->
<div class="flex justify-center space-x-8">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🔬</div>
    <div class="font-bold">Pharm. Bara'atu Junaidu</div>
    <div class="text-sm text-gray-600">Supervisor</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🏫</div>
    <div class="font-bold">Pharm. Abubakar Hussaini</div>
    <div class="text-sm text-gray-600">Supervisor</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍🔬</div>
    <div class="font-bold">Pharm. Rita Ohyoma</div>
    <div class="text-sm text-gray-600">Supervisor</div>
  </div>
</div>

<!-- Row 3 (4 members) -->
<div class="flex justify-center space-x-6">
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍💻</div>
    <div class="font-bold"> Pharm. Dapan Pankwat Livinus</div>
    <div class="text-sm text-gray-600">Member</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍💻</div>
    <div class="font-bold">Pharm. Ugwu Blessing</div>
    <div class="text-sm text-gray-600">Member</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👩‍🏫</div>
    <div class="font-bold">Pharm. Rabiat Abdulrazzaq</div>
    <div class="text-sm text-gray-600">Member</div>
  </div>
  
  <div class="flex flex-col items-center">
    <div class="w-15 h-15 rounded-lg bg-gray-200 mb-2 flex items-center justify-center text-3xl">👨‍🏫</div>
    <div class="font-bold">Pharm. Ugwu Stanley</div>
    <div class="text-sm text-gray-600">Member</div>
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
  font-size: 2rem;
  margin-bottom: 0.3rem;
  margin-top: 1rem;
}

.toc-container {
  display: grid;
  grid-template-columns: 2fr 2fr;
  gap: 0.8rem;
  width: 100%;
}

.toc-item {
  font-size: 0.9rem;
  margin-bottom: 0.2rem;
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
  height: 0.1rem;
  margin: 0.2rem 0 0.2rem 0.8rem;
}
</style>

<CircleShape position="top:15%; left:-5%; size:60px; color:rgba(3, 80, 105, 0.4)" />
<PillShape position="bottom:-5%; right:-10%; width:8%; height:16px; color:rgba(33,150,243,0.06)" />

# [Table of Contents]{.toc-heading}

<div class="toc-container">

<!-- Left Column (10 items) -->
<div>
  <div class="toc-item" @click="$slidev.nav.go(2)">1. Team members</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(4)">2. Introduction</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(5)">3. Antimicrobial definition</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(6)">4. Major resistant organisms</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(8)">5. What is Antimicrobial Stewardship (AMS)?</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(10)">6. Antimicrobial resistance (AMR)</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(13)">7. Principles of AMS</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(15)">8. Antimicrobial stewardship programs (ASPs) evolution</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(18)">9. WHO AWaRe Classification</div>
  <div class="toc-divider"></div>
   <div class="toc-item" @click="$slidev.nav.go(19)">10. AMS Techniques</div>
</div>

<!-- Right Column (10 items) -->
<div>
<div class="toc-item" @click="$slidev.nav.go(20)">10.a Front-end interventions</div>
  <div class="toc-divider"></div>
 <div class="toc-item" @click="$slidev.nav.go(21)">10.b Back-end interventions</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(22)">10.c Evidence & outcomes</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(23)">11. The 4 Ds of prescribing</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(25)">12. The 4 c antibiotics for CDI</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(28)">13. Pharmaceutical importance of AMS</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(30)">14. Pharmacist-led stewardship activities</div>
  <div class="toc-divider"></div>
   <div class="toc-item" @click="$slidev.nav.go(38)">15. Survey results</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(40)">16. Conclusion</div>
  <div class="toc-divider"></div>
  <div class="toc-item" @click="$slidev.nav.go(41)">17. References</div>
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
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<div class="space-y-4 text-lg">

<v-clicks>

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<h2 class="text-xl font-bold mb-4" style="color: rgb(11, 104, 134);">What is Antimicrobial?</h2>
<p style="font-size: 1.2rem; line-height: 2;">Antimicrobials are agents that either kill microorganisms (biocidal effect) or inhibit their growth (biostatic effect).</p>

<p style="font-size: 1.2rem; line-height: 2; margin-top: 1rem;">
Antimicrobials include agents that act against viruses, fungi, parasites, and bacterials. 
</p>
<!-- <p>this presentation focuses on <strong>bacterial infections</strong> and the use of <strong>antibiotics</strong>, which are the most commonly misused and most affected by resistance. </p> -->
</div>
<div class="bg-white bg-opacity-10 p-3 rounded-xl">
  <h2 class="text-xl font-bold mb-4" style="color: rgb(11, 104, 134);">
    Gram-Positive vs Gram-Negative Bacteria
  </h2>
  <p class="text-lg leading-7">
    Bacteria are broadly classified into:
    <strong>Gram-positive</strong> (e.g. <em>Staphylococcus aureus</em>) and 
    <strong>Gram-negative</strong> (e.g. <em>E. coli, Klebsiella</em>) based on their cell wall structure.
  </p>
  <ul class="mt-4 list-disc pl-6 text-lg leading-7">
    <li><strong>Gram-Positive:</strong> Thick peptidoglycan wall, no outer membrane.</li>
    <li><strong>Gram-Negative:</strong> Thin wall + outer membrane; often more resistant due to efflux pumps & enzymes.</li>
  </ul>
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

<style>
.gradient-heading2 {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 1.5rem;
  margin-bottom: 0.5rem;
}

.organism-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 1rem;
  font-size: 1rem;
}

.organism-column {
  background: rgba(255,255,255,0.03);
  border-radius: 8px;
  padding: 1.2rem;
}

.column-title {
  font-weight: 700;
  color: rgb(9, 131, 172);
  border-bottom: 2px solid rgba(9, 131, 172, 0.3);
  padding-bottom: 0.2rem;
  margin-bottom: 0.8rem;
}

.organism-item {
  margin-bottom: 0.8rem;
}

.organism-name {
  font-weight: 600;
  margin-bottom: 0.8rem;
}

.organism-resistance {
  font-size: 1rem;
}
.criticality {
  font-size: 0.75rem;
  color:rgb(51, 51, 51);
  margin-top: -0.5rem;
  text-align: center;
  margin-top: 0.2rem
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

## [Major Organisms that Pose Serious Threat to Current Antimicrobial Therapies]{.gradient-heading2}

<div class="organism-grid">
  <!-- Column 1 -->
  <v-click>
  <div class="organism-column">
    <div class="column-title">Gram-Negative Bacteria
    <div class="criticality">Critical urgent threats</div>
    </div>
    
   <div class="organism-item">
      <div class="organism-name">Carbapenem-resistant Enterobacteriaceae (CRE)<br>(e.g. <i class="italic tetx-sm">K. pneumoniae, E. coli</i>)</div>
      <div class="organism-resistance">Resistant to nearly all beta-lactams, including carbapenems</div>
   </div>
    
  <div class="organism-item">
      <div class="organism-name"><i class="italic"> Pseudomonas aeruginosa</i> </div>
      <div class="organism-resistance">Often resistant to multiple drug classes</div>
    </div>
    
    
  <div class="organism-item">
      <div class="organism-name">Extended-Spectrum Beta-Lactamases (ESBL)-producing <i class="italic">Enterobacteriaceae</i></div>
      <div class="organism-resistance">Inactivate 3rd-gen cephalosporins</div>
    </div>
  </div>
  </v-click>

  <!-- Column 2 -->
  <v-click at="2">
  <div class="organism-column">
    <div class="column-title">Gram-Positive Bacteria
    <div class="criticality">High Priority</div>
    </div>
    
   <div class="organism-item">
      <div class="organism-name">MRSA (Methicillin-resistant <i class="italic"> Staphylococcus aureus)</i> </div>
      <div class="organism-resistance">Resistant to most beta-lactams</div>
   </div>
    
   <div class="organism-item">
      <div class="organism-name">VRE (Vancomycin-resistant Enterococci)</div>
      <div class="organism-resistance">Resistant to vancomycin, often multidrug-resistant</div>
   </div>
    
   <div class="organism-item">
      <div class="organism-name">Drug-resistant <i class="italic">Streptococcus pneumoniae</i>  </div>
      <div class="organism-resistance">Resistance to penicillin, macrolides</div>
   </div>
  </div>
  </v-click>

  <!-- Column 3 -->
  <v-click at="3">
  <div class="organism-column">
    <div class="column-title">Other Emerging Threats</div>
    
  <div class="organism-item">
      <div class="organism-name"><i class="italic"> Neisseria gonorrhoeae</i>  </div>
      <div class="organism-resistance">Resistance to fluoroquinolones, cephalosporins, azithromycin</div>
  </div>
    
  <div class="organism-item">
      <div class="organism-name">Salmonella (including Typhi)</div>
      <div class="organism-resistance">MDR and extensively drug-resistant (XDR) strains</div>
    </div>
    
   <div class="organism-item">
      <div class="organism-name"> <i class="italic"> Mycobacterium tuberculosis (MDR-TB, XDR-TB)</i> </div>
    <div class="organism-resistance">Resistance to rifampicin and isoniazid (MDR); fluoroquinolones and injectable drugs (XDR)</div>
    </div>
  </div>
  </v-click>
</div>

---
layout: center
class: text-center
background: linear-gradient(-45deg, rgba(11, 104, 134, 0.9), rgba(9, 131, 172, 0.9))
text: white
---

<style>
.callout-box {
  background: rgba(255,255,255,0.1);
  backdrop-filter: blur(8px);
  border-radius: 16px;
  padding: 3rem;
  max-width: 900px;
  margin: 0 auto;
}

.callout-message {
  font-size: 2rem;
  line-height: 1.9;
  font-weight: 500;
  margin: 0.8;
  padding: 0;
}

.callout-message span {
  display: inline-block;
  margin: 0.8rem 0;
}

.strong-emphasis {
  font-weight: 800;
  color: rgba(255,255,255,0.1);
  padding: 0 0.2rem;
  font-size: 1.8rem;
}

.stewardship-icon {
  font-size: 4rem;
  margin-bottom: 2rem;
  display: inline-block;
  text-shadow: 0 2px 8px rgba(0,0,0,0.2);
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(255,255,255,0.15)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(255,255,255,0.1)" />

<div class="callout-box">
  <div class="stewardship-icon">🛡️</div>
  <p class="callout-message">
    These resistant organisms challenge treatment <br>
  </p>
  <p class="callout-message"> and highlight the urgent need for <br>
    <span class="strong-emphasis">Antimicrobial Stewardship</span><br>
    to preserve antibiotic effectiveness.</p>
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
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<div class="space-y-8 text-lg">

<v-clicks>

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<p class="text-2xl font-bold mb-4" style="color: rgb(11, 104, 134);">Antimicrobial Stewardship (AMS) is a coordinated program involving healthcare teams (multidisciplinary) that seeks to promote;</p>

<ul class="text-xl space-y-6 pl-6" style="list-style-type: disc;">
  <li class="pl-2">The <span class="font-semibold">appropriate use</span> of antimicrobials</li>
  <li class="pl-2"><span class="font-semibold">Improves patient outcomes</span> through optimized treatment</li>
  <li class="pl-2">Helps <span class="font-semibold">reduce antimicrobial resistance</span></li>
  <li class="pl-2">Limits the <span class="font-semibold">spread of infections</span> from multidrug-resistant organisms</li>
</ul>

</div>

</v-clicks>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
ul {
  margin-bottom: 1rem;
}
 .pl-2 li::before {
  content: "•";
  color: rgb(9, 131, 172);
  font-size: 2rem;
  position: absolute;
  left: -1.5rem;
  top: 0.1rem;
}
</style>



---
layout: default
class: px-8 py-6
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style>
/* Enhanced heading */
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 1.5rem;
  margin: 0 0 1.5rem 0;
  line-height: 1.3;
}

/* Bullet list container */
ul {
  list-style: none;
  padding-left: 0;
  margin: 0;
  font-size: 1rem;
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

**- Resistance mechanism**

  🔹 **Efflux pumps:** Bacteria actively expel antimicrobials to lower intracellular concentration.

  🔹 **Decreased uptake: Reduced** drug entry prevents antimicrobial action.

  🔹 **Inactivating enzymes:** Enzymes chemically destroy or modify the drug.

  🔹 **Target overproduction:** Excess target dilutes drug effectiveness.

  🔹 **Modified target:** Mutation alters the drug’s binding site.

</v-clicks>

---
layout: default
---

<CircleShape position="top:20%; left:-6%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

### [Antimicrobial Resistance (AMR) cont'd..]{.gradient-heading}

<v-clicks>

<div class="w-[75%] ml-[10%]">
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
class: px-8 py-10
---

## [Leading Causes of Antimicrobial Resistance (AMR)]{.gradient-heading}

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 2.5rem;
  margin-bottom: 1.5rem;
}

.bullet-container {
  display: flex;
  flex-direction: column;
  gap: 1.5rem;
  padding: 2rem 3rem;
  height: 65vh;
}

.bullet-item {
  display: flex;
  align-items: flex-start;
  gap: 2.5rem;
}

.bullet-icon {
  font-size: 1.8rem;
  color: rgb(9, 131, 172);
  margin-top: 0rem;
}

.bullet-content h3 {
  color: rgb(24, 24, 24);
  font-weight: 600;
  font-size: 1.6rem;
  margin-bottom: 0.5rem;
}

.bullet-content p {
  color:rgb(24, 24, 24);
  font-size: 1.5rem;
  line-height: 1.5;
}
</style>

<div class="bullet-container">
  <!-- Item 1 -->
  <div class="bullet-item">
    <div class="bullet-icon">•</div>
    <div class="bullet-content">
      <h3>Overuse and Misuse</h3>
      <!-- <p>~30% of hospital antimicrobial prescriptions are unnecessary, fueling resistance and C. difficile infections (CDC, 2019).</p> -->
    </div>
  </div>

  <!-- Item 2 -->
  <div class="bullet-item">
    <div class="bullet-icon">•</div>
    <div class="bullet-content">
      <h3>Agricultural Use</h3>
      <!-- <p>70% of global antibiotic consumption is in livestock for growth promotion and disease prevention (O'Neill Review, 2016).</p> -->
    </div>
  </div>

  <!-- Item 3 -->
  <div class="bullet-item">
    <div class="bullet-icon">•</div>
    <div class="bullet-content">
      <h3>Infection Control</h3>
      <!-- <p>Inadequate hand hygiene, environmental cleaning, and isolation allow resistant organisms to spread in hospitals (WHO, 2021).</p> -->
    </div>
  </div>

  <!-- Item 4 -->
  <div class="bullet-item">
    <div class="bullet-icon">•</div>
    <div class="bullet-content">
      <h3>Innovation Gap</h3>
      <!-- <p>Insufficient development of novel antimicrobials; resistance outpaces new drug approvals (WHO, 2021).</p> -->
    </div>
  </div>
</div>


---
layout: default
class: px-10 py-2
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
text: white
---


<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Principles of Antimicrobial Stewardship]{.gradient-headinga}

<div class="grid grid-cols-2 p-2 gap-6 mt-1" style="font-size: 1.2rem;">

<!-- Column 1 -->
<div class="space-y-10">
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
<div class="space-y-10">
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
.gradient-headinga {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 2rem;
  margin-bottom: 0.5rem;
  margin-top: 3rem;
}
</style>

---
layout: default
class: px-10 py-8
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<!-- Left Column - Text Content -->

<div class="col-left" style="width: 50%; padding-right: 2rem;">

## [Why AMS Matters in the Hospitals]{.gradient-heading}

<v-clicks>

- **4.7 million deaths as at 2021** associated with bacterial AMR globally
- **8.2 million deaths by 2050** if unaddressed
- **50–70% of hospitalized patients** receive antimicrobials (WHO)
- Increasing local AMR rates leading to **hard‑to‑treat infections**
- **Resource constraints**: ICU beds, lab diagnostics
- **Economic pressure**: Costs of last‑line drugs and extended stays
- Alignment with **Nigeria AMR National Action Plan 2024–2028**

</v-clicks>
</div>



<!-- Right Column - Image -->
<div class="flex items-center justify-center">
  <img src="/images/stats2.png" class="w-full h-auto object-contain rounded-lg">
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
  gap: 1rem;
}
.slidev-vclick-target {
  transition: opacity 400ms ease;
}
.slidev-vclick-hidden {
  opacity: 0;
  pointer-events: none;
}
ul {
  margin-top: 0.5rem;
  line-height: 1.6;
}
li {
  padding-left: 0.5rem;
}
</style>

