# L46_ifm24
L46 Coursework Project

This repository holds all of the scripts used to acquire the data for the plots presented in the L46 project submission for CSRID: Ifm24.

The data is not stored in this repository as it exceeds 10GB in size and, therefore, cannot be stored on GitHub. To access results and scripts go to: Architecture > Dataset and the script containing the results will be accessible there. For all of the figures from architecture please go to: Architecture > Dataset > Visualisation. All visualisations are held in these respective folders with the scripts to produce them included. Each script is identical in structure and was created to allow for computation to be done in parallel in Google Collab. 

Base model and independent model creation are done in the script, along with self-distillation and quantization in the training scripts. The implemented method for L1 pruning is held in the pruning folder, which contains the code to the novel implementation of L1 pruning in Keras for this work.
