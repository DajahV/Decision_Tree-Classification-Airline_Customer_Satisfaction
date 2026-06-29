# Decision_Tree-Classification-Airline_Customer_Satisfaction

Decision Tree Model Evaluation
Overview
Decision Tree Classification – Airline Customer Satisfaction
Project Overview
In this project, you will analyze passenger survey data using Python and Scikit-learn to build an optimized Decision Tree classifier. You will learn how to tune hyperparameters with GridSearchCV, visualize decision pathways, evaluate performance using F1-score and confusion matrices, and extract feature importance to drive targeted service improvements. This project strengthens your ability to build transparent, interpretable models that stakeholders can easily understand and act upon.

Step-by-Step Project Tasks
• Load the dataset and prepare features for binary classification
• Split data into training and testing sets for unbiased evaluation
• Implement GridSearchCV to optimize `max_depth` and minimum sample splits/leaves
• Train the final Decision Tree model using the best hyperparameters
• Generate a Confusion Matrix and calculate the F1-score for the "Satisfied" class
• Visualize the decision tree using `plot_tree` to reveal the classification logic
• Extract and rank feature importance scores (e.g., Seat Comfort, In-flight Wifi)
• Compare Decision Tree interpretability and performance against Logistic Regression for this business context

Project Goal
By the end of this project, your analysis should:
• Successfully tune hyperparameters to prevent overfitting and improve model generalization
• Fit a Decision Tree model with optimal structure validated on held-out test data
• Evaluate performance using Confusion Matrix and F1-score to balance precision/recall trade-offs for the "Satisfied" class
• Visualize the decision tree to make model logic transparent and auditable for non-technical users
• Identify and rank the top operational drivers of customer satisfaction
• Deliver a clear stakeholder report comparing Decision Tree vs. Logistic Regression trade-offs (e.g., interpretability, handling of non-linear relationships, and business actionability)

Project Submission
GitHub repository link containing:
• Jupyter Notebook (e.g., decision_tree_airline.ipynb) with all cells executed, including GridSearchCV output, confusion matrix, F1-score, and a clearly rendered `plot_tree` visualization
• README.md summarizing the dataset, best hyperparameters found during tuning, top feature rankings, and overall modeling approach
• Clean, well-documented code with Markdown cells explaining your tuning strategy, evaluation rationale, and business comparison for airline management

