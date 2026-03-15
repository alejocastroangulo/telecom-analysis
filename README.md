# 📊 ConnectaTel Customer Usage Analysis
This project analyzes customer usage behavior for ConnectaTel, a telecommunications company.   The objective is to identify usage patterns in calls and text messages, segment customers based on their behavior and age, and generate business insights that can help improve the company's service plans.

🎯 Business Problem

Telecommunications companies need to understand how customers use their services in order to design competitive plans and improve customer satisfaction.

This project explores customer usage data to identify behavioral segments and detect opportunities to optimize plan offerings.

## 📂 Dataset

The dataset includes three main tables:

**users**
- user_id
- age
- city
- reg_date
- plan

**usage**
- user_id
- date
- type (call, text)
- duration

**plans**
- plan details
- service limits
  

## ⚙️ Data Analysis Process

The project follows these main steps:

1. Data cleaning and preprocessing
2. Handling missing values and incorrect records
3. Exploratory Data Analysis (EDA)
4. Customer segmentation by age and usage level
5. Identification of usage patterns and outliers
6. Business insights and recommendations

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


## 📊 Key Insights

- Most customers fall into low or moderate usage segments.
- A smaller group of users shows high service consumption.
- Adult customers represent the largest share of the user base.
- High-usage customers may generate additional revenue through overage charges.

## 💡 Business Recommendations

- Develop differentiated plans based on customer usage segments.
- Offer plan upgrades to customers who frequently exceed their limits.
- Create targeted offers for high-value customers with intensive usage patterns.




## 📁 Repository Structure

├── data  
├── notebooks  
├── images  
├── README.md
