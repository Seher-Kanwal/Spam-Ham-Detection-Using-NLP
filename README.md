![NLP](https://th.bing.com/th/id/R.5f505c58c5d0182bd738cc4847216324?rik=mOwGsGNiQ52NkQ&pid=ImgRaw&r=0)

# Spam-Ham-Detection-Using-NLP (Useing Stemming and Stop Word on Data)
This includes the different approaches of NLP to solve the spam ham problem 

## Libraries Used:
- __nltk__
- __sklearn__
- __pandas__
- __re__

## Steps for test and trainign model with stem Data:
- First we perform stemming along with eliminAting the stop words
- convert all to lower case
- Create a Bag of word that contains 2500 words
- Perform One Hot Encoding on our dependent data
- divided data into train and test data 
- Create the MultinomialNB Model
- Determine the Accuracy
-
### Here we again train and test our model with Tfidf approach 
- Create a Tfidf doc
- Perform One Hot Encoding on our dependent data
- divided data into train and test data 
- Create the MultinomialNB Model
- Determine the Accuracy
- print the accuracy report 


## Result:
The Bag of Words gives Good accuracy score in this problem 
