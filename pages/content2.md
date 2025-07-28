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
  margin-bottom: 0.3rem;
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
  font-size: 1.5rem;
  margin-bottom: 1.5rem;
}

/* Make medicine list items bolder */
.text-sm ol li {
  font-weight: 500;
}

/* Add compact styling for the table */
.compact-grid {
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 1rem; /* Reduced gap */
}

.compact-column {
  padding-right: 0.5rem;
}

.compact-list {
  font-size: 0.9rem; /* Smaller font */
  margin-top: 0.5rem;
}

.compact-list ol {
  padding-left: 1rem; /* Reduced padding */
}

.compact-list li {
  margin-bottom: 0.2rem; /* Tighter spacing */
}

/* Key point section styling */
.key-point {
  margin-top: 1.5rem;
  text-align: left;
  font-size: 0.5rem;
  line-height: 1;
}

.aware-emphasis {
  color: rgb(9, 131, 172);
  font-weight: 700;
}

.high-risk {
  color: #dc2626;
  font-weight: 600;
   font-size: 1.1rem;
}
</style>
<CircleShape position="top:15%; left:-5%; size:70px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-8%; right:-10%; width:10%; height:18px; color:rgba(33,150,243,0.08)" />

## [WHO AWaRe Classification for Antimicrobials/Antibiotics]{.gradient-heading}

<v-clicks>
<ul id="aware-bullet">
  <li>WHO grouped antibiotics into <strong>Access</strong>, <strong>Watch</strong>, and <strong>Reserve</strong> to guide usage.</li>
</ul>
</v-clicks>

<div class="mt-2 grid compact-grid"> <!-- Reduced top margin -->
  <!-- Access Group -->
  <v-click>
    <div class="border-r border-gray-200 compact-column">
      <h2 class="gradient-heading text-lg">Access Group</h2> <!-- Smaller heading -->
      <p class="font-semibold text-sm">First-line narrow-spectrum</p> <!-- Smaller text -->
      <div class="compact-list">
<ol>
<li>Amoxicillin <span class="text-xs text-gray-500">(Amoxil®)</span></li>
<li>Cotrimoxazole <span class="text-xs text-gray-500">(Septrin®)</span></li>
<li>Nitrofurantoin <span class="text-xs text-gray-500">(Macrodantin®)</span></li>
<li>Cloxacillin <span class="text-xs text-gray-500">(Cloxapen®)</span></li>
<li>Benzylpenicillin <span class="text-xs text-gray-500">(Crystapen®)</span></li>
</ol>
</div>
</div>
</v-click>

<!-- Watch Group -->
<v-click>
<div class="border-r border-gray-200 compact-column">
  <h3 class="gradient-heading text-lg">Watch Group</h3> <!-- Smaller heading -->
  <p class="font-semibold text-sm">Higher resistance potential</p> <!-- Smaller text -->
  <div class="compact-list">
<ol>
<li><b>Co-amoxiclav</b> <span class="text-xs text-gray-500">(Augmentin®)</span></li>
<li>Ciprofloxacin <span class="text-xs text-gray-500">(Ciprotab®)</span></li>
<li>Ceftriaxone <span class="text-xs text-gray-500">(Rocephin®)</span></li>
<li>Azithromycin <span class="text-xs text-gray-500">(Zithromax®)</span></li>
<li>Cefuroxime <span class="text-xs text-gray-500">(Zinnat®)</span></li>
</ol>
</div>
</div>
</v-click>

<!-- Reserve Group -->
<v-click>
<div class="compact-column">
  <h3 class="gradient-heading text-lg">Reserve Group</h3> <!-- Smaller heading -->
  <p class="font-semibold text-sm">Last-resort agents</p> <!-- Smaller text -->
  <div class="compact-list">
<ol>
<li>Meropenem <span class="text-xs text-gray-500">(Meronem®)</span></li>
<li>Colistin <span class="text-xs text-gray-500">(Colimycin®)</span></li>
<li>Linezolid <span class="text-xs text-gray-500">(Zyvox®)</span></li>
<li>Vancomycin <span class="text-xs text-gray-500">(Vancox®)</span></li>
<li>Tigecycline <span class="text-xs text-gray-500">(Tygacil®)</span></li>
</ol>
</div>
<div class="mt-2 text-xs bg-red-50 p-1 rounded"> <!-- Compact restriction note -->
🔒 Restricted use (consultant approval)
</div>
</div>
</v-click>
</div>

<div class="key-point">
<v-click>
<p class="text-xl"> 
Prioritizing Access antibiotics
reduces gut flora disruption
and lowers <span class="high-risk"><i>C. difficile infection (CDI) risk</i></span></p>


<div class="mt-1 text-xl"> <!-- Slightly smaller text -->
<p> 
<span class="font-bold">The 4C antibiotics:</span>
(<span class="high-risk">Clindamycin, Cephalosporins, Co-amoxiclav, Ciprofloxacin</span>)
</p>

</div>
</v-click>
</div>