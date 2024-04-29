
# Participatory Budget Allocation Algorithm

## Overview
This project implements a participatory budget allocation algorithm in Python. The algorithm aims to distribute budgets among participants based on their predicted importance scores, ensuring fairness and efficiency in resource allocation. The project includes functionalities for simulating budget allocations, visualizing allocation patterns, and handling input data from a CSV file.

## Requirements
- Python 3.x
- matplotlib library (for visualization)

## Setup
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/your_username/participatory-budget-allocation.git
   ```

2. Navigate to the project directory:
   ```
   cd participatory-budget-allocation
   ```

3. Install the required dependencies:
   ```
   pip install matplotlib
   ```

## Usage
1. Ensure that the `budget.csv` file containing budget data is located in the project directory.

2. Run the Python script `PBAA.py` to execute the participatory budget allocation algorithm:
   ```
   python PBAA.py
   ```

3. The script will read the budget data from the `budget.csv` file, simulate budget allocations for different scenarios, and visualize the allocation patterns using bar charts and line plots.

4. Review the generated visualizations to analyze how budgets are allocated across different sectors and budget amounts.

## Input Data Format
The `budget.csv` file should contain budget data in the following format:
```
budget
10000
20000
30000
...
```
Each row represents a budget amount to be allocated.

## Output
The script generates visualizations of budget allocations, including bar charts illustrating allocations for different budgets and sectors, as well as line plots showing allocation trends across different sectors as the total budget varies.
