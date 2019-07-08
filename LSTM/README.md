Assignment:
-------------
1. Implement Model 1 as per below

    * Input_seq_total_text_data --- You have to give Total text data columns. After this use the Embedding layer to get word vectors. Use given predefined glove word vectors, don't train any word vectors. After this use LSTM and get the LSTM output and Flatten that output.
    * Input_school_state --- Give 'school_state' column as input to embedding layer and Train the Keras Embedding layer.
    * Project_grade_category --- Give 'project_grade_category' column as input to embedding layer and Train the Keras Embedding layer.
    * Input_clean_categories --- Give 'input_clean_categories' column as input to embedding layer and Train the Keras Embedding layer.
    * Input_clean_subcategories --- Give 'input_clean_subcategories' column as input to embedding layer and Train the Keras Embedding layer.
    * Input_clean_subcategories --- Give 'input_teacher_prefix' column as input to embedding layer and Train the Keras Embedding layer.
    * Input_remaining_teacher_number_of_previously_posted_projects.resourcesummary_contains_numerical_digits.price.quantity ---concatenate remaining columns and add a Dense layer after that.
