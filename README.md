# TexRERT-classifier
Description: Developed a text classification pipeline using BERT for sequence classification. The project involved converting
a labeled JSON dataset into a format compatible with Hugging Face’s Transformers library, training a BERT model, and
deploying it for real-time text classification.
Model Training: Utilized the bert-base-uncased model for sequence classification. Split the dataset into training and
evaluation sets, tokenized the text data, and trained the model using the Hugging Face Trainer class with appropriate
hyperparameters.
Evaluation and Deployment: Evaluated the model on the test set, saved the trained model and tokenizer, and implemented a
prediction function to classify new text inputs.
Output: Achieved a trained text classification model with real-time prediction capability, saved the results, and predictions to
an Excel file for further analysis.
Tools & Technologies: Python, Hugging Face Transformers, PyTorch, pandas, Excel.
