# Netflix-EDA

## Project Overview
This project explores Netflix’s Movies and TV Shows catalog using exploratory data analysis (EDA). The goal was to better understand Netflix’s content strategy, genre distribution, and growth trends over time while developing strong, industry-relevant data analysis skills.

This project focuses on **data understanding, cleaning, visualization, and insight generation** rather than predictive modeling.

---

## Objectives
- Build fluency with exploratory data analysis workflows
- Practice working with real-world datasets containing missing values
- Analyze how Netflix’s content has evolved over time
- Identify dominant genres across the platform
- Strengthen analytical reasoning and data storytelling skills

---

## Dataset
- **Source:** Kaggle – Cleaned Netflix Movies and TV Shows
- **Total Records:** ~8,800 titles

### Key Columns
- `type` (Movie or TV Show)
- `title`
- `directors`
- `cast`
- `countries`
- `date_added`
- `release_year`
- `rating`
- `duration`
- `listed_in` (genres)

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Lab

---

## Analysis Summary

### Data Exploration & Quality Checks
- Inspected dataset structure using `head()`, `info()`, and `describe()`
- Identified missing values in columns such as `directors`, `cast`, and `countries`
- Interpreted missing data as a reflection of content structure (e.g., episodic TV shows vs movies), not data errors

---

### Movies vs TV Shows
- Netflix’s catalog is consistently movie-heavy
- TV shows grow steadily but remain lower in total volume

---

### Content Growth Over Time
- Rapid expansion began around **2015**
- Major growth occurred between **2017–2019**, driven primarily by movies
- A noticeable decline appears in **2020–2021**, likely due to COVID-related production slowdowns

#### Content Added by Year

| Year | Movies | TV Shows |
|------|--------|----------|
| 2016 | 253 | 176 |
| 2017 | 839 | 349 |
| 2018 | 1237 | 412 |
| 2019 | 1424 | 592 |
| 2020 | 1284 | 595 |
| 2021 | 993 | 505 |

---

### Genre Analysis
- Processed multi-label genre data by splitting and exploding the `listed_in` column
- Identified dominant genres across Netflix’s catalog
- Drama-related genres appear most frequently, reflecting Netflix’s focus on broad audience appeal

---

## Key Insights
- Netflix’s major content expansion began in 2015
- Movies consistently outnumber TV shows
- TV shows have more missing director and cast information due to episodic production structures
- External events such as COVID-19 are clearly reflected in production trends

---

## Skills Developed
This project helped strengthen the following skills:

- Exploratory data analysis (EDA)
- Handling missing and inconsistent real-world data
- Multi-label categorical data processing
- Trend analysis and interpretation
- Data visualization and storytelling
- Structuring clean, reproducible analysis workflows in Jupyter

---

## Future Work
- Compare genre distributions between Movies and TV Shows
- Analyze genre trends over time
- Explore regional content patterns
- Extend analysis into predictive or recommendation-based models

---

## Author
Daylin Hart  
Feel free to explore my other projects or connect with me on LinkedIn.
