# Survey Feedback Analyzer

**Module End Assignment 4 – Python Fundamentals**

## 📌 Project Overview

The Survey Feedback Analyzer is a Python-based project that collects customer feedback, cleans text data, analyzes specific words, and generates useful insights from customer ratings and comments.

The project uses basic Python concepts such as dictionaries, lists, loops, functions, conditional statements, string methods, and sorting.

## 🎯 Objectives

- Store preloaded customer feedback data.
- Allow users to enter additional feedback.
- Clean feedback text by removing specified punctuation and extra spaces.
- Count feedback entries containing specific words.
- Calculate the average customer rating.
- Identify the longest feedback comment.
- Find all unique words used in the feedback.
- Sort feedback by rating from highest to lowest.

## 🛠️ Technologies Used

- **Programming Language:** Python 3
- **Environment:** Jupyter Notebook
- **Libraries:** Python Standard Library

## ⚙️ Features

### Step 1: Preloaded Feedback Data
The program initializes a dataset containing 10 customer feedback records, including serial numbers, names, comments, and ratings.

### Step 2: Add More Feedback
Users can enter additional customer names, feedback comments, and ratings. The program validates ratings to ensure they are between 1 and 5 and automatically generates serial numbers.

### Step 3: Text Cleaning
The program:
- Converts feedback text to lowercase.
- Removes specified punctuation marks.
- Replaces multiple spaces with a single space.
- Removes leading and trailing whitespace.

### Step 4: Word Count Insights
The program counts how many feedback entries contain each of the following words:
- `good`
- `poor`
- `excellent`

Each feedback entry is counted only once per target word.

### Step 5: Final Summary and Insights
The program displays:
- The final cleaned feedback dataset.
- The average customer rating.
- The longest feedback comment by word count.
- A sorted list of unique words.
- Feedback sorted by rating in descending order (optional).

## 🚀 How to Run the Project

1. Install Python 3 or open Google Colab.
2. Clone or download this repository.
3. Open the Python file or Jupyter Notebook.
4. Run the program from Step 1 through Step 5 in order.
5. Enter the number of additional feedback entries when prompted.
6. Provide the requested customer details and ratings.
7. View the generated analysis and summary.

## 📊 Sample Output

```text
========== WORD COUNT INSIGHTS ==========
Number of feedbacks containing 'good': 3
Number of feedbacks containing 'poor': 2
Number of feedbacks containing 'excellent': 1

========== LONGEST FEEDBACK ==========
Serial Number: 8
Name: Kiran
Feedback: poor response and poor handling of issue
Word Count: 7

========== UNIQUE WORDS ==========
['ambience', 'and', 'bad', 'better', 'but', 'care', 'could', 'excellent', 'experience', 'food', 'good', 'great', 'happy', 'handling', 'issue', 'not', 'okay', 'of', 'poor', 'quick', 'response', 'satisfied', 'service', 'staff', 'support', 'very', 'will', 'again', 'come']
```

*Note: Actual output depends on the additional feedback entered by the user. The sample word counts and summary are based on the original 10 records.*

## 📚 Python Concepts Demonstrated

- Variables and data types
- Lists and dictionaries
- Loops (`for` and `while`)
- Conditional statements (`if`, `else`)
- Functions and return values
- String manipulation
- Sets for unique values
- Exception handling
- `sum()`, `len()`, `sorted()`, and `zip()`
- Lambda expressions

## 🔮 Future Enhancements

- Export analyzed feedback to CSV or Excel.
- Generate charts showing customer
