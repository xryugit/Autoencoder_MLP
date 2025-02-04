# Autoencoder Combined with the Multilayer Perceptron for Alzheimer’s Disease Classification

Alzheimer's disease (AD) is a prevalent neurodegenerative disorder that poses significant challenges for accurate diagnosis and treatment. The classification of AD Neurofibrillary Changes (ADNC) levels is crucial for understanding disease progression and developing effective interventions. In this paper, a method was proposed for classifying ADNC levels based on single-cell RNA sequencing (scRNA-seq) data obtained from the SEA-AD dataset. An autoencoder was employed to reduce the dimensionality of the scRNA-seqdata, followed by a Multilayer Perceptron (MLP) for classification based on the autoencoder's embedding. The autoencoder effectively reduces the dimension of the scRNA-seq data from 4344 to 30 features. However, the embedding does not exhibit clear boundaries between different ADNC levels. The MLP model achieves a classification accuracy of 39% on the ADNC levels, indicating the complexity of the task and the need for more advanced classification methods. Additionally, theoverfitting in both models was observed, and dropout regularization is applied to mitigate this issue. While the results indicate the potential of feature extraction and dimensionality reduction using autoencoders, the accuracy of ADNC level classification remains limited. Combining multiple approaches and aspects in AD diagnosis is necessary, as RNA-seq data alone may not be sufficient for accurate prediction. Future work could explore more sophisticated classification algorithms to improve the accuracy of ADNC level classification and consider integrating other data modalities to enhance disease diagnosis and understanding.

<img width="454" alt="image" src="https://github.com/user-attachments/assets/6a19e67c-4181-4aef-a15c-6bdf14a4c74f">

**Figure 1:** The architecture of the autoencoder used in this study.


<img width="279" alt="image" src="https://github.com/user-attachments/assets/2e1f4a0f-0d83-4135-845f-6805530a94ba">

**Figure 2:** The architecture of the MLP.

