---
title: "Arbitrary-scale Fusion Operator for High-resolution Hyperspectral Imaging"
collection: publications
category: manuscripts
permalink: /publication/AFO
# excerpt: 'This paper is about the number 2. The number 3 is left for future work.'
date: 2025-07-14
venue: 'IEEE Transactions on Multimedia'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
# paperurl: 'http://academicpages.github.io/files/paper2.pdf'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

For high-resolution hyperspectral (HrHs) imaging, spatial-spectral fusion offers a promising alternative to expensive equipment. However, retraining multiple models for varied scaling factors is currently unavoidable, costing extra computational resource and human labor. To address this issue, we propose Arbitrary-scale Fusion Operator (AFO), a lightweight solution for HrHs fusion given arbitrary scalings, turning the
retraining strategy into “training-free” ones. Specifically, AFO treats low-resolution hyperspectral (LrHs) images and highresolution multispectral (HrMs) images as light-wise degraded functions within the spectrum, which are initially embedded into a high-dimensional space to simulate the original light signals, tapping the potential of enriched prior learning. Then, a flow of kernel integration (KI) is meticulously crafted, followed by a rival step of dimension reduction for HrHs generation. For a well-behaved KI computation, an Attention-Driven Convolution Integration (ADCI) is engineered to restore the broken discretization invariance derived by convolutions, yet with the locally inductive bias preserved. In addition, we propose an Implicit Neural Functional Integration (INFI) to achieve crossdomain interaction of spatial degradation functions, followed by the use of Galerkin-type Integration (GI) as a decoder to handle high-frequency information. Finally, the bonded activation functions are improved for the principle of continuous-discrete equivalence. Extensive experiments validate the superiority of our approach over cutting-edge methods. Notably, our proposal holds significantly better generalization on arbitrary scaling factors, yet requires only 0.07M parameters.