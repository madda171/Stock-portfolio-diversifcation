# Stock-portfolio-diversifcation
📊 Project Overview
This project analyses stock market data from the Colombo Stock Exchange (CSE) to build an optimal diversified investment portfolio using clustering techniques. It combines:

K-Means Clustering: Groups companies based on risk-return and liquidity characteristics.

Hierarchical Clustering: Provides an alternative grouping structure to compare cluster stability.

Time Series Clustering: Groups companies based on their weekly return patterns, capturing behavioural similarity over time.

The final output helps investors select a diversified portfolio by choosing top-performing stocks from different clusters, reducing unsystematic risk.

🔧 Installation
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/portfolio-diversification-clustering.git
cd portfolio-diversification-clustering
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
(Ensure you have Python 3.8+ and libraries like pandas, numpy, matplotlib, scikit-learn, tslearn, and Streamlit for dashboard visualisation.)

🚀 Usage
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook w1911180_2021549.ipynb
Run each cell sequentially to:

Load and preprocess stock market data

Perform K-Means, Hierarchical, and Time Series clustering

Calculate Sharpe ratios for each company

Identify the best stocks for portfolio inclusion

Generate visualisations for investor insights

For the Streamlit dashboard, run:

bash
Copy
Edit
streamlit run dashboard.py
(If a separate dashboard script is included.)

📈 Key Methods
✔️ Data Preprocessing

Cleaning and feature engineering (annualised return, volatility, share volume, turnover)

✔️ K-Means & Hierarchical Clustering

Optimal cluster determination using elbow and silhouette methods

Cluster interpretation with financial insights

✔️ Time Series Clustering (DTW)

Weekly return patterns grouped using Dynamic Time Warping to identify similar behaviour stocks

✔️ Sharpe Ratio Calculation

Ranking stocks within each cluster to pick top-performing assets

✔️ Portfolio Diversification Strategy

Combining clustering methods to ensure stocks have different risk profiles and return behaviours.

📊 Results Summary
The project results include:

Cluster profiles detailing average risk, return, and liquidity metrics

Best stocks selected from each cluster to maximise return while minimising risk

Dashboard visualisations for intuitive investor decision-making

(Refer to the notebook’s conclusion and dashboard for detailed interpretations.)


