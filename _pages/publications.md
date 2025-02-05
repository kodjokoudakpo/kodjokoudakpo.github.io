---
layout: page
permalink: /Research/
title: Research
description: #publications by categories in reversed chronological order. generated by Jekyll-scholar.
years:   #[1967, 1956, 1950, 1935, 1905]
nav: true
nav_order: 1
---




 <div class="home">

 <h2 id="research"> <b> Working papers </b> </h2>

 <p > <strong> Fiscal Rules and Fiscal Policy: A Quantitative Analysis </strong> [<a href= "/assets/pdf/Kodjo_Koudakpo_FRFP_JMP.pdf"> Job Market Paper </a>]</p>
<p align="justify"> This paper provides a quantitative analysis of the optimal design of deficit limits
under imperfect enforcement. Utilizing data on primary balances and fiscal
rules from 2000 to 2021, I document two critical patterns in low-income countries :
the persistence of primary deficits and frequent instances of noncompliance with
fiscal rules. To elucidate the role of noncompliance in shaping optimal deficit limits,
I employ a tractable fiscal policy model to conduct a quantitative exercise. The
model incorporates a key assumption that the cost of noncompliance with a deficit
limit rises as borrowing increases. Analytical results demonstrate that the optimal
deficit limit is determined by the magnitude of sanctions associated with violations
of fiscal rules. Calibration for Sub-Saharan African (SSA) economies suggests that
an optimal deficit limit ranges from 5.12% to 9.5% of GDP, while the sanctions
vary between 0.33% and 2.7% of GDP. These findings contribute to the broader
discourse on the reform of fiscal rules in SSA countries, offering evidence-based insights
into the trade-offs between fiscal flexibility and the enforcement of compliance
mechanisms. </p>
 
  <p> <strong> Trade Policy and U.S. Multinationals activities </strong> </p> 
 <p align="justify">  This paper studies the implications of trade fragmentation on U.S. Multinational Majority-Owned Foreign Affiliates (MOFA) activities. I use data on services trade restrictiveness to document that a higher level of services trade barriers is associated with a higher and persistent decline in US MOFAs' employment and investment. To explain the role of the services trade barriers in the decline of U.S. MOFA activities, I build a general equilibrium of trade and Multinational production with a fragmentation of service trade. Consistent with my empirical findings using OECD data, the model generates a drop in U.S. MOFAs' activities and output. My findings suggest that there is room for policy to mitigate the substantial impacts of service trade restrictions.  </p>
  
</div>

<div class="home">

 <h2 id="research"> <b> Work in progress </b> </h2>

 <p> <strong> Transition to Renewables and Public Debt Sustainability, ( with Fansa Kone and Lucien Chaffa ) </strong> </p>
</div>

<br/> 

<div class="home">

  <h2 id="research"> <b> Policy papers </b> </h2>

     <p>  Do subsistence zones matter for poverty reduction?, 2024, World Bank Group, Washington DC (with Grace Doherty and Johannes Hoogeveen)  </p>

     <p>   Creating Consistent Subsistence Zones with Spatial Clustering for the Sahel Region, 2024, World Bank Group, Washington DC (with Grace Doherty and Johannes Hoogeveen) </p>
     
   <p> <a href="https://documents1.worldbank.org/curated/en/485881623304212722/pdf/Results-from-Iterative-Beneficiary-Facility-Staff-as-Part-of-the-KIRA-Project-March-15-April-2-2021.pdf"> Monitoring health service delivery in Burundi, 2021, World Bank Group, Washington DC, (joint with Alexandra Jarotschkin et al.)</a>.   </p>


  <p> <a href="https://pdf.usaid.gov/pdf_docs/PA00X8GH.pdf"> Poverty and Malnutrition in Haiti, 2020, Washington, D.C.: USAID-RTAC  (with Viceisza et al.) </a>.  </p>

</div>


<br/> <br/>
<body>
  <footer class="pt-5 my-5 text-muted border-top">
  <div class="home">
    <div class="col-md-6 text-end social-media-icons">
      
        <a href="https://github.com/kodjokoudakpo" class="ms-3 fs-5"><i class="fab fa-github"></i></a>
      
        <a href="https://twitter.com/KoudakpoKodjo" class="ms-3 fs-5"><i class="fab fa-twitter"></i></a>
      
        <a href="https://www.linkedin.com/in/kodjo-nixon-koudakpo-26733975/" class="ms-3 fs-5"><i class="fab fa-linkedin"></i></a>
      
    </div>
  </div>
</footer>
</body>






<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div> 
