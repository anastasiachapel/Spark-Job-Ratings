# Spark Job Ratings

## 📌 Project Description
This project consists of two Jupyter Notebooks that analyze and derive insights from IT job ratings. The analysis is conducted in two steps:

1. **Step 1 - Data Processing (`IT Job Ratings - Step 1 - BRZ to SLVR.ipynb`)**  
   - ## Setting Global Config
   - **Total Code Cells:** 19
   - **Total Markdown Cells:** 4

2. **Step 2 - Data Insights (`IT Job Ratings - Step 2 - Insights.ipynb`)**  
   - ## Setting Global Config
   - **Total Code Cells:** 22
   - **Total Markdown Cells:** 8

## 🛠️ Technologies Used
- Python
- Jupyter Notebook
- Pandas, NumPy (for data manipulation)
- Matplotlib, Seaborn (for visualization)

## 📂 Files in This Repository
- **`IT Job Ratings - Step 1 - BRZ to SLVR.ipynb`** - Data processing notebook.
- **`IT Job Ratings - Step 2 - Insights.ipynb`** - Insights and analysis notebook.
- **`it_job_ratings.csv`** - Raw data for analysis.
- **`requirements.txt`** - List of dependencies.

## 🚀 How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/IT-Job-Ratings-Analysis.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open and run the notebooks in Jupyter:
   ```bash
   jupyter notebook "IT Job Ratings - Step 1 - BRZ to SLVR.ipynb"
   jupyter notebook "IT Job Ratings - Step 2 - Insights.ipynb"
   ```

## 📊 Key Libraries Used
```python
from pyspark.sql.functions import regexp_replace, col
from pyspark.sql.session import SparkSession
from pyspark.sql.functions import *
from pyspark.sql import functions as F
import numpy as np
import pandas as pd
from functools import reduce
import os
import pandas as pd
import os
from pyspark.sql.session import SparkSession
import numpy as np
```

## 🏗️ Future Improvements
- Improve data visualization and reporting.
- Add machine learning predictions for job trends.
- Automate data collection and transformation.

## 📩 Contact
If you have any questions or suggestions, feel free to reach out!

---
