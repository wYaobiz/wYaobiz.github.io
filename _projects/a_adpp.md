---
layout: page
title: ADPP
description: ADPP, a Novel Anomaly Detection and Privacy-Preserving Framework Using Blockchain and Neural Networks in Tokenomics
img: assets/img/project_preview/adpp_100.jpg
importance: 3
category: Academia
---

The increasing popularity of crypto assets has resulted in greater cryptocurrency investor interest and more exposure in both industry and academia. Despite the substantial socioeconomic benefits, the anonymous character of cryptocurrency trading makes it prone to abuse and a magnet for illicit purposes, which cause monetary losses for individual traders and erosion in the standing of the tokenomics industry. To regulate the illicit behavior and secure users' privacy for cryptocurrency trading, we present an Anomaly Detection and Privacy-Preserving (ADPP) Framework integrating blockchain and deep learning technologies. Specifically, ADPP leverages blockchain technologies to build a user management platform that ensures anonymity and enhances the privacy-preservation of user information. Atop the user management system, an Anomaly Detection System adapts neural networks and imbalanced learning on topological cryptocurrency flow among users to identify anomalous addresses and maintain a sanction list repository. The experiments on the real-world dataset demonstrate the effectiveness and superior performance of ADPP. The flexible framework can be easily generalized to the crypto assets with public real-time transaction (e.g., Non-fungible Token), which takes up a significant proportion of market capitalization in the domain of tokenomics.

The workflow of ADPP is shown in Figure 1. TCs first complete their initialization and provision process. TCs can then evaluate and authorize TPs who apply to establish a trading platform. Once a TP is authorized, a corresponding blockchain transaction is published on the TP-DLT. Authorized TPs then issue VCs to their customer PCs through blockchain transactions on the PC-DLT. With more transaction data available, ADS learns anomalous behaviors from crypto transaction data. The suspicious illicit addresses detected by ADS are added into SLR. When two PCs want to trade cryptocurrency, they can verify each other's credentials and check whether the counterparty is in the SLR. Note that ADS can either be maintained by TC or the TP consortium.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p_adpp_blockchain.jpg" title="ADPP Architecure" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 1. ADPP Architecure  
</div>

To extract topological dependence and temporal dynamics simultaneously from transaction networks, ADS integrates GCN with GRU, which are introduced in the previous section, into a sequence of layers, as shown in Figure 2.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/p_adpp.jpg" title="Anomaly Detection Model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Figure 2. Overall Structure of Anomaly Detection Model 
</div>
