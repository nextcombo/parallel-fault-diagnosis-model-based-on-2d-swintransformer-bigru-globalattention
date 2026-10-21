# Parallel Fault Diagnosis Model Based on 2D-SWinTransformer + BiGRU-GlobalAttention

1. Dataset: CWRU West Reserve University Bearing Dataset
2. Environment Framework: Python 3.9, PyTorch 1.8 or higher versions are compatible for execution
3. Accuracy: 100% accuracy on the test set
4. User Requirements: Paper requirements, graduation design requirements
5. Code Guarantee: The code is detailed with comments that can be run directly.
6. Note: We also provide accompanying model explanations (for learning network structures) and parameter tuning guidance! For those who need a graduation project or to write a paper, this is essential. The module is rich, innovative, and highly performant!!
A Highly Innovative Model Based on 2D-SwinTransformer + BiGRU-GlobalAttention
High innovation, evident results! Innovation points:
1. Preprocessing part: Combining Fast Fourier Transform (FFT) and Variational Mode Decomposition (VMD) for signal time-frequency and domain feature extraction, which can mine multi-scale features in fault signals;
2. We creatively propose not converting one-dimensional fault signals into two-dimensional images (stacking data) for 2D convolution learning based on the top-level model SWinTransformer, utilizing its window attention mechanism to extract local features of fault signals;
3. Propose a GlobalAttention-optimized BiGRU network model to extract multi-scale feature global temporal features after preprocessing fault signals;
4. Through parallel model fusion of two branches to extract local features and global temporal features, the representation ability of features is improved to achieve fault signal recognition, achieving excellent results!
Preface
This article is based on the CWRU bearing data, conducting data preprocessing using Fast Fourier Transform (FFT) and Variational Mode Decomposition (VMD), and finally implementing a parallel feature fusion model based on 2D-SWinTransformer + BiGRU-GlobalAttention for fault data classification through Python.
1. Data preprocessing for bearing faults
1.1 Import data
Refer to the previous article for preprocessing of fault classification 10, and the Case Western Reserve University bearing data set: Classification 10 dataset.
\ttrain_set, val_set, test_set are all divided into training set, validation set and test set according to the ratio of 7:2:1, and finally save the data.
1.2 Fault FFT Transformation Visualization
\t1.3 Fault VMD Decomposition and Visualization
\t1.4 Preprocessing of fault data feature dataset
\t  
2. Bearing Fault Diagnosis Classification Based on 2D-SwinTransformer + BiGRU-GlobalAttention
2.1 Set parameters and train the model
\t  
2.2 Model Evaluation
Accuracy, Precision, Recall, F1 Score
\tFault classification confusion matrix:
\tOther visualizations:
(1) Classification Label Visualization
(2) Original Data t-SNE Feature Visualization
(3) t-SNE feature visualization after model training:
The model classification effect is significant, achieving 100% accuracy with 50 epochs. The Fast Fourier Transform (FFT) and Variational Mode Decomposition (VMD) can effectively mine multi-scale features from signals. The 2D-SwinTransformer + BiGRU-GlobalAttention model innovatively extracts spatial and temporal features of bearing fault signals, exhibiting fast convergence and superior performance. It accurately captures critical features from the frequency and time domain characteristics of fault signals, significantly enhancing its effectiveness.
Click to download: Complete original data, Python code
Previously Featured Content:
Python-Case Western Reserve University (CWRU) Bearing Data Interpretation and Classification Process
Python Bearing Fault Diagnosis (I) Short-Time Fourier Transform STFT
Python Bearing Fault Diagnosis (II) Continuous Wavelet Transform CWT
Python Bearing Fault Diagnosis (III) Empirical Mode Decomposition EMD
Pytorch-LSTM Bearing Fault One-Dimensional Signal Classification (I)
Pytorch-CNN Bearing Fault One-Dimensional Signal Classification (II)
Pytorch-Transformer Bearing Fault One-Dimensional Signal Classification (III)
Python Bearing Fault Diagnosis (IV) Fault Classification Based on EMD-CNN
Python Bearing Fault Diagnosis (V) Fault Classification Based on EMD-LSTM
Python Bearing Fault Diagnosis (VI) Fault Classification Based on EMD-Transformer
Python Bearing Fault Diagnosis (VII) Fault Classification Based on EMD-CNN-LSTM
Python Bearing Fault Diagnosis (VIII) Fault Classification Based on EMD-CNN-GRU Parallel Model
FFT + CNN - BiGRU-Attention Fusion of Time and Frequency Features for Bearing Fault Identification Model
FFT + CNN - Transformer Fusion of Time and Frequency Features for Bearing Fault Identification Model
Python Bearing Fault Diagnosis (IX) Fault Classification Based on VMD+CNN-BiLSTM
Python Bearing Fault Diagnosis (X) Fault Classification Based on VMD+CNN-Transformer
Python Bearing Fault Diagnosis (XI) Fault Classification Based on VMD+CNN-BiGRU-Attenion
Cross Attention Fusion of Time and Frequency Features for Bearing Fault Identification Model with VMD + CNN - BiLSTM-CrossAttention
Cross Attention Fusion of Time-Domain and Frequency-Domain Features for Bearing Fault Identification Model with FFT + CNN-Transformer
Introduction to Python Bearing Fault Diagnosis
Python Bearing Fault Diagnosis (13) Super Machine Learning Recognition Model Based on Fault Signal Feature Extraction
Python Bearing Fault Diagnosis (14) Highly Innovative Fault Recognition Model
Python Bearing Fault Diagnosis (15) One-Dimensional Fault Signal Recognition Model Based on CNN-Transformer
Python Bearing Fault Diagnosis (16) Highly Innovative Fault Recognition Model (II)
SCI 1st Class Highly Innovative Bearing Fault Diagnosis Model!
Python Bearing Fault Diagnosis (18) Innovative Diagnosis Model Based on CNN-TCN-Attention
Based on GADF+Swin-CNN-GAM Highly Innovative Bearing Fault Diagnosis Model
Attention Magic Modification | Super Bearing Fault Diagnosis Model!
Bearing Fault—Innovative Cross Attention Model Full Set
Python Bearing Fault Diagnosis (19) Innovative Diagnosis Model Based on Transformer-BiLSTM
END

## Images

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
