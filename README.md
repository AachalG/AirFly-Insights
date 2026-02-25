✈️ AirFly Insights
Flight Delay & Operational Performance Analysis








📌 Project Overview

AirFly Insights is a data analytics project focused on analyzing U.S. flight operational data to uncover patterns in:

✈️ Arrival & departure delays

🛫 Airline performance

🕒 Time-based delay trends

🗺️ Route-level insights

The objective is to transform raw flight records into actionable operational insights using data cleaning, feature engineering, and exploratory data analysis (EDA).

📊 Dataset Summary
Feature	Value
Original Dataset Size	~3 Million Records
Sample Used	100,000 Rows
Columns	32+
Source	U.S. DOT Flight Records
Storage Strategy	Raw data excluded from GitHub (size constraints)

⚠️ Raw datasets are excluded from this repository using .gitignore due to GitHub file size limits.

🛠️ Tech Stack

Python 3.13

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook

Git & GitHub

📂 Project Architecture
AirFly-Insights/
│
├── data/
│   ├── raw/              # Ignored large raw datasets
│   └── processed/        # Cleaned dataset output
│
├── notebooks/
│   └── Milestone1_DataFoundation.ipynb
│
├── visuals/              # Saved charts & analysis visuals
│
├── requirements.txt
└── README.md
🚀 Milestone 1 – Data Foundation
✔ Data Handling

Efficient loading using row limitation (100k rows)

Memory-aware dataset handling

Data structure inspection (info(), describe())

✔ Data Cleaning

Missing value analysis

Data type validation

Structured dataset preparation

✔ Feature Engineering

Created ROUTE feature (ORIGIN → DEST)

Extracted DEPARTURE_HOUR

Prepared dataset for advanced analytics

✔ Export

Generated cleaned dataset in data/processed/

📈 Key Analytical Insights
1️⃣ Delay Trend by Departure Hour

Early morning flights show relatively lower delays.

Midday peaks indicate higher congestion impact.

Evening delays rise gradually due to accumulated schedule shifts.

2️⃣ Airline Operational Volume

Identified top airlines by total flights.

Compared carrier-level operational patterns.

📊 Sample Visualization

(You may optionally add a screenshot image here later)

🧠 Technical Learnings

Handling large datasets efficiently

Git large file management

Version control best practices

Data cleaning & feature engineering

EDA workflow design

Git history rewriting & repository optimization

⚙️ How to Run
1️⃣ Clone the repository
git clone https://github.com/AachalG/AirFly-Insights.git
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Launch notebook
jupyter notebook

Run:
Milestone1_DataFoundation.ipynb

🔮 Future Enhancements

📉 Delay prediction model (Machine Learning)

📊 Cancellation rate modeling

🗺️ Route clustering analysis

🌐 Interactive dashboard (Streamlit / Power BI)

⚡ Performance optimization for full 3M dataset

👩‍💻 Author

Aachal G
Data Analytics Internship Project
GitHub: https://github.com/AachalG