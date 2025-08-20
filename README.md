⚽ Hypothesis Testing with FIFA World Cup Data
📌 Project Overview

This project investigates whether women’s FIFA World Cup matches have more goals scored on average compared to men’s. Using statistical hypothesis testing, we analyze official match data since 2002 to test this claim.

📂 Dataset

men_results.csv – Men’s international matches (since the 19th century)

women_results.csv – Women’s international matches (since the 20th century)

Filtered to FIFA World Cup matches (2002–present)

🛠️ Tools & Libraries

Python (pandas, matplotlib, scipy, pingouin)

Mann-Whitney U Test for comparing distributions

Data visualization for goal-scoring trends

📊 Methodology

Load and clean men’s & women’s datasets

Filter matches: only FIFA World Cup since 2002

Calculate total goals per match

Perform Mann-Whitney U test (α = 0.10)

Interpret p-value and draw conclusion

📈 Results

Null Hypothesis (H0): Mean goals in women’s matches = men’s

Alternative (HA): Women’s matches have more goals

Statistical results indicate whether we reject or fail to reject H0.

🚀 Key Learnings

Hands-on practice with hypothesis testing in sports analytics

Real-world use of Python libraries for statistical analysis

Practical demonstration of non-parametric testing methods

📑 How to Run
# Clone the repo
git clone https://github.com/yourusername/soccer-hypothesis-testing.git

# Install dependencies
pip install -r requirements.txt

# Run the analysis
python analysis.py
