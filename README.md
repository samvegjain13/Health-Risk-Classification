# Health-Risk-Classification

## Brief introduction to project 

The primary objective of this project is to develop a predictive model that can accurately determine a person's risk category using these measurable features. By leveraging historical data and applying a Naive Bayes classification algorithm, the model aims to identify patterns that correlate with varying levels of health risk. Such a tool can be instrumental in supporting early intervention strategies, raising awareness about the impact of lifestyle choices, and guiding individuals toward healthier behaviours.

## Brief methodology of project

The project follows a supervised machine learning approach to classify individuals into health risk categories—low, medium, or high—based on lifestyle indicators such as BMI, exercise frequency, and junk food consumption. The dataset was first explored and verified for completeness. Since all features were numerical, minimal preprocessing was required.

A Gaussian Naive Bayes classifier was selected due to its efficiency with continuous data and probabilistic foundations. The dataset was split into training and testing subsets using an 80:20 ratio. The model was trained on the training data and evaluated using accuracy, a confusion matrix, and a classification report on the test set.

This approach provides a simple yet effective way to assess health risk based on easily measurable lifestyle factors.
