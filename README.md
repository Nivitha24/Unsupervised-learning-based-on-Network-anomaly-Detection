![graph_9](https://github.com/user-attachments/assets/c17751d3-0eed-4df8-905b-205403e6f81e)![graph_8](https://github.com/user-attachments/assets/87981430-63e4-43fa-b730-17aef8d05b83)![graph_7](https://github.com/user-attachments/assets/bb1c7d6f-4630-482d-a8c8-ed0bcf32ea3a)![graph_1](https://github.com/user-attachments/assets/6a6e76b6-449e-42d5-9e53-87e25a5d11ac)# Unsupervised-learning-based-on-Network-anomaly-Detection
Using One class SVM, Isolation Forest and Local outlier Factor

📌 Project Overview: Unsupervised Anomaly Detection in Network Traffic
This project focuses on detecting anomalies in network traffic data using unsupervised machine learning algorithms. Since anomalies (e.g., intrusions, attacks, unusual patterns) are rare and often unlabeled, unsupervised methods are ideal for identifying such irregular behavior without prior knowledge of labels.

🎯 Objective
To build and evaluate various unsupervised learning models capable of identifying anomalies in a network dataset, with minimal supervision and high accuracy.

📂 Dataset
The dataset contains both normal and anomalous traffic records.

Each record is described by several numerical features extracted from network connections.

Class labels are used only for evaluation, not during training.

🧠 Models Used
One-Class SVM – Learns a decision boundary around normal data.

Local Outlier Factor (LOF) – Detects outliers based on local density differences.

Isolation Forest – Randomly isolates points to detect anomalies.

Autoencoder (Neural Network) – Reconstructs input data and flags high reconstruction loss as anomaly.

📊 Evaluation Metrics
Accuracy

Precision / Recall

ROC Curve

Confusion Matrix

Visualization of anomaly scores and decision boundaries

🔍 Key Highlights
Imbalanced data handling through unsupervised techniques.

Visualizations help interpret model behavior and detect performance gaps.

Autoencoder showed strong performance in identifying subtle anomalies.

✅ Outcome
All models were able to detect anomalies to varying degrees. Isolation Forest and Autoencoder performed particularly well on the test data. This proves the effectiveness of unsupervised models in real-world network security scenarios where labeled data is scarce.


## 🖼️ Output Screens / Visual Results
Below are the graphs generated during model training and evaluation.
Each graph helps visualize how the models performed on detecting anomalies.


### 📊 Output 1: Class Distribution in the Dataset

![graph_1](https://github.com/user-attachments/assets/32cc92ca-b3de-4c05-9381-a2b551d17c71)

### 📊 Output 2: Feature Distribution / PCA or t-SNE Projection

![graph_2](https://github.com/user-attachments/assets/280a0cac-5a05-4584-ace7-6ff0819cd382)


### 📊 Output 3: One-Class SVM - Training Set Visualization

![graph_3](https://github.com/user-attachments/assets/4a3e9a57-f4fd-475a-b6a0-b9b5538f7a56)

### 📊 Output 4: One-Class SVM - Test Set Performance

![graph_4](https://github.com/user-attachments/assets/73d486da-56f1-44d5-8fe6-7c4e985a8e03)

### 📊 Output 5: LOF - Training Set Performance

![graph_5](https://github.com/user-attachments/assets/a9ed8436-a265-4301-ad46-a15482f5282f)

### 📊 Output 6: LOF - Test Set Performance

![graph_6](https://github.com/user-attachments/assets/725cdbfc-1da4-401b-8955-d7b4da7c41c1)

### 📊 Output 7: Isolation Forest - Training Set Visualization

![graph_7](https://github.com/user-attachments/assets/59a82837-f6c0-4b5c-8dbc-1432df3584f2)

### 📊 Output 8: Isolation Forest - Test Set Detection

![graph_8](https://github.com/user-attachments/assets/3bd34f6f-70b1-4c9e-bb28-72b86fc7d670)

### 📊 Output 9: Autoencoder - Loss Distribution on Test Data

![graph_9](https://github.com/user-attachments/assets/91d53fb7-b037-4d86-bbed-a0b09e69e964)











