🎧 DeepFake Audio Detection Using MFCC and Pretrained VGG16

📌 Overview

This project presents a deep learning approach for detecting deepfake audio using MFCC (Mel Frequency Cepstral Coefficients) and a pretrained VGG16 model. The primary goal is to classify audio clips as real or fake with high accuracy, leveraging the visual representation of MFCC features and the transfer learning capabilities of VGG16.

🚀 Features

Utilizes MFCC for audio feature extraction

Employs pretrained VGG16 model for transfer learning

Detects deepfake audio with high accuracy

Works on the Fake or Real (FoR) Audio Dataset

Outperforms traditional ML models like SVM and Gradient Boosting

🧠 Model Architecture

Audio Preprocessing

Normalize and clean raw audio

Convert to a uniform format

Feature Extraction

Extract MFCC features from audio

Convert MFCC into image format suitable for CNN input

Model Training

Use a pretrained VGG16 model

Fine-tune the model for binary classification (real vs fake audio)

Evaluation

Assess model performance using accuracy, precision, recall, and F1-score
📈 Results

Accuracy: ~95%

Precision: High on both real and fake samples

Performance superior to traditional models

📚 Bibliography

Simonyan, K., & Zisserman, A. (2014). Very Deep Convolutional Networks for Large-Scale Image Recognition. arXiv preprint arXiv:1409.1556.

Sahu, P. K., & Jain, R. (2021). Audio Deepfake Detection using MFCC and CNN. IEEE Transactions.

FoR Dataset: https://github.com/RUB-SysSec/Audio-Deepfake-Detection

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📄 License

This project is licensed under the MIT License.

