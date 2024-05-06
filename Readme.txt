Training Dataset:
Utilize the 'GPT-wiki-intro-reformat-100000' dataset or another dataset of your choice for training the model. Ensure your dataset is properly formatted and relevant to the task at hand.

Test Dataset:
Create an Excel file for testing, with two columns labeled 'id' and 'article'. Populate the 'id' column with unique identifiers for each text and the 'article' column with the texts to be evaluated. For model evaluation including graphs, add a third column named 'class' and categorize each text with a '0' for human-written or '1' for AI-generated content. Refer to the 'article_level_data' dataset for an example of how to structure your file.

1. Ensure TensorFlow and TensorFlow Text version 2.15.0 are installed.
2. Install Transformers, version 4.37.2.
3. Import any additional libraries as required or install them if not already present. 
4. Adjust the main file paths in the code to correspond to your training and test datasets, as well as paths for saving/loading the model, metrics, and any submission files.
5. Make sure the updated file paths in the code reflect your specific setup.
6. For output-specific instructions, refer to the test dataset guidelines. To run the main model without the graphs, execute the sections titled 'Import libraries and file paths', 'Datasets preparation', 'F1 class function', 'model configuration', and the section pertaining to the main model (BERT model). Exclude the graph sections within each model for this purpose.
7. To run the entire code seamlessly, ensure your test dataset is formatted in the same way as the 'article_level_data' dataset.
