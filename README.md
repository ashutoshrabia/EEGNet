# EEGNet
<p> Intent-based brain-computer interfaces (BCIs) represent a promising technology for enabling direct 
communication between the brain and external devices, particularly benefiting individuals with severe motor 
impairments.The P300 speller paradigm is a key application that detects the P300 event-related potential for 
character selection.  </p>
 <p> The primary aim of this project is to enhance the accuracy of P300 signal classification in intent-based 
brain-computer interfaces (BCIs) using advanced machine learning techniques. By leveraging a combination 
of traditional machine learning models and state-of-the-art neural network architectures, such as EEGNet and 
LMDA-Net, the project aims to improve the reliability and performance of BCIs for more effective 
communication and control applications.</p>
<p> Also applied multiple machine learning techniques (SVM, Logistic Regression, Random Forest, etc) and deep learning model dedicated for EEG data ([EEGNET](https://arxiv.org/pdf/1611.08024.pdf)). </p>

| Model             | AUC Score            | Inference Time(CPU) | Inference Time(GPU)   | Accuracy                                                             |
| ----------------- | -----------------| -------------------------------- | --------------  | -------------------- |
| Random Forest | 0.73|  8.28 |  -|  73.2%|
| Stacknet | 0.76|  8.21 |  -|  76%|
| EEGNet | 0.79|  1.79 |  0.101|  75.32%|
| LMDANet| 0.81 |  4.43 |  0.242|  80.68%|
