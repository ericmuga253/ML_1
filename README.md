

# **Customer Enrollment Prediction Based on Website Likes**
![Screenshot 2025-03-04 134353](https://github.com/user-attachments/assets/2e2068cc-ac1c-4a08-9eeb-7590712bea54)
  

## **Project Overview**  
This project explores the relationship between customer engagement (measured by likes on a company’s website) and customer enrollment. Using machine learning classification techniques, the goal is to determine whether the number of likes influences customer enrollment. The dataset for this project was sourced from **Kaggle** and contains relevant features related to user interaction and conversion rates.  

## **Objective**  
- Analyze how website likes impact customer enrollment.  
- Build a **classification model** to predict whether a customer will enroll based on engagement metrics.  
- Use machine learning techniques to improve decision-making for marketing strategies.  

## **Dataset**  
- **Source:** Kaggle  
- **Key Features:**  
  - `likes`: Number of likes on the company website  
  - `visits`: Number of website visits  
  - `time_spent`: Time spent on the website  
  - `customer_status`: Whether a customer enrolled (Target Variable: **Yes/No**)  
- **Target Variable:** **Customer Enrollment** (Binary Classification: **Enrolled** or **Not Enrolled**)  

## **Technologies Used**  
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - `pandas`, `numpy` for data manipulation  
  - `matplotlib`, `seaborn` for data visualization  
  - `scikit-learn` for machine learning modeling  
  - `Jupyter Notebook` for experimentation and analysis  

## **Project Workflow**  
1. **Data Collection & Cleaning:**  
   - Load the dataset from Kaggle  
   - Handle missing values and outliers  
   - Convert categorical variables if needed  
2. **Exploratory Data Analysis (EDA):**  
   - Understand patterns between website engagement and customer enrollment  
   - Visualize key insights using bar charts, histograms, and correlation heatmaps  
3. **Feature Engineering:**  
   - Create relevant features that improve classification performance  
   - Normalize or standardize numerical values if necessary  
4. **Model Selection & Training:**  
   - Train multiple classification models:  
     - Logistic Regression  
     - Decision Tree  
     - Random Forest  
     - Support Vector Machine (SVM)  
   - Evaluate model performance using accuracy, precision, recall, and F1-score  
5. **Hyperparameter Tuning:**  
   - Optimize the best-performing model using GridSearchCV  
6. **Model Evaluation & Insights:**  
   - Compare model results and identify the most accurate classifier  
   - Generate insights on how website engagement influences customer behavior  

## **Installation & Setup**  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo-name.git
   cd your-repo-name
   ```
2. Install required dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to execute the analysis:  
   ```bash
   jupyter notebook
   ```

## **Results & Insights**  
- **Key Findings:**  
  - There is a significant correlation between the number of likes and customer enrollment.  
  - Customers who spend more time on the website tend to enroll more frequently.  
  - The **Random Forest model** achieved the highest accuracy, making it the best classifier for this dataset.  

## **Future Improvements**  
- Collect more diverse data to enhance model generalization.  
- Experiment with deep learning models to improve accuracy.  
- Implement a real-time prediction API for marketing teams.  

## **Contributing**  
If you’d like to contribute, feel free to fork the repository, make changes, and submit a pull request.  

## **License**  
This project is licensed under the **MIT License**.  

---

