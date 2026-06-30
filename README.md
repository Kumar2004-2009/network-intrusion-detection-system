# Network Intrusion Detection System

A Machine Learning-based Network Intrusion Detection System (NIDS) that analyzes network traffic and classifies connections as **Normal** or **Attack**. The project leverages data preprocessing, feature selection, and multiple classification algorithms to detect malicious network activities and improve cybersecurity monitoring.

## 🚀 Features

- Network traffic classification into **Normal** and **Attack**
- Data preprocessing using Label Encoding and Standard Scaling
- Feature selection using Recursive Feature Elimination (RFE)
- Comparison of multiple machine learning models:
  - K-Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest
  - Logistic Regression
  - Bernoulli Naive Bayes
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Feature importance analysis for model interpretability
- Real-time intrusion prediction on unseen network connections

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📊 Workflow

1. Load and preprocess network traffic dataset.
2. Encode categorical features using Label Encoding.
3. Scale numerical features using StandardScaler.
4. Select important features using Recursive Feature Elimination (RFE).
5. Train multiple classification models.
6. Evaluate model performance using standard metrics.
7. Analyze feature importance and model behavior.
8. Predict intrusion status for new network traffic samples.

## 📈 Models Evaluated

| Model | Purpose |
|---------|---------|
| KNN | Distance-based classification |
| Decision Tree | Rule-based classification |
| Random Forest | Ensemble learning |
| Logistic Regression | Linear classification |
| Bernoulli Naive Bayes | Probabilistic classification |

## 📋 Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## 📁 Project Structure

```text
Network-Intrusion-Detection-System/
│
├── Train_data.csv
│── Test_data.csv
│
├──network-intrusion-detection.ipynb
│
└── README.md
```

## 🎯 Results

The project benchmarks multiple machine learning algorithms and identifies the most effective model for intrusion detection based on Accuracy, Precision, Recall, and F1-Score. Feature importance analysis provides insights into the network attributes that contribute most to attack detection.

## 🔮 Future Enhancements

- Deep Learning-based intrusion detection
- Real-time packet monitoring
- Streamlit dashboard for visualization
- Multi-class attack classification
- Deployment as a web application

## 🤝 Contributing

Contributions are welcome. Feel free to fork the repository and submit pull requests.

## 📜 License

This project is licensed under the MIT License.

---

**Developed using Python and Machine Learning for Network Security Analysis.**
