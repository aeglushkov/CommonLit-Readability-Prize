# CommonLit-Readability-Prize  
In this competition, we're predicting the reading ease of excerpts from literature. We've provided excerpts from several time periods and a wide range of reading ease scores. Note that the test set includes a slightly larger proportion of modern texts (the type of texts we want to generalize to) than the training set.  
  
Also note that while licensing information is provided for the public test set (because the associated excerpts are available for display / use), the hidden private test set includes only blank license / legal information.  

## Files  
* train.csv - the training set  
* test.csv - the test set  
* sample_submission.csv - a sample submission file in the correct format  

## Columns  
* `id` - unique ID for excerpt  
* `url_legal` - URL of source - this is blank in the test set.  
* `license` - license of source material - this is blank in the test set.  
* `excerpt` - text to predict reading ease of  
* `target` - reading ease  
* `standard_error` - measure of spread of scores among multiple raters for each excerpt. Not included for test data.  