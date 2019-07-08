Assignment Details:
----------------------
**1. Apply Decision Tree Classifier(DecisionTreeClassifier) on these feature sets**

    * Set 1: categorical, numerical features + project_title(BOW) + preprocessed_eassay (BOW)
    * Set 2: categorical, numerical features + project_title(TFIDF)+ preprocessed_eassay (TFIDF)
    * Set 3: categorical, numerical features + project_title(AVG W2V)+ preprocessed_eassay (AVG W2V)
    * Set 4: categorical, numerical features + project_title(TFIDF W2V)+ preprocessed_eassay (TFIDF W2V)
    
**2. Hyper paramter tuning (best `depth` in range [1, 5, 10, 50, 100, 500, 100], and the best `min_samples_split` in range [5, 10, 100, 500])**

**3. Graphviz**

      * Visualize your decision tree with Graphviz. It helps you to understand how a decision is being made, given a new vector.
      * Since feature names are not obtained from word2vec related models, visualize only BOW & TFIDF decision trees using Graphviz
      * Make sure to print the words in each node of the decision tree instead of printing its index.
      
      
**4. Summarize the results with observation.**
