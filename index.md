# Table of Contents

* TOC
{:toc}

# Introduction

Well, here could be a really fancy introduction about Latent Dirichlet allocation, and the probabilistic models of semantic topic analysis. But there isn't. Instead it can be found following [this link to introduction](./notebooks/introduction.html).

# Data acquisition

When one wants to do research based on real life data, the best thing to do first is to acquire said data. That is exactly what I did. I a number of tweets (goal is 100 000 for each topic) related to popular topics like #MAGA or #brexit, and also some tweets on a locational basis: around New York and London. Not much else to say, as data collection is mainly waiting for the Twitter API to do its job. If you are interested in the details (which I doubt) the you can take a look at the [tweet_collector notebook](./notebooks/tweet_collector.html).

# Data cleaning

Before working with the downloaded tweets, the data must be "cleaned". This means extracting the useful words of a tweet, and discarding the "rubbish" like emojis, stopwords (have, at, me, etc.), usernames, etc. (and those hated specially encoded characters from the deepest pits of hell like `˙¸˛). Of course every research find different words meaningful, so I will explain why I defined "rubbish" as I did.



