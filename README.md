# Semi-Supervised-Text-Classification-with-Generative-Adversarial-Nets

# Background
Text classification is an extremely important information for companies. Thanks to the invention of transformer based model like Bidirectional Encoder Representations from Transformers(BERT) and Gener-ative Pre-trained Transformer(GPT),  has largely improved the performance of text classification compared to original Recurrent Neural Network. In real business scenarios, most of good performances come from millions of annotated instances , but usually it’s impossible for some companies getting enough annotated data because it needs too much time and labour. 

Previous research has proposed GAN-BERT, which combined Generative Adversarial Nets(GAN)and BERT for training a semi-supervised model.It shows GAN could improve the performance of BERT in semi-supervised tasks. In this research, we propose the GAN-GPT2 model which combined GAN and GPT, and compare it with BERT,GPT2,GAN-BERT in semi-supervised experiments. 

# Methodology
For each model, we test it on three datasets: Amazon Review dataset, Yelp Review dataset and Financial Review dataset, with different proportion of annotated examples. Experiment result shows GAN-BERT and GAN-GPT2 only need less annotated examples to get a good performance. Compared to the result of BERT and GPT training with all annotated examples, GAN-BERT and GAN-GPT2 only need 5%-10% annotated examples to get the same performance. Especially, our result shows GAN could largely improve GPT2’s performance when facing less than 10% annotated data.

# Model



# Result

# Dataset

