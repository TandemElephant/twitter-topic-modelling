# Twitter Topic Modelling

Topic modelling of tweets, using two different approaches:
- The pLSI based LDA (Latent Dirichlet Allocation)
- Community detection on word co-occurence network 

## Instructions for reproducing:
- Every notebook can be found under the *notebooks* folder (who would have thought...)
- Graph-tool will be needed for doing the hSBM topic modelling. You can find instructions for installing it [here](https://git.skewed.de/count0/graph-tool/wikis/installation-instructions). I followed the instructions for starting a jupyter notebook server inside the docker container, and everything worked fine (I had to specify the path for my other python apckages though, see the [topic_modelling.ipynb](./notebooks/topic_modelling.ipynb) for more details)
- If you want to download your own data, run the cells of [tweet_collector.ipynb](./notebooks/tweet_collector.ipynb). Otherwise you can use the #MAGA data provided in the [data/tweets_maga](./data/tweets_maga) folder.
- Running the cells of [data_cleaning.ipynb](./notebooks/data_cleaning.ipynb) will read all *tweet_#.json* files in the specified folder, then clean them as needed for the project, and save it to *data_merged.csv*.
- Regarding the [topic_modelling.ipynb](./notebooks/topic_modelling.ipynb): I suggest only creating the word-tweet network, and sticking to hSBM model. You can try to make other community finding algorithms work, but they might be exttremely slow. 

Post an issue here if anything goes wrong :)
