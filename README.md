# Regression Analysis Final Project - Reading Habits by Age

Overview

This project was developed as part of a university course in data analysis and regression modeling. Using a dataset from Kaggle (originally collected by the Pew Research Center), the project explores how age influences reading habits and preferred book formats among respondents. The goal was to apply statistical and machine learning techniques in R to identify trends, relationships, and significant differences across reader demographics and behaviors.

Alongside the analysis script, a PowerPoint presentation summarizing key findings and visualizations is included in the repository.

--- 

**Dataset**

The dataset contained 2,832 responses and 14 variables, including:
- Demographics: Age, Sex, Race, Education, Income, Employment, Marital_Status
- Reading activity: Num_of_Books, Printed, EBooks, Audio
- Reading habits: Acquisition_Method, Daily_News/Newspaper, Magazines/Journals

The analysis focused on variables most relevant to the research question:
- Age, Num_of_Books, Printed, EBooks, and Audio.

---

**Analysis and Methods**

The project followed a structured five-step workflow within R Markdown:
- Identify the Research Problem and Collect Data
- Research question: Does age influence reading habits and preferred formats?
- Context drawn from real-world shifts in reading behavior and generational differences.
- Data Cleaning and Visualization
- Renamed variables for clarity and removed inconsistent or irrelevant responses.
- Visualized distributions with histograms, box plots, and stacked bar charts.
- Explored relationships between age, number of books read, and reading format.

---

**Hypothesis Testing**

- Conducted ANOVA and Tukey HSD tests to compare mean ages across print, audio, and eBook readers.
- Found a statistically significant difference between Printed and EBooks readers (p = 0.045).

---

**Statistical Modeling**

- Linear regression tested whether age predicts number of books read.
- Found a weak positive relationship (R² ≈ 0.003).
- Binary logistic regression tested if age predicts reading format preference.
- Only the EBooks model showed significance: older respondents were less likely to read eBooks.

---

**Interpretation and Recommendations**

- Reading frequency showed little correlation with age.
- Printed books remain the dominant format across all ages.
- Suggested targeted marketing for eBooks toward younger demographics and potential digital partnerships (e.g., Kindle, Audible).

---

**Tools and Skills**

- R and R Markdown
- Libraries: dplyr, ggplot2, tidyr, pROC, VGAM
- Data Visualization and Hypothesis Testing
- Linear and Logistic Regression Modeling
- ANOVA and Post-hoc Analysis
- Presentation and Communication of Results

---
