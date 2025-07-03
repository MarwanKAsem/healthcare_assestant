# 🩺 Symptom-to-Disease Classification

This repository contains a machine learning pipeline for classifying diseases based on reported symptoms. The project aims to support health-assistance applications by mapping user-described symptoms to likely diseases.

## Features

* End-to-end workflow in Jupyter Notebook
* Data preprocessing and symptom encoding
* Machine learning training and evaluation
* Performance metrics including accuracy, precision, recall, and F1-score
* Confusion matrix visualization

## 📂 Project Structure

```
Symptom_to_Disease_Classification.ipynb   # Main notebook
data/                                     # Dataset storage (optional)
README.md                                 # Project overview
requirements.txt                          # Python dependencies
```

## Methods

* Cleaning and encoding symptom data
* Feature engineering
* Model selection (e.g., Random Forest, Logistic Regression, etc.)
* Cross-validation for evaluation
* Confusion matrix analysis

## Results

* Baseline accuracy and evaluation metrics:

```
                         precision    recall  f1-score   support
             bronchitis       0.98      0.86      0.92       295
possible nstemi / stemi       0.88      0.61      0.72       150
                 anemia       0.98      0.94      0.96       140
                   urti       0.91      0.92      0.91       136
      viral pharyngitis       0.93      0.93      0.93       136
              pneumonia       0.91      0.88      0.89        98
        unstable angina       0.93      0.86      0.89        92
     allergic sinusitis       1.00      0.99      0.99        85
guillain-barré syndrome       0.99      0.94      0.96        80
        localized edema       1.00      0.97      0.99        79

micro avg       0.95      0.88      0.91      1291
macro avg       0.95      0.89      0.92      1291
weighted avg       0.95      0.88      0.91      1291
```


## ⚖️ Disclaimer

This project is intended for research and educational purposes only. It is not a substitute for professional medical advice or diagnosis.

## 📜 License

MIT License. See [LICENSE](LICENSE) for details.

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests.


🤝 Contributing
Feel free to open issues or submit pull requests to improve the model, add datasets, or extend functionality!
