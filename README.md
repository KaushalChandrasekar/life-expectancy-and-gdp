**🌍 Life Expectancy & GDP Analysis**


Exploring the relationship between economic growth (GDP) and life expectancy across six countries (2000–2015).


**📖 Introduction**


How does a country’s wealth relate to the health of its people?

This project analyzes a dataset of life expectancy at birth and GDP for six diverse nations — Chile, China, Germany, Mexico, United States, and Zimbabwe — between 2000 and 2015.

We use data visualization, summary statistics, and correlation analysis to uncover patterns such as:


Have life expectancies improved consistently across countries?


How closely is GDP growth tied to life expectancy improvements?


Are there diminishing returns at higher income levels?


The analysis is fully reproducible in a Jupyter Notebook and a standalone Python script, making it ideal for portfolio demonstration and further extension.


**📊 Dataset**


File: all_data.csv

Variables:

Country – Name of the country

Year – Year (2000–2015)

Life expectancy at birth (years)

GDP – Gross Domestic Product (absolute USD)


*⚙️ Setup & Installation**


Clone the repo:

git clone https://github.com/KaushalChandrasekar/life-expectancy-and-gdp.git

cd life-expectancy-and-gdp


Create a virtual environment (optional but recommended):

python -m venv venv

source venv/bin/activate   # On Windows: venv\\Scripts\\activate


Install dependencies:

pip install -r requirements.txt


**▶️ Usage**

**Option 1:** Run the Jupyter Notebook

Open Life_Expectancy_GDP_EDA.ipynb and run all cells.
Figures will be saved to ./figures/ and summary outputs to ./outputs/.

**Option 2:** Run the Script
python analysis.py --data ./data/all_data.csv --outdir .


**📈 Example Outputs**


Some of the visualizations produced:

Life expectancy over time by country

GDP growth over time

Life expectancy vs. log10(GDP) with regression line (Preston curve)

Distribution (histogram, boxplot, violin plots)

Facet grids for country-specific comparisons


**✅ Conclusions**


**🔍 What We Did**

Scoped research questions on GDP–life expectancy links.

Explored all_data.csv (2000–2015) across six countries.

Cleaned data & derived helper variables (GDP in billions, log-GDP).

Visualized trends using diverse plots (lines, scatter+regression, histograms, boxplots, violins, facet grids).

Computed correlations & averages.

Packaged the process in both a Jupyter Notebook and a Python script.


**🧠 What We Learned**

Strong positive correlation overall (r ≈ 0.79) between life expectancy and log-GDP.

Country-level correlations >0.92, showing robust within-country links.

Zimbabwe’s recovery and China’s exceptional growth stood out.

High-income countries showed diminishing returns on life expectancy gains.


**📌 Key Takeaways**

GDP growth strongly supports health improvements at lower/mid income levels.

Country context (policies, crises, recovery) can reshape the curve.

Visualization variety helps reveal nuanced insights.

Reproducibility ensures transparent, updatable analysis.


**🚀 Next Steps**

Add population data for GDP per capita analysis.

Integrate other health/socio-economic indicators (e.g., healthcare spending).

Run hypothesis testing to confirm group differences.

Explore policy lessons from outliers (countries achieving more health per GDP).


**📜 License**

This project is released under the MIT License.
