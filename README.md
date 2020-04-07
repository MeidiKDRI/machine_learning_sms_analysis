## SMS Analysis use Case
In this training case, we have to classifiy and predict if a SMS is a ham or a spam.
To achieve our goal, we have to first clean the data, classify the data, and then train some models for the prediction.

## Clean the data
As usual in texts, we have a lot of useless words.
So first we remove stopwords with the following library:
```from nltk.corpus import stopwords```


## Classification
In this training use case, we have to classi



Dans ce cas pratique on cherche à entraîner un modèle capable de prédire si un texto est un spam ou non.
On s'appuie pour cela sur une base de données contenant des sms labellisés comme spam ou non spam 
(trouvée sur https://archive.ics.uci.edu/ml/datasets.php, voir readme pour plus d'informations).
