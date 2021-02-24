## maroxtn.github.io

# Abdessalem Boukil Data Science Portfolio
This is a list of work that I have done in the field of data science and deep learning. It includes competitions that I've participated in, personal projects, guides and notebooks. This list will updated constantly.

## **Predictive sales dashboard**
I created and deployed an LSTM deep learning model in a real-time dashboard that computes sales prediction for a list of +160 products. This was during the course of an internship as a data scientist. I used Tensorflow to train the model, and Flask to deploy it. All the code is available [here](https://github.com/maroxtn/forecast-dashboard).

![dashboard](image/dashboard.png)

## **Solo silver medal (2%) in a kaggle competition**
I was ranked the 39th out of 3345 competitor (2%) that won me a silver medal. The competition is a featured competition targeting the knowledge tracing problem, i.e. estimating if a student would answer a question right or wrong based on their history. For my solution, I used an ensemble of an LGBM and SAINT transformer model, which you can find their respective sources, [here](https://github.com/maroxtn/LGBM-riiid-kaggle) and [here](https://github.com/maroxtn/SAINT-Transformer-riiid-kaggle).

![rank](image/rank.PNG)
## **Attention types comparison**
The goal behind this project was to compare between [RNN using Bahdanau attention](https://arxiv.org/abs/1409.0473) translation, and Transformer translation, in terms of attention weights and translation quality. Both models had only one layer, similar in network size, training data, and number of epochs. The code is available [here](https://github.com/maroxtn/Transformer-vs-bahdanau-attention). The code is fully reproducible.
&nbsp;

![rank](image/1.gif)


The difference between transformer translation (first) attention weights, and Bahdanau attention translation (second).
## **SAINT Transformer guide notebook**
After the Riiid competition ended, I wrote a notebook that extensively explains my implementation of the model, and my way of performing inference. You can find it [here](https://www.kaggle.com/abdessalemboukil/saint-training-inference-guide-39th-solution/comments).
## **Scraped and trained a text generation model in Tunisian Arabic**
I scraped tweets, Facebook comments and articles in Tunisian Arabic, that I used to train a text generation LSTM cell, which outputed interesting results. 

## **Trump Speech Generator**
I used the huggingface Transformers library to immitate Trump's style of speech. To do that, I fine tuned GPT2 model on the bulk of 30 Trump's rally speeches. I used different text generation techniques to generate the text. This project was a good opportunity to test the huggingface library, and to experience the ease of their abstraction.

**Seed**: Obama is

**Generated text**: Obama is the craziest person I've ever met." I said, "You mean like him when he's on this show? I haven't seen him in over 25 years because of all the crazy stuff. He's crazy." But we have them all because he has such a big following. If I didn't have that massive following for a candidate, or for other things too, I would have not done so well. When I did, it was all done for political. And then I think we...

*Source code*: [https://colab.research.google.com/drive/12hw55uGm80ikiq9wLtZ2GsWpRnGUCdXv?usp=sharing](https://github.com/maroxtn/trump_speech_generator)

*Try it yourself in Colab*: [https://colab.research.google.com/drive/12hw55uGm80ikiq9wLtZ2GsWpRnGUCdXv?usp=sharing](https://colab.research.google.com/drive/12hw55uGm80ikiq9wLtZ2GsWpRnGUCdXv?usp=sharing)