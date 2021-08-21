# Awesome Multi-Agent Path Finding [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources about **Multi-Agent Path Finding**.

If you want to contribute to this list, please feel free to send a pull request or contact me.

## Contents
* [Multi-Agent Path Finding](#Multi-Agent-Path-Finding)
  * [Guide](#Guide)
  * [Survey](#Survey)
  * [Optimal](#Optimal)
  * [Suboptimal](#Suboptimal)
* [Others](#Others)
  * [Target-Assignment and Path-Finding](#Target-Assignment-and-Path-Finding)
  * [Anonymous MAPF problem](#Anonymous-MAPF-problem)
  * [MAPF with Deadlines](#MAPF-with-Deadlines)


## Multi-Agent Path Finding

### Guide
- [SoCS 2019] ([paper](https://arxiv.org/abs/1906.08291)) Multi-Agent Pathfinding: Definitions, Variants, and Benchmarks
- [AAAI 2013] ([paper](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.648.6789&rep=rep1&type=pdf)) Structure and Intractability of Optimal Multi-Robot Path Planning on Graphs
  - Studies the structure and computational complexity of optimal multi-robot path planning problems on graphs that are NP-hard.

### Survey
- [SoCS 2017] ([paper](https://people.engr.tamu.edu/guni/Papers/SOCS17-MAPF.pdf)) Search-Based Optimal Solvers for the Multi-Agent Pathfinding Problem: Summary and Challenges

### Optimal

#### 1. Search-based
- **A***
  - [AAAI 2010] ([paper](https://www.cs.huji.ac.il/~jeff/aaai10/02/AAAI10-039.pdf)) Finding optimal solutions to cooperative pathfinding problems (A\*+OD+ID*)
  
  - [AAAI 2012] ([paper](https://people.engr.tamu.edu/guni/Papers/PEA-AAAI12.pdf)) Partial-Expansion A* with Selective Node Generation (EPEA*) 
  - [JAIR 2014] ([paper](https://people.engr.tamu.edu/guni/Papers/EPEA-JAIR14.pdf)) Enhanced partial expansion A*  (EPEA*) 
  
  - [IROS 2011] ([paper](http://biorobotics.ri.cmu.edu/papers/paperUploads/iros2011_wagner.pdf)) M*: A Complete Multirobot Path Planning Algorithm with Performance Bounds
  - [ICRA 2013] ([paper](http://biorobotics.ri.cmu.edu/papers/paperUploads/ICRA2013_Ferner_ODrM_Optimal_Multirobot_Path_Planning_in_Low_Dimensional_Search_Spaces.pdf)) ODrM* optimal multirobot path planning in low dimensional search spaces (ODrM*)


- **CBS**
  - [AAAI 2012] ([paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI12/paper/viewFile/5062/5239)) Conflict-Based Search For Optimal Multi-Agent Path Finding (CBS)
  - [SoCS 2012] ([paper](https://people.engr.tamu.edu/guni/Papers/SOCS12-MACBS.pdf)) Meta-Agent Conflict-Based Search For Optimal Multi-Agent Path Finding (MA-CBS)
  - [IJCAI 2015] ([paper](https://www.ijcai.org/Proceedings/15/Papers/110.pdf)) ICBS: Improved Conflict-Based Search Algorithm for Multi-Agent Pathfinding (ICBS)
  - [ICAPS 2018] ([paper](http://idm-lab.org/bib/abstracts/papers/icaps18a.pdf)) Adding Heuristics to Conflict-Based Search for Multi-Agent Path Finding (CBSH)
  - [IJCAI 2019] ([paper](https://www.ijcai.org/proceedings/2019/0063.pdf)) Improved Heuristics for Multi-Agent Path Finding with Conflict-Based Search (CBSH-RM) (CBSH2)
  - [ICAPS 2020] ([paper](http://idm-lab.org/bib/abstracts/papers/icaps20c.pdf)) Multi-Agent Path Finding with Mutex Propagation (CBSH-MP)


- **ICTS**
  - [IJCAI 2011] ([paper](https://people.engr.tamu.edu/guni/Papers/ICTS-IJCAI11.pdf)) The Increasing Cost Tree Search for Optimal Multi-Agent Pathfinding (ICTS)
  
#### 2. Reduction-based

  - [AAAI 2013] ([paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI13/paper/view/6293/7140)) A general formal framework for pathfinding problems with multiple agents
  - [IJCAI 2016] ([paper](https://www.andrew.cmu.edu/user/gswagner/workshop/IJCAI_2016_WOMPF_paper_5.pdf)) Efficient SAT Approach to Multi-Agent Path Finding under the Sum of Costs Objective (SAT)
  - [IEEE 2016] ([paper](https://arxiv.org/pdf/1507.03290.pdf)) Optimal Multi-Robot Path Planning on Graphs: Complete Algorithms and Effective Heuristics (ILP)
  
#### 3. Hybrid

  - [(IJCAI 2019] ([paper](https://www.ijcai.org/proceedings/2019/0164.pdf)) Unifying Search-based and Compilation-based Approaches to Multi-agent Path Finding through Satisfiability Modulo Theories (SMT-CBS)
  - [IJCAI 2019] ([paper](https://www.ijcai.org/proceedings/2019/0179.pdf)) Branch-and-Cut-and-Price for Multi-Agent Pathfinding (BCP)


### Suboptimal

#### 1.  Search-based
- **A***
  - [AIIDE 2005] ([paper](https://www.aaai.org/Papers/AIIDE/2005/AIIDE05-020.pdf)) Cooperative Pathfinding (CA\*,HCA\*,WHCA\*)
  
- **ECBS**
  - [SoCS 2014] ([paper](https://www.aaai.org/ocs/index.php/SOCS/SOCS14/paper/viewFile/8911/8875)) Suboptimal Variants of the Conflict-Based Search Algorithm for the Multi-Agent Pathfinding Problem (ECBS)
  - [SoCS 2015] ([paper](http://idm-lab.org/bib/abstracts/papers/socs15b.pdf)) Feasibility Study: Using Highways for Bounded-Suboptimal Multi-Agent Path Finding (ECBS+HIGHWAY)
  - [SoCS 2021] ([paper](https://ojs.aaai.org/index.php/SOCS/article/view/18569/18358)) ECBS with Flex Distribution for Bounded-Suboptimal Multi-Agent Path Finding (FECBS)
  - [AAAI 2021] ([paper](http://idm-lab.org/bib/abstracts/papers/aaai21a.pdf)) EECBS: A Bounded-Suboptimal Search for Multi-Agent Path Finding (EECBS)
  
#### 2.  Reduction-based  
  - [ICRA 2010] ([paper](http://vigir.missouri.edu/~gdesouza/Research/Conference_CDs/IEEE_ICRA_2010/data/papers/0186.pdf)) Constraint-based multi-robot path planning (CSP)
  
  
## Others

### Target-Assignment and Path-Finding
  - [AAMAS 2016] ([paper](https://arxiv.org/pdf/1612.05693.pdf)) Optimal Target Assignment and Path Finding for Teams of Agents
    - Contains a discussion about the difference between anonymous and non-anonymous MAPF problems.
  - [AAMAS 2018] ([paper](http://act.usc.edu/publications/Hoenig_AAMAS2018a.pdf)) Conflict-Based Search with Optimal Task Assignment
  
### Anonymous MAPF
  - [AAAI 2015] ([paper](https://ojs.aaai.org/index.php/AAAI/article/view/9424/9283)) SCRAM: Scalable Collision-Avoiding Role Assignment with Minimal-Makespan for Formational Positioning

### MAPF with Deadlines
  - [IJCAI 2018] ([paper](https://arxiv.org/pdf/1806.04216.pdf)) Multi-Agent Path Finding with Deadlines
  
  
## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
