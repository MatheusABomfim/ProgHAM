ProgHAM
Description:
The ProgHAM repository contains the implementation of a Gradient Boosting machine learning model trained to predict the prognosis of People Living with HTLV (PLwHTLV). The model was developed using a clinical dataset of 121 PLwHTLV, employing undersampling via Tomek Links to address data imbalance.

The goal of ProgHAM is to provide a predictive model that supports medical follow-up for patients, enabling better risk stratification for the progression of Tropical Spastic Paraparesis/HTLV-Associated Myelopathy (TSP/HAM).

🔬 Key Features
Data Preprocessing: Cleaning, normalization, and balancing using Tomek Links.
Model Training: Implementation of Gradient Boosting for clinical prognosis prediction.
Results Interpretation: Analysis of the importance of clinical features in forecasting TSP/HAM progression.
Reproducibility: Modular code and notebooks to facilitate pipeline execution.
📁 Model Development
The ProgHAM_model_development folder contains all the steps for model development, including:

Data preprocessing and feature selection
Model training and hyperparameter tuning
Performance evaluation and validation
Interpretability analysis
🖼 Repository Overview
To better illustrate the project, the README includes an image:


(Replace path/to/your/image.png with the actual image path in the repository.)

🚀 How to Run
Clone this repository:
bash
Copiar
Editar
git clone https://github.com/your-username/ProgHAM.git
cd ProgHAM
Install the dependencies:
bash
Copiar
Editar
pip install -r requirements.txt
Run the notebooks to train and evaluate the model.
📢 Contributing
Suggestions and contributions are welcome! Feel free to open issues or submit pull requests.
