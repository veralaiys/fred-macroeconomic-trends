# Analysis of US Macroeconomic Indicators
### Executive Summary
This project analyses key economic health indicators, specifically **Unemployment Rates** and **Labour Force Participation**, using the **FRED API**. I developed this to bridge the gap between theoretical economic models and real-world data visualisation.

### 🚀 Key Features
*  **Automated Data Retrieval:** Connected to the St. Louis Fed's (FRED) database to pull live, time-series economic data
*  **Data Cleaning & Wrangling:** Used **Pandas** to handle missing values and align different time frequencies
*  **Macroeconomic Visualisation:** Created interactive charts to identify trends during major economic shifts (e.g. the 2008 Financial Crisis and 2020)

### 🛠️ Tech Stack
*  **Language:** Python
*  **Environment:** VS Code
*  **Libraries:** `pandas`, `matplotlib`, `fredapi`
*  **Version Control:** Git/GitHub

### 📊 Insights & Findings
*  **Correlation:** Observed a lag in labour force recovery relative to unemployment
*  **Trend Analysis:** While unemployment recovered briskly after April-May 2020, participation plummeted and has remained persistently below pre-pandemic levels.

### ⚙️ Local Setup (VSCode)
1. **Clone the Repo:** `git clone` https://github.com/veralaiys/fred-macroeconomic-trends.git
2. **Environment Secrets:** Create a `.env` file in the root directory and add your API key: `FRED_API_KEY=your_key_here`
3. **Install Dependencies:** Run `pip install -r requirements.txt` in the VS Code terminal
4. **Run:** Open the `.ipynb` file in VS Code and select your Python kernel to run the cells
