---
layout: archive
title: "Theory and Simulation"
permalink: /theoryandsimulation/
author_profile: true
---

{% include base_path %}

Project 1: Efficiency Optimization and Angular Misalignment Analysis of Interlayer Grating Couplers 
* A new theory, the “equivalent index slab (EIS)” method, is proposed to extend the rigorous coupled-wave analysis (RCWA) to rectangular diffraction grating involving surface waves. The new RCWA-EIS method is less numerical sensitivity and more computationally efficient. In this method, the grating layer is replaced by multiple uniform slab waveguides, called the equivalent index slabs, such that the field amplitudes and phases at the cover-grating interface and the grating-waveguide interface remain unchanged. This step circumvents the necessity of constructing a large dimensional matrix and avoids round-off errors during matrix inversion. For example, in a grating structure that supports two propagating orders i=0 and i=1, the equivalent index slabs replicate the fields outside the grating region, as shown in the figure below. <br/>
<center><img src="/images/fig_slab.png" alt="Equivalent Index Slabs" style="width:500px;height:250px;"></center>

* The proposed RCWA-EIS method can be used to calculate grating coupling efficiency of various grating structures, including binary gratings, sawtooth gratings, parallelogramic gratings, volume gratings, as well as grating with bottom reflectors, etc. The calculations are compared with those obtained from FDTD simulations. The RCWA-EIS method, implemented in Matlab and solving problem analytically, is 2000 times faster than 2D FDTD, e.g. 0.1 second versus minutes. <br/>
<center><img src="/images/fig_gr_opt.png" alt="Optimized Gratings" style="width:700px;height:360px;"></center>

* The benefit of the RCWA-EIS method is that it solves the waveguide grating coupling problem from the in-coupling process, thus the conical incidence formulation can be used to model the angular misalingment effects. For example, if the bottom waveguide grating is rotated with respective to the top waveguide grating, the out-diffracted light from the top grating will be conically incident onto the bottom grating. The in-coupling efficiency into the bottom grating will be affected according to the relative rotation. The animated movies show the in-coupling efficiency changes as a function of rotation angle about the x axis, z axis, and an arbitrary vector [221] in the top coordinate system. The calculated results obtained from the RCWA-EIS method match pretty well with those obtained from 3d FDTD simulations. Once again, the advantage of the RCWA-EIS method is the calculation efficiency. The RCWA-EIS calculation is 86400 times faster than 3D FDTD, which requires lots of iterations and computation memories! Here we are talking about seconds (RCWA-EIS) versus days (3D FDTD). <br/>
<center><img src="/images/fig_rot.png" alt="Rotated Bottom Grating" style="width:500px;height:300px;"></center>
<br/>

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_conf.gif)  | 

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_eff.gif)  |    


Project 2: Design of Grating-Assisted-Cylindrical-Resonant-Cavities (GARC) Interlayer Couplers 
* The traditional rectangular grating couplers have many limitations, such as narrow spectral bandwidth, sensitive to misalignments/ridge variations, and the presence of substrate leakage loss, etc. In order to overcome these issues, I have invented a fundamentally new interlayer coupler, called the grating-assisted-cylindrical-resonant-cavities (GARC) coupler, to achieve efficient and broadband coupling. The GARC coupler consists of three resonant cavities: two waveguide cavities in the horizontal direction and one cylindrical via cavity in the vertical direction. Note that the resonant cavities are used for field enhancement, but they don't have very large Q as in resonators because field will leak out from the cavities into the waveguide by evanescent coupling. The waveguide cavities are modulated by Bessel-function-defined circular gratings. The structure of the GARC coupler and the spectral response are shown in the following figures. The movies show the field propagation in the GARC coupler (from left to right: vertical cross section, the bottom waveguide, and the top waveguide, simulation done by MEEP FDTD), assuming the input field is launched from the top waveguide from the right. We can see that the GARC coupler is efficient and much more broadband compared with the conventional rectangular grating coupler. 
<center><img src="/images/fig_garc.png" alt="GARC Coupler" style="width:500px;height:560px;"></center>
<br/>
<center><img src="/images/fig_GARC_bandwidth.png" alt="GARC Bandwidth" style="width:500px;height:350px;"></center>
<br/>
     
![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/GARC_field_y.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/GARC_field_gr.gif)
