# thai-clickbait-classification-with-pretrained-nlp

Step to run the file
1. Download prachathai-67k: https://www.kaggle.com/datasets/ratthachat/pythainlp-prachatai-67k
2. Download Thai-clickbait: https://github.com/9meo/Thai-Clickbait
3. Upload all data files to colab at '/content/' or any desired location
4. Run the 'Data Preparation' part of the code
5. Run the 'Run Once' part of either the 'Word Tokenize' or 'Sentence Vectorize' section
6. Locate the config.model_name in wandb.config in 'Run Many Times for the chosen section and change to desired NLP model
7. Run the 'Run Many Times' parts using you wandb API key
