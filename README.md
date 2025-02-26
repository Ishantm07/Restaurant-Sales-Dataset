📊 Restaurant Sales Data Analysis
📌 Project Overview
This project analyzes a restaurant's sales dataset to derive insights using Python and data visualization techniques. The goal is to clean, process, and visualize the data for better decision-making.

📂 Dataset
The dataset contains various sales-related attributes.
Unwanted columns are dropped, and column names are standardized.
Manager-related data is considered for further insights.
🛠️ Tools & Libraries Used
Python (Pandas, NumPy)
Data Visualization (Matplotlib, Seaborn)
Jupyter Notebook
🔍 Key Steps
Data Cleaning & Preparation
Removing unnecessary columns
Renaming and formatting column names
Exploratory Data Analysis (EDA)
Understanding sales trends
Identifying high-performing items/managers
Visualizing key metrics
Insights & Visualizations
Sales trends over time
Revenue distribution
Manager performance analysis
📈 Sample Code
python
Copy
Edit
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns

# Load Dataset
df = pd.read_excel("file.xlsx")

# Display basic details
print(df.shape)
df.head()
🚀 How to Use
Clone the repository
Install required dependencies:
bash
Copy
Edit
pip install numpy pandas seaborn matplotlib
