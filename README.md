# Customer Support Ticket Analyzer

## Project Overview

The Customer Support Ticket Analyzer is a Python-based project designed to store, clean, and analyze customer support tickets.

The project helps identify common customer issues, analyze ticket priorities, and extract useful insights from customer support data.

## Objectives

- Store customer support ticket data using Python dictionaries and lists.
- Add new tickets dynamically.
- Clean and standardize issue descriptions.
- Analyze ticket descriptions using keyword-based searches.
- Identify ticket priorities and find the longest issue description.
- Extract unique words from all issue descriptions.

## Technologies Used

- Python
- Jupyter Notebook
- Google Colab (optional)

## Dataset Description

The project uses a dictionary of lists containing customer support ticket information.

### Data Columns

| Column Name | Description |
|---|---|
| Ticket_No | Unique ticket identification number |
| Customer_Name | Name of the customer |
| Issue_Description | Customer's support issue |
| Priority | Priority level of the ticket |

## Project Workflow

### Step 1: Preloaded Tickets

- Created a dictionary of lists containing 10 customer support tickets.
- Stored ticket numbers, customer names, issue descriptions, and priority levels.
- Printed the initial ticket data in a readable format.

### Step 2: Add More Tickets

- Asked the user how many new tickets to add.
- Collected customer name, issue description, and priority for each ticket.
- Validated priority values (High, Medium, Low).
- Automatically incremented ticket numbers starting from 11.
- Appended the new ticket information to the existing dictionary.

### Step 3: Text Cleaning

Cleaned all issue descriptions using Python string methods.

The cleaning process included:

- Removing punctuation.
- Converting text to lowercase.
- Removing extra spaces.
- Removing leading and trailing spaces.
- Replacing common slang and shorthand with standard words.

### Step 4: Keyword-Based Issue Insights

Created a function called `count_tickets_with_word(word)` to count the number of ticket descriptions containing a given keyword.

The function performs case-insensitive searches.

Keywords analyzed:
- Poor
- Good
- Slow
- Excellent

### Step 5: Final Summary and Insights

Performed the following analysis:

1. Displayed the final cleaned ticket data.
2. Calculated the number of High, Medium, and Low priority tickets.
3. Identified the ticket with the longest issue description based on word count.
4. Extracted all unique words from the issue descriptions.
5. Displayed the number of unique words and the sorted word list.

## Key Findings

### Keyword Analysis

| Keyword | Number of Tickets |
|---|---:|
| Poor | 3 |
| Good | 2 |
| Slow | 1 |
| Excellent | 1 |

### Priority Analysis

| Priority | Number of Tickets |
|---|---:|
| High | 5 |
| Medium | 4 |
| Low | 3 |

### Longest Issue Description

- Ticket Number: 6
- Customer Name: Divya
- Cleaned Issue: good support and good behaviour
- Word Count: 5

### Unique Words

- Total unique words: 32
- Unique words were extracted and displayed in sorted order.

## Python Concepts Practiced

- Variables and data types
- Lists and dictionaries
- Loops
- Conditional statements
- User input and validation
- Functions
- String methods
- Sets
- List comprehension
- Data cleaning
- Basic text analysis

## How to Run the Project

1. Open the project notebook in Jupyter Notebook or Google Colab.
2. Run the cells in order, starting from Step 1.
3. Enter the required information when prompted in Step 2.
4. Run the text cleaning and keyword analysis steps.
5. Run the final summary and insights section to view the results.

## Project Deliverables

- Python Jupyter Notebook containing all assignment steps.
- Cleaned customer support ticket data.
- Keyword-based analysis and priority insights.
- One-page summary report.

## Conclusion

This project demonstrates how Python can be used to organize, clean, and analyze customer support ticket data.

By applying lists, dictionaries, functions, loops, and string manipulation techniques, the project extracts useful information about customer issues and ticket priorities.

The analysis provides a foundation for understanding support ticket trends and improving customer service operations.

## Author

**Hemarubini**

**Project:** Customer Support Ticket Analyzer

**Domain:** Python Data Analysis
