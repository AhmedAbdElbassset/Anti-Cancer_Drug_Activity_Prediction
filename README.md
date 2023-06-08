# Anti-Cancer_Drug_Activity_Prediction
![VectorVsGraph](https://github.com/AhmedAbdElbassset/Anti-Cancer_Drug_Activity_Prediction/assets/92690999/80690c69-56db-4f47-b686-8c91341877ce)

# Problem Definition

- Our goal is to create a model that can predict the effectiveness of chemical compounds against non-small cell lung cancer using complex chemical structured data. The model will be designed to distinguish between compounds that are effective and those that are not.
- input data consists of 2 feature sets: the first set represents the nodes, and the second set represents the edges between these nodes.
- output is if this chemical compound is effective 1 or not 0

# Data mining function

- classification and prediction

# Challenges

- Our dataset is stored in SDF files, which are chemical files that represent each sample as nodes and the edges that connect these nodes, along with the corresponding output. Therefore, we require a specialized function to extract the relevant information from these files.

- The data is imbalanced

# Model impact

- Addressing this medical problem has the potential to make significant progress in the field of medicine.

# The ideal solution

- Trial "9" GNN-FiLM Using RandomOverSample was the highest Test Accuracy = 88.37% with those Hyperparameters
- hidden_dim = 32, num_layers = 6, film_parameter_MLP_hidden_layers = 1
