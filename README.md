# Instructions
The src/classification_task.ipynb contains the code to finetune BERT uncased model. It categorizes the email into 3 categories i.e., student, corporate, and researcher.

1. Please download the finetuned model from here. Due to large file size constraint it couldn't be uploaded in github. Place the zip file in src/results.
> https://drive.google.com/drive/folders/1_tZtqs6rJYzx4SFmTclzIEbsqUqCHO8l?usp=drive_link
2. Install the requirements from the requirements.txt file by creating a virtual/conda environment.
3. After the installation first run the import statements.
4. Run the subsequent lines from loding the model and trying out on example emails.


# Aproach
BERT is already trined on huge corpus of text, making it highly effective at understanding the complexity of natural language. It captures both left-to-right and right-to-left context due to which its performance would be greater than LSTM that focus on the preceding tokens. Also, the way it captures context is much needed in categorizing emails as small changes in emails would reflect who the sender is. Moreover, its ability to process 512 tokens makes it a good choice over RNN and LSTM.