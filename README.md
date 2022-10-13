<div><img src="https://wx1.sinaimg.cn/mw690/00752cx4ly1giwaot2hg8j30u00uzmya.jpg" width=256></div>

#
[![](https://img.shields.io/badge/Download-Latest-yellow.svg)](https://github.com/BIMK/PlatEMO/archive/master.zip) 
[![](https://img.shields.io/github/release/BIMK/PlatEMO.svg)](https://github.com/BIMK/PlatEMO/releases/)
[![](https://img.shields.io/badge/Matlab-%3E%3D%202018a%20-blue.svg)](#PlatEMO)  
[![](https://img.shields.io/badge/Windows-Pass-brightgreen.svg)](#PlatEMO)
[![](https://img.shields.io/badge/Linux-Pass-brightgreen.svg)](#PlatEMO)
[![](https://img.shields.io/badge/MacOS-Pass-brightgreen.svg)](#PlatEMO)
<h3>Evolutionary multi-objective optimization platform</h3>
Developed by BIMK (Institute of Bioinspired Intelligence and Mining Knowledge) of Anhui University and NICE (Nature Inspired Computing and Engineering Group) of University of Surrey
<div>
<img src="https://wx2.sinaimg.cn/mw690/00752cx4ly1gnpnfh0i4yj30m80m83zx.jpg" width=160>
<img src="https://wx2.sinaimg.cn/mw690/00752cx4ly1gnpnfgz0ulj30px08n74t.jpg" height=140>
</div>

* 200+ open source evolutionary algorithms
* 400+ open source benchmark problems
* Powerful GUI for performing experiments in parallel
* Generating results in the format of Excel or LaTeX table by one-click operation
* State-of-the-art algorithms will be included continuously

Thank you very much for using PlatEMO. The copyright of PlatEMO belongs to the BIMK Group. This
tool is mainly for research and educational purposes. The codes were implemented based on our
understanding of the algorithms published in the papers. You should not rely upon the material or
information on the website as a basis for making any business, legal or any other decisions. We
assume no responsibilities for any consequences of your using any algorithms in the tool. All
publications using the platform should acknowledge the use of “PlatEMO” and reference the
following literature:

## Copyright
> The Copyright of the PlatEMO belongs to the BIMK group. You are free to [use the PlatEMO](https://github.com/BIMK/PlatEMO/releases) for **research purposes**. All publications which use this platform or any code in the platform should **acknowledge the use of "PlatEMO" and reference** _"Ye Tian, Ran Cheng, Xingyi Zhang, and Yaochu Jin, PlatEMO: A MATLAB Platform for Evolutionary Multi-Objective Optimization [Educational Forum], IEEE Computational Intelligence Magazine, 2017, 12(4): 73-87"._  

```
@article{PlatEMO,
  title={{PlatEMO}: A {MATLAB} platform for evolutionary multi-objective optimization},
  author={Tian, Ye and Cheng, Ran and Zhang, Xingyi and Jin, Yaochu},
  journal={IEEE Computational Intelligence Magazine},
  volume={12},
  number={4},
  pages={73--87},
  year={2017},
}
```

# Release Highlights of PlatEMO 4.0
[Release Note can be found here](./Doc/releasenote.md)
* Dynamic optimization, multitasking optimization, bilevel optimization, and robust optimization are now supported in PlatEMO.

* Hybrid encoding is now supported in PlatEMO, where a problem can include real variables, integral variables, label variables, binary variables, and permutation variables simultaneously.

* Maximum runtime is provided as a new termination criterion, which can be set instead of maximum number of function evaluations.

* More algorithms and problems for single-objective optimization, multi-objective optimization, constrained optimization, sparse optimization, expensive optimization, multimodal optimization, dynamic optimization, multitasking optimization, bilevel optimization, and robust optimization. There are currently 216 algorithms and 432 problems in the platform.

* More efficient and powerful GUI, where the execution of algorithms in the test module and application module is highly accelerated.

* More performance metrics for different types of optimization problems, and the metrics are also tagged with labels. Different metrics will be shown in the dropdown lists when selecting different labels in the GUI.

* Gradient based search is now supported in PlatEMO, where users can define gradient functions to accelerate the convergence via mathematical programming algorithms and gradient assisted evolutionary algorithms.


# Features of PlatEMO
*  Totally Developed in MATLAB  
PlatEMO consists of a number of MATLAB functions without using any other libraries. Any machines able to run MATLAB can use PlatEMO regardless of the operating system.  

*  Includes Many Popular Algorithms  
PlatEMO includes more than ninety existing popular MOEAs, including genetic algorithm, differential evolution, particle swarm optimization, memetic algorithm, estimation of distribution algorithm, and surrogate model based algorithm. Most of them are representative algorithms published in top journals after 2010.  

*  Various Figure Demonstrations  
Users can select various figures to be displayed, including the Pareto front of the result, the Pareto set of the result, the true Pareto front, and the evolutionary trajectories of any performance indicator values.  

*  Powerful and Friendly GUI  
PlatEMO provides a powerful and friendly GUI, where users can configure all the settings and perform experiments in parallel via the GUI without writing any code.  

*  Generates Data in the Format of Excel or LaTeX  
Users can save the statistical experimental results generated by PlatEMO as an Excel table or LaTeX table, which can be directly used in academic writings. 

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=BIMK/PlatEMO&type=Date)](https://star-history.com/#BIMK/PlatEMO&Date)

# Support  
* [**recommend**] You can ask any question in [issues block](https://github.com/BIMK/PlatEMO/issues) and upload your contribution by pulling request(PR).   
* If you want to add your MOEA, MOP, operator or performance indicator to PlatEMO, please send the MATLAB code (able to be used in PlatEMO) and the relevant literature to field910921@gmail.com.  
* If you have any question, comment or suggestion to PlatEMO or the algorithms in PlatEMO, please contact Ye Tian (field910921@gmail.com) or join the group of QQ(Group number: 721627832).    

<img src="https://wx2.sinaimg.cn/orj360/00752cx4ly1h3o150chxij309x0afwg2.jpg" width=180>  

# Acknowledge  
This repo belongs to BIMK group and has been transferred project from [BIMK](http://bimk.ahu.edu.cn/) to github by Ye Tian and Shichen Peng[@anonymone](https://github.com/anonymone).
