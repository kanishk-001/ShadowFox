# T5-SQL Generator

## Project Overview
The T5-SQL Generator is a deep learning-based tool that converts natural language queries into SQL queries using a pre-trained T5 model. This project fine-tunes the T5 model for the task of translating English queries into SQL commands.

## Features
- **Natural Language to SQL Translation**: Converts user input in natural language to SQL commands.
- **Fine-Tuning of T5**: Fine-tunes a pre-trained T5 model using a custom dataset for SQL query generation.
- **Interactive Command-Line Interface**: Allows users to input natural language queries and receive the corresponding SQL queries interactively.

## Technologies Used
- **Transformers**: Hugging Face library for handling transformer models.
- **PyTorch**: Deep learning framework for model training and inference.
- **scikit-learn**: For dataset splitting and evaluation.
- **matplotlib**: For visualizing model performance and outputs.
- **seaborn**: For generating heatmaps and other visualizations.

### Setup and Installation

## 1. Clone the Repository

Clone the repository to your local machine using the following command:

bash
git clone https://github.com/your-username/t5-sql-generator.git


## 2. Install Dependencies
install the required libraries:

transformers
datasets
torch
scikit-learn
matplotlib
seaborn

## 3. Dataset Preparation
Ensure that your dataset is in the correct format with two columns:
text_query (Natural Language query)
sql_command (Corresponding SQL query)

## 4. Training the Model:
Run the following Python script to train the model:
python train_model.py

## 5. Running the Model :
Once the model is trained, run the following script to interactively generate SQL queries from natural language input:
python generate_sql.py

## 6. Acknowledgments
Hugging Face for the transformers library.
PyTorch for the deep learning framework.
The Spider dataset for text-to-SQL tasks.







