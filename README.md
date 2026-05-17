# 🎫 Customer Support Ticket Analyzer
Customer support teams handle numerous service tickets daily. Analysing support tickets helps identify common issues, customer sentiment, support quality, and areas for improvement. Build a Python-based Ticket Analysis System that stores, cleans, analyses, and extracts insights from customer support tickets.


## 📌 Project Overview

The **Customer Support Ticket Analyzer** is a Python-based mini project developed to manage, clean, and analyze customer support tickets efficiently.
The system stores ticket details such as:

* Ticket Number
* Customer Name
* Issue Description
* Priority Level

The project demonstrates the use of:

* Python dictionaries & lists
* Loops and conditional statements
* Functions
* String manipulation
* Text cleaning
* Keyword analysis
* Data insights generation

---

# 🎯 Project Objectives

* Store and manage customer support tickets
* Add new support tickets dynamically
* Clean and standardize issue descriptions
* Perform keyword-based issue analysis
* Generate ticket analytics and insights
* Identify service quality trends

---

# 🛠️ Technologies Used

* Python
* String Processing
* Dictionary of Lists Data Structure

---

# 📂 Dataset Structure

The project begins with **10 preloaded customer tickets** stored using a dictionary of lists.

## Ticket Fields

| Field Name        | Description            |
| ----------------- | ---------------------- |
| Ticket_No         | Unique ticket ID       |
| Customer_Name     | Customer name          |
| Issue_Description | Customer issue details |
| Priority          | Ticket priority level  |

---

# 🚀 Project Workflow

## Step 1️⃣ Preloaded Tickets

The program starts with predefined customer support tickets.

### Features

* Stores ticket details in dictionary format
* Displays ticket data in readable format

```python id="l5g31f"
ticket_data = {
    'Ticket_No': [1,2,3,4,5,6,7,8,9,10]
}
```

---

# ➕ Step 2️⃣ Add More Tickets

Users can dynamically add new support tickets.

## User Inputs

* Customer Name
* Issue Description
* Priority (High / Medium / Low)

## Features

✅ Auto-increment ticket numbers
✅ Priority validation
✅ Append new ticket data dynamically

### Validation Logic

```python id="o8k4jx"
if priority in ["High", "Medium", "Low"]:
```

---

# 🧹 Step 3️⃣ Text Cleaning

The issue descriptions were cleaned and standardized for better analysis.

## Cleaning Operations Performed

* Removed punctuation (`.,!?-`)
* Converted text to lowercase
* Removed extra spaces
* Removed leading/trailing spaces
* Replaced slang words (`ok → okay`)

### Example

Before Cleaning:

```text id="o0c8df"
" Internet not working!!! "
```

After Cleaning:

```text id="tq5jwd"
"internet not working"
```

---

# 🔍 Step 4️⃣ Keyword-Based Issue Insights

A function was created to count issue descriptions containing specific keywords.

## Function Used

```python id="u5o9vz"
def count_tickets_with_word(word):
```

## Features

✅ Case-insensitive search
✅ Keyword occurrence analysis

## Keywords Analyzed

* poor
* good
* slow
* excellent

---

# 📊 Step 5️⃣ Final Summary & Insights

The program generates detailed ticket analytics and summaries.

---

# 📈 Priority Analysis

The system calculates:

* Number of High-priority tickets
* Number of Medium-priority tickets
* Number of Low-priority tickets

### Insights

* High-priority tickets require immediate attention
* Medium and Low priority tickets help schedule support workload efficiently

---

# 📝 Longest Issue Description Analysis

The program identifies the ticket with:

* Longest issue description
* Highest word count

### Displays

* Ticket Number
* Customer Name
* Cleaned Issue Description
* Word Count

### Purpose

Helps identify:

* Complex customer issues
* Detailed complaints requiring deeper analysis

---

# 🔤 Unique Word Extraction

The program extracts all unique words from issue descriptions.

## Outputs

* Total count of unique words
* Sorted unique word list

### Benefits

* Vocabulary analysis
* Frequently used complaint terms
* Service trend identification

---

# 📌 Key Findings

✅ High-priority tickets need immediate attention
✅ “Slow” and “Poor” are common complaint keywords
✅ Positive words like “Good” and “Excellent” indicate successful support cases
✅ Text cleaning improves data quality and consistency
✅ Unique word extraction helps identify customer service trends

---

# 📖 Learning Outcomes

Through this project, I learned:

* Python dictionary operations
* Data cleaning and preprocessing
* String manipulation techniques
* Looping and conditional logic
* Function creation
* Keyword analysis
* Data analytics using Python

---

# 🧠 Skills Demonstrated

* Python Programming
* Text Processing
* Data Cleaning
* Data Analysis
* Problem Solving
* Logical Programming

---

# 📌 Conclusion

The **Customer Support Ticket Analyzer** successfully demonstrates Python-based ticket management and text analysis.
The project provides insights into customer complaints, service quality, and support priorities through text cleaning, keyword analysis, and ticket analytics.

It is a practical demonstration of Python skills in:

* Data handling
* Text processing
* Functions
* Loops
* Data analysis
