# FEYNNLABS_INTERNSHIP
McDonald's Market Segmentation Analysis

This project replicates a case study from the book Market Segmentation Analysis (Page 269), using Python.

🧠 Objective

To identify hidden customer segments based on their perception of McDonald's and understand what drives customer liking in each segment.

📂 Dataset

The dataset includes:

11 perception variables (e.g., Taste, Cleanliness, Value for Money)

1 target variable: Like (ordinal scale from "I hate it!-5" to "I love it!+5")

🧪 Methodology

Converted ordinal responses to numeric scale

Converted categorical Yes/No responses to binary

Applied a Gaussian Mixture Model to segment customers into 2 groups

Fitted a linear regression model to each segment to understand which perceptions influence liking in that group

💻 Technologies Used

Python

pandas

NumPy

scikit-learn

statsmodels

Jupyter Notebook

📈 Key Learnings

Different customer groups value different features of a brand

Segmentation helps in personalizing marketing strategies

Model-based segmentation offers deeper insight than basic clustering
