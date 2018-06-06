# tom-fe
For TomFeBn project

05/18/2018
Several unsuccessful runs due to a SCF processing error. Chatted with EF and found coordinates have two molecules!

05/22/2018
Module upgrade yesterday, may affect runs, but full run time on optimizations and calculations have been completed for first successful tests. 
Unfortunately, forgot to change multiplicity on dft function, so error came up in the files. 
Can't run until incompatibility with slurm is fixed. 1106

05/24/2018
Run is working, set a run today 1541 for 6-31g basis
Able to fix dft issue

06/05/2018
Ran up to 6311g- learned to isolate out to one single Fe atom to ensure results. Eliminate auto symmetry and auto z (use noautosym 
and noautoz for future runs) Starting back again with 631g for single molecule.
