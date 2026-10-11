# Market-analysis-internship
# Market Research & Consumer Insights Project

A beginner-friendly, GitHub-ready market research portfolio project that explores consumer preferences, shopping behaviour, price sensitivity, satisfaction, and repurchase intent using Python.

> **Data transparency:** The included dataset is synthetic and generated for demonstration. It does not represent real customers, a real company, or a completed internship. Treat findings as practice examples—not as evidence of actual market conditions.

## Project goals

This project demonstrates a practical market research workflow:

1. Load and inspect survey data.
2. Clean and validate fields.
3. Summarise respondent profiles and shopping behaviour.
4. Visualise product preferences, discovery channels, satisfaction, and repurchase intent.
5. Export charts and a concise findings report.
6. Translate descriptive results into cautious, testable business recommendations.

## Research questions

- Which product categories are most frequently preferred in this sample?
- Which channels do respondents usually use to purchase products?
- How do respondents discover products?
- How price-sensitive are respondents?
- How satisfied are respondents, and how likely are they to repurchase?
- What is the distribution of estimated spend across categories?

## Tech stack

- **Python 3.10+**
- **Pandas** for data preparation and analysis
- **Matplotlib** for charts
- **CSV** as the data format

## Repository structure

```text
market-analysis-internship/
├── data/
│   └── market_survey_synthetic.csv
├── outputs/
│   ├── charts/                 # Created when the script runs
│   └── findings_report.md      # Created when the script runs
├── src/
│   └── analyze_market.py
├── .gitignore
├── requirements.txt
└── README.md
```

## Quick start

### 1. Clone your repository

After you create a repository on GitHub, replace `YOUR-USERNAME` with your GitHub username:

```bash
git clone https://github.com/YOUR-USERNAME/market-analysis-internship.git
cd market-analysis-internship
```

Or download this project ZIP and extract it locally.

### 2. Create a virtual environment (recommended)

**Windows PowerShell:**

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
```

**macOS/Linux:**

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the analysis

From the project root:

```bash
python src/analyze_market.py
```

The script will create:

- `outputs/charts/category_preferences.png`
- `outputs/charts/purchase_channels.png`
- `outputs/charts/product_discovery.png`
- `outputs/charts/satisfaction_levels.png`
- `outputs/charts/repurchase_intent.png`
- `outputs/charts/average_spend_by_category.png`
- `outputs/findings_report.md`

## Dataset dictionary

The file `data/market_survey_synthetic.csv` contains 150 synthetic survey responses.

| Column | Meaning |
|---|---|
| `respondent_id` | Anonymous synthetic respondent ID |
| `age_group` | Age band |
| `gender` | Self-described gender response option |
| `region` | Broad fictional sample region |
| `preferred_category` | Preferred product category |
| `purchase_frequency` | Reported purchase frequency |
| `usual_purchase_channel` | Usual purchase channel |
| `price_sensitivity` | Self-reported sensitivity to price |
| `satisfaction` | Satisfaction response |
| `estimated_spend_inr` | Synthetic estimated spend in INR |
| `product_discovery_channel` | Channel where products are discovered |
| `repurchase_intent` | Stated intention to purchase again |

## Methodology

- The dataset is created programmatically and is **not real survey research**.
- The script uses descriptive statistics and simple counts/averages.
- Charts are saved as PNG files for use in a portfolio or presentation.
- Recommendations are framed as hypotheses that would need validation with a real, appropriately sampled survey.

## How to interpret the results responsibly

A sample of 150 synthetic rows cannot establish real market demand, causation, or representative consumer behaviour. For genuine research, define a target population, use a transparent sampling method, obtain informed consent where appropriate, avoid collecting unnecessary personal data, and document limitations.

## Possible improvements

- [ ] Replace the demo data with a properly collected and anonymised survey dataset.
- [ ] Add cross-tabulations by age group, region, or product category.
- [ ] Add confidence intervals and statistical tests where appropriate.
- [ ] Build an interactive dashboard in Power BI or Streamlit.
- [ ] Add a Jupyter Notebook explaining each analysis step.
- [ ] Add a short PDF presentation with findings and limitations.

## Skills demonstrated

**Market research · Data cleaning · Exploratory data analysis · Consumer behaviour · Data visualisation · Business communication · Python**

## Author

**YOUR NAME**

- GitHub: `https://github.com/YOUR-USERNAME`

Update this section with your own details. Do not describe this practice project as a real internship or client engagement unless that is accurate.

---

If this project helps you practise market research, feel free to fork it, adapt it, and explain your own analysis in your portfolio.
