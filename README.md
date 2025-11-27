# FinalProject_DataWrangling_2025

## 1. Purpose

The purpose of this group final project is to put into practice the tools and knowledge you’ve gained throughout this course. This project will:

1. Give you more experience using Python data-wrangling tools on real-world data.
3. Start or strengthen your data science portfolio with a reproducible analysis you can show to others.

## 2. Project Goal

The main goal is to:

- Import a real dataset, clean and tidy it, and perform basic exploratory data analysis (EDA) using Python, producing a fully reproducible Jupyter Notebook report.

Core tasks:

- Import data from at least one real-world dataset.
- Clean & tidy the data (handle missing values, messy formats, etc.).
- Transform and wrangle the data to make it analysis-ready.
- Perform exploratory data analysis with tables, summaries, and visualizations.
- Present everything in a Jupyter Notebook (.ipynb) with clear explanations in Markdown.

A predictive model is **optional**, not required.

## 3. Project Data

Choose one dataset from the four below: 
1. Petfinder.com Dog Data
  - Adoption data for dogs (attributes like breed, age, etc.).
2. Hotel Bookings Data
  - Booking, cancellation, and stay information for city and resort hotels.
3. NFL Attendance Data
  - Game-level attendance information for NFL teams.
4. Spotify Genre Data
 - Track-level audio features (e.g., danceability, energy) by genre.

Each dataset has:
- Multiple data types: numbers, strings, dates.
- Non-normalized characteristics: punctuation, mixed case, etc.
- Potential need to merge/join tables.
- Unclean data: missing values, odd codes, inconsistencies.
- Variables that can be created from existing ones.
- Rows that may need to be filtered out.

You are encouraged to look up the original GitHub repositories/data dictionaries for details about each dataset. 
Xiaorui

Important: Even if classmates choose the same dataset, each group must show original work and analysis.

## 4. Tools & Environment (Python Version)

You must use Python as your main tool. A typical stack:

- Core
  - pandas for data wrangling
  - numpy for numerical operations
- Visualization
  - matplotlib and/or seaborn
  - Optional: plotly, bokeh, or altair for interactive plots
- Notebook Environment
  - Jupyter Notebook (local, JupyterLab, VS Code, Google Colab, etc.)

All imports should appear at the top of the notebook.

5. Project Report & Deliverables

You will create a Jupyter Notebook that tells a clear story with the data.

Deliverables:

Main report:

A Jupyter Notebook (.ipynb) with:

Markdown cells explaining your thought process.

Python code cells for data work and plots.

Exported report:

HTML or PDF export of the notebook (so it can be read without running code).

Data & extras:

A copy of the dataset(s) used (or clear link if online).

Any additional files used (images, helper scripts, etc.).

Your notebook should be a narrative, not just loose code + random plots. Think “data → insights → actions”, not “100 pretty graphs with no point.” 
Xiaorui

6. Suggested Structure (Sections)

Use section headings similar to these:

Introduction

Packages & Setup

Data Preparation (Importing, Cleaning & Tidying)

Exploratory Data Analysis (EDA)

Summary & Conclusions

(Optional) Limitations & Future Work

You may add more subsections if helpful (e.g., “Missing Data Handling”, “Feature Engineering”, etc.).

7. Grading Rubric (Python Version, 50 points)

(Adapted from the original R final project rubric. 
Xiaorui
)

7.1 Introduction – 5 points

1.1 Problem statement:
Clearly describe the question or problem you are addressing. Why is this interesting or important?

1.2 Plan & data overview:
Briefly explain which dataset you use and how you will approach the problem.

1.3 Proposed analysis approach:
Mention what analysis/techniques you plan to use (descriptive stats, time series trends, group comparisons, etc.).

1.4 Value to the consumer:
Explain how your analysis could be useful for a decision-maker or stakeholder.

7.2 Packages & Setup – 5 points

2.1 Imports up front:
All Python packages (import pandas as pd, etc.) are imported at the top.

2.2 Clean output:
Unnecessary warnings/messages are suppressed where appropriate (e.g. using warnings module or notebook settings).

2.3 Package purpose explained:
Short comments/Markdown explaining why main packages are used (don’t assume the reader knows all of them).

7.3 Data Preparation – 10 points

3.1 Data source citation:
State and link the original data source (e.g., GitHub repo, original article).

3.2 Describe raw data:
Explain:

Original purpose of the data

When/how it was collected

Number of rows/columns

How missing values or special codes are recorded

3.3 Clear wrangling steps:
In words + code, explain and justify your cleaning steps:

Handling missing values

Fixing data types

Renaming variables

Filtering rows

Joining/merging tables (if any)

3.4 Show final cleaned data:
Provide a compact view: e.g., df.head(), df.sample(5), or a nicely formatted table.

3.5 Summaries of key variables:
Instead of dumping df.info() and df.describe() raw, give:

A condensed table of key columns with simple stats, or

A well-written paragraph describing distributions, ranges, etc., using inline code (e.g., df['age'].mean()).

7.4 Exploratory Data Analysis – 10 points

4.1 Go beyond obvious:
Don’t only re-plot raw data. Create new variables, groupings, or aggregated summaries.

4.2 Variety of outputs:
Use both plots and tables:

At least several meaningful visualizations

At least one useful summary table

4.3 Plot quality:
Each important plot:

Has a clear title and axis labels

Uses appropriate scales

Is readable (no overlapping text, etc.)

Focuses on one main point

4.4 Table quality:
Tables are:

Sized appropriately

Easy to read and interpret

Focused on key comparisons

4.5 Insightful interpretation:
You write clear, concise explanations of what you found. The reader should not need to guess what the graphs/tables mean.

7.5 Summary & Reflection – 5 points

6.1 Restate the problem:
Briefly remind the reader of the goal.

6.2 Recap approach:
Summarize data used and what you did to analyze it.

6.3 Key findings:
Highlight the most important insights.

6.4 Implications:
Explain what actions or decisions could be supported by your findings.

6.5 Limitations & future work:
Honestly discuss limitations (data quality, time, methods) and suggest how someone could improve or extend your work.

7.6 Coding Style, Reproducibility & Creativity – 15 points

7.1 Code style & comments:

Clean, readable code (consistent naming, spacing, etc.).

Comments where needed to explain non-obvious logic.

7.2 Systematic workflow:

Complex tasks broken into smaller steps.

Use of appropriate data structures (DataFrames, Series, lists, etc.).

Checks for common issues (e.g., verifying merges worked as expected).

7.3 Achievement & creativity:

Competent use of course tools.

Bonus for creative or advanced elements (e.g., additional Python libraries, deeper analysis).

7.4 Reproducibility:

Notebook runs from top to bottom without errors.

All paths and file references are clear.

The exported HTML/PDF matches the notebook output.

Total: 50 points

8. Optional Advanced Challenge (Python Version)

For students who are more advanced or want extra challenge:

Build a small interactive dashboard using a Python framework such as:

Plotly Dash

Streamlit

Bokeh server

Voila (turn notebook into an app)

This dashboard should allow basic interaction (filtering, selecting categories, etc.) based on your analysis, similar in spirit to the Shiny app challenge in the original R assignment. 
Xiaorui

This part can be rewarded with bonus points or extra credit.

9. Submission Instructions (you can edit)

Deadline: __________ (fill in date & time).

Submit via LMS/Email/GDrive:

.ipynb notebook file

Exported HTML or PDF report

Dataset file(s) or clear links

Any additional assets (images, extra scripts, etc.)

File naming convention (example):

2025_DataWrangling_Lastname_Firstname_FinalProject.ipynb
2025_DataWrangling_Lastname_Firstname_FinalProject.html
