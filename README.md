Differentially Private Federated Learning on Medical Data

- Base paper here: https://arxiv.org/abs/2101.11693 


## Abstract 
While rich medical datasets are hosted in hospitals distributed across the world, concerns on patients' privacy is a barrier against using such data to train deep neural networks (DNNs) for medical diagnostics. We propose Dopamine, a system to train DNNs on distributed datasets, which employs federated learning (FL) with differentially-private stochastic gradient descent (DPSGD), and, in combination with secure aggregation, can establish a better trade-off between differential privacy (DP) guarantee and DNN's accuracy than other approaches. Results on a diabetic retinopathy~(DR) task show that Dopamine provides a DP guarantee close to the centralized training counterpart, while achieving a better classification accuracy than FL with parallel DP where DPSGD is applied without coordination. 

## Folders:
 
1. `report`: includes the final report. For `1.Design document showing the reasons for the choice of privacy-preserving technique and the network architectural components.`
2. `private_training`: includes the source code and a JupyterNotebook tutorial for training the privacy-preserving model explained in the report. For `
3. 2.Source code for the implementation of the privacy-preserving design across various architectural components.`
4. `private_inference`: includes the source code and demo for running inference on the privately trained model. For `3.Tested code and Test Report for all implementations- Implementations of Privacy-Preserving AI Technique, Trained Data Model.`


## Tutorial

We provided a Jupyter Notebook for training on Google Colab. Please see the file `JNotebook_running_FSCDP_on_Colab.ipynb` in the `private_training` folder.


