<div class="relative w-full mt-6">
  <!-- Y-axis label -->
  <div class="absolute left-0 top-1/2 -translate-y-1/2 -rotate-90 origin-left text-sm font-medium text-gray-600">
    Response Rate (%)
  </div>

  <div class="h-[40vh] ml-8 flex items-end gap-6 justify-center border-b-2 border-l-2 border-gray-300">
    <!-- Question 1 -->
    <div class="flex flex-col items-center justify-end h-full">
      <div class="text-sm text-gray-700 mb-1">72%</div>
      <div class="w-16 rounded-t-md relative" 
           style="height: 72%; background: linear-gradient(to top, rgb(11, 104, 134), rgb(9, 131, 172))">
      </div>
      <div class="mt-2 font-medium">Q1</div>
    </div>

   <!-- Question 2 -->
   <div class="flex flex-col items-center justify-end h-full">
      <div class="text-sm text-gray-700 mb-1">58%</div>
      <div class="w-16 rounded-t-md relative"
           style="height: 58%; background: linear-gradient(to top, rgb(11, 104, 134), rgb(9, 131, 172))">
      </div>
      <div class="mt-2 font-medium">Q2</div>
    </div>

   <!-- Question 3 -->
  <div class="flex flex-col items-center justify-end h-full">
      <div class="text-sm text-gray-700 mb-1">85%</div>
      <div class="w-16 rounded-t-md relative"
           style="height: 85%; background: linear-gradient(to top, rgb(11, 104, 134), rgb(9, 131, 172))">
      </div>
      <div class="mt-2 font-medium">Q3</div>
    </div>

   <!-- Question 4 -->
   <div class="flex flex-col items-center justify-end h-full">
      <div class="text-sm text-gray-700 mb-1">63%</div>
      <div class="w-16 rounded-t-md relative"
           style="height: 63%; background: linear-gradient(to top, rgb(11, 104, 134), rgb(9, 131, 172))">
      </div>
      <div class="mt-2 font-medium">Q4</div>
    </div>

   <!-- Question 5 -->
   <div class="flex flex-col items-center justify-end h-full">
      <div class="text-sm text-gray-700 mb-1">47%</div>
      <div class="w-16 rounded-t-md relative"
           style="height: 47%; background: linear-gradient(to top, rgb(11, 104, 134), rgb(9, 131, 172))">
      </div>
      <div class="mt-2 font-medium">Q5</div>
    </div>
  </div>

  <!-- X-axis label -->
  <div class="text-center mt-3 text-sm font-medium text-gray-600">Survey Questions</div>
</div>

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
  font-size: 1.2rem;
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