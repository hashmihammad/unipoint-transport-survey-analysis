# UniPoint Transport Survey Analysis 

## Project Overview
This project performs **Exploratory Data Analysis (EDA)** on real survey data collected from students of the **University of Sindh, Jamshoro** regarding the **UniPoint (University Transport) system**.

The goal of this analysis is to understand:
- Student travel patterns
- Availability of UniPoint pickup points
- Satisfaction levels with punctuality and bus conditions
- Common problems and suggestions reported by students

The insights from this project can help university management improve transport services, safety, and accessibility.

---

## Dataset Description
- **Source:** Student survey responses (Google Form)
- **Format:** CSV
- **Rows:** 80+ responses
- **Key Features:**
  - Gender
  - Department / Faculty
  - Area of travel
  - Mode of transport
  - Number of UniPoint pickup points
  - UniPoint availability near area
  - Transport ratings (1–5)
  - Student suggestions and feedback

> ⚠️ Personal identifiers (emails, roll numbers) are not used for analysis purposes.

---

## Tools & Technologies
- **Python**
- **Pandas** – data cleaning & manipulation  
- **NumPy** – numerical operations  
- **Matplotlib & Seaborn** – data visualization  
- **Jupyter Notebook** – analysis workflow  

---

## Data Processing Steps
- Loaded raw survey data from CSV
- Renamed long column names for readability
- Handled missing values using median and placeholders
- Converted numeric fields to appropriate data types
- Saved a cleaned dataset for reuse
- Encoded selected categorical fields for analysis

---

## Exploratory Data Analysis (EDA)
The analysis includes:
- Gender distribution of respondents
- Distribution of UniPoint service ratings
- Mode of transport usage by gender
- Area-wise analysis of pickup point availability
- Average rating calculation
- Identification of common transport issues through student feedback

Visualizations were created to clearly communicate trends and problem areas.

---

## Key Insights
- A significant number of students reported **low satisfaction** with UniPoint services
- **Overcrowding, poor bus condition, and lack of pickup points** are common issues
- Certain residential areas have **insufficient UniPoint coverage**
- Many students rely heavily on UniPoint due to lack of alternative transport

---

## Project Structure
```

unipoint-transport-survey-analysis/
│
├── unipoint_analysis.ipynb        # Jupyter Notebook (EDA & visualizations)
├── unipoint_survey.csv            # Raw survey data
├── README.md                      # Project documentation

````

---

## How to Run the Project
1. Navigate to the project folder:

   ```bash
   cd unipoint-transport-survey-analysis
   ```
2. Open the notebook:

   ```bash
   jupyter notebook unipoint_analysis.ipynb
   ```

---

## Conclusion

This project demonstrates practical **data analysis skills using real-world data**, focusing on data cleaning, visualization, and insight generation. It reflects how data science can be applied to solve **real institutional problems**.

---

## Author

**Syed Hammad Hashmi**

* LinkedIn: [https://linkedin.com/in/syed-hammad-hashmi](https://linkedin.com/in/syed-hammad-hashmi)
* GitHub: [https://github.com/hashmihammad](https://github.com/hashmihammad)

