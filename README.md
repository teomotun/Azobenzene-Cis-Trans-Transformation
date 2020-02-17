# Azobenzene-Cis-Trans-Transformation

![Picture1.png](Picture1.png)

Azobenzene (pictured above) is a photosensitive molecule that has been used to design photoresponsive materials such as adsorbents, surfactants, and self-assembled nanostructures. The N=N double bond isomerizes between the cis and the trans conformations when exposed to light. The trans→cis transition occurs when the molecule is exposed to ultraviolet light, whereas the cis→trans transition happens under blue Visible light. 

I examined the electronic absorption spectrum of trans-diazobenzene using the CIS(D) method. Configuration Interaction Singles (CIS) gives the same solution as
Hartree-Fock for the ground state, but is the simplest method to study excited electronic states. CIS(D) is a 2-
order perturbation method that uses CIS as its reference (just like MP2 uses the Hartree-Fock solution as a
reference).

## PROCEDURES

* Used N.C State University Hyper Computing Cluster to build a Gaussian input file for a geometry optimization of trans-azobenzene in vacuum using B3LYP with the 6-31G* basis set.

* Ran a geometry optimization in the cluster and requested a single-point energy calculation (SP) using the CID(S) method with the 6-31G* basis set using the converged geometry read from the checkpoint file.

* I compared the result to the values from Fliegl et al., J. Am. Chem. Soc. 125, 9821 (2003) and the method performed really as welll as shown below in the report file
