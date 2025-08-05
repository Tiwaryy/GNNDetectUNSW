# GNNDetectUNSW
Graph Neural Network-based anomaly detection model using the UNSW-NB15 dataset. This project constructs dynamic contextual graphs and leverages an enhanced Graph Autoencoder with Tuned Behavior-Driven Scoring (TBDS) to identify anomalous activities in IoT networks.

🧠 GNN-Based Anomaly Detection using UNSW-NB15 Dataset
📌 Overview
This project applies Graph Neural Networks (GNNs) for anomaly detection in IoT networks using the UNSW-NB15 dataset. It constructs dynamic contextual graphs and employs an enhanced Graph Autoencoder (GAE) with Tuned Behavior-Driven Scoring (TBDS) to detect network intrusions effectively.

📁 Dataset
UNSW-NB15 Dataset
Preprocessed and converted into graph format.
@info: http://research.unsw.edu.au/projects/unsw-nb15-dataset

🛠 Features
Dynamic graph construction based on contextual behavior i.e., DCS score.
Graph Autoencoder model for learning node embeddings.
TBDS scoring mechanism for improved anomaly detection.
Custom metrics and visualizations for performance evaluation.

🧪 Requirements
Python ≥ 3.8
PyTorch
PyTorch Geometric
Scikit-learn
Pandas, NumPy, Matplotlib

install via: **_pip install -r requirements.txt_**
To run: **python main.py**
📓 [Click here to view the full implementation notebook](./GNN_Anomaly_Detection.ipynb)

STEPS INVOLVED:
Preprocess the dataset
Construct the graph
Train the GAE model
Apply TBDS scoring
Evaluate and visualize results

📊 Evaluation Metrics
ROC-AUC
Precision, Recall, F1-Score
Reconstruction Error Distribution

├── data/                   # Preprocessed dataset and graph
├── models/                 # GAE model and utility modules
├── main.py                 # Main training and detection script
├── utils.py                # Helper functions
├── requirements.txt
└── README.md

🔍 Results
Achieved high anomaly detection accuracy with significant improvement using TBDS over baseline GAE.
Visualizations of latent embeddings show strong class separation.
![Visualization Outputs](https://github.com/user-attachments/assets/c93b29f6-b2fa-49e6-8590-b827f81a28d7)


👤 Author
Shubham Kumar
linkedin.com/in/shubham-kumar-15414026b
