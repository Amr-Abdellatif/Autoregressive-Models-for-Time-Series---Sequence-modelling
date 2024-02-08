# Lets break down our problem

## The autoencoding approach has been very successful for images, signals, and even fully connected models with tabular data. But what if our data is a sequence problem? Especially if our data is in a language represented by discrete tokens, it’s hard to add meaningful noise to things like a letter or word. Instead, we can use an autoregressive model, which is an approach specifically designed for time-series problems.

## You can use an autoregressive model for basically all the same applications for which you might use an autoencoding one. You can use the representation an autoregressive model learns as the input to another ML algorithm that doesn’t understand sequences

-----
![Capture](https://github.com/Amr-Abdellatif/Autoregressive-Models-for-Time-Series---Sequence-modelling/assets/92921252/be6a1fba-7359-43f0-bec2-d50d31372308)
----
### The first thing we need is our data. Andrej Karpathy has shared some text from Shakespeare online that we will download. There are about 100,000 characters in this text, so we store the data in a variable called shakespear_100k. We use this dataset to show the process of training an autoregressive model, as well as its generative capabilities and its all listed in the notebook in this repo
