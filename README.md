# Stack Overflow Developer Survey EDA

## Project Overview

This project presents an Exploratory Data Analysis (EDA) of the Stack Overflow Developer Survey dataset. The analysis focuses on understanding developer demographics, employment patterns, remote work preferences, job satisfaction, education levels, and programming language trends.

The project demonstrates data cleaning, missing value handling, feature transformation, statistical analysis, and data visualization using Python and industry-standard data analysis libraries.

---

## Dataset

The dataset contains responses from software developers worldwide and includes information related to:

- Employment status
- Job satisfaction
- Remote work preferences
- Professional coding experience
- Programming languages used
- Educational background
- Country of residence

---

## Key Insights

### Experience and Job Satisfaction
- Developers with more than 10 years of professional experience reported higher median job satisfaction compared to early-career developers.
- Median satisfaction increased from approximately **7/10** among less experienced developers to **8/10** among developers with over 10 years of experience.

### Weak Correlation Between Experience and Satisfaction
- Professional coding experience showed a very weak correlation with job satisfaction.
- This suggests that factors such as work environment, compensation, flexibility, and career growth may influence satisfaction more strongly than experience alone.

### Remote Work Trends
- Remote and hybrid work arrangements were widely adopted among developers.
- Full-time employees represented the largest group participating in remote work.

### Education and Employment
- Bachelor's and Master's degree holders constituted a significant portion of employed developers.
- Higher education levels were strongly represented across professional employment categories.

### Programming Language Adoption
- Programming language preferences varied across countries.
- Popular technologies such as Python, JavaScript, SQL, and HTML/CSS appeared frequently across multiple regions.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Imported and inspected the survey dataset.
- Explored dataset structure and column information.

### 2. Data Cleaning
- Identified missing values.
- Imputed categorical variables using mode values.
- Removed records with missing target analysis fields.

### 3. Feature Engineering
- Converted professional coding experience into experience groups.
- Prepared data for comparative analysis and visualization.

### 4. Exploratory Data Analysis
- Analyzed job satisfaction across experience levels.
- Investigated remote work patterns.
- Examined education and employment relationships.
- Explored programming language trends across countries.

### 5. Visualization
Created multiple visualizations including:

- Bar Charts
- Count Plots
- Scatter Plots
- Correlation Heatmaps
- Country-Language Heatmaps

---

## Repository Structure

```text
stackoverflow-developer-survey-eda/
│
├── README.md
├── exploratory_data_analysis_stackoverflow.ipynb
├── cleaned_survey_dataset.csv
└── requirements.txt
```

---

## Results

The analysis revealed meaningful trends in developer satisfaction, work preferences, educational backgrounds, and technology adoption. While experience contributes modestly to satisfaction, the findings suggest that other workplace factors play a larger role in shaping developer experiences.

The project highlights how exploratory data analysis can uncover valuable insights from survey data and support data-driven decision-making.

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/alanoudfd/stackoverflow-developer-survey-eda.git
```

2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open and run:

```text
exploratory_data_analysis_stackoverflow.ipynb
```


**Alanoud Fawaz**

Computer Science Graduate | Data Analyst | Machine Learning Enthusiast
