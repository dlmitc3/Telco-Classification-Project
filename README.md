Telco Retention Review

                  **Classification Project**
PROJECT OBJECTIVES:

Perform data analysis on Telco data and predict customer churn. Using machine learning classification models analyze customers behavior and develop strategies to increase retention.

GOALS:

Find drivers for customer churn at Telco.

Construct a Machine Learning classification models that accurately predicts customer churn.

Document finding and presented report to jemison cohorts.

What's in the dateset ?

Source : Telco Dataset

Telco provided data scientist with customer data to help predict churn based on demographic, usage and account information. My main objective is to analyze churned customer behavior and develop strategies to increase retention.

A. Demographic:

Gender: Male / Female

Partner, Dependent and Senior Citizen : "Yes"/"No"

B. Services: remove no internet service

Phone service : "Yes"/"No"

Multiline Phone service : "Yes"/"No"/"No phone service"

Internet Service : "DSL"/"Fiber optic"/"No"

Online security : "Yes"/"No"/"No internet service"

Online backup : "Yes"/"No"/"No internet service"

Device protection : "Yes"/"No"/"No internet service"

Tech support : "Yes"/"No"/"No internet service"

Streaming TV : "Yes"/"No"/"No internet service"

Streaming Movies : "Yes"/"No"/"No internet service"

C. Account Information:

CustomerID: unique identifier (UID):

unique identifier (UID) is a numeric or alphanumeric string that is associated with a single entity within a given system
Tenure: Numerical

Contract type: "Month-to-month"/"Two year"/"One year"

Paperless billing: "Yes"/"No"

Payment method: "Mailed check"/"Electronic check"/"Credit card (Automatic)"/"Bank transfer (Automatic)"

D. Usage:

Monthly charges: Numerical

Total charges: Numberical

E. Target:

Churn:"Yes"/"No"

PLANNING:

Acquire data from the Codeup Database using acquire/prepare function to automate analysis and collection process. Saved files will be imported into Final Report Notebook.

Clean and prepare data for preparation then create a function to automate the process.

The function is saved in a prepare.py file located on my home computer.
Define two hypotheses and set an alpha 0.05, run the statistical tests needed and document all findings and takeaways.

Establish a baseline accuracy and document well.

Establish and Train three different classification models.

Evaluate models on train and validate datasets.

Choose the model that performs best. And evaluate the model on the test dataset.

Final:

Create csv file with customer_id, probability of churn, and prediction of churn
AUDIENCE:

Codeup Data Science team

STATED HYPOTHESES:

𝐻𝑜 : There is no difference in churn rate between customers with 1 month of tenure and the customers longer tenure

𝐻𝑎 : There is a difference in churn rate between customers with 1 month of tenure and the customers with longer tenure

INSTRUCTIONS FOR RECREATING PROJECT:

Read this README.md Create a env.py file that has (user, host, password) in order to get the database

Download the aquire.py, prepare.py, model_func.py, explore.py and final_notebook_project.ipynb into your working directory Run the final_notebook_project.ipynb notebook

DELIVER:

A Jupyter Notebook Report showing process and analysis with goal of finding drivers for customer churn.

A README.md file containing project description with goals, a data dictionary, project planning (lay out your process through the data science pipeline), instructions or an explanation of how someone else can recreate your project and findings (What would someone need to be able to recreate your project on their own?), and key findings and takeaways from your project.

A CSV file with customer_id, probability of churn, and prediction of churn.

Individual modules, .py files, that hold your functions to acquire and prepare your data.

A notebook presentation walkthrough with a high-level overview my project charts and data.