# PDAN_Tutorial

# **PDAN8411 POE Part 1: Linear Regression \- Student Guide & Skeleton**

**Note:** This skeleton is designed to help you structure your submission to meet the 2026 POE requirements. Ensure you replace all placeholder text with your own original analysis and research.

## **Section 1: The Report (PDF Format)**

### **1\. Executive Summary**

* Summarize the purpose of the analysis (predicting medical aid charges).  
* Briefly state the key findings (e.g., "Smoking status is the primary driver of costs").  
* Mention the final model's performance (e.g., R-squared value).

### **2\. Introduction & Justification of Suitability**

* Define Linear Regression and why it is used for continuous numeric targets like insurance premiums.  
* **Requirement Check:** Discuss the quality of the dataset and mention potential pitfalls (e.g., outliers or multicollinearity).

### **3\. Analysis Plan**

* Provide a roadmap of your technical steps.  
* Include a table or infographic detailing your planned EDA, feature selection, and evaluation metrics.

### **4\. Methodology (EDA & Feature Selection)**

* Explain the cleaning steps taken (handling nulls, duplicates).  
* Describe your Feature Selection strategy (e.g., using P-values or SelectKBest).

### **5\. Model Training & Comparative Analysis**

* Detail the training process.  
* **Pro Tip:** Compare your linear model against a non-linear model (like KNN) to show additional research and justify the linear approach.

### **6\. Interpretation of Results & Evaluation**

* Justify your choice of metrics (MSE, R-squared).  
* Interpret what the coefficients mean for the client (e.g., "For every year increase in age, charges increase by $X").

### **7\. Conclusion**

* Final verdict on the model's effectiveness for the medical aid scheme.  
* Suggestions for future improvements.

### **8\. References**

* List all sources (tutorials, documentation, LLM usage) using the Harvard referencing style.

## ---

**Section 2: The Jupyter Notebook (.ipynb)**

### **Markdown Header: Project Identification**

\# Name: \[Student Name\]  
\# Student Number: \[stXXXXXXXX\]  
\# Module: PDAN8411 POE Part 1

### **Step 1: Imports & Data Loading**

* Import pandas, numpy, seaborn, and sklearn.  
* Load the insurance.csv dataset.

### **Step 2: Exploratory Data Analysis (EDA)**

* **Code:** Check for nulls and duplicates.  
* **Visuals:** Use sns.heatmap for correlations and sns.pairplot for patterns.  
* **Markdown:** Explain what the graphs reveal about the data.

### **Step 3: Feature Engineering**

* Convert categorical variables (smoker, region, sex) into dummy variables.  
* Use Feature Selection (e.g., f\_regression) to isolate significant predictors.

### **Step 4: Training the Model**

* Split data into training and testing sets (train\_test\_split).  
* Fit the LinearRegression() model.

### **Step 5: Evaluation**

* Calculate and display MSE and R-squared.  
* **Markdown:** Interpret these scores in plain English for the client.

## How to push to GitHub using GitHub Desktop

### Using VS Code
1. Go to ARC
2. Go to the assessments tab
3. Go to your assignment and click on it assuming the assignment has been made available
4. Go accept your GitHub link.
5. If you get a "Repository not found" or something along those lines go profile picture, profile picture then organisations and hit accept
6. Click the green code button and click on "Open with GitHub Desktop"
7. This will clone the repository for you and open it in GitHub Desktop for you.
8. Then right click and open the folder in your File Explorer.
9. This is the cloned repos folder. Now you are going to copy and paste your .ipynb file and report into this cloned folder. If you have not yet started you can just open the folder in VS Code from GitHub Desktop and work from there.
10. When you add or remove files/folders from the clones folder you should see changes on Desktop.
11. Next you "Add a summary", "Commit to main" and Publish Repository. **Make sure to push to origin**. Check that your work is online 
12. Congratulations, your code is now on GitHub. You can now push changes the same way using step 11.

### Using Google Colab

1. You can follow a similar process as the VS Code one.
2. You can maybe download the .ipynb file from Colab into your cloned folder and follow the aforementioned VS Code process or you can put your GitHub account on Colab.
3. Go to settings and then GitHub and add your account to the platform.
4. From there you can "Save a copy in GitHub" and select your assignments repo and push from there.
