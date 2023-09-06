This code computes the random walk (electrostatic) capacity of certain three and four dimensional sets. The file "Cap.nb" computes those capacities, which are stored in the file "SRWCapacityData.nb", and the file "Errors.nb" computes the maximal error made by these computations.  It is used to prove Lemma B.4 in the article "Phase transition for the late points of random walk" by the same authors to determine the sets whose capacity is larger than the capacity of two points at infinite distance.

The main part of the code computes the Green function of certain points using the method from "The lace expansion for self-avoiding walk in five or more dimensions" by Hara and Slade (Rev. Math. Phys., 4(2):235–327, 1992). This method has already been used in the notebook "SRW.nb" available at 

https://www.fitzner.nl/noble/noble.html

 for the computer-assisted proof of the paper "Generalized approach to the non-backtracking lace expansion" by Fitzner and van der Hofstad (Probab. Theory Related Fields, 169(3-4):1041–1119, 2017). We modify this notebook to fit our purposes.