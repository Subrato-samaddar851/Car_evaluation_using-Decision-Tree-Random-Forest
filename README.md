# Car_evaluation_using-Decision-Tree-Random-Forest
This assignment focuses on gaining hands-on experience with two widely used classification algorithms: Decision Tree and Random Forest. The goal is to evaluate the importance of car features using the Car Evaluation Dataset and compare the performance of these algorithms.

Objectives
Preprocess and explore the Car Evaluation Dataset.

Implement and train a Decision Tree classifier.

Implement and train a Random Forest classifier.

Evaluate and compare the performance of both models.

Analyze feature importance to understand which attributes most influence car evaluation.

Dataset
The Car Evaluation Dataset contains attributes related to car features such as:

buying: Buying price (e.g., v-high, high, med, low)

maint: Maintenance price (e.g., v-high, high, med, low)

doors: Number of doors (e.g., 2, 3, 4, 5-more)

persons: Capacity in terms of persons (e.g., 2, 4, more)

lug_boot: Size of the luggage boot (e.g., small, med, big)

safety: Estimated safety of the car (e.g., low, med, high)

The target variable is class, which represents the car's acceptability (e.g., unacc, acc, good, v-good).

Requirements
Python 3.8+

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

Installation
Clone the repository:

bash
Copy
git clone https://github.com/yourusername/car-evaluation-classification.git
Install dependencies:

bash
Copy
pip install -r requirements.txt
Usage
Place the car.data file in the data/ directory.

Run the preprocessing script to clean and prepare the data:

bash
Copy
python preprocess.py
Train and evaluate the Decision Tree model:

bash
Copy
python decision_tree.py
Train and evaluate the Random Forest model:

bash
Copy
python random_forest.py
Compare the performance of both models:

bash
Copy
python compare_models.py
Results
Model performance metrics (accuracy, precision, recall, F1-score) are saved in the results/ directory.

Feature importance plots for both models are generated and saved in the plots/ directory.

License
This project is licensed under the MIT License. See LICENSE for details.

Contact
For questions or feedback, email: your.email@example.com

This README provides a clear and concise guide to understanding and running the project. Let me know if you need further assistance!

New chat
