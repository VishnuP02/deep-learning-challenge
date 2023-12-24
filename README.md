Task: The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With my knowledge of machine learning and neural networks, I used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

Resources used to complete activity:
  - Lecture Slides, Class recordings, AskBCS session with Learning Assistant Sathwik Kesappragada


                              Report on Neural Network Model Performance for Alphabet Soup

        OVERVIEW OF THE ANALYSIS:

        The purpose of this analysis is to develop a deep learning model for Alphabet Soup that can predict whether applicants will be successful in
        receiving funding based on various features. The goal is to create an efficient classification model that aids in decision-making for allocating
        resources.

        RESULTS:

        Data Processing

          - What variable(s) are the target(s) for your model?

            The target variable is the "IS_SUCCESSFUL" column, indicating whether the funding application was successful or not
    
          - What variable(s) are the features for your model?

            Features include various columns such as "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "STATUS", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", and "ASK_AMT".
    
          - What variable(s) should be removed from the input data because they are neither targets nor features?

            The "EIN" (Employer Identification Number" and "NAME" columns are typically removed as they don't contribute to the predictive power of the model.
    
        Compiling, Training, and Evaluating 

          - How many neurons, layers, and activation functions did you select for your neural network model, and why?
    
          - Were you able to achieve the target model performance?

            I was unable to make 3 successful attempts at achieving the target model performance. The quality and quantity of my data could have played a crucial role in this. Insufficient or noisy data can negatively impact the model's ability to generalize to new data. Something I could have donw is ensure that my dataset was representative and contained enough samples for each class.
    
          - What steps did you take in your attempts to increase model performance?
    
        SUMMARY:

        In summary, the deep learning model developed for Alphabet Soup showed [insert performance metrics]. While the model demonstrates a reasonable
        predictive capability, there's room for improvement. To enhance performance, experimenting with different architectures, hyperparameters, and
        conducting further feature engineering could be beneficial.

        RECOMMENDATION:

        Considering the nature of the classification problem, an alternative model like a gradient boosting algorithm (e.g., XGBoost or LightGBM)
        could be explored. Ensemble methods often perform well in tabular data classification tasks. They are robust, handle non-linearity well, and
        can provide insights into feture importance. This approach may yield better interpretability and generalization to unseen data. However, the
        choice of the model ultimately depends on the specific requirements and constrainst of Alphabet Soup.

