**Problem:** *Explore text message data and create models to predict if a message is spam or not.*

**Packages:**
  * pandas
  * numpy
  * re
  * scipy
    * sparse
      * csr_matrix
      * hstack
  * sklearn
    * model_selection
      * train_test_split
    * feature_extraction.text
      * CountVectorizer
      * TfidfVectorizer
    * naive_bayes
      * MultinomialNB
    * metrics
      * roc_auc_score
    * svm
      * SVC
    * linear_model
      * LogisticRegression
