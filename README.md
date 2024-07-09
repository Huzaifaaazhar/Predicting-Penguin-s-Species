# Predicting Penguin's Species

The main objective of this project is to build a predictive model that can classify the species of penguins based on their physical and categorical features. The project involves the following steps:

#### 1. Data Loading
The dataset is loaded from a CSV file located at "G:\Proxima AI\StreamLIT\Penguins predictor app\penguins_cleaned.csv".

#### 2. Feature Encoding
Categorical features (`sex` and `island`) are converted into dummy/one-hot encoded variables. This process involves creating new binary columns for each unique value in the categorical columns.

#### 3. Target Encoding
The target variable (species) is mapped to numerical values for the classification task.

#### 4. Model Training
The features (`X`) and target (`Y`) are separated, and a RandomForestClassifier is trained on this data.

#### 5. Model Serialization
The trained model is saved to a file using pickle for future use in a prediction application.
