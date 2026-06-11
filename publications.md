---
layout: page
title: "Publications"
permalink: /publications/
---
<div class="card-box">
      <h2>A Hybrid Lung and Colon Histopathological Image Classification Framework Using MobileNetV3-Small Deep Features and Differential Evolution Optimization</h2>
      <i>MDPI, Diagnostics 2026, 16(9), 1256</i>
      <br>
      <p style="text-align: justify;">
      Background/Objectives: Cancer remains one of the leading causes of mortality worldwide, with lung and colon cancers among the most prevalent. Conventional histopathological diagnosis is time-consuming, requires expert pathologists, and is susceptible to human error. Methods: To address these limitations, this study proposes an automated classification framework for lung and colon cancer using histopathological images. The proposed method employs a lightweight pretrained deep learning model, MobileNetV3-Small, through transfer learning. Training is performed on an enhanced version of the LC25000 dataset, in which redundant image patches are removed to improve robustness and clinical generalizability. The images were initially available in multiple resolutions, which are resized to 224 × 224 × 3 to match the canonical input size of MobileNetV3-Small. Deep features are extracted from the dropout layer as it provides regularized representation of high-level features by reducing the overfitting (dimension N × 1024), which are optimized using a differential evolution algorithm, reducing the feature space to N × 60. These optimized features are evaluated using multiple classifiers. Results: Experimental results demonstrate a maximum classification accuracy of 98.14% using a Quadratic Support Vector Machine (SVM) and a 21.3× speed-up achieved with bagged trees, outperforming several state-of-the-art approaches representing a 3.34% improvement over the baseline study on the enhanced dataset. Conclusions: The results confirm that the proposed framework effectively balances high accuracy with computational efficiency. The use of a lightweight deep model combined with feature optimization makes the approach well-suited for practical clinical environments.
      </p>
      lung and colon cancer; histopathological imaging; deep learning; transfer learning; feature optimization; classification
      <br>
      <p class="social-icons">
            <a href="https://doi.org/10.3390/diagnostics16091256"><i class="fa-solid fa-link"></i></a>
      </p>
</div>
<div class="card-box">
      <h2>Lung Cancer Classification through Transfer Learning and Deep Feature Extraction using EfficientNetB3</h2>
      <i>Journal of Computing & Biomedical Informatics, 9(02)</i>
      <br>
      <p style="text-align: justify;">
      Worldwide, lung cancer is one of the deadliest diseases. It is critical to make an early diagnosis of lung cancer for treatment. The standard process of diagnosis by a pathologist is by examining the histopathology images. The assessment of images by a pathologist is still prone to errors and time-consuming. To enhance the speed of the entire process and to accurately diagnose cancer in images, an automated procedure of cancer diagnosis is essential. In this paper, an automated process for lung cancer classification is proposed by using a pretrained deep model, EfficientNetB3. The proposed scheme uses lung cancer histopathological images, which are obtained from the ‘LC25000’ dataset. During the preprocessing phase, images were resized to a fixed dimension of 224x224x3 pixels. EfficientNetB3 was trained over 15,000 images of lung cancer classes, including squamous cell carcinoma, adenocarcinoma, and benign. After transfer learning, features are extracted from the model's second-to-last layer, or the dropout layer, which has an Nx512 dimension. The classifiers are then fed the feature vector as input to classify lung cancer after it has been divided into 80%, 10%, and 10% for training, validation, and testing. The proposed methodology is evaluated by different performance metrics, i.e., accuracy, recall, precision, FNR, TNR, FPR, F1-score, and misclassification rate. The results show that achieved the highest accuracy of 0.9980 with a misclassification rate of 0.0020, which was achieved by the proposed technique for Bilayered NN, which represents an improvement over the state-of-the-art techniques.
      </p>
      Keywords: Lung Cancer, CNN, Histopathology Images, Transfer Learning, EfficientNetB3
      <br>
      <p class="social-icons">
            <a href="https://www.jcbi.org/index.php/Main/article/view/1076"><i class="fa-solid fa-link"></i></a>
      </p>
</div>