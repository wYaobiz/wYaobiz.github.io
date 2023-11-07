---
layout: page
permalink: /publications/
title: publications
description:
years: [2022,2023]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

#### Preprints
<!-- - A survey on consortium blockchain consensus mechanisms. **Wei Yao**, Junyi Ye, Renita Murimi, Guiling Wang. [[arxiv](https://arxiv.org/abs/2102.12058)] -->
<!-- - Consensus Mechanisms in Consortium Blockchain: A Systematic Survey and Critical Analysis. **Wei Yao**, Fadi Deek, Renita Murimi, Guiling Wang.  -->
- VDKMS: Vehicular Decentralized Key Management System for Cellular Vehicular-to-Everything Networks, A Blockchain-Based Approach. **Wei Yao**, Yuhong Liu, Fadi Deek, Guiling Wang. Accepted by IEEE GLOBECOM 2023. 
- iBCTrans: A Practical Blockchain-Based Framework for Cellular Vehicular-To-Everything Networks.  **Wei Yao**, Yuhong Liu, Fadi Deek, Guiling Wang. Accepted by IEEE Blockchain 2023.  
- Considerations for Decision-makers and Developers toward Adoption of Decentralized Key Management Systems Technology in Emerging Applications. **Wei Yao**, Nicholas Gorlewski, Fadi Deek, Guiling Wang. Accepted by IEEE Computer.
- A Systematic Approach for Evaluating Blockchain-Based Self-Sovereign Identity Systems. **Wei Yao**, Fadi Deek, Guiling Wang. Under Review. 


#### Papers
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
