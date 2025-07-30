---
layout: center
transition: fade-out
---


# [AMS Techniques]{.gradient-text}

<!-- CSS styling for .gradient-text class -->
<style>
    .gradient-text {
      background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
      font-size: 2em; 
      line-height:1.2;
      font-weight: 900;
    }
   
</style>

---
layout: default
class: px-8 py-4
---

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
  font-size: 2.5rem;
  margin-bottom: 0.2rem;
}

.gradient-subheading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 600;
  font-size:3rem;
}

.intervention-container {
  display: flex;
  height: 72vh;
  gap: 2.5rem;
  margin-top: 0.5rem;
}

.left-column {
  flex: 1;
  padding-right: 1.5rem;
}

.right-column {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.card-section {
  font-size: 1.5rem;
  line-height: 1.7;
}

.icon-header {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

.bullet-list {
  list-style: none;
  padding-left: 1.8rem;
}

.bullet-list li {
  position: relative;
  margin-bottom: 1rem;
}

.bullet-list li::before {
  content: "•";
  color: rgb(9, 131, 172);
  font-size: 2rem;
  position: absolute;
  left: -1.2rem;
  top: -0.3rem;
}

.pros-cons {
  background: rgba(255,255,255,0.05);
  padding: 1.5rem;
  border-radius: 12px;
  margin: 0.5rem 0;
}

.pros-cons p {
  margin-bottom: 0.8rem;
  font-size: 1.5rem;
}

.highlight-box {
  background: rgba(9, 131, 172, 0.15);
  padding: 1.5rem;
  border-radius: 12px;
  margin-top: auto;
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Front-End Interventions]{.gradient-heading}
## [Pre-Authorization Strategy]{.gradient-subheading}

<div class="intervention-container">
  <!-- Left Column -->
  <div class="left-column p-4">
    <div class="icon-header">🔒</div>
    <h3 class="text-2xl font-bold mb-4">Approval Required Before Prescribing</h3>
    
   <div class="card-section">
      <p class="font-semibold mb-2">Who approves:</p>
      <ul class="bullet-list">
        <li>Medical Doctor</li>
        <li>Pharmacist</li>
      </ul>
    </div>
  </div>

  <!-- Right Column -->
  <div class="right-column">
    <div class="pros-cons">
      <p class="font-bold text-green-500 text-xl mb-3">Pros:</p>
      <p>✓ Immediate control of high-risk drugs</p>
      <p>✓ Prevents inappropriate use upfront</p>
      
   <p class="font-bold text-red-500 text-xl mt-6 mb-3">Cons:</p>
      <p>✗ May delay therapy in emergencies</p>
      <p>✗ Adds administrative burden</p>
    </div>

  <div class="highlight-box">
      <p class="font-bold text-lg mb-2">Example:</p>
      <p class="text-xl">Restrict Reserve antibiotics like carbapenems</p>
    </div>
  </div>
</div>

---
layout: default
class: px-8 py-4
---

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
  font-size: 2.5rem;
  margin-bottom: 0.2rem;
}

.gradient-subheading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 600;
  font-size: 3rem;
}

.intervention-container {
  display: flex;
  height: 72vh;
  gap: 2.5rem;
  margin-top: 0.5rem;
}

.left-column {
  flex: 1;
  padding-right: 1.5rem;
}

.right-column {
  flex: 1;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
}

.card-section {
  font-size: 1.5rem;
  line-height: 1.7;
}

.icon-header {
  font-size: 2rem;
  margin-bottom: 0.5rem;
}

.bullet-list {
  list-style: none;
  padding-left: 1.8rem;
}

.bullet-list li {
  position: relative;
  margin-bottom: 1rem;
}

.bullet-list li::before {
  content: "•";
  color: rgb(9, 131, 172);
  font-size: 2rem;
  position: absolute;
  left: -1.2rem;
  top: -0.3rem;
}

.pros-cons {
  background: rgba(255,255,255,0.05);
  padding: 1.5rem;
  border-radius: 12px;
  margin: 0.5rem 0;
}

.pros-cons p {
  margin-bottom: 0.8rem;
  font-size: 1.5rem;
}

.highlight-box {
  background: rgba(9, 131, 172, 0.15);
  padding: 1.5rem;
  border-radius: 12px;
  margin-top: auto;
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

# [Back-End Interventions]{.gradient-heading}
## [Audit & Feedback Strategy]{.gradient-subheading}

<div class="intervention-container">
  <!-- Left Column -->
  <div class="left-column p-4">
    <div class="icon-header">🔍</div>
    <h3 class="text-2xl font-bold mb-4">Review After Antibiotic Initiation</h3>
    
   <div class="card-section">
      <p class="font-semibold mb-2">Who reviews:</p>
      <ul class="bullet-list">
        <li>Pharmacist</li>
        <li>Stewardship team</li>
      </ul>
    </div>
  </div>

  <!-- Right Column -->
  <div class="right-column">
    <div class="pros-cons">
      <p class="font-bold text-green-500 text-xl mb-3">Pros:</p>
      <p>✓ Prescriber autonomy preserved</p>
      <p>✓ High educational value</p>
      
   <p class="font-bold text-red-500 text-xl mt-6 mb-3">Cons:</p>
      <p>✗ Labor-intensive</p>
      <p>✗ Slower impact (48-72h)</p>
    </div>

   <div class="highlight-box">
      <p class="font-bold text-lg mb-2">Example:</p>
      <p class="text-xl">Daily "time-out" rounds in ICU</p>
    </div>
  </div>
</div>

---
layout: default
class: px-10 py-8
---

<style>
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
  font-size: 3rem;
  margin-bottom: 1.5rem;
}

.bullet-list {
  list-style: none;
  padding-left: 2rem;
  font-size: 1.6rem;
  line-height: 2;
  margin-top: 1rem;
}

.bullet-list li {
  position: relative;
}

.bullet-list li::before {
  content: "•";
  color: rgb(9, 131, 172);
  font-size: 2rem;
  position: absolute;
  left: -1.5rem;
  top: 0.1rem;
}

.highlight {
  font-weight: 700;
  color: rgb(9, 131, 172);
}

.slidev-page {
  display: flex;
  flex-direction: column;
  justify-content: center;
  height: 100%;
}
</style>

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

## [Evidence and Outcomes]{.gradient-heading}

<ul class="bullet-list">
  <li>Both strategies are core components of Antimicrobial Stewardship Programs (ASPs)</li>
  <li><span class="highlight">Hybrid models are common:</span></li>
  <li>Pre-authorization works well for Reserve drugs</li>
  <li>Audit/feedback is usually practiced on broad-spectrum use</li>
  <li>Studies show reduced resistance and improved prescribing behavior</li>
</ul>

---
layout: center
transition: fade-out
---

<style>
    .gradient-text {
      background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
      -webkit-background-clip: text;
      -moz-background-clip: text;
      -webkit-text-fill-color: transparent;
      -moz-text-fill-color: transparent;
      font-size: 2.5rem; 
      line-height:1.2;
      font-weight: 900;
    }
   
</style>

# [The “4 Ds” of Antimicrobial Prescribing]{.gradient-text}

---
layout: default
---


<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />

<style> 
.gradient-subheading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 1.2rem;
  margin-bottom: 1.2rem;
}
</style>
<v-click>

- The 4Ds of Antimicrobial Prescribing is simply the appropriate use of antimicrobial with respect to the drug, dose, duration and diagnosis.

</v-click>

<div class="mt-3 grid grid-cols-2 gap-8">

<!-- Left Column - appears on first click -->
<v-click>
<div class="mt-2 pr-4">

### 💊 1.[Right Drug]{.gradient-subheading}

- Select the most targeted antimicrobial/antibiotic for the infection.

- Avoid broad-spectrum agents unless absolutely necessary.
- Consider local resistance patterns and patient allergies.
- *Example: Use nitrofurantoin for uncomplicated urinary tract infections instead of a fluoroquinolone like ciprofloxacin.*
</div>
</v-click>

<!-- Right Column - appears on same click as left column -->
<v-click>
<div class="mt-2 pl-4">

### 📏 2. [Right Dose]{.gradient-subheading}

- Tailor the dose to:

- Patient weight
- Renal and hepatic function
- Severity of infection
- Underdosing risks treatment failure; overdosing risks toxicity.
- *Vancomycin dose reduced to once daily in a patient with kidney impairment to prevent toxicity.*
</div>
</v-click>

</div>
---
layout: default
---

<CircleShape position="top:20%; left:-5%; size:80px; color:rgba(3, 80, 105, 0.55)" />
<PillShape position="bottom:-5%; right:-10%; width:10%; height:20px; color:rgba(33,150,243,0.08)" />


## [The “4 Ds” of Antimicrobial Prescribing cont'd..]{.gradient-heading}

<div class="mt-3 grid grid-cols-2 gap-8">

<!-- Left Column -->
<v-click>
<div class="pr-4">

### ⏳ 3. [Right Duration]{.gradient-subheading}

- Prescribe for the shortest effective course possible.

- Overly long durations increase risk of resistance and side effects.

- Reassess therapy at 48–72 hours and adjust based on clinical response.

- *Example: Community-acquired pneumonia often requires 5–7 days, not 10+.*

</div>
</v-click>

<!-- Right Column -->
<v-click>
<div class="pl-4">

### 🔄 4. [De-escalation/Diagnosis ]{.gradient-subheading}

- Once culture and susceptibility results are available:

- Stop unnecessary antibiotics

- Switch from broad-spectrum to narrow-spectrum agents

- De-escalation reduces collateral damage to the microbiome and lowers resistance risk.

- *Example: If vancomycin was started empirically for MRSA, but cultures show MSSA, switch to nafcillin or cefazolin.*

</div>

</v-click>

</div>

<style>
  li::before {
  content: "•";
  color: rgb(9, 131, 172);
  font-size: 2rem;
  position: absolute;
  left: -1.5rem;
  top: 0.1rem;
}
.gradient-heading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 800;
  font-size: 1.5rem;
  margin-bottom: 1.5rem;
}
.gradient-subheading {
  background: linear-gradient(-45deg, rgb(11, 104, 134), rgb(9, 131, 172));
  -webkit-background-clip: text;
  background-clip: text;
  color: transparent;
  font-weight: 700;
  font-size: 1.2rem;
  margin-bottom: 1.2rem;
}
</style>