🚢 Titanic Survival Prediction
This project aims to predict the survival of Titanic passengers using machine learning algorithms built with Python and scikit-learn.

📁 Dataset
The dataset used is Titanic-Dataset.csv, which contains passenger information such as:

Name

Age

Gender

Ticket Class

Number of Siblings/Spouses Aboard

Embarked (Port of Embarkation)

And more.

🧪 Analysis Steps
1. Import Libraries & Load Data
Utilizing libraries such as pandas, numpy, matplotlib, seaborn, and sklearn.

2. Data Exploration and Cleaning
Displaying initial info and statistics

Handling missing values

Label encoding for categorical features

Normalizing numerical features

3. Modeling
Training classification models using Support Vector Machine (SVM) and Random Forest

Evaluating model performance using metrics like:

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

4. Result Evaluation
Comparing the performance of both models

Visualizing results using confusion matrices and other plots

💻 How to Run
Make sure you have Python installed along with the required dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn
Then run the Jupyter notebook:

jupyter notebook titanic.ipynb
Ensure the file Titanic-Dataset.csv is located in the same directory as the notebook.

📊 Results
The models predict whether a passenger survived or not, with evaluation metrics such as accuracy and F1-score provided for each algorithm.
