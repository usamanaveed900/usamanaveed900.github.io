---
layout: page
title: "Publications"
permalink: /publications/
---

# Publications

## Lung Cancer Classification through Transfer Learning and Deep Feature Extraction using EfficientNetB3
_Journal of Computing & Biomedical Informatics_
Worldwide, lung cancer is one of the deadliest diseases. It is critical to make an early diagnosis of lung cancer for treatment. The standard process of diagnosis by a pathologist is by examining the histopathology images. The assessment of images by a pathologist is still prone to errors and time-consuming. To enhance the speed of the entire process and to accurately diagnose cancer in images, an automated procedure of cancer diagnosis is essential. In this paper, an automated process for lung cancer classification is proposed by using a pretrained deep model, EfficientNetB3. The proposed scheme uses lung cancer histopathological images, which are obtained from the ‘LC25000’ dataset. During the preprocessing phase, images were resized to a fixed dimension of 224x224x3 pixels. EfficientNetB3 was trained over 15,000 images of lung cancer classes, including squamous cell carcinoma, adenocarcinoma, and benign. After transfer learning, features are extracted from the model's second-to-last layer, or the dropout layer, which has an Nx512 dimension. The classifiers are then fed the feature vector as input to classify lung cancer after it has been divided into 80%, 10%, and 10% for training, validation, and testing. The proposed methodology is evaluated by different performance metrics, i.e., accuracy, recall, precision, FNR, TNR, FPR, F1-score, and misclassification rate. The results show that achieved the highest accuracy of 0.9980 with a misclassification rate of 0.0020, which was achieved by the proposed technique for Bilayered NN, which represents an improvement over the state-of-the-art techniques.

Key technologies used: Lung Cancer, CNN, Histopathology Images, Transfer Learning, EfficientNetB3

**[Link →](https://www.jcbi.org/index.php/Main/article/view/1076)**  

---