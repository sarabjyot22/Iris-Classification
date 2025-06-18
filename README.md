*Overview*
The Iris Classification project demonstrates how to build a machine learning model to classify iris flowers into one of three species based on sepal and petal measurements.

*Dataset*
The dataset used is the classic Iris dataset, which includes:

150 samples

4 features: SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm

3 species: Iris-setosa, Iris-versicolor, Iris-virginica

*Tools & Technologies*
Tools: Jupyter Notebook, VS Code

Libraries: pandas, seaborn, matplotlib, scikit-learn

Language: Python

*Project Structure*
Iris_Classification_Project.ipynb: The Jupyter Notebook with all code and visualizations.

Iris.csv: Dataset used for training and testing.

Iris_Classification_Project_Report.docx: Formal report detailing the project's approach and results.

*Steps Involved*
Data Loading & Cleaning

Removed unnecessary columns

Encoded categorical labels

Checked for missing values

Exploratory Data Analysis

Pair plots, heatmaps, box plots for insights

Checked feature correlations

Preprocessing

Standardized the features using StandardScaler

Split dataset into training and testing sets (75/25)

Model Building

*Trained and evaluated three models:*

Random Forest Classifier

K-Nearest Neighbors

Support Vector Machine

*Evaluation*

Accuracy, confusion matrix, classification report

Cross-validation on Random Forest

*Results*
All models achieved high accuracy

Random Forest performed the best across metrics

Petal measurements were the most informative features
