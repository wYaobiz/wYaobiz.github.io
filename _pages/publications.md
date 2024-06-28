---
layout: page
permalink: /publications/
title: publications
description:
years: [2022,2023,2024]
nav: true
nav_order: 1
---
<!-- _pages/publications.md -->

#### Preprints
<!-- - A survey on consortium blockchain consensus mechanisms. **Wei Yao**, Junyi Ye, Renita Murimi, Guiling Wang. [[arxiv](https://arxiv.org/abs/2102.12058)] -->
<!-- - Consensus Mechanisms in Consortium Blockchain: A Systematic Survey and Critical Analysis. **Wei Yao**, Fadi Deek, Renita Murimi, Guiling Wang.  -->
<!-- - VDKMS: Vehicular Decentralized Key Management System for Cellular Vehicular-to-Everything Networks, A Blockchain-Based Approach. **Wei Yao**, Yuhong Liu, Fadi Deek, Guiling Wang. Accepted by IEEE GLOBECOM 2023.  -->
<!-- - iBCTrans: A Practical Blockchain-Based Framework for Cellular Vehicular-To-Everything Networks.  **Wei Yao**, Yuhong Liu, Fadi Deek, Guiling Wang. Accepted by IEEE Blockchain 2023.   -->
<!-- - Considerations for Decision-makers and Developers toward Adoption of Decentralized Key Management Systems Technology in Emerging Applications. **Wei Yao**, Nicholas Gorlewski, Fadi Deek, Guiling Wang. Accepted by IEEE Computer. -->
- Establishing a Baseline for Evaluating Blockchain-Based Self-Sovereign Identity Systems: A Systematic Approach to Assess Capability, Compatibility, and Interoperability. **Wei Yao**, Wenlu Du, Jingyi Gu, Junyi Ye, Fadi Deek, Guiling Wang. Accepted by 2024 6th Blockchain and Internet of Things Conference (BIOTC 2024).


#### Papers
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
