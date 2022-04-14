THIEN WIN, PE
April 2022

PROJECT: RECOMMEND a KDRAMA!

INTRODUCTION:
This project looks to build a content based Korean Drama recommender based on a dataset found on Kaggle that was
scraped from iMDb. This project is for fun and for learning so please feel free to play around with the code.

DATA: https://www.kaggle.com/datasets/chanoncharuchinda/imdb-korean-tv-series 

SETUP: Required libraries and modules
	import pandas as pd
	import matplotlib.pyplot as plt
	from sklearn.feature_extraction.text import CountVectorizer
	from sklearn.metrics.pairwise import cosine_similarity

LIMITATIONS:
Only movies found in the dataset can be used to provide recommendations.


