---
layout: center
transition: fade-out
setup: |
  import DecoratedLayout from './components/DecoratedLayout.vue'
  import CircleShape from './components/CircleShape.vue'
  import PillShape from './components/PillShape.vue'
---

# [BACKGROUND ]{.gradient-text}

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

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<h2 class="text-2xl font-bold mb-4" style="color: rgb(11, 104, 134);">Antimicrobial Stewardship</h2>
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

## [Why AMS Matters at FMC Keffi]{.gradient-heading}



<v-clicks>

- **4.95 million deaths/year** globally linked to AMR (Lancet 2022)
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
  margin-top: 1.5rem;
  line-height: 1.6;
}
li {
  margin-bottom: 0.8rem;
  padding-left: 0.5rem;
}
</style>


<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />
---
layout: center
class: px-10 py-8
background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172))
text: white
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
  font-size: 1.8rem;
  margin-bottom: 1.5rem;
  margin-top: 1.5rem;
}
</style>

<div class="w-full h-full flex flex-col justify-center">

## Historical Evolution of Antimicrobial Stewardship Programs (ASPs){.gradient-heading}

<div class="bg-white bg-opacity-10 p-8 rounded-xl">
<v-clicks>

<ul class="space-y-4 text-xl">
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">1940s:</span> Sir Alexander Fleming warned about emerging antibiotic resistance</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">1996-97:</span> Term "Antimicrobial Stewardship" was coined by McGowan & Gerding; Incorporated into IDSA guidelines.</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">2007:</span> IDSA/SHEA formally endorse Hospital ASPs as a core strategy.</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">2009-13:</span> CDC launches US national stewardship initiatives (Education -> Formal Strategy).</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">2016:</span> WHO & UN General Assembly endorse global ASP; WHO issues toolkits.</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">Mid-2010s Onwards:</span> Accreditation bodies & governments (e.g., EU 2017) mandate ASPs globally.</span>
</li>
</ul>

</v-clicks>
</div>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
ul {
  list-style: none;
  padding-left: 0;
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

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: bold;
  display: inline-block;
  font-size: 1.8rem;
  margin-bottom: 1.5rem;
  margin-top: 4rem;
}
</style>

<div class="w-full h-full flex flex-col justify-center">

## Nigeria's National AMR Response{.gradient-heading}

<div class="bg-white bg-opacity-10 p-6 rounded-xl">
<v-clicks>

<ul class="space-y-2 text-xl">
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">2017-22:</span> Launch of 1st National Action Plan (NAP-1.0) on AMR (One Health: Human, Animal, Env.).</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span>NAP-1.0 Mid-term Review: ~44% activities completed; Gaps identified (e.g., weak environmental/agricultural involvement).</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span><span class="font-bold">Oct 2024:</span> Launch of NAP-2.0 (2024-2028) - Aligns with UN/Global Health Security.</span>
</li>
<li class="flex items-start mt-6">
  <span class="mr-3 text-blue-300">•</span>
  <span class="font-bold">NAP-2.0 Priorities:</span>
</li>
<li class="flex items-start ml-8">
  <span class="mr-3 text-blue-300">-</span>
  <span>Strengthen ASPs</span>
</li>
<li class="flex items-start ml-8">
  <span class="mr-3 text-blue-300">-</span>
  <span>Enhance AMR Surveillance</span>
</li>
<li class="flex items-start ml-8">
  <span class="mr-3 text-blue-300">-</span>
  <span>Promote Research</span>
</li>
<li class="flex items-start ml-8">
  <span class="mr-3 text-blue-300">-</span>
  <span>Bolster Health Systems (One Health)</span>
</li>
</ul>

</v-clicks>
</div>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
ul {
  list-style: none;
  padding-left: 0;
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

<div class="w-full h-full flex flex-col justify-center">

## ASP Implementation in Nigerian Hospitals so far{.gradient-heading}

<div class="bg-white bg-opacity-10 p-8 rounded-xl">
<v-clicks>

<ul class="space-y-4 text-lg leading-relaxed">
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span>Only <span class="font-bold">13% to 35%</span> of Nigerian tertiary hospitals have formal ASP teams/committees (Ohaju-Obodo et al., 2020).</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span>Critical gaps exist: <span class="font-bold">~24%</span> have local treatment guidelines & only <span class="font-bold">~12%</span> enforce mandatory antibiotic review/approval.</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span>Pharmacists commonly perform <span class="italic">ad-hoc</span> stewardship (e.g., prescription review) despite lacking formal ASP programs (Ogunnigbo et al., 2021).</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span>Key barriers: Insufficient AMS/Prof. training, shortage of Prof-specialized pharmacists, & weak administrative support.</span>
</li>
<li class="flex items-start">
  <span class="mr-3 text-blue-300">•</span>
  <span class="font-bold">Nigerian hospitals show "significant inadequacies" in ASP implementation.</span>
</li>
</ul>

</v-clicks>
</div>

</div>

<style>
.slidev-vclick-target {
  transition: all 0.3s ease;
}
ul li{
  list-style: none;
  padding-left: 0;
  font-weight: 600;
}
</style>

