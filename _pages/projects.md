---
layout: archive
title: "Theory and Simulation"
permalink: /theoryandsimulation/
author_profile: true
---

{% include base_path %}
Details of Project 1 and 2 can be found from the publications or [<b>here</b>](http://congshanwan.github.io/files/proposal_Congshan_Wan.pdf). 

**Project 1**: Efficiency Optimization and Angular Misalignment Analysis of Interlayer Grating Couplers 

* A new theory, the “equivalent index slab (EIS)” method, is proposed to extend the rigorous coupled-wave analysis (RCWA) to rectangular diffraction grating involving surface waves. The grating layer is replaced by multiple uniform slab waveguides, the equivalent index slabs, such that the field amplitudes and phases at the cover-grating interface and the grating-waveguide interface remain unchanged. <br/>
<center><img src="/images/fig_slab.png" alt="Equivalent Index Slabs" style="width:500px;height:250px;"></center>

* The proposed RCWA-EIS method can be used to calculate grating coupling efficiency of various grating structures, including binary gratings, sawtooth gratings, parallelogramic gratings, volume gratings, as well as grating with bottom reflectors, etc. The RCWA-EIS method, implemented in Matlab and solving problem analytically, is 2000 times faster than 2D FDTD, e.g. 0.1 second versus minutes. <br/>
<center><img src="/images/fig_gr_opt.png" alt="Optimized Gratings" style="width:700px;height:360px;"></center>

* The benefit of the RCWA-EIS method is that it solves the waveguide grating coupling problem from the in-coupling process, thus the conical incidence formulation can be used to model the angular misalignment effects. The RCWA-EIS calculation is 86400 times faster than 3D FDTD, which requires lots of iterations and computation memories! Here we are talking about seconds (RCWA-EIS) versus days (3D FDTD). <br/>
<center><img src="/images/fig_rot.png" alt="Rotated Bottom Grating" style="width:500px;height:300px;"></center>
<br/>

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_conf.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_conf.gif)  | 

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_001_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_100_eff.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/rotate_221_eff.gif)  |    


**Project 2**: Design of Grating-Assisted-Cylindrical-Resonant-Cavities (GARC) Interlayer Couplers 

* A fundamentally new  GARC coupler is proposed to achieve efficient and broadband interlayer coupling. The GARC coupler consists of three resonant cavities: two waveguide cavities in the horizontal direction and one cylindrical via cavity in the vertical direction. The structure of the GARC coupler and the spectral response are shown in the following figures. 

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/fig_garc.png)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/fig_GARC_bandwidth.png) |

* The movies show the field propagation in the GARC coupler (from left to right: vertical cross section, the bottom waveguide, and the top waveguide, simulation done by MEEP FDTD), assuming the input field is launched from the top waveguide from the right.

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/GARC_field_y.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/GARC_field_gr.gif) |

* GARC coupler is also simulated using Lumerical 3D FDTD. In this case, light is launched from the bottom waveguide, and thus GARC exhibits reciprocal coupling. <br/>
<center><img src="/images/fig_y_Hy_abs_show2.jpg" alt="GARC Lumerical" style="width:500px;height:130px;"></center>
<br/>



**Side Projects**: FDTD, FEM and BPM Simulations

* Self-coded 3D FDTD simulation of a patch antenna implemented in Matlab

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/antenna_Ez.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/antenna_Hx.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/antenna_Hy.gif)  |

* Self-coded 2D FDTD simulation using different boundary conditions implemented in Matlab

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/b_Ez_PEC.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/b_Ez_PMC.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/b_Ez_ABC.gif)  | ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/b_Ez_PML.gif)  |

* Self-coded 2D FEM simulation of a microstrip implemented in Matlab
<center><img src="/images/fig_FEM_potential.png" alt="FEM" style="width:500px;height:380px;"></center>

* Self-coded FFT-BPM simulation of a Mach–Zehnder interferometer implemented in Matlab

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/FFT_BPM1.png)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/FFT_BPM.png) |

* Self-coded FD-BPM simulation of a waveguide coupler implemented in Matlab

![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/fig_FD_BPM2.png)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/fig_FD_BPM3.png) |    ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/images/fig_FD_BPM4.png) |

* Lumerical Mode Solutions 2.5D var-FDTD simulation of a ring-resonator
<p align="center">
<img src="https://github.com/congshanwan/congshanwan.github.io/raw/master/files/ring_res_Hmag.gif"/>
</p>

* Lumerical Mode Solutions 2.5D var-FDTD simulation of an arrayed waveguide grating
![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/AWG1.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/AWG2.gif)  |  ![Alt Text](https://github.com/congshanwan/congshanwan.github.io/raw/master/files/AWG3.gif)  | 

* Lumerical FDTD Solutions port excitation of an interlayer grating coupler
<p align="center">
<img src="https://github.com/congshanwan/congshanwan.github.io/raw/master/files/lumerical_movie_gr.gif"/>
</p>

* Lumerical INTERCONNECT simulation of a 4-channel wavelength-division multiplexing network (PDK)
<center><img src="/images/interconnect_WDM_4ch2.png" alt="COMSOL" style="width:1000px;height:500px;"></center>

* MEEP FDTD simulation of a fiber grating coupler
<center><img src="/images/fig_meep.png" alt="MEEP" style="width:500px;height:350px;"></center>

* COMSOL FEM simulation of pillar size changes in a photonic waveguide
<p align="center">
<img src="https://github.com/congshanwan/congshanwan.github.io/raw/master/files/photonic_waveguide.gif"/>
</p>

* COMSOL FEM simulation of an interlayer grating coupler
<center><img src="/images/fig_inter_gr.png" alt="COMSOL" style="width:500px;height:350px;"></center>






