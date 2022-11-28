# Transfer-Function-GA
Genetic Algorithm for the Matter Transfer Function

The file Transfer_Function_GA.nb is a Mathematica notebook with the Genetic Algorithm used to find the Matter Transfer Functions shown in https://arxiv.org/abs/2211.06393. The notebook has several comments to help the reader. However, further comments to improve the presentation of the code are always very welcome. 

In Data.zip you will find the following files:

1) CLASS_Data.ipynb: a jupyter notebook to compute the gravitational potential as a function of the scale k, and the reduced density parameters of baryons, matter, and massive neutrinos. It will create two datasets:

    i) Transfer_Function.txt, where the reduced density parameters of baryons and cold dark matter are varying, and,
    
   ii) Transfer_Functions_Neutrinos.txt, where also the mass of one massive neutrino varies.

2) Save_State.txt and Save_State_Neutrinos.txt: where we look for a "good randomseed" for the GA. The randomseeds producing the best-fit candidates are used in long runs of the GA (10000 generations).

3) Accuracy_Evolution.txt and Accuracy_Evolution_Neutrinos.txt: Datasets containing the value of the fitness for each generation (10000 in total). They are used to plot the evolution of the fitness of the population through the generations.

The GA code is based in the code by Savvas Nesseris which you can find at https://members.ift.uam-csic.es/savvas.nesseris/codes.html
