# MAT280Project
bag-of-words model recommender system for cannabis strains

The motivation behind this project is that medical marijuana patients are often prescribed or recommended particular strains to alleviate their health concerns. However, specific strains may not always be readily available to a patient. To address this problem, I have developed a recommender system that uses the description of cannabis strains in order to recommend similar ones. The recommender relies on a bag-of-words model and analyzes a publicly available dataset (https://www.kaggle.com/datasets/kingburrito666/cannabis-strains). 

The key function within the code is recommendations, which takes the index of a specific strain in the dataset as input. It can then output the top 10 most similar strains using a cosine similarity function to compute distance. 
