# Model Card

For additional information see the Model Card paper: https://arxiv.org/pdf/1810.03993.pdf

## Model Details
This project uses a Random Forest classifier to predict whether an individual's annual income is greater than $50,000 or less than or equal to $50,000. The model was developed using scikit-learn and is part of a machine learning pipeline that processes Census data and makes income classifications.

## Intended Use
This model is intended to predict whether an individual's annual income is greater than $50,000 or less than or equal to $50,000 based on Census data. It is intended for educational purposes as part of this machine learning project.

## Training Data
The model was trained using the provided Census dataset. The data includes demographic and employment-related features such as age, education, occupation, workclass, marital status, and hours worked per week. The training portion contained 80% of the dataset.

## Evaluation Data
The evaluation data consisted of the remaining 20% of the Census dataset. This data was kept separate from the training data and was used to evaluate the model's performance on unseen examples.

## Metrics
The model was evaluated using precision, recall, and F1 score. On the test data, the model achieved a precision of 0.7419, recall of 0.6384, and F1 score of 0.6863.

## Ethical Considerations
The dataset contains demographic information such as race and sex, which may introduce bias into the model. The model should not be used to make high-stakes decisions about individuals, such as employment, lending, or access to services.

## Caveats and Recommendations
The model is limited by the quality and age of the Census data used for training. Its performance may not generalize to current populations or other datasets. Future improvements could include testing additional models, tuning model parameters, and evaluating potential bias across different demographic groups.