---
layout: page
title: projects
permalink: /projects/
description: 
nav: true
nav_order: 3
display_categories: [published, working papers, work in progress]
horizontal: false
---
<div class="projects">

<h2 class="category"> Job Market Paper </h2>
<h5> Beyond Sparsity: Local Projections Inference with High-Dimensional Covariates </h5>
<span class="abstract-toggle" onclick="toggleAbstract(this)">[Abstract]</span> 
<p class="abstract-content hidden">
  Impulse response analysis studies how the economy responds to shocks, such as changes in interest rates, and helps policymakers manage these effects. While Vector Autoregression Models (VARs) with structural assumptions have traditionally dominated the estimation of impulse responses, local projections, the projection of future responses on current shock, have recently gained attention for their robustness and interpretability. Including many lags as controls is proposed as a means of robustness, and including a richer set of controls helps in its interpretation as a causal parameter. In both cases, an extensive number of controls leads to the consideration of high-dimensional techniques. While methods like LASSO exist, they mostly rely on sparsity assumptions - most of the parameters are exactly zero, which has limitations in dense data generation processes. This paper proposes a novel approach that incorporates high-dimensional covariates in local projections without relying on sparsity constraints. Adopting the Orthogonal Greedy Algorithm with a high-dimensional AIC (OGA+HDAIC) model selection method, this approach offers advantages including robustness in both sparse and dense scenarios, improved interpretability by prioritizing cross-sectional explanatory power, and more reliable causal inference in local projections.
</p>
<a href="https://drive.google.com/file/d/1zDoOTL6MqoVcN1KEJhjs2qlXNwv6x_vh/view?usp=drive_link">[Most Recent]</a>
<a href="https://arxiv.org/abs/2402.07743">[arXiv]</a>

<h2 class="category"> Published Papers </h2>
<h5> Inference in High-dimensional Regression Models without exact or \(L^p\) sparsity</h5>
- joint with <a href="https://sites.google.com/view/haroldchiang/">Harold D. Chaing</a> and <a href="https://sites.google.com/site/yuyasasaki/">Yuya Sasaki</a>
<br>
- <em>The Review of Economics and Statistics</em>, 2023
<br>
<span class="abstract-toggle" onclick="toggleAbstract(this)">[Abstract]</span> 
<p class="abstract-content hidden">
  We propose a new inference method in high-dimensional regression models and high-dimensional IV regression models. The method is shown to be valid without requiring the exact sparsity or \(L^p\) sparsity conditions. Simulation studies demonstrate superior performance of this proposed method over those based on the LASSO or the random forest, especially under less sparse models. We illustrate an application to production analysis with a panel of Chilean firms.
</p> 
<a href="https://doi.org/10.1162/rest_a_01349">[Published version]</a>
<a href="https://arxiv.org/abs/2108.09520">[arXiv]</a>
<a href="https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DFBV7K">[Replication Data]</a>

<h2 class="category"> Working Papers </h2>
<h5>Bounds for Standard Errors from Interdependent Data</h5>
- joint with <a href="https://sites.google.com/site/yuyasasaki/">Yuya Sasaki</a>
<br>
<span class="abstract-toggle" onclick="toggleAbstract(this)">[Abstract]</span>
<p class="abstract-content hidden">
  We propose a method to construct bounds for the standard error of a parameter estimated by moments from different samples. Using the best-possible distributional bounds of Frank, Nelsen, and Schweizer (1987), we construct bounds for the limit distribution, and then derive the bounds for its standard deviation based on them. We present a theory to guarantee the validity of this method. While Cocci and Plagborg-Møller (2021) propose an upper bound, we provide a lower bound in addition.
</p>




</div>