# Deep-Learning-in-classification-of-common-Carp-intestine-classification
Master thesis revolving around applying differrent DL approaches to Common Carp microbiome classification 
If youd like to learn more about the project you can visit [project describtion](https://theta.edu.pl/grants/common_carp/).
Check out [poster](https://theta.edu.pl/wp-content/uploads/2025/05/Neural_nets_carp_aiEAAP-2025.pdf) or (Paper)[]

Abstract: 
Abstract 
Deep learning methods can overcome many challenges of high-dimensional, sparse microbiome data. This study aimed to apply and compare feedforward and convolutional neural networks combined with two dimensionality-reduction techniques—PCA and autoencoder embeddings—to classify probiotic treatments from common carp (Cyprinus carpio) gut microbiomes.
Abundance tables from 125 samples, transformed using CLR, served as the dataset for evaluating six configurations (raw-FNN, raw-CNN, PCA-FNN, PCA-CNN, AE-FNN, AE-CNN) under five-, three-, and two-class scenarios. Models were tuned via 5-fold cross-validation and trained with early stopping. Baselines included random assignment and XGBoost.
AE-FNN achieved the highest accuracy (84% in the five-class scenario), outperforming all other methods. PCA-FNN and raw-FNN also exceeded baseline performance in multi-class tasks, while CNNs; particularly without dimensionality reduction, underperformed, reflecting the lack of spatial structure in the input features. FNNs consistently matched or outperformed XGBoost, showing robustness on compositional data. Autoencoder embeddings captured nonlinear patterns that improved the most complex classification task.
Future work should incorporate feature-importance analysis to identify key taxa, integrate environmental and host metadata, and explore larger datasets and advanced architectures (e.g., graph or transformer models) to enhance predictive accuracy and biological insight.

Requirements: 
- Python 3.10
- numpy
- pandas
- matplotlib
- xgboost
- sklearn
- tensorflow
- imblearn
- seaborn
