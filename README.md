# UB_Cyberbullying_Project

Full dataset is a .zip file in /data, the notebooks will automatically unzip the file

When experimenting on a subset of the data, cyberbullying_subset.pkl and non_cyberbullying_subset.pkl are pickle files of a list containing the path of 100 cyberbullying and non_cyberbullying images respectively

The feature_generation folder contains code for automatically generating and selecting features for a CoT prompt

Currently, a general zero-shot prompt (GP.ipynb), a general zero-shot prompt with a definition (GP.ipynb, set with_def to True), a 10-shot prompt, and a CoT (CoT.ipynb) prompt are evaluated

General Prompt: 0.0 precision, 0.0 recall, 0.495 accuracy
General Prompt w/ Definition: 0.67 precision, 0.02 recall, 0.505 accuracy
10-shot Prompt: 0.66 precision, 0.24 recall, 0.55 accuracy
CoT prompt based on 5 factors: 0.76 precision, 0.38 recall, 0.63 accuracy
CoT prompt based on automatically generated features: 0.83 precision, 0.39 recall, 0.66 accuracy


