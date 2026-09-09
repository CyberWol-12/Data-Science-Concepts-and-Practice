# Data Science Revision & Concepts Journey

A structured collection of my hands-on practice, revision notebooks, coding exercises, and data science fundamentals built while strengthening my Python and Data Science foundation.

This repository documents my learning journey from **Python programming fundamentals** to concepts used in **Data Science and AI**, with practical notebooks and exercises based on real datasets and programming problems.

---

## Table of Contents

- [About This Repository](#about-this-repository)
- [Learning Journey](#learning-journey)
- [Repository Highlights](#repository-highlights)
- [Topics Covered](#topics-covered)
- [Python Fundamentals](#python-fundamentals)
- [Python Data Structures](#python-data-structures)
- [Control Flow](#control-flow)
- [Functions and Object-Oriented Programming](#functions-and-object-oriented-programming)
- [File Handling](#file-handling)
- [NumPy](#numpy)
- [Exception Handling](#exception-handling)
- [HTTP Requests and Web Data](#http-requests-and-web-data)
- [Pandas and Data Loading](#pandas-and-data-loading)
- [Text Analysis](#text-analysis)
- [Data Analysis Practice](#data-analysis-practice)
- [Visual Learning](#visual-learning)
- [Skills Developed](#skills-developed)
- [Tools and Technologies](#tools-and-technologies)
- [Repository Structure](#repository-structure)
- [How to Run](#how-to-run)
- [Learning Outcomes](#learning-outcomes)
- [Future Improvements](#future-improvements)
- [About Me](#about-me)
- [Connect With Me](#connect-with-me)

---

## About This Repository

This repository is my personal **Data Science revision and concepts practice workspace**.

Instead of keeping programming concepts only in theory, I have practiced them through:

- Python notebooks
- Coding exercises
- Data manipulation
- NumPy arrays
- File operations
- HTTP requests
- Exception handling
- Text analysis
- Object-oriented programming
- Pandas
- Dataset loading
- Web data extraction
- Data analysis exercises

The repository contains hands-on work covering the fundamentals required before moving deeper into:

**Data Analytics → Machine Learning → Deep Learning → NLP → AI**

---

## Learning Journey

My learning path in this repository can be summarized as:

```text
Python Fundamentals
        ↓
Expressions & Variables
        ↓
Strings
        ↓
Lists / Tuples / Sets / Dictionaries
        ↓
Conditions & Loops
        ↓
Functions
        ↓
Object-Oriented Programming
        ↓
File Handling
        ↓
Exception Handling
        ↓
NumPy
        ↓
HTTP Requests & Web Data
        ↓
Pandas & Data Loading
        ↓
Text Analysis
        ↓
Data Analysis
        ↓
Machine Learning & AI
```

This progression helped me build a stronger programming foundation for Data Science and AI projects.

---

# Repository Highlights

## Python Programming

Hands-on practice with:

- Variables
- Expressions
- Arithmetic operations
- Strings
- Lists
- Tuples
- Sets
- Dictionaries
- Conditions
- Loops
- Functions
- Classes and Objects
- File handling
- Exception handling

---

## Data Science Foundations

Practice with:

- NumPy
- Pandas
- DataFrames
- Dataset loading
- CSV files
- Excel files
- Web data
- Data preprocessing
- Basic data analysis
- Text analysis

---

## Practical Data Work

The repository also contains practice involving:

- GDP datasets
- Product datasets
- Text datasets
- Web-based datasets
- External HTTP resources
- Data extraction using Pandas
- Data extraction using BeautifulSoup
- Data manipulation using NumPy and Pandas

---

# Topics Covered

| Area | Concepts |
|---|---|
| Python | Syntax, variables, expressions, operators |
| Strings | String creation, indexing, slicing, methods |
| Lists | Indexing, manipulation, copying |
| Tuples | Indexing, slicing, sorting |
| Sets | Unique collections and set operations |
| Dictionaries | Keys, values and data access |
| Conditions | Comparison and Boolean logic |
| Loops | `for`, `while`, `range` |
| Functions | Built-in and user-defined functions |
| OOP | Classes, objects and attributes |
| Files | Reading and writing files |
| Exceptions | Error detection and handling |
| NumPy | Arrays and numerical operations |
| Pandas | DataFrames and data loading |
| HTTP | Requests, URLs and responses |
| Web Data | BeautifulSoup and table extraction |
| Text Analysis | Word processing and frequency analysis |
| Data Analysis | Dataset exploration and transformation |

---

# Python Fundamentals

The initial notebooks focus on building a strong Python foundation.

### Concepts practiced

- Python syntax
- `print()`
- Variables
- Expressions
- Arithmetic operators
- Data types
- Type conversion
- Comments
- Error messages
- Basic debugging

Example:

```python
x = 30 + 20 - 40
print(x)
```

Output:

```text
10
```

I also practiced understanding common Python errors such as:

```text
NameError
SyntaxError
```

Understanding errors and reading error messages is an important part of becoming a better programmer.

---

# Python Data Structures

## Lists

Practice includes:

- Creating lists
- Indexing
- Slicing
- Updating elements
- List manipulation
- Copying and cloning lists

Example:

```python
albums = ["The BodyGuard", "Thriller", "Back in Black"]

print(albums[0])
```

---

## Tuples

Practice includes:

- Creating tuples
- Indexing
- Slicing
- Sorting
- Accessing tuple elements

Example:

```python
album = ("Michael Jackson", "Thriller", 1982)

print(album[0])
```

---

## Sets

Sets were used to understand collections containing unique elements.

Example:

```python
genres = {
    "pop",
    "rock",
    "soul",
    "hard rock",
    "rock"
}

print(genres)
```

Duplicate values are automatically removed from a set.

---

## Dictionaries

Dictionary practice focused on:

- Keys
- Values
- Accessing elements
- Updating data
- Working with structured key-value information

Example:

```python
student = {
    "name": "Divya",
    "field": "Data Science",
    "skill": "Python"
}

print(student["name"])
```

---

# Control Flow

## Conditional Statements

Practice with:

```python
if
elif
else
```

and comparison operators:

```text
==
!=
>
<
>=
<=
```

Example:

```python
age = 20

if age >= 18:
    print("Adult")
else:
    print("Minor")
```

---

## Loops

The repository includes practice with:

- `for` loops
- `while` loops
- `range()`
- Nested logic
- Conditional logic inside loops

Example:

```python
for i in range(1, 5):
    print(i)
```

Loops are fundamental for processing collections of data efficiently.

---

# Functions and Object-Oriented Programming

## Functions

I practiced both predefined and user-defined functions.

Example:

```python
def add(a):
    return a + 1

result = add(5)

print(result)
```

Topics include:

- Function definition
- Parameters
- Arguments
- Return values
- Reusable code
- Docstrings

---

## Object-Oriented Programming

The repository includes practical work with:

- Classes
- Objects
- Attributes
- Methods
- Object creation

Examples include working with classes such as:

```text
Circle
Rectangle
```

This helped me understand how Python can be used to organize larger programs into reusable components.

---

# File Handling

The repository contains hands-on practice with reading and writing files.

## Reading Files

Practice includes:

- Opening files
- Reading text
- Reading file contents
- Working with external files

Example:

```python
with open("example1.txt", "r") as file:
    data = file.read()

print(data)
```

---

## Writing Files

Example:

```python
with open("Example2.txt", "w") as file:
    file.write("This is line A")
```

Understanding file handling is important when working with datasets and data pipelines.

---

# NumPy

NumPy is one of the main foundations for numerical computing in Python.

The repository includes practice with:

- NumPy arrays
- 1D arrays
- 2D arrays
- Array indexing
- Array operations
- Mathematical operations

Example:

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])

print(a)
```

### 2D Array Example

```python
import numpy as np

a = np.array([
    [11, 12, 13],
    [21, 22, 23],
    [31, 32, 33]
])

print(a)
```

NumPy practice provides the foundation for later work with:

- Pandas
- Machine Learning
- Scientific Computing
- Data Processing

---

# Exception Handling

The repository includes a dedicated practice notebook for exception handling.

Topics include:

- Understanding exceptions
- Handling errors
- `try`
- `except`
- Error management

Example:

```python
try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero")
```

Exception handling is useful for writing more reliable data science applications and scripts.

---

# HTTP Requests and Web Data

I also practiced understanding how web communication works.

Topics include:

- HTTP requests
- HTTP responses
- URLs
- Web resources
- Client-server communication
- GET requests
- Endpoints

Basic example:

```python
import requests

response = requests.get("https://example.com")

print(response.status_code)
```

This is useful for working with:

- APIs
- Online datasets
- Web scraping
- Data collection

---

# Pandas and Data Loading

Pandas is one of the most important libraries in my Data Science workflow.

The repository contains practice with:

- DataFrames
- Loading datasets
- CSV files
- Excel files
- Data inspection
- Data manipulation

Example:

```python
import pandas as pd

df = pd.read_csv("data.csv")

print(df.head())
```

---

# Web Data Extraction with Pandas

One of the notebooks demonstrates extracting tables from a web page using:

```python
pd.read_html()
```

Example:

```python
import pandas as pd

tables = pd.read_html(URL)

df = tables[3]
```

The extracted data was then:

- Selected
- Cleaned
- Renamed
- Filtered
- Saved to CSV

Example:

```python
df.to_csv("Largest_economics.csv")
```

---

# Data Analysis Practice

## Largest Economies Dataset

The repository contains:

```text
Largest_economics.csv
```

This dataset was created from a web-based GDP table.

The workflow included:

```text
Web Page
   ↓
Pandas read_html()
   ↓
Table Extraction
   ↓
Data Selection
   ↓
Column Renaming
   ↓
Filtering
   ↓
CSV Export
```

Example:

```python
df = df[[0, 2]]

df = df.iloc[1:11]

df.columns = [
    "Country",
    "GDP(mILLION USD)"
]

df.to_csv("Largest_economics.csv")
```

This practice helped me understand how raw web data can be converted into a structured dataset for analysis.

---

# Text Analysis

The repository also includes a text analysis practice lab.

Text analysis focuses on extracting useful information from textual data.

Topics practiced include:

- Text preprocessing
- Converting text to lowercase
- Finding unique words
- Counting word frequency
- Searching for specific words
- Basic text analytics

This provides an early foundation for future work in:

**Natural Language Processing (NLP)**

---

# Visualization Practice

Although this repository primarily focuses on programming and Data Science fundamentals, the concepts practiced here support later visualization work.

The data structures, Pandas DataFrames, NumPy arrays and cleaned datasets can be used with:

```text
Matplotlib
Seaborn
Plotly
Dash
```

for exploratory data analysis and visualization.

---

# Visual Learning

When I add screenshots of important notebook outputs, they can be organized like this:

```text
screenshots/
│
├── python/
│   ├── variables.png
│   ├── data-types.png
│   ├── conditions.png
│   └── loops.png
│
├── numpy/
│   ├── numpy-1d-array.png
│   └── numpy-2d-array.png
│
├── pandas/
│   ├── dataframe.png
│   └── dataset-analysis.png
│
├── web-data/
│   ├── html-table.png
│   └── extracted-data.png
│
└── text-analysis/
    └── word-frequency.png
```

For example:

```markdown
![NumPy 2D Array](screenshots/numpy/numpy-2d-array.png)
```

---

# Canada Immigration Visualization

If the following image is added to the repository:

```text
Immigration to Canada from 1980 to 2013.png
```

it can be displayed in the README using:

```markdown
![Immigration to Canada from 1980 to 2013](Immigration%20to%20Canada%20from%201980%20to%202013.png)
```

Or, preferably, rename it to:

```text
immigration-canada-1980-2013.png
```

and place it inside:

```text
screenshots/
```

Then use:

```markdown
![Immigration to Canada from 1980 to 2013](screenshots/immigration-canada-1980-2013.png)
```

This keeps the repository structure cleaner and makes image paths easier to manage.

---

# Tools and Technologies

### Programming

- Python

### Data Science

- NumPy
- Pandas

### Web & Data Collection

- Requests
- BeautifulSoup
- `pd.read_html()`

### Development Environment

- Jupyter Notebook
- JupyterLab
- Python scripts

### Data Formats

- CSV
- TXT
- Excel
- HTML tables

---

# Repository Structure

```text
DataScience_revision _concepts_journey/
│
├── 1.PY0101EN-1-1-Getting_Started_With_Python (1).ipynb
├── 2.PY0101EN-1-1-Expressions_Variables.ipynb
├── 3.PY0101EN-1-1-Expressions_Variables (1).ipynb
│
├── python.ipynb
├── pythonxlm.ipynb
├── Largest_economics.csv
│
├── python-practise/
│   └── 01-day1.py
│
├── python_cognitive.py/
│   ├── 1.first prgram.ipynb
│   ├── PY0101EN-1-2-Strings.ipynb
│   ├── PY0101EN-2-1-Tuples (1).ipynb
│   ├── PY0101EN-2-1-Tuples (2).ipynb
│   ├── PY0101EN-2-3-Sets (2).ipynb
│   ├── PY0101EN-3-3-Functions-jupyterlite (2).ipynb
│   ├── PY0101EN-3-4-Classes (2).ipynb
│   ├── PY0101EN-4-1-ReadFile (2).ipynb
│   ├── PY0101EN-4-2-WriteFile (1).ipynb
│   ├── PY0101EN-4-3-LoadData (1).ipynb
│   ├── PY0101EN-5 3_Requests_HTTP.ipynb
│   └── PY0101EN-5-2-Numpy2D.ipynb
│
├── python_for_data_science_and_ai/
│   ├── 3-1 2ExcecptionHandling-Copy2.ipynb
│   ├── PY0101EN-2-1-Tuples.ipynb
│   ├── PY0101EN-2-2-Lists.ipynb
│   ├── PY0101EN-2-2-Lists (2).ipynb
│   ├── PY0101EN-2-3-Sets (1).ipynb
│   ├── PY0101EN-2-4-Dictionaries (1).ipynb
│   ├── PY0101EN-3-1-Conditions (1).ipynb
│   ├── PY0101EN-3-2-Loops.ipynb
│   ├── PY0101EN-3-3-Functions-jupyterlite.ipynb
│   ├── PY0101EN-3-4-Classes (1).ipynb
│   ├── PY0101EN-3-5-Practice lab (1).ipynb
│   ├── PY0101EN-4-1-ReadFile (1).ipynb
│   ├── PY0101EN-4-2-WriteFile.ipynb
│   ├── PY0101EN-5 4_WorkingWithDifferent.ipynb
│   ├── PY0101EN-5-1-Numpy1D (1).ipynb
│   └── python.ipynb
│
└── screenshots/
    ├── python/
    ├── numpy/
    ├── pandas/
    ├── web-data/
    └── text-analysis/
```

---

# Skills Developed

Through this revision journey, I have strengthened my understanding of:

### Python

- Programming fundamentals
- Variables
- Data types
- Operators
- Strings
- Collections
- Conditions
- Loops
- Functions
- OOP

### Data Handling

- File operations
- CSV handling
- DataFrames
- Data cleaning foundations
- Dataset loading
- Web data extraction

### Numerical Computing

- NumPy arrays
- 1D arrays
- 2D arrays
- Array operations

### Data Collection

- HTTP requests
- URLs
- Web resources
- HTML table extraction
- BeautifulSoup

### Data Science Foundations

- Exploratory data work
- Text analysis
- Structured datasets
- Data preprocessing concepts

---

# How to Run

## 1. Clone the repository

```bash
git clone https://github.com/CyberWol-12/DataScience_revision-_concepts_journey.git
```

## 2. Move into the project

```bash
cd DataScience_revision-_concepts_journey
```

## 3. Create a virtual environment

```bash
python -m venv venv
```

## 4. Activate the environment

### Windows

```bash
venv\Scripts\activate
```

### macOS / Linux

```bash
source venv/bin/activate
```

## 5. Install required libraries

```bash
pip install numpy pandas requests beautifulsoup4 lxml openpyxl jupyter
```

## 6. Start Jupyter Notebook

```bash
jupyter notebook
```

Open any notebook and run the cells sequentially.

---

# Learning Outcomes

This repository helped me move beyond simply learning Python syntax.

I focused on understanding how programming concepts connect to actual Data Science workflows.

For example:

```text
Python
  ↓
Data Structures
  ↓
NumPy
  ↓
Pandas
  ↓
Data Collection
  ↓
Data Processing
  ↓
Data Analysis
  ↓
Visualization
  ↓
Machine Learning
  ↓
AI
```

The goal of this repository is therefore not only to store notebooks, but to document the programming foundation behind my Data Science journey.

---

# Future Improvements

I plan to continue expanding this repository with:

- Advanced Pandas
- Advanced NumPy
- Data Cleaning
- Exploratory Data Analysis
- Matplotlib
- Seaborn
- Plotly
- SQL
- Statistics
- Machine Learning
- Deep Learning
- Natural Language Processing
- Recommendation Systems
- End-to-End Data Science Projects

The repository will continue evolving as my Data Science and AI skills grow.

---

# About Me

## Divya Upadhyay

B.Tech Computer Science Engineering student specializing in **Artificial Intelligence**, building a strong foundation in programming, Data Science and AI through hands-on projects and continuous practice.

My technical interests include:

- Data Science
- Data Analytics
- Machine Learning
- Deep Learning
- Natural Language Processing
- Recommendation Systems
- Artificial Intelligence
- Data Visualization
- Predictive Analytics
- SQL and Database Management

I enjoy working with data, finding patterns, building analytical solutions and gradually converting data into useful insights and intelligent systems.

---

# Current Technical Focus

```text
Python
SQL
Pandas
NumPy
Matplotlib
Seaborn
Plotly
Scikit-learn
TensorFlow
NLP
Deep Learning
Recommendation Systems
Data Visualization
Machine Learning
```

---

# Connect With Me

### GitHub

https://github.com/CyberWol-12

### LinkedIn

https://www.linkedin.com/in/divya-upadhyay-a77060348

### Email

divyau0802@gmail.com

---

# Conclusion

This repository represents my continuous effort to strengthen the fundamentals required for a career in **Data Science and Artificial Intelligence**.

From writing my first Python programs to working with NumPy, Pandas, files, web data and text analysis, each notebook represents a step in my learning journey.

I am continuing to build on these fundamentals through increasingly practical projects in:

**Data Science → Machine Learning → Deep Learning → NLP → AI**

---

## Learning by Building. Improving by Practicing. Growing with Data.

**Divya Upadhyay**