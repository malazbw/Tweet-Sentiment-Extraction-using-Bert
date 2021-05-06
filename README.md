# Tweet Sentiment Extraction

## Problem
- Extract support phrases for sentiment labels.

## Approach

- We use QuestionAnswering approach to solve this porblm
- Context: tweet
- Question: sentiment
- Answer: phrases (start logits and  end logits)

## Modeling
DistilBertForQuestionAnswering


## LINKS :
 * Kaggle competition - https://www.kaggle.com/c/tweet-sentiment-extraction
 * Kaggle kernel - https://www.kaggle.com/malazbw/tweet-bert?scriptVersionId=62014866
 * Dataset - https://www.kaggle.com/c/tweet-sentiment-extraction/data
 * Model - https://huggingface.co/transformers/model_doc/distilbert.html#tfdistilbertforquestionanswering
 

## RESULTS :

- training: jaccard=0.775, loss=0.456
- valid: 0.68
- test: 0.0.672


