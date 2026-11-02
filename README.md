🐍 Python Course – Learning & Practice
Welcome to my Python Course Repository! This repository contains my learning journey, class notes, and practical exercises as I develop my Python programming and data analysis skills.
📌 About This Repository
This repository documents the concepts and hands-on work covered during my Python course. It includes Jupyter Notebook exercises and examples that help me understand how Python can be used to explore and analyse data.
📚 Day 1 – Introduction to Data Analysis with Python
In my first practical session, I worked with a student depression dataset and learned how to inspect and understand data using Python.
Topics Covered
- Importing Python libraries
- Reading CSV files
- Exploring datasets
- Viewing the first and last rows
- Checking dataset dimensions
- Understanding dataset information
- Generating descriptive statistics
- Selecting random samples
- Identifying data types
- Displaying column names
- Separating numerical and categorical columns
🛠️ Libraries Used
Library	Purpose
Pandas	Reading, managing, and analysing tabular data
Matplotlib	Creating data visualisations


import pandas as pd
import matplotlib.pyplot as plt
💻 Practical Work
The Day 1 notebook includes examples of the following Pandas operations:
# Read a CSV file
df = pd.read_csv("Student_Depression_Dataset.csv")

# Display the first 5 rows
df.head()

# Display the first 20 rows
df.head(20)

# Display the last 5 rows
df.tail()

# Check the dataset dimensions
df.shape

# Display a random sample
df.sample(5)

# Check data types
df.dtypes

# Get column names
df.columns.tolist()

# Get numerical columns
df.select_dtypes(include="number").columns.tolist()

# Get categorical columns
cat_cols = df.select_dtypes(exclude="number").columns.tolist()
Other notebook exercises explore dataset information and descriptive statistics.
📂 Repository Structure
Python-Course/
│
├── README.md
├── python class day 1.ipynb
└── Student_Depression_Dataset.csv
Note: Keep the CSV dataset in the same folder as the notebook so the file-reading code can locate it.
🚀 Tools & Technologies
- Python
- Jupyter Notebook
- Pandas
- Matplotlib
- CSV datasets
🎯 Learning Goals
- Build a strong foundation in Python.
- Understand data handling using Pandas.
- Learn to explore and analyse datasets.
- Practise Python through hands-on exercises.
- Gradually develop data analysis and visualisation skills.
📈 My Learning Journey
This repository will be updated as I progress through my Python course. I will continue adding new notebooks, concepts, and practical projects.
🙌 A Little About Me
I'm currently pursuing BCA from G.M.N. College and enjoy learning new skills and exploring technology. Through this course, I aim to strengthen my programming knowledge and gain practical experience with Python.
⭐ Thanks for visiting my Python learning repository!

Learning step by step, coding by coding.
