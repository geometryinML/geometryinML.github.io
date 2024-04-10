---
layout: page
title: Lab Geometry Processing (MA-INF 2226, 9CP)
collection: teaching
permalink: /teaching/ss24/lab-geoproc
---

### Description

This lab course will offer projects related to recent topics in (3D) geometry processing. For most this will mean implementing an existing baseline or algorithm and then improving one aspect of it. The topics this semester are: 

**Triangle Mesh Reconstruction via Voronoi Diagrams**

Based on the following publication(s): [VoroMesh: Learning Watertight Surface Meshes with Voronoi Diagrams by Maruani et al. 2023](https://nissmar.github.io/voromesh.github.io/), [Voronoi Diagrams](https://en.wikipedia.org/wiki/Voronoi_diagram)

The proposed method generates general polygon meshes, however, triangle meshes are more common in geometry processing applications. The goal of the project is to implement the original method, construct generating sets from an already given triangle meshes and try to impose properties of these generating sets during optimization. Alternatively, the method can be extended from watertight meshes to open surfaces by introducing additional point labels. 


**Laplace-Beltrami Operator on Gaussian Splatting**

Based on the following publication(s): [Laplace-Beltrami: The Swiss Army knife of Geometry Processing by Solomon et al. 2015](https://www.cs.cmu.edu/~kmcrane/Projects/Other/SwissArmyLaplacian.pdf), [3D Gaussian Splatting for Real-Time Radiance Field Rendering by Kerbl et al. 2023](https://arxiv.org/abs/2308.04079)

Gaussian splatting has recently been very popular for geometry reconstruction and rendering. The goal of the project is to implement the Laplace-Beltrami operator, which is important for many geometry processing applications, on Gaussian splatting (this does not mean deriving any new forms for the operator but extending existing versions to work with the data representation and make use of all the given information) and show some example applications. 


**Fourier Features in Isometry-Invariant Networks**

Based on the following publication(s): [Harmonics of Learning: Universal Fourier Features Emerge in Invariant Networks by Marchetti et al. 2023](https://arxiv.org/pdf/2312.08550.pdf)

The goal of the project is to analyze and check the theory proposed in the paper for a wider range of groups, specifically the isometry group wrt. geodesic distance (classes of objects with the same surface distance, e.g. a human in different poses). This will include replicating the results from the paper and choosing/implementing/running existing isometry-invariant networks to analyze. The paper is quite math heavy, you will not be expected to understand every detail but doing the project requires a general understanding of it and possibly more extended reading than the other projects. Please self-evaluate if this is something you can do. 


**Assembly of Fractured Shapes**

Based on the following publication(s): [Breaking Bad: A Dataset for Geometric Fracture and Reassembly by Sellán et al. 2022](https://arxiv.org/pdf/2210.11463.pdf)

This is a recent dataset of geometric objects that were fractured and need to be reassembled to their original shapes. The challenge is that there is no overlap between the fractures. The goal of the project is to implement one baseline from the paper and then try to come up with your own algorithm that improves the baseline (can be an extension of the baseline or a completely new approach you came up with). 


### Requirements

* There are no formal course requirements.
* All projects will be implemented in Python and prior experience is highly recommended. There will be no introduction to Python and the projects will be hard to complete while learning the language. 
* Prior experience with 3D geometric data is beneficial but not necessary. 

### Participation

* Topics can be worked on in groups of max. three students. Working in groups is recommended but the expected amount of work done increases with a bigger group size. 
* If you would like to participate, send an email to laehner at cs.uni-bonn.de until **February 14th** with your two ranked preferred topics with a **short** reason why chose these, the names of your group members if you have any (everyone needs to send an email though) or if you are open to be assigned a group with free spots. 
* Groups and topics will be announced on February 15th.
* There will be (mostly in-person) office hours Tuesdays 10-12 (see Basis for the room) where you can get help with your project. Weekly attendance is not mandatory but there will be no meetings at other times/constant help via email so if you can never attend in this time slot, you are on your own. 
* You will be graded based on a final report and presentation done about your work (if what you did makes sense and is well presented/documented not necessarily if it also lead to good results). 
* The presentation will be 30min + 10 minutes questions.
* The final reports should be 10 pages (+ references) and use this [report template](https://cg.cs.uni-bonn.de/courses).
