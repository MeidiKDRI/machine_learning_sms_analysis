## SMS Analysis use Case
In this training case, we have to classifiy and predict if a SMS is a ham or a spam.  
To achieve our goal, we have to first clean the data, classify the data, and then train some models for the prediction.

## Clean the data
As usual in texts, we have a lot of useless words.  
So first we remove stopwords with the following library :  
```python
from nltk.corpus import stopwords
```
We clean also the text with library re.
Then we can show most used words with ```python WordCloud```

## Prediction
After cleaning steps, we can train some models for the prediction,  
And show the efficiency of the prediction with ```python confusion_matrix```
