📊 Bank Marketing Prediction using Decision Tree
📌 Project Overview

This project applies a Decision Tree Classifier to the Bank Marketing Dataset to predict whether a client will subscribe to a term deposit.
It demonstrates a complete machine learning workflow, including data preprocessing, model training, evaluation, and visualization.

⚙️ Tech Stack

Python 3.x

Pandas – Data manipulation

Scikit-learn – Machine learning

Matplotlib – Visualization

📂 Dataset

The dataset used is the Bank Marketing Dataset (commonly available from the UCI repository).

Input features: demographic, job-related, and campaign-related attributes.

Target variable:

yes → 1 (Client subscribed)

no → 0 (Client did not subscribe)

🚀 Workflow

Data Loading & Cleaning

Read CSV with semicolon separator (;).

Strip and map target values (yes → 1, no → 0).

Apply one-hot encoding for categorical variables.

Drop duration column to prevent data leakage.

Feature Selection & Splitting

Define X (features) and y (target).

Train-test split (80% training, 20% testing).

Model Training

Train a DecisionTreeClassifier with random_state=42.

Evaluation

Accuracy score.

Classification report (precision, recall, F1-score).

Visualization (Optional)

Plot decision tree structure.

Plot feature importance.

📈 Results

Outputs accuracy score and classification report.

Provides visual interpretation of decision-making using tree and feature importance plots.

🖼️ Example Visualizations

Decision Tree Plot – Shows the model structure.

Feature Importance Bar Chart – Highlights the most influential features.

▶️ How to Run

Clone this repository or copy the script into your project folder.

Place bank.csv in the same directory (or update the path in the script).

Install dependencies if not already installed:

pip install pandas scikit-learn matplotlib


Run the script in Spyder IDE or any Python environment.

📌 Future Improvements

Try Random Forest or XGBoost for better accuracy.

Perform hyperparameter tuning on Decision Tree.

Use cross-validation for robust evaluation.

👤 Author

Developed by Tanu Khetwal ✨
Machine Learning Enthusiast | Python Developer
