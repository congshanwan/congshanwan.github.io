---
layout: archive
title: "Theory and Simulation"
permalink: /theoryandsimulation/
author_profile: true
---

{% include base_path %}

Project 1: Efficiency Optimization and Angular Misalignment Analysis of Interlayer Grating Couplers 
* A new theory, the “equivalent index slab (EIS)” method, is proposed to extend the rigorous coupled-wave analysis (RCWA) to rectangular diffraction grating involving surface waves. The new RCWA-EIS method is less numerical sensitivity and more computationally efficient. In this method, the grating layer is replaced by multiple uniform slab waveguides, called the equivalent index slabs, such that the field amplitudes and phases at the cover-grating interface and the grating-waveguide interface remain unchanged. This step circumvents the necessity of constructing a large dimensional matrix and avoids round-off errors during matrix inversion. For example, in a grating structure that supports two propagating orders i=0 and i=1, the equivalent index slabs replicate the fields outside the grating region, as shown in the figure below. <br/>
<center><img src="/images/fig_slab.png" alt="Equivalent Index Slabs" style="width:600px;height:300px;"></center>

* The proposed RCWA-EIS method can be used to calculate grating coupling efficiency of various grating structures, including binary gratings, sawtooth gratings, parallelogramic gratings, volume gratings, as well as grating with bottom reflectors, etc. The calculations are compared with those obtained from FDTD simulations. <br/>
<center><img src="/images/fig_gr_opt.png" alt="Optimized Gratings" style="width:700px;height:360px;"></center>

* The benefit of the RCWA-EIS method is that it solves the waveguide grating coupling problem from the in-coupling process, thus conical incidence formulation can be used to model the angular misalingment effects. For example, if the bottom waveguide grating is rotated with respective to the top waveguide grating, the out-diffracted light from the top grating will be conically incident onto the bottom grating. The in-coupling efficiency into the bottom grating will be affected according to the relative rotation. The animated movies show the in-coupling efficiency changes as a function of rotation angle about the x axis, z axis, and an arbitrary vector [221].<br/>
<center><img src="/images/fig_rot.png" alt="Rotated Bottom Grating" style="width:500px;height:300px;"></center>

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_conf.gif)  | 

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_eff.gif)  |    













Project 2: Design and Fabrication of Grating-Assisted-Cylindrical-Resonant-Cavities (GARC) Interlayer Couplers for 2.5D/3D Integrated Photonics

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/ASi_movie_y_res150_t400.gif)
