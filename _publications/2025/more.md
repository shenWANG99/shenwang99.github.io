---
title:          "City-Scale Radiance-Field Reconstruction via Mixture of Radio Experts"
date:           2025-11-24 00:01:00 +0800
selected:       true
pub:            "ACM Mobicom (CCF-A)"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-custom badge-success">Spotlight</span>'
pub_date:       "2026"

abstract: >-
    Accurately modeling the radiance field of 5G signals in urban environments is essential for reliable network operation and scalable planning of next-generation wireless systems. Recent advances in neural radiance fields NeRF^2 have shown great success in capturing the spatially continuous behavior of radio propagation. However, existing NeRF^2 frameworks remain limited to small-scale scenes, suffering from severe accuracy degradation and prohibitive computational costs when extended to city-scale deployments. In this work, we present Mixture of Radio Experts (MoRE), a mixture-of-experts architecture designed for city-scale 5G radiance field reconstruction. MoRE integrates two complementary components: (i) a Mixture of Cell Experts, where each expert captures localized attenuation effects within distinct geographic regions; and (ii) a Mixture of Radiance Experts, which leverages shared and dynamically routed experts to model diverse propagation phenomena. To evaluate MoRE, we conducted a large-scale measurement campaign comprising 7,073,565 timestamped and geotagged RF samples from 13,602 base stations across 1,900 km^2 in a tier-one city. Experimental results show that MoRE delivers up to a 16 dB improvement over standard NeRF^2 by scaling from 0.69 million to 300 million parameters, while activating only 0.28% of the parameters (about 0.85 million) per inference.
cover:          assets/images/covers/more.jpg
authors:
  - Shen Wang
  - Guosheng Wang
  - Donghui Dai
  - Lei Yang
links:
#  Paper: https://doi.org/10.1145/3636534.3690706
#  Demo: https://www.youtube.com/watch?v=rP-Oe07ZGT4
  
---

