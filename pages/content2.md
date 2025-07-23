---
layout: default
---

<style>
/* Targeted bullet styling only for the WHO point */
#aware-bullet {
  list-style: none;
  padding-left: 1.5em;
}

#aware-bullet li {
  position: relative;
  font-size: 1.3rem;
  font-weight: 600; /* Bolder text */
  line-height: 1.7;
  margin-bottom: 0.6rem;
}

#aware-bullet li::before {
  content: "•";
  color: rgb(9, 131, 172); /* Your theme color */
  font-size: 1.8em;
  position: absolute;
  left: -0.8em;
  top: -0.4em;
  font-weight: bold;
}

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

/* Make medicine list items bolder */
.text-sm ol li {
  font-weight: 500;
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:1%; right:1%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

## [WHO AWaRe Classification for Antimicrobials/Antibiotics]{.gradient-heading}

<br>
<v-clicks>
<ul id="aware-bullet">
  <li>WHO groups antibiotics into <strong>Access</strong>, <strong>Watch</strong>, and <strong>Reserve</strong> to guide usage.</li>
</ul>
</v-clicks>

<div class="mt-8 grid grid-cols-3 gap-8">
  <!-- Column 1: Access Group -->
  <v-click>
    <div class="border-r border-gray-200 pr-4">
      <h2 class="gradient-heading">Access Group</h2>
      <p class="font-semibold">First-line narrow-spectrum</p>
      <div class="text-sm mt-2 pl-4">
<ol>
<li>Amoxicillin <span class="text-xs text-gray-500">(e.g., Amoxil®)</span></li>
<li>Cotrimoxazole <span class="text-xs text-gray-500">(Septrin®)</span></li>
<li>Nitrofurantoin <span class="text-xs text-gray-500">(Macrodantin®)</span></li>
<li>Cloxacillin <span class="text-xs text-gray-500">(Cloxapen®)</span></li>
<li>Benzylpenicillin <span class="text-xs text-gray-500">(Crystapen®)</span></li>
</ol>
</div>
</div>

</v-click>

<!-- Column 2: Watch Group -->
<v-click>

<div class="border-r border-gray-200 pr-4">

## [Watch Group]{.gradient-heading}

**Higher resistance potential**  
<div class="text-sm mt-2 pl-4">
<ol>
<li><b>Co-amoxiclav</b> <span class="text-xs text-gray-500">(Augmentin®)</span></li>
<li>Ciprofloxacin <span class="text-xs text-gray-500">(Ciprotab®)</span></li>
<li>Ceftriaxone <span class="text-xs text-gray-500">(Rocephin®)</span></li>
<li>Azithromycin <span class="text-xs text-gray-500">(Zithromax®)</span></li>
<li>Cefuroxime <span class="text-xs text-gray-500">(Zinnat®)</span></li>
</ol>
</div>
<div class="mt-4 text-xs bg-yellow-50 p-2 mt-2 rounded">
⚠️ Classified as Watch due to ESBL risk
</div>
</div>

</v-click>

<!-- Column 3: Reserve Group -->
<v-click>

<div>

## [Reserve Group]{.gradient-heading}

**Last-resort agents**  
<div class="text-sm mt-2 pl-4">
<ol>
<li>Meropenem <span class="text-xs text-gray-500">(Meronem®)</span></li>
<li>Colistin <span class="text-xs text-gray-500">(Colimycin®)</span></li>
<li>Linezolid <span class="text-xs text-gray-500">(Zyvox®)</span></li>
<li>Vancomycin <span class="text-xs text-gray-500">(Vancox®)</span></li>
<li>Tigecycline <span class="text-xs text-gray-500">(Tygacil®)</span></li>
</ol>
</div>
<div class="mt-4 text-xs bg-red-50 p-2 mt-2 rounded">
🔒 Restricted use (requires consultant approval)
</div>
</div>
</v-click>

</div>



