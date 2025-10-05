🧠 AI-Driven Intrusion Detection System (IDS)
Detecting Network Attacks Using Machine Learning

This project implements an AI-powered Intrusion Detection System that identifies malicious network activity using both unsupervised and supervised learning models.
The goal is to detect cyberattacks such as scanning, brute force, and data exfiltration using real-world network traffic data from the UNSW-NB15 dataset.

⚙️ Features

🧩 Preprocesses and cleans the UNSW-NB15 dataset (train + test sets)

🔢 Encodes categorical network features into numeric form

🤖 Trains two types of models:

Isolation Forest – Anomaly detection without labeled attack data

Random Forest – Supervised classification of attacks vs normal traffic

📊 Evaluates both models using:

Precision, recall, F1-score

Confusion matrix heatmaps

ROC curves and AUC scores

📈 Compares performance between unsupervised and supervised methods

🧪 Results Summary
Model	Type	Accuracy	ROC-AUC
Isolation Forest	Unsupervised	~45%	~0.70
Random Forest	Supervised	~90%	~0.95

Conclusion:
The unsupervised model effectively detects unusual patterns without labels, while the supervised Random Forest achieves higher accuracy when trained on labeled attack data.

📂 Dataset

UNSW-NB15 Dataset
Developed by the Australian Centre for Cyber Security (ACCS).
📦 Official Dataset Page

For this project, only two CSV files are required:

UNSW_NB15_training-set.csv
UNSW_NB15_testing-set.csv


Place them in a data/ folder or alongside the notebook in your project directory.

🧰 Requirements

Python 3.8 or higher

Jupyter Notebook

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn

🚀 Usage

Open Jupyter Notebook

Navigate to your project directory:

C:\Users\abdiq\Desktop\AI_IDS


Launch:

jupyter notebook


Open and run all cells in AI_IDS.ipynb

You’ll see:

Training and testing outputs

Performance metrics

Visualization plots (confusion matrices and ROC curves)

Comparison chart between models

⚠️ Warning

This project is for educational and research purposes only.

Do not deploy trained IDS models in live production networks without proper authorization.

The dataset simulates attack traffic — no real scanning or probing is performed.

Unauthorized use of intrusion detection tools or datasets on third-party systems may violate laws or institutional policies.

By using this repository, you accept full responsibility for your actions.

📊 Example Outputs

Confusion Matrix Heatmap

ROC Curve (Model Performance)

Model Comparison Bar Chart

🧑‍💻 Author

Abdiqani Hassan
AI-Driven Intrusion Detection System (IDS) — 2025
For cybersecurity, cloud, and AI research portfolio
