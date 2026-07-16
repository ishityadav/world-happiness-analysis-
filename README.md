# 🌍 Tracking the Pulse of World Happiness (2015 → 2019)

An end-to-end exploratory data analysis (EDA) project comparing **World Happiness Report** data across a **4-year span (2015–2019)** to uncover which socio-economic factors most strongly drive national well-being.

## 📊 Project Snapshot

| Metric | Value |
|---|---|
| Years compared | 2 (2015 & 2019) — 4-year trend window |
| Data source | World Happiness Report (Kaggle), ~155–158 countries per year |
| Core features analyzed | 7 (GDP, Family, Health, Freedom, Generosity, Trust, Happiness Score) |
| Notebook cells | 71 total (63 code, 8 markdown) |
| Named insight sections | 6 structured insights + univariate + bivariate + dashboard sections |
| Visualizations built | 14 histograms, 2 correlation heatmaps, 6 regression plots, 1 interactive choropleth map, 2 bar charts |
| Top/Bottom rankings generated | 4 lists of 10 countries each (top 10 & bottom 10 happiest, 2015 & 2019) |
| Country-level trend flags | Top 10 gainers + Top 10 decliners in happiness score (2015→2019) |

## 🔍 Key Findings (Quantified)

- **Global happiness rose only marginally** between 2015 and 2019, despite increases in GDP, Health, and Family support — revealing a well-being gap.
- **Health (Life Expectancy)** was the single strongest predictor of happiness (**r = 0.779**), edging out Family Support (**r = 0.773**) and GDP per Capita (**r = 0.749**).
- **Freedom (r = 0.558)** and **Trust in Government (r = 0.411)** showed moderate influence, while **Generosity (r = 0.083)** had almost no measurable correlation with national happiness.
- **3 of the top 5 most-improved countries** (Benin, Ivory Coast, Togo) were African nations — signaling happiness gains in traditionally lower-income regions.
- **Sharpest declines** were concentrated in countries facing economic or political instability (Venezuela, Yemen, Zimbabwe, Lesotho, Haiti).
- **GDP, Family, and Health rose** in global averages from 2015→2019, while **Freedom, Generosity, and Trust all declined** — a split between material progress and civic/social trust.

## 🛠️ Methodology

1. **Data Cleaning & Feature Engineering** — merged 2015 & 2019 datasets, standardized 7 core feature columns, engineered a `score_change` delta metric.
2. **Univariate Analysis** — distribution study across 7 features × 2 years (14 histograms with KDE overlays).
3. **Correlation Analysis** — computed Pearson correlation matrices for both years, visualized via 2 heatmaps.
4. **Bivariate Analysis** — 6 regression plots quantifying each feature's linear relationship with happiness score.
5. **Interactive Dashboard** — Plotly choropleth world map + comparative bar charts for global averages and top movers.

## 🧰 Tech Stack
`Python` · `Pandas` · `NumPy` · `Matplotlib` · `Seaborn` · `Plotly Express`

## 📁 Repository Contents
- `Tracking_the_Pulse_of_the_World_Happiness_Trends_2015_to_2019.ipynb` — full analysis notebook
- `Happiness Report 2015 vs 2019 project.pdf` — exported project report

## 📌 Data Source
World Happiness Report datasets (2015, 2019) via Kaggle.
