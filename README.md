# Physical-Task-Performance-Prediction

### Project Overview
This project focuses on developing and evaluating multiple machine learning classifiers to predict individual performance levels in a complex obstacle course. Utilizing a dataset of 10,000 individuals, the model analyzes demographic data (age, gender), body composition (height, weight, body fat %), and physical fitness metrics (grip strength, flexibility, sit-ups, and broad jump) to categorize performance into four distinct classes (A to D).

### Technical Implementation
Exploratory Data Analysis (EDA): Conducted in-depth analysis to identify correlations between physiological features—such as the relationship between body fat % and gripForce—and their impact on final performance classification.

Multi-Model Architecture & Evaluation: Implemented and benchmarked five diverse classifiers, ranging from baseline linear models (Logistic Regression) and kernel-based methods (SVM) to ensemble learning (Random Forest, Gradient Boosting) and deep learning (Multilayer Perceptron/MLP).

Hyperparameter Optimization: Utilized Grid Search and Cross-Validation to fine-tune critical parameters, including SVM kernel types, tree depth for ensemble methods, and hidden layer configurations for the MLP.

Feature Importance & Interpretability: Extracted and visualized feature importance to determine which physical attributes (e.g., explosive power vs. endurance) are the strongest predictors of "Elite" (Class A) performance.

Technical Communication & Reporting: Leveraging my background as a Professional Undergraduate Ambassador, I translated complex algorithmic logic—such as high-dimensional spatial partitioning in SVMs—into an accessible "Non-Expert Report." This ensured that technical findings remained actionable for stakeholders without a data science background.

### Experimental Results
Model Selection: Identified Random Forest as the optimal classifier based on accuracy and F1-score balance.

Unlabelled Data Inference: Successfully applied the finalized model to predict the performance categories of 20 unlabelled individuals with high confidence.
