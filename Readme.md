🏏 IPL Big Data Analysis (2008–2024)

📌 Project Overview

This project focuses on analyzing Indian Premier League (IPL) data from 2008 to 2024 using Python and Dask.

The main objective of this project is to perform large-scale data analysis and demonstrate how big data tools like Dask can handle large datasets efficiently compared to traditional tools like Pandas.

The analysis includes player performance, team statistics, match insights, and scalability comparison.


🚀 Technologies Used

- Python 
- Pandas
- Dask (for big data processing)
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook


📂 Dataset

The dataset used in this project contains:
- `matches.csv` → match-level data
- `deliveries.csv` → ball-by-ball data

📥 Dataset Source:
https://www.kaggle.com/code/mahipalkumarsingh/ipl-complete-data-analysis-2008-to-2024

👉 Place both files inside: data/

📊 Key Features of the Project

This project includes:
- Data loading using **Dask and Pandas**
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Visualization of insights
- Performance comparison (Dask vs Pandas)
- Big Data scalability demonstration


🔍 Insights Generated

🏏 Top Run Scorers
- Identified top 15 batsmen with highest runs in IPL history
- Shows consistency and dominance of players


🎯 Top Wicket Takers
- Analysis of leading bowlers based on wickets taken
- Excludes run-outs for accurate results


🏆 Team Performance
- Teams ranked based on total wins
- Helps identify most successful IPL teams


🎲 Toss Impact Analysis
- Checked whether winning toss increases chances of winning match
- Result shows only a small advantage


 📈 Season-wise Trends
- Total runs scored per IPL season
- Shows growth of aggressive batting over time


⚡ Strike Rate Analysis
- Top players based on strike rate (min 500 balls faced)
- Highlights power hitters


🏟️ Venue Analysis
- Most frequently used IPL stadiums
- Helps understand match distribution


💥 Boundary Analysis
- Comparison of number of 4s and 6s per season
- Shows increase in attacking gameplay


⚡ Dask vs Pandas (Scalability)

This project demonstrates:
- Dask uses **lazy evaluation**
- Pandas loads full data into memory
- Dask performs better for large datasets

👉 Benchmark includes:
- Groupby operations  
- Filtering operations  

📦 Installation

Option 1 (Recommended)
pip install -r requirements.txt

Option 2 (Manual)
pip install dask[dataframe] pandas matplotlib seaborn kaggle

▶️ How to Run the Project
Clone the repository:
git clone https://github.com/Loner8118/IPL-Analysis
Navigate to project folder:
cd IPL-Analysis

Install dependencies:
pip install -r requirements.txt

Open Jupyter Notebook:
jupyter notebook
Run all cells

📁 Project Structure
IPL-Analysis/
│
├── data/
│   ├── deliveries.csv
│   ├── matches.csv
│
├── notebook/
│   └── Analysis.ipynb
│
├── images/
│   ├── charts and graphs
│
├── requirements.txt
├── README.md

📌 Key Learning Outcomes
Learned how to use Dask for big data analysis
Understood difference between lazy and eager execution
Improved data visualization skills
Gained experience in handling real-world datasets
Learned how to structure a complete data project

🚀 Future Improvements
Add machine learning model for match prediction
Build interactive dashboard (Power BI / Tableau)
Deploy project using Flask

👨‍💻 Author
Tanish Akre

⭐ Final Note
This project demonstrates how big data tools like Dask can scale data analysis efficiently and provide meaningful insights from large datasets like IPL.
