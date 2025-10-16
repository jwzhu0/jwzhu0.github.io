---
title: "SpecSolver: Solving Spatial-Spectral Fusion via Semantic Transformer"
collection: publications
category: conferences
permalink: /publication/specsolver
excerpt: 'SpecSolver is a semantic transformer-based solver for spatial-spectral fusion.'
date: 2025-07-06
venue: 'In Proc. ACMMM'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
# paperurl: 'http://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
By clustering pixels with locally similar values, superpixel-based approaches have shown great potential in processing hyperspectral
images (HSI) , thereby reducing the computational burden associated with large spatial dimensions. However, specific for spatialspectral fusion (SSF), superpixel segmentation is inherently nondifferentiable and irreversible; hence it is inapplicable. To address the issues, we propose a semantic transformer-based solver, namely
SpecSolver, which is basically inspired by the benefits of superpixelbased approaches, yet with the inner mechanism completely improved. The core idea lies in learning the intrinsic semantic states of
HSIs hidden behind discretized pixel representations. Specifically, we propose a new Semantic-Attention to adaptively split the image
domain into a series of learnable slices of flexible shapes, where image pixels under similar semantic states will be ascribed to the same
slice. By calculating attention to the Semantic-Superpixel tokens encoded from slices, SpecSolver can effectively capture intricate
semantic correlations from the vast number of pixels, which also empowers the solver with an endogenous capacity for modeling different magnification scales and allows for efficient computation in
linear complexity. On that basis, we elaborate a SpatialNet module, which extracts multiscale local spectral information, and a FreqNet module, which supplements global information, capturing subtle
details and variations across different spectra. Experiments on two benchmark SSF datasets verify the state-of-the-art (SOTA) performance of the proposed method, both visually and quantitatively.
Also, ablation studies validate the mentioned contributions.
