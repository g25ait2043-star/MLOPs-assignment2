# MLOPs-assignment2
MLOPS ASSIGNMENT
This project demonstrates a complete end-to-end MLOps workflow using Hugging Face Transformers, Kaggle GPU training, Weights & Biases (W&B) experiment tracking, and Hugging Face Hub deployment. The objective of this assignment was to understand how machine learning models are trained, tracked, evaluated, and deployed using modern MLOps practices. A DistilBERT model was fine-tuned on Goodreads review data to classify book genres based on review text.

Technologies Used
Hugging Face Transformers
PyTorch
Kaggle GPU
Weights & Biases (W&B)
Hugging Face Hub
Scikit-learn
Python
Model Used
DistilBERT (distilbert-base-cased)
DistilBERT was selected because it is lightweight, faster than BERT, and suitable for training on Kaggle free GPU resources while still providing strong NLP performance.

Setup Instructions
Install required dependencies:

pip install -r requirements.txt
Run the notebook in Kaggle with:

GPU enabled
Internet enabled
Add these Kaggle Secrets:

WANDB_API_KEY
HF_TOKEN
Workflow
Imported notebook into Kaggle
Enabled GPU and Internet access
Configured Kaggle Secrets
Loaded Goodreads review dataset
Fine-tuned DistilBERT model
Tracked experiments using W&B
Evaluated model performance
Uploaded trained model to Hugging Face Hub
Published project to GitHub
Results
Metric	Score
Accuracy	0.59
F1 Score	0.5913
Eval Loss	2.4473
Project Links
Kaggle Notebook: https://www.kaggle.com/code/jahnveeyadav2043/mlops2/edit

Hugging Face Model: https://huggingface.co/arcsaber2302/distilbert-goodreads-genres

W&B Dashboard: https://wandb.ai/g25ait2043-iit-jodhpur/mlops-assignment2?nw=nwuserg25ait2043

GitHub Repository: https://github.com/g25ait2043-star/MLOPs-assignment2

Learning Outcomes
Through this assignment, I learned how to:

Train transformer-based NLP models on cloud GPUs
Use W&B for experiment tracking and visualization
Manage API secrets securely in Kaggle
Deploy trained ML models to Hugging Face Hub
Maintain reproducible ML workflows using GitHub
This project provided practical exposure to modern MLOps workflows and deployment practices.
