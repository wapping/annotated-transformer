# About

This is an implementation of the transformer from ['Attention is All You Need'](https://arxiv.org/abs/1706.03762), based on the code of a [post](http://nlp.seas.harvard.edu/2018/04/03/attention.html).  We reorganized the code for the following reasons:

- The code in the post was organized for `.ipynb` editors, but we want to run the code by python command or python IDE (like PyCharm).
- The post did not give running environment. Some problems occered when we ran the code as the post.
- The necessary datasets and models are downloaded by the code, which will lead to connection errors in some areas. We provide the datasets and installation packges of the models.


# Requirements

```
python==3.8.8
torch==1.9.0
numpy==1.20.1
matplotlib==3.3.4
spacy==2.2.2
torchtext==0.6.0
```

#Install Models

```
cd packages
pip install en_core_web_sm-2.2.5.tar.gz
pip install de_core_news_sm-2.2.5.tar.gz
```

# Train

```
python transformer.py
```

