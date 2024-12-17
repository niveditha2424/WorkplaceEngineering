# Employee Attrition Prediction and Analysis

## Files Included

- `Workplace Engineering.ipynb`: Jupyter Notebook for data analysis and attrition prediction.
- `Workplace Engineering.html`: HTML file, which is a direct export of the Jupyter Notebook.

## Instructions to Replicate Results

1. Download `Workplace Engineering.ipynb`.

2. Open the notebook in Jupyter Notebook or Google Colab.

3. **Update File Paths**: Modify file paths in the notebook for:
   - `data_dictionary.xlsx`
   - `general_data.csv`
   - `employee_survey_data.csv`
   - `manager_survey_data.csv`
   - `in_time.csv`
   - `out_time.csv`

   Example:
   ```python
   import pandas as pd

   # Read data
   dd = pd.read_excel('path/to/data_dictionary.xlsx')
   gen = pd.read_csv('path/to/general_data.csv')
   es = pd.read_csv('path/to/employee_survey_data.csv')
   ms = pd.read_csv('path/to/manager_survey_data.csv')
   it = pd.read_csv('path/to/in_time.csv')
   ot = pd.read_csv('path/to/out_time.csv')
