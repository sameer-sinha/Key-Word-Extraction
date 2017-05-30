# Key-Word-Extraction

Script to extract keywords from the comments on Airbnb reviews file using NLTK module of Python

* As the csv file contains more than 600,000 records and I am writing the keywords into csv file, this script takes a long time to run.
* So, here I have run the script on a subset of the original file.  
* Link to original csv file can be found in the text file.
* Have removed any non english word from the comments

# Future Agendas
* Can make more use of __NLTK Wordnet__ to discover word collocations
* Spelling correction with __Enchant__
* Replace negation with __antonyms__
* After extracting relevant keywords from reviews, __sentiment analyasis__ can be easily carried after creating __bag of words__, __features__ and __featureset__  with relevant words
* Result of __Naive Bayes__, __scikit learn__ and other classifiers can be combined with __voting__ to give higher accuracy, AUROC and other estimators of the model 
