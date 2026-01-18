# AI Job Market Analysis (Pandas EDA)

## Overview
This project explores trends in the AI job market using **Python and pandas**.  
The goal is to better understand job postings by working with real, structured data and applying filtering, string operations, grouping, and aggregation.

Each row in the dataset represents a single AI-related job posting, making this a realistic example of the kind of tabular data commonly used in industry.

The project is intentionally scoped as an **exploratory data analysis (EDA)** exercise to strengthen pandas fundamentals before moving on to visualization, machine learning, or full-stack systems.

---

## Dataset
The dataset contains AI job postings with features such as:
- Job title  
- Industry  
- Company name  
- Skills required  
- Experience level  
- Employment type  
- Location  
- Salary range  
- Company size  
- Preferred tools  

Most columns are categorical, with salary represented as a range.  
Each row corresponds to **one job posting**.

---

## Skills Demonstrated
This project focuses on core pandas skills that are essential for data analysis and AI-related workflows.

### Data Inspection & Exploration
- Loading and inspecting CSV data  
- Understanding dataset structure and column types  
- Distinguishing between numeric and categorical features  
- Reviewing sample rows to understand the data  

### Filtering & Boolean Indexing
- Filtering rows based on specific conditions  
- Combining conditions using AND, OR, and NOT  
- Case-insensitive string matching  
- Safely handling missing values  

### String Operations
- Identifying patterns in text using `.str.contains`  
- Checking prefixes and suffixes  
- Splitting job titles into words  
- Comparing word counts versus character counts  

### Grouping & Aggregation
- Grouping data by one or multiple columns  
- Counting job postings using row-based aggregation  
- Identifying the most and least common job titles  
- Comparing role diversity across industries  
- Sorting and interpreting aggregated results  

---

## Key Questions Explored
- Which industries post the most AI-related jobs?  
- What job titles appear most and least frequently?  
- Which companies post the highest number of AI roles?  
- How diverse are job roles within each industry?  
- Are some industries dominated by a narrow set of roles?  

---

## Key Observations
- AI job postings are not spread evenly across industries, with a small number accounting for a large share of roles.  
- A handful of job titles appear far more often than others, suggesting demand is centered around core AI roles.  
- Some industries offer a wider variety of roles, while others focus on a narrower set of positions.  
- Hiring activity is concentrated among certain companies rather than being evenly distributed across employers.  
- Technical roles, such as engineering and research positions, appear more frequently than product-focused roles.  
- Job titles vary widely in length and specificity, reflecting differences in specialization and seniority.  

---

## Why This Project Matters
Before building machine learning models or full-stack applications, it’s important to understand the data itself.

This project reflects real-world tasks commonly performed by:
- Data analysts  
- AI and machine learning engineers  
- Research and product teams  

Strong fundamentals in filtering, aggregation, and interpretation form the foundation for reliable, scalable data-driven systems.

---

## Future Work & Extensions
This analysis can serve as a starting point for more advanced projects, including:
- Converting salary ranges into numeric minimum and maximum values  
- Adding visualizations to better communicate trends  
- Applying NLP techniques to analyze skills and job descriptions  
- Predicting job categories based on titles and required skills  
- Building a backend API to serve job market insights  
- Developing a full-stack dashboard to explore AI hiring trends interactively  

These extensions would build directly on the pandas-based analysis completed here.

---

## Conclusion
This project demonstrates strong foundational data analysis skills using pandas while staying focused and approachable.

It serves as:
- A complete exploratory data analysis project  
- A template for future structured data work  
- A stepping stone toward machine learning and full-stack platforms  
