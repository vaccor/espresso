# Espresso AI 3-Class (EAI-3Class) Multiclass logistic regression classifier
## Objective
This work presents a supervised multiclass predictive model that replaces rigid deterministic rules with a probabilistic, data-driven methodology capable of handling heterogeneous and incomplete real-world datasets. By learning from diverse key performance indicators provided in the data set, the model automatically categorizes mobile-network sites and can assist in several use cases such as the early detection of potential faults.
## Dataset
Source: “KPI_set2”: 6 KPIs from “CIB_Network@20250930” (from MUSA Project “CIB_for_Espresso”). Size: 5.933.520 records
Useful for training: 6 KPI, 4 contextual features,target class performance class (Good, Medium, Poor).
## Model Goals 
Multiclass logistic regression computes one linear score per class, transforms them into probabilities using a softmax function, and assigns the class with the highest probability via argmax.
## Development
JupyterLab 4.5.0, Msty Studio 2.2.1, Language Python 3.11 and 3.10, Libraries NumPy, Pandas, Sklearn, Matplotlib, Joblib. 
## Collaborator
ChatGPT 4o Plus.
## Bibliography and Inspiration
Python and Machine Learning A. Bellini, A. Guidi, McGraw-Hill. The Machine Learning Gym A. Metelli, F. Trovò , McGraw-Hill. Deep Learning, S. Weidman, Tecniche Nuove
