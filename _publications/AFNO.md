---
title: "Arbitrary-scale Fusion Neural Operator"
collection: publications
category: conferences
permalink: /publication/AFNO
excerpt: 'This paper employs neural operators to achieve arbitrary-scale spectral fusion for the first time.'
date: 2025-07-06
venue: 'In Proc. ACMMM'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
Spatial-spectral fusion offers a promising alternative to expensive equipment in high-resolution hyperspectral (HrHs) imaging. However, training separate models for different scaling factors remains costly. To address this, we propose the Arbitrary-scale Fusion Neural Operator (AFNO), a lightweight solution for HrHs fusion across arbitrary scalings. Instead of entities, AFNO treats low-resolution hyperspectral (LrHs) and high-resolution multispectral (HrMs) images as functions and performs meticulously designed integrations as the mapping operator. The key components include Attention-Driven Convolution Integration (ADCI) to restore discretization invariance disrupted by convolutions, Implicit Neural Functional Integration(INFI) for cross-domain interaction of spatial degradations, and Galerkin-type Integration as a decoder for high-frequency details. Additionally, the bonded activation opeartor are improved for the principle of continuous-discrete equivalence. Extensive experiments validate the superiority of our approach over cutting-edge
methods. Notably, AFNO holds significantly better generalization on arbitrary scaling factors, yet requiring only 0.07M parameters.
