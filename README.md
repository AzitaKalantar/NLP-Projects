# NLP-Projects

I study NLP through books and papers in my free time. I'm going to put my projects' sourse code in this repository. The codes I put here are 95% written by me. I hope thay would be useful for you :)

## Some of the main resources I'm using :

[Speech and Language Processing](https://web.stanford.edu/~jurafsky/slp3/) : for learning NLP consepts

[Natural Language Processing with PyTorch](https://learning.oreilly.com/library/view/natural-language-processing/9781491978221/) : for learning the structure of NLP projects' code and NLP consepts

## Projects

### 1. Sentiment and Emotion Detector using ISEAR dataset

[ISEAR](https://www.unige.ch/cisa/research/materials-and-online-research/research-material/) dataset, is a free, open sourse dataset containing some texts and their corresponding emotion (joy, fear, anger, sadness, disgust, shame, and guilt). This data was gathered from 3000 respondents in 37 countries by a large group of psychologists.

in this folder I try different methods and models to train a model to ditect emotions based on a text, at the end I choose the best model and apply it on Tweeter data to find out the emotions behind the tweetes. 

### 2. Text Generation - Next word Prediction using Enron dataset

[Enron](https://www.cs.cmu.edu/~enron/) dataset, is a free, open-sourse dataset containing 0.5 M email messages. It contains data from about 150 users, mostly senior management of Enron, organized into folders.

In this folder I use a sequential model (containing GRU layer) to capture the meaning of a sequence and predict the next word. I trained my model on 600 KB data with 10 epochs. It took 5 hours to run. The model's accuracy can improve siginificantly if the model was larger (had more RAM on the system) and trained for a longer time.
