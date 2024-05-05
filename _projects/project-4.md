---
title: "Learning to print"
collection: projects
---

[![styled-image](/images/Leap.png){: .align-left style="width: 30%;"}](/images/Leap.png) Laser powder bed fusion process promises to automate the fabrication of high quality custom designed metal parts. However, the relationship between the process parameters and the quality of the fabricated part is complex. Disentangling it requires one to solve multiscale multiphysics problems which are computationally very expensive, precluding the application of this approach to process optimization and control. During the printing process, temperature field, its gradient, and cooling rate have a significant effect on residual stress and microstructure of the fabricated part and consequently on the part properties. Hence, obtaining the relation between these quantities and the process parameters and their fast inference is imperative to optimizing the printing process. We propose a deep learning approach to learn these quantities from high fidelity thermo-fluid simulations of the printing process using the spherical particle hydrodynamics (SPH) method. We employ a convolutional neural network to learn the temperature field, its gradient, and cooling rate as a function of process parameters such as laser power, and laser speed, among others.  
  
[1] Perraudin, N., **Manav, M.**, Lin, Y., Afrasiabi, M., Perez-Cruz, F., Bambach, M., & De Lorenzis, L. Predicting temperature field, melt pool geometry, and their rate of change in additive manufacturing with a neural network based surrogate. *In preparation*.
