# Kernalized-MICA
All the experiments are in the notebook `kMICA.ipynb`<br>
But we noticed that the projection algorithm (which uses the HOSVD function) returned the same results no matter which core tensor we got from the different MICA experiments. That is why we created a second notebook `kMICA_2.ipynb` that reports the same experiments as `kMICA.ipynb`, but we modified HOSVD, so that it does not perfom the local optimization part when truncation. 
By doing this, we noticed that the accuracy significatively increased for every experiments.
