# Twitter Topic Modelling

Topic modelling of tweets, using two different approaches:
- The pLSI based LDA (Latent Dirichlet Allocation)
- Community detection on word co-occurence network 

## Instructions for reproducing:
- Every notebook can be found under the *notebooks* folder (who would have thought...)
- Graph-tool will be needed for doing the hSBM topic modelling. You can find instructions for installing it [here](https://git.skewed.de/count0/graph-tool/wikis/installation-instructions). I followed the instructions for starting a jupyter notebook server inside the docker container, and everything worked fine (I had to specify the path for my other python apckages though, see the [topic_modelling.ipynb](./notebooks/topic_modelling.ipynb) for more details)
- If you want to download your own data, run the cells of *tweet_collector.ipynb*. Otherwise you can use the #MAGA data provided in the *data/tweets_maga* folder
- 
