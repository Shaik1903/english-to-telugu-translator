This is a translator built from scratch using transformers which translates from english-to-telugu.
We used semanantar dataset for this which includes 4.8 million english-telugu pairs
We trained our transformer with 1 million English-Telugu sentence pairs

Please check the Explanation bit by bit(1 lakh sentences) python notebook first

Explanation bit by bit(1 lakh sentences) python notebook:
Here we trained our transformer with a mini batch (1 lakh sentences) and showcased whats happening in each and every block with an example batch sentences. But it took too much GPU ram even before training the transformer so only 5 GB Ram left for the transformer to train. So we have used a separate notebook only for training the transformer. It doesn't include any examples.

English to Telugu Translator(1 million) python notebook: 
Here we trained our transfomer with 1 million sentences. Here no examples are used and notebook completely used for the training. Here we included some translation examples too... 

Transformers notebook:
this notebook is used for the practice when we are learning the transformers. Here we tried to use work tokenizer. Mostly for the practice.
