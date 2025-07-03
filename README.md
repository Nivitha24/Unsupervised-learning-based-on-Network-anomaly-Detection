# Unsupervised-learning-based-on-Network-anomaly-Detection
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
/
