A machine learning project that predicts HIV patient treatment status based on drug resistance mutations, gene data, and clinical features.
Built using Python with Pandas, Scikit-learn, XGBoost, Matplotlib, and Seaborn
Dataset includes features like patient ID, HIV subtype, gene, mutation, drug class, drug name, and resistance level
Performed label encoding on 8 categorical columns including mutation, subtype, and drug class
Conducted exploratory data analysis (EDA) with bar charts, histograms, and distribution plots
Visualized relationships between resistance level and treatment status using box and bar plots
Analyzed feature correlations using a heatmap after dropping the target variable
Applied Logistic Regression as a baseline model for treatment status classification
Implemented XGBoost Classifier with multi-class softmax for improved prediction accuracy
Evaluated both models using accuracy score, confusion matrix, and classification report
Useful for identifying drug resistance patterns and supporting HIV treatment decision-making.
