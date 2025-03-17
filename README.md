📊 Sales Data Analysis
📌 Project Overview
This project analyzes sales data using Python & Excel, focusing on data cleaning, wrangling, and visualization. The goal was to extract key insights about product performance across different regions.

1️⃣ Tools & Libraries Used
🔧 Programming & Data Tools:
Python (VS Code) – Data wrangling, cleaning, and visualization
Excel – Additional data manipulation & formatting
📦 Python Libraries:
pandas – Data manipulation
numpy – Numerical operations
seaborn & matplotlib – Data visualization
os & io – File management
colorama – Terminal color formatting (optional, for readability)
2️⃣ Data Wrangling Process
A custom Python script was developed to automate preprocessing steps:

✔ Automated CSV File Detection – Finds the dataset without manually specifying file paths.
✔ Initial Data Overview – Loads as a pandas DataFrame and prints a colorized summary.
✔ Handling Duplicates – Detects and prompts the user to remove duplicate rows.
✔ Exploratory Data Analysis –

Generates a histogram to visualize column distributions.
Prompts the user to drop unnecessary columns interactively.
✔ Handling Missing Values – Provides three options:
Normalize
Drop
Fill with zero
✔ Final Cleanup & Export – Saves the cleaned dataset as wrangled_{fname}.csv.
3️⃣ Key Data Cleaning & Transformations
🟢 Dropped the ‘Employee’ Column – It didn’t seem relevant to product sales.
🟢 Fixed Data Types – Converted 'Amount' from an object to an integer.
🟢 Corrected Typos – Fixed a recurring typo (Sliky → Silky).
🟢 Grouped Data for Analysis – Aggregated data by Country, Product, and Amount.
🟢 Adjusted Date Format – Changed 'Date' to DD.MMM.YYYY for better readability.

4️⃣ Visualizations & Insights
📊 Experimented with Multiple Groupings:
✔ Some visualizations were useful, while others didn’t provide meaningful insights.
✔ Lesson Learned: Not all visualizations add value—choosing the right ones is key.

❌ Mistake: I didn’t screenshot my code while experimenting with visualizations.
🔹 Future Improvement: Better documentation to track what worked and what didn’t.

5️⃣ Final Analysis & Takeaways
Did not restore the ‘Employee’ column – It didn’t add value to the final analysis.
Would appreciate feedback – Was dropping this column a mistake for the data story?
🔹 Future Improvements
💡 Next Steps:
✅ Capture screenshots of analysis steps for better documentation.
✅ Experiment with interactive visualizations (e.g., Plotly, Streamlit).
✅ Improve README structure for clarity and engagement.

### 📂 Project Structure

Chocolate-Company-Sales-Data/
│
├── datasets/
│   ├── chocolate_sales.csv
│   └── wrangled_chocolate_sales.csv
│
├── reports/
│   ├── Process Overview.pdf
│   └── Sales Performance Analysis.pdf
│
├── scripts/
│   ├── data_wrangler.py
│   └── data_wrangler_README.txt
│
├── requirements.txt
└── README.md

📄 Full Analysis Report
You can download the analysis documents here:
🔗 [Process Overview PDF](reports/Process%20Overview.pdf)
🔗 [Sales Performance Analysis PDF](reports/Sales%20Performance%20Analysis.pdf)

🚀 How to Use This Project
1️⃣ Clone the repository
git clone https://github.com/Gundesaelf/Chocolate-Company-Sales-Data.git

2️⃣ Install dependencies
pip install -r requirements.txt

3️⃣ Run the wrangler in Jupyter Notebook or Python
python scripts/data_wrangler.py

🔗 Connect with Me
https://www.linkedin.com/in/chris-gundes
