# Tensorflow chatbot pretrained model

This repository collect some pretrained model for the implementation [tf_chatbot_seq2seq_antilm](https://github.com/Marsan-Ma/tf_chatbot_seq2seq_antilm)


## Files

1. **example.tar.gz**

  (params: size = 128, vocab_size = 100000, num_layers = 4)
  
   A pre-trained model using twitter_en corpus from [this repository](https://github.com/Marsan-Ma/chat_corpus)  
   
   File is splitted to walk-around file size limit, please combine them by:
    `cat example.tar.gz.part-* > example.tar.gz`
   

2. **twitter_en_big_model.tar.gz**

  (params: size = 256, vocab_size = 100000, num_layers = 4)
  
   The full model trained by twitter_en_big.txt.gz from [this repository](https://github.com/Marsan-Ma/chat_corpus)
   The network is bigger, and thus takes longer time to the predict.  
  
   File is splitted to walk-around file size limit, please combine them by:
    `cat twitter_en_big.txt.gz* > twitter_en_big.txt.gz`
   



