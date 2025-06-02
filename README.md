🚗 Description of Car Data Machine Learning Project
🧠 Project Title
Decision Tree Classifier on Car Dataset

🎯 Objective
The objective of this project is to build a Decision Tree Classifier that predicts how acceptable a car is (acceptable, unacceptable, good, very good) based on its features.

📊 Dataset Description
Source: Car Evaluation Dataset
Attributes (Features):

Buying: Cost of buying the car (v-high, high, med, low)

Maint: Maintenance cost (v-high, high, med, low)

Doors: Number of doors (2, 3, 4, 5-more)

Persons: Seating capacity (2, 4, more)

Lug_boot: Size of luggage boot (small, med, big)

Safety: Safety level (low, med, high)

Target Variable (Class):

Unacc, Acc, Good, V-Good

⚙️ Technologies Used
Python 3.x

pandas

scikit-learn

LabelEncoder

DecisionTreeClassifier

train_test_split

accuracy_score

🔍 Key Steps Performed
Loading Data:
The car.data file was read into a pandas DataFrame.

Encoding Data:
Since all features are categorical, LabelEncoder was used to convert them into numerical values.

Splitting Data:
The dataset was split into training and testing sets using train_test_split() (80% training, 20% testing).

Model Building and Training:
A DecisionTreeClassifier was created and trained on the training data.

Prediction and Comparison:
Predictions were made on the test data and compared with actual values.

Evaluating Accuracy:
The model’s accuracy was measured using accuracy_score().

📈 Output / Result
A DataFrame was created showing actual vs predicted values.

The accuracy score was quite high (e.g., Accuracy: 0.95).

✅ Conclusion
The Decision Tree model was able to accurately classify the car's acceptability based on the input features, proving it to be an effective classification model.
