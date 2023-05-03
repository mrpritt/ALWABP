# A heuristic and a branch-and-bound algorithm for the assembly line worker assignment and balancing problem

This respository contains the instances and supplementary data used in Borba, Ritt, [A heuristic and a branch-and-bound algorithm for the assembly line worker assignment and balancing problem](http://dx.doi.org/10.1016/j.cor.2013.12.002), Comp. Oper. Res., 45:87–96, May 2014.

## Abstract

 In traditional assembly lines, it is reasonable to assume that task execution times are the same for each worker. However, in Sheltered Work Centres for Disabled this assumption is not valid: some workers may execute some tasks considerably slower or even be incapable of executing them. Worker heterogeneity leads to a problem called the Assembly Line Worker Assignment and Balancing Problem (ALWABP). For a fixed number of workers the problem is to maximize the production rate of an assembly line by assigning workers to stations and tasks to workers, while satisfying precedence constraints between the tasks. This paper introduces new heuristic and exact methods to solve this problem. We present a new MIP model, propose a novel heuristic algorithm based on beam search, as well as a task-oriented branch-and-bound procedure which uses new reduction rules and lower bounds for solving the problem. Extensive computational tests on a large set of instances show that these methods are effective and improve over existing ones.

## Supplementary material

* Detailed results for MIP model M1 by Miralles et al. (2008) from Table 3, columns M1: [M1](data/m1.csv).
* Detailed results for MIP model M2 from Table 3, columns M2: [M2](data/m2.csv).
* Detailed results for MIP model M3 from Table 3, columns M3: [M3](data/m3.csv).
* Detailed results for the iterated beam search by Blum and Miralles (2011) from Table 5, columns IBS: [IBS](data/ibs.csv).
* Detailed results for the hybrid genetic algorithm by Moreira et al. (2012) from Table 5, columns HGA: [HGA](data/hga.csv).
* Detailed results for the iterative genetic algorithm by Mutlu et al. (2013) from Table 6, columns IGA: [IGA](data/iga.csv).
* Detailed results for the interval probabilistic beam search from Table 5, columns IPBS: [IPBS](data/ipbs.csv).
* Detailed results for the branch-and-bound method from Table 7 and Table 8, columns B&B: [BB](data/bb.csv).
* The [instances](instances) proposed by Chaves et al. (2007).
* General [information on the instances](data/instances.csv).

## How to cite

```bibtex
%%%%% 2014 (6+3)
@Article{Borba.Ritt/2014,
  author =   {Leonardo M. Borba and Marcus Ritt},
  title =    {A heuristic and a branch-and-bound algorithm for the assembly line worker assignment and balancing problem},
  journal =  {Comp. Oper. Res.},
  year =     {2014},
  volume =   {45},
  pages =    {87--96},
  month =    may,
  doi =      {10.1016/j.cor.2013.12.002},
}
```
