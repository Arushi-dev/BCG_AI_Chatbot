

# Financial Data Analysis and Simple Chatbot  

This project demonstrates how to work with financial data using **Python** and **Pandas**, and includes a simple chatbot that provides insights based on predefined queries. The data used here is financial data extracted from corporate 10-K filings.

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
  - [Data Loading and Analysis](#data-loading-and-analysis)
  - [Chatbot Interaction](#chatbot-interaction)
- [Sample Output](#sample-output)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project covers:
1. Loading and analyzing financial data from a CSV file using Pandas.
2. A simple chatbot implementation to provide predefined responses for specific financial queries.

The sample dataset includes financial data for companies like Microsoft and Tesla.

## Technologies Used
- Python 3.9+
- Pandas (for data manipulation and analysis)

## Setup and Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Arushi-dev/financial-data-chatbot.git
   cd financial-data-chatbot
   ```
2. **Install dependencies:**
   Ensure you have Python installed and set up a virtual environment (optional).
   ```bash
   pip install pandas
   ```

3. **Add the CSV file:**
   Place the financial dataset (`10-k fillings BCG.csv`) in the appropriate directory as mentioned in the script.

## Usage

### Data Loading and Analysis
The script loads financial data from a CSV file, processes it, and displays key financial metrics like revenue, net income, assets, liabilities, and cash flow from operating activities.

**Steps:**
1. Open the file `main_script.py` (or equivalent name).
2. Modify the `file_path` variable to point to your CSV file location.
3. Run the script to view the processed data:
   ```bash
   python main_script.py
   ```

### Chatbot Interaction
The chatbot provides answers to predefined queries about the financial data:
- Total revenue
- Net income changes
- Total assets
- Cash flow from operating activities

**Example queries:**
```python
simple_chatbot("What is the total revenue?")
simple_chatbot("How has net income changed over the last year?")
```

## Sample Output
Here’s an example of the chatbot’s output:
```
The total revenue is $211,915 million.
The net income has decreased by 1% over the last year.
The total assets amount to $411,976 million.
The cash flow from operating activities is $87,582 million.
```
If the chatbot receives a query it doesn't understand:
```
Sorry, I can only provide information on predefined queries.
```

### To Do
- Expand the chatbot’s capabilities to handle dynamic queries.
- Add data visualizations for financial trends.
