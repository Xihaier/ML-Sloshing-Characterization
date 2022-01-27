# ML_Sloshing_Characterization
  Supplementary material for the manuscript titled "A Machine Learning-based Characterization Framework for Parametric Representation of Nonlinear Sloshing", authored by Xihaier Luo, Ahsan Kareem, Liting Yu, and Shinjae Yoo.

## Overview

  The growing interest in creating a parametric representation of liquid sloshing inside a container stems from its practical applications in modern engineering systems. The resonant excitation, on the other hand, can cause unstable and nonlinear water waves, resulting in chaotic motions and non-Gaussian signals. This paper presents a novel machine learning-based framework for nonlinear liquid sloshing representation learning. The proposed method is a parametric modeling technique that is based on sequential learning and sparse regularization. The dynamics are categorized into two parts: linear evolution and nonlinear forcing. The former advances the dynamical system in time on an embedded manifold, while the latter causes divergent behaviors in temporal evolution, such as bursting and switching. The proposed framework's merit is demonstrated using an experimental dataset of liquid sloshing in a tank under horizontal excitation with a wide frequency range and various vertical slat screen settings.

<p><img src="Framework/proposed_method.png" title="proposed method" width="700"><p>

## Methodology
The propsoed method contains two phases: clustering and idenifcation.

<p><img src="Framework/phase_1.png" title="phase 1" width="700">
<p><img src="Framework/phase_2.png" title="phase 2" width="700">

## Attractor reconstruction 
These are the attractor reconstruction results for the two additional clusters studied in the paper. 
<p><img src="Framework/phase_1.png" title="phase 1" width="700">
<p><img src="Framework/phase_2.png" title="phase 2" width="700">
 
## CFD Simulation
We performed computational fluid dynamics simulations of liquid sloshing in a small tank with a middle water depth to better understand the nonlinear properties of water sloshing. Using experimental results, we are now validating the numerical model for simulation. Here's a look at what we have right now.

<p><img src="Simulation/20.gif" title="Excitation Amplitude 20mm" width="700"><figcaption>(a) Excitation Amplitude 20mm</figcaption><p>
<p><img src="Simulation/22.gif" title="Excitation Amplitude 22mm" width="700"><figcaption>(b) Excitation Amplitude 22mm</figcaption><p>
<p><img src="Simulation/50.gif" title="Excitation Amplitude 50mm" width="700"><figcaption>(c) Excitation Amplitude 50mm</figcaption><p>
<p><img src="Simulation/100.gif" title="Excitation Amplitude 100mm" width="700"><figcaption>(d) Excitation Amplitude 100mm</figcaption><p>
