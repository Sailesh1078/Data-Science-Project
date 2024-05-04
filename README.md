# Project Title: Advertisement Optimization

---

### Description:
This project focuses on optimizing advertisement strategies based on user behavior data. It encompasses various stages including data cleaning, handling missing values, outlier detection, data discretization, classification, transformation, and budget allocation. The code is primarily written in Python, utilizing libraries such as pandas, seaborn, and scikit-learn.

---

### Usage:

1. **Data Preparation:**
   - Ensure the dataset ('proj.csv') is in the same directory as the code.
   - The dataset should contain columns such as 'Age', 'Mobile Screen Time (Hours)', 'Web Browsing Habit [1-3]', 'Web Browsing Time [1-3]', 'Social Media Platform [1-2]', 'Social Media Time [1-2]', etc.

2. **Running the Code:**
   - Execute the code in a Python environment (Jupyter Notebook, Python script, etc.).
   - Follow the prompts to input necessary information during execution.

---

### Readme:

#### 1. **Cleaning Data:**
   - Age is grouped into bins, and the 'Age Group' column is created.
   - Missing values are handled using forward filling.
   - Outliers in 'Mobile Screen Time (Hours)' are detected and removed.

#### 2. **User Categorization:**
   - Web browsing habits are mapped to classes ('Education' or 'Recreational').
   - Users are categorized based on their browsing habits and accumulated time spent.

#### 3. **Data Discretization and Classification:**
   - Data is preprocessed using label encoding and standard scaling.
   - K-Nearest Neighbors (k-NN) classifier is trained to predict user categories.
   - Accuracy and F1 score are calculated for model evaluation.

#### 4. **Transformation:**
   - User specifies the type of advertisement ('Education' or 'Recreational').
   - Advertisement priorities are assigned based on user preferences and screen time.
   - Heatmap visualization of advertisement priorities is generated.

#### 5. **Budget Allocation:**
   - Total budget is entered by the user.
   - Budget allocation is calculated based on age group and composite score.
   - Percentage distribution of budget by age group is visualized.

#### 6. **Score Calculation and Top Platforms:**
   - Scores are calculated for web browsing habits and social media platforms.
   - Top 
