# Transfer-Function-GA
Genetic Algorithm for the Matter Transfer Function

The file Transfer_Function_GA.nb is a Mathematica notebook with the Genetic Algorithm used to find the Matter Transfer Function shown in . The notebook has several comments to help the reader of the code. However, further comments are always very welcome. 

In Data.zip you will find the following files:

1) CLASS_Data.ipynb: a jupyter notebook to compute the gravitational potential as a function of the scale k. It will create two datasets:

    i) DataGraTz0.txt, where the reduced density parameters of baryons and cold dark matter are varying, and,
    
   ii) DataGraTz0_nu.txt, where also the mass of one massive neutrino varies.

2) Save_State.txt: Dataset containing the data retrieved from the search of the best GA configuration, specifically, population, crossover probability, mutation probability, and the random seed. The best-fit function found here is then used for a long run (50000 generations).

3) Elite.txt: Dataset containing the value of the fitness for each generation (50000 in total) of the best-fit function found by the GA.
