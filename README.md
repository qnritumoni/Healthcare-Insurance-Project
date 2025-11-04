# Healthcare Insurance Data Analytics
Health insurance is a contract between the policyholder and an insurance company. It's important because it Protects from high medical costs,ensures access to healthcare when needed,encourages preventive care & keeping you healthier,Provides financial peace of mind during illness or accidents.Here I am using a Insurance Dataset to provide a comprehensive and data-driven analysis to turn raw insurance data into actionable insights for smarter pricing, risk management, and better healthcare planning.

<img width="2048" height="1536" alt="health-insurance-features" src="https://github.com/user-attachments/assets/4c4434a9-7446-49cc-9dc8-957689c7a073" />



# Dataset
https://1drv.ms/x/c/6daacb3298e20a70/EXmXRkRZzQ1PtQ0VmFn24lABXHhSzP42NIvOPqFeur3EFA?e=pRBcs2

# Data Summary
I used the mentioned dataset that contains information on the relationship between personal attributes (age, gender, BMI, family size, smoking habits), geographic factors, and their impact on medical insurance charges.The goal is to provide a clear, visual understanding of how personal and lifestyle attributes impact insurance expenses across the country.It can be used to study how these features influence insurance costs and develop predictive models for estimating healthcare expenses.
Here-
🧓 Age: Age of primary beneficiary or insured person.

👫 Sex: Gender (male or female) of the insured person.

🧈 BMI (Body Mass Index): A measure of body fat based on height and weight.

🧒 Children:The number of dependents covered by insirance.

🚭 Smoker: Smoking status of insured person (yes or no).

🏳️ Region: The geographic area of coverage (northeast,northwest,southeast,southwest).

💰 Charges: The medical insurance charges billed by health insurance.

### Tools Being Used
- **Excel** – Data cleaning, filtering, and visualization basics
- **SQL (MySQL / SQLite)** – Data querying and aggregation in Colab and Jupyter Notebook.
- **Python (Pandas, Matplotlib, Seaborn)** – Exploratory Data Analysis (EDA)
- **Power BI** – Data modeling and dashboard creation
- **GitHub** – Project version control and sharing

### Expected Outcomes
- Understand the key factors influencing insurance charges
- Compare smokers vs. non-smokers, gender, region, and BMI impact
- Build interactive Power BI dashboards for visualization

### Project Overview:

<img width="567" height="418" alt="image" src="https://github.com/user-attachments/assets/f1102457-4d32-4896-8ccd-eda1dab01938" />
### Pivot table analysis:

<img width="618" height="327" alt="image" src="https://github.com/user-attachments/assets/802a9195-db15-4d5f-8338-f497bff4c398" />
Avg Charge by region

<img width="708" height="427" alt="image" src="https://github.com/user-attachments/assets/c6713f8e-bdb9-4f63-a0aa-28967b400e05" />
Gender Distribution

<img width="726" height="431" alt="image" src="https://github.com/user-attachments/assets/3d51f73d-7e19-4f62-8531-ff9ba3fc6760" />
Avg Charge by Smoker

<img width="694" height="427" alt="image" src="https://github.com/user-attachments/assets/a4cb976b-42b1-4354-93b6-80d031a7b411" />
Avg BMI by gender

<img width="700" height="423" alt="image" src="https://github.com/user-attachments/assets/cf75d4fa-5882-4b11-b31c-4b5b4622e8d3" />
Smoker by region

### In Excel I used formula like-XLOOKUP,SUM,AVERAGE,COUNTIFS,IF,FILTER,INDEX,MAX,MIN,SUMIFS,COUNT for doing some  calculations.





### Power BI Dashboards:
### Dashboard-1: Demographic Overview
<img width="744" height="423" alt="image" src="https://github.com/user-attachments/assets/be3f6eed-3f8b-4011-8181-61b243387524" />

### Focus: Understanding patient demographics  across the region.

### Factors Covered by this Dashboard-1

* What is the distribution of patients by region, gender, and age group?
* What is the average BMI and number of children per region?
* What is the gender distribution within each region?
* How does the age distribution vary across regions?
* What percentage of patients are smokers vs non-smokers in each region?

### Dashboard-2: Insurance Cost Analysis
<img width="749" height="419" alt="image" src="https://github.com/user-attachments/assets/0862a291-542b-41b6-a1f9-0f903661a9af" />

### Focus: Explore how insurance charges vary by profile.

### Factors Covered by this Dashboard-2

* What is the average insurance charge by region?
* How do smokers vs. non-smokers compare in terms of average charges?
* Does the number of children affect the total insurance cost?
* What is the correlation between BMI and insurance charges?
* Which age group or gender incurs the highest average charges?

  <img width="953" height="432" alt="image" src="https://github.com/user-attachments/assets/1b23cb0c-c8ce-44ad-8d58-186654332d28" />
  
This scatter plot visualizes the relationship between BMI (x-axis) and insurance charges (y-axis), with a trendline included. Here’s the conclusion from the chart:

### Positive Correlation:

The dotted trendline slopes upward, suggesting a mild positive correlation between BMI and insurance charges. As BMI increases, average charges tend to increase, though the trend is not very steep.
### High Variability:

There’s a wide spread of charges across most BMI levels. For example, individuals with a BMI around 30 show charges ranging from under $10K to over $60K—indicating other factors also strongly influence costs (e.g., smoking, age, region).
### Clustered Lower Charges:

Most of the data points are clustered below $20K, showing that the majority of patients incur relatively low charges regardless of BMI.
### Outliers Drive the Trend:

A few high-cost outliers with high BMI are likely influencing the upward slope of the trendline. These might represent high-risk patients (e.g., high BMI, smokers or elderly patients with conditions).

### Insight:
While higher BMI is associated with higher insurance charges, it’s not a strong standalone predictor. Combining BMI with smoking status, age, and region would give more accurate insights into what drives insurance costs.

### Dashboard 3: Cost Drivers

<img width="746" height="421" alt="image" src="https://github.com/user-attachments/assets/1b46f752-94cb-4318-9d5c-ec92909fe755" />

### Focus: Identify the factors driving up costs.

### Factors Covered by this Dashboard-3

* Which combinations (e.g., Age + high BMI) lead to the highest charges?
* What are the top 10% costliest patients, and what traits do they share?
* How does BMI bins relate to insurance charges?
* Patients who are in the top 10% for BMI or number of children.

### Insights:
* Most top 10% patients are smokers
* They often have BMI > 30 (Obese)
* Tend to be older
* May have more children or from a certain region

### Conclusion

This project provides a comprehensive, data-driven exploration of healthcare insurance data by integrating Python-based analysis, SQL queries, and Power BI visualizations.

Through Python, the dataset was cleaned, transformed, and statistically analyzed to uncover patterns in age, gender, region, BMI, smoking habits, and charges.
SQL was used to perform precise data extractions and aggregations, helping to identify high-risk groups and cost-driving factors within the insurance data.
Finally, Power BI brought these insights to life through interactive dashboards, enabling clear visual understanding of trends such as regional charge variations, demographic distributions, and the impact of lifestyle factors like smoking and BMI on medical expenses.

Overall, this end-to-end analysis demonstrates how combining tools across different data stages — Python for processing, SQL for querying, and Power BI for visualization — leads to a powerful, evidence-based understanding of insurance risk and cost behavior. It highlights the value of integrating analytics and visualization to support smarter decision-making, risk prediction, and strategic planning in the healthcare insurance domain.
  



