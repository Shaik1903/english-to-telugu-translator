Group members:
Bhuvanesh - 21bds018
Abhiram - 21bds029
Hrutin Suriya - 21bds031
Sadikh Shaik - 21bds059

Data Set link = https://www.kaggle.com/datasets/mathurinache/samanantar

Reference papers links:
Attention is All you need paper:
https://proceedings.neurips.cc/paper_files/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html

Samanantar Dataset Corpus :
https://arxiv.org/abs/2104.05596

Introduction: 
This is a translator built from scratch using transformers which translates from english-to-telugu.
We used semanantar dataset for this which includes 4.8 million english-telugu pairs
We trained our transformer with 1 million English-Telugu sentence pairs

How to use this repository: 
Please check the Explanation bit by bit(1 lakh sentences) python notebook first

Explanation bit by bit(1 lakh sentences) python notebook:
Here we trained our transformer with a mini batch (1 lakh sentences) and showcased whats happening in each and every block with an example batch sentences. But it took too much GPU ram even before training the transformer so only 5 GB Ram left for the transformer to train. So we have used a separate notebook only for training the transformer. It doesn't include any examples.

English to Telugu Translator(1 million) python notebook: 
Here we trained our transfomer with 1 million sentences. Here no examples are used and notebook completely used for the training. Here we included some translation examples too... 

Transformers notebook:
this notebook is used for the practice when we are learning the transformers. Here we tried to use work tokenizer. Mostly for the practice.
