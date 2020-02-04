1. 我将要解决的问题是什么？
2. 最重要的问题是什么？
3. 它的核心关键在哪里？
4. 已有的解决方案有哪些？
5. 我如何才能做出更好的方案？
6. 我的方案应该如何拆解逐步，逐步实施？







论文研究计划

1. Lamb wave 在comsol 激发问题。

先不考虑使用压电激励，可以仅仅利用理想激励条件

理想激励条件，怎么开展？

激励条件设置需要注意固定边界，消除刚体移动。



（进展：S0 A0 从comsol 仿真出来了，为了明显看出效果，scale 比例2000） 

 ![image-20200204122722304](/Users/apprentice/Library/Application Support/typora-user-images/image-20200204122722304.png)

![image-20200204122728442](/Users/apprentice/Library/Application Support/typora-user-images/image-20200204122728442.png)

Dispersive 激励信号怎么添加？



sin(2*f*pi*t/10)*sin(2*pi*f*t)*(t<5/f) 



Comsol time domain physics 中怎么设置？默认含时间



Lamb wave low reliability of the structural health monitoring methods based on the Piezoelectric Transducer (PT). 



Structural health monitoring (SHM) technology has become ______________

Lamb wave and Piezoelectric Transducer (PT) based method is a promising one because it has large monitoring area and is sensitive to small damage. 

For aerospace applications, the above



Finite element analysis (FEA) has been widely studied in recent decades to achieve the simulation of the linear and non-linear LW propagation in isotropic structures, anisotropic structures and even complex structures. 



The method to simulate damage such as the crack of aluminum structures and the delimitation of composite plates by FEA has also been proposed. 



Some of the simulations do not take the PTs into account while some of the simulations consider the full Lamb wave excitation-propagation sensing by integrating the PTs with the FEA models. 



There are two branches of the lamb wave simulation which consider the PTs. The first branch uses the FEA to simulate the Lamb wave propagated in a structure and uses the piezoelectric constitutive equations in theory to calculate the Lamb wave excitation stress and the voltage of the lamb wave sensing signals. The other branch directly integrates the FEA model of the PTs with the Lamb wave simulation by using the electromechanical coupling between the PTs and the structure. The latter branch is called Multiphysics simulation. One physics is the electromechanical coupling governed by the piezoelectric constitutive equations to simulate the piezoelectric effect of the lamb wave excitation and sensing. The other one is the solid mechanics governed by the wave motion equations to simulate lamb wave propagation in a solid structure. 



The Multiphysics simulation is closer to the actual situation and has been validated by comparing the simulated results with the experimental results. 



Compared with the theory modeling and numerical analysis of the lamb wave, the simulation based on the FEA is more intuitive and easier to be applied to the complex structures. Furthermore, the spectral element method and quadrature element method which are based on higher order polynomials have also been studied to reduce the computational amount and improve the accuracy of the lamb wave simulation. 



Especially for a simulation method which fully considers the influence of time-varying conditions obtained by the PTs adhered on a structure. 



Among a lot of time-varying factors, the varying load condition is a main factor. According to the previous studies the structural load can introduce large variations to the velocity and amplitude of the lamb wave signals obtained by the PTs. 



Piezoelectric materials become electrically when strained. 









Although the early interest in acoustic surface waves ralated almost solely to seismological applications, and although such waves are becoming increasing ly important for NDE considerations, the principal impact of the acoustic surface wave field today and over the past frew years has been on signal processing, with important applications to radar, communications, and electronic warfare. It was the recognition that acosutic surface wavs could furnish a new approach to signal processing that gave the acoustic wave field its enormous impetus during the past decade.