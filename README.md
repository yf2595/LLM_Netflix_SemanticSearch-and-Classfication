# LLM_Netflix_SemanticSearch-and-Classfication

## Project Summary
This project involves working with a dataset of Netflix TV shows and movies, focusing on implementing semantic search and fine-tuning a classification model.

## Key Components:
### Semantic Search:

Objective: Implement a semantic search mechanism to retrieve relevant shows or movies based on user queries.
Approach: Utilize pre-trained language models (like BERT) to encode text descriptions and titles. These embeddings are then used to compute similarity scores between user queries and available titles, enabling efficient and meaningful search results.

### Classification Model Fine-Tuning:

Objective: Fine-tune a classification model to categorize content based on various features (e.g., genre, production country, and popularity).
Approach: Leverage transfer learning by fine-tuning a pre-trained model on the specific dataset, optimizing for performance metrics such as accuracy and AUC-ROC. The model is trained to predict categories or ratings (e.g., IMDb scores) based on input features.

### Features and Techniques:

Data Preprocessing: Handling missing data, normalizing inputs, and preparing text for embedding generation.
Model Selection: Exploring different classification algorithms, including transformer-based models for NLP tasks.
Evaluation: Assessing model performance using standard metrics and refining the model through hyperparameter tuning.
