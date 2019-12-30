---
layout: post
title:  "Simulation of Microstructural evolution and analysis of grain growth kinetics"

img: sea.png # Add image post (optional)
date:   2019-12-24 18:24:51 -0500

---

* ### Analysing grain growth in gradiented microstructures: 

### Skills Learnt

* Surface Evolver
* Mathematica
* Linear Regression

### Libraries 

* Pandas
* Scipy


Surface Evolver was used to simulate grain growth under motion
by mean curvature starting with non-uniform microstructures. <img src = "{{site.url}}/assets/images/gradients.png" style="display: block; margin: auto;" />

The study was conducted for different microstructures that begin evolving with an identical mean grain area and a differing value of statistical variance of the grain areas. Correlation between a microstructure’s initial variance, a geometric property of the polycrystalline network, and its growth rate in the normal regime was studied. It was observed that the microstructures evolved at different growth rates. The microstructures with the largest and smallest variances evolved with highest and
lowest growth rates. The analysis was performed in the normal grain growth regime. It is observed that a direct correlation can be made between the initial variance of the microstructure and its growth rate in the normal regime. These results highlight the importance of including the grain size variance when controlling microstructure using non-uniform thermal fields.


<img src = "{{site.url}}/assets/images/GSD1_area_xc.gif" hspace="20" height="300" width="300" />
<img src = "{{site.url}}/assets/images/GSD1_subarea_xc.gif" hspace="20" height="300" width="300" />

   Variation of spatial distribution of area with time for Grain Size Distribution 1

<img src = "{{site.url}}/assets/images/GSD9_area_xc.gif" hspace="20" height="300" width="300" />
<img src = "{{site.url}}/assets/images/GSD9_subarea_xc.gif" hspace="20" height="300" width="300" />

  Variation of spatial distribution of area with time for Grain Size Distribution 9


<img src = "{{site.url}}/assets/images/SDvsK1-4.png" style="display: block; margin: auto;"/>

  Variation of normalized grain growth rate as a function of the initial standard deviation of the microstructure

* ### Studying the inter-dependence of microstructural and chemical parameters in influencing grain growth regimes: 
We investigate the kinetic regimes of solute segregation inhibited grain growth under the condition of dynamic solute redistribution between the grain boundaries and the bulk.Langmuir-Mclean's analytical framework is adopted to model solute equilibrium between grain boundaries and the bulk, and the Gibbs adsorption isotherm is used to model the dependence of the grain boundary energy on the solute mole fraction. The inhibition of grain growth is incorporated in the model through a segregation-induced reduction in the grain boundary interfacial energy. Two-dimensional numerical simulations, performed by implementing this model within the framework of Surface Evolver, are used to validate predictions from the analytical framework and provide insights into the kinetic behavior of alloy systems under the given conditions. The bulk mole fraction of solute (X-bulk) is modeled as a dynamic variable during the growth process, and an analytical form for X-bulk corresponding to zero grain boundary inter-facial energy (X-bulk* ) is derived. Under the stated assumptions, two different regimes of grain growth are identified depending on the steady state value of X-bulk. When X-bulk is asymptotic to X-bulk* , grain growth is completely impeded, whereas when it is asymptotic to X-tot, the total mole fraction of solute in the material, grain growth continues unimpeded. A parameter, X-ratio (X-bulk* /X-tot), which encapsulates information about the alloy system as well as about the microstructure, is defined. It is shown the n-exponent predicted for an alloy system strongly depends on the magnitude of X-ratio, thereby suggesting its potential as a feature vector component in the material design process for grain growth stability.

<img src = "{{site.url}}/assets/images/Regime-Summary.png" style="display: block; margin: auto;" />

