# News-NLP 
News NLP Categorization

# Natural Language Processing: News Article Categorization
## Data 
It contain the news of different title and content with their published date and source.It full data is of 810 rows  

---

### Content

* `Title`: Title of the News.

* `Content`: Content of the News.

* `NOTE`: Both title and content were concatenated (combined) prior to the modeling process.


---

### Predictor Value

* `topic`: Each news's classification.


---

## Methods Used 

**Data Preparation**
 
* `Removing Stop Words`: Words unnecissary towards predicting the category (ex: the, in, a, on). 


* `Tokenizing Words`: Sepparating all headline and desciptions into individual words to then combine them as a list of words.

* `Lemmatizing Words`: Removing affixes from words (reducing words to their root by removing any letters attached to them).

* `Vectorization:` Transformed lemmatized words into numerical values in order to predict the news.

* `Modeling:` Used a Logistic Regression to determine the model predictions for an F1 score.

* `Pickeling:` Used pickeling to save our model to use for deployment.


---

## Conclusions

* The model was able to predict the category of each article description with 62 percent accuracy with a slight overfit on the training data - 66 percent F-1 score. 

* While the model accuracy was not substantially high, it would prove to be a meaningful model in predicting news article categories for Huffington Post.


---

## Next Steps 

* To add a new feature that would account for the percentage of the different parts of speech in each description to improve model accuracy.

* To reduce model bias and overfitting by using a Grid Search CV to establish the best use hyperparameters.

* To host the final logistic regression model on a website domain. 


--- 
## Test Sets 
| Original Content |New Content | Removed Lines | Further Metrics |
|------------------|------------|---------------|-----------------|
| It contaion 810 lines| It contain less lines after removing extra words and puncuations | removing the stops words   | metrics is fully updated         |








