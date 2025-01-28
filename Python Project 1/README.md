# A/B Testing Analysis with Python and Tableau

## Project Overview
This project demonstrates the analysis of A/B testing results using Python for data preparation and statistical testing, and Tableau for visualization. The goal is to assess the significance of changes introduced in the test groups and evaluate their impact on key business metrics.

## Tools and Technologies
- **Python**: Pandas, NumPy, SciPy
- **Google Colab**: For code execution and collaboration
- **Tableau**: For interactive visualization
- **Google Sheets**: For sharing data

## Key Steps in the Analysis
1. **Data Preparation**:
   - Events and sessions data were grouped by test, device, and channel.
   - Conversion rates (CTR) were calculated for test and control groups.
   
2. **Statistical Testing**:
   - Performed z-tests to evaluate the statistical significance of differences in CTR between test and control groups.
   - Calculated metrics such as p-value and z-statistics.

3. **Visualization**:
   - Created Tableau dashboards to showcase dynamic insights and trends.

## Statistical Tests and Metrics
- Conversion metrics (e.g., `add_payment_info_per_session`, `begin_checkout_per_session`) were derived as ratios of specific events to sessions.
- Z-tests were conducted to compare test and control groups, evaluating the significance at a threshold of `p-value < 0.05`.

## Outputs and Visualizations
- Tableau Dashboard: [View on Tableau Public](https://public.tableau.com/app/profile/pikhulia.victoriia/viz/Test_17373178112810/CTRsignificance)
- Data for Visualization:
  - [Main Dataset](https://docs.google.com/spreadsheets/d/17lsMDF4udfYeAxC6IQeB0ihF7ikTPZ5Y/edit?usp=sharing)
  - [Additional Metrics for Tableau](https://docs.google.com/spreadsheets/d/1OyySs4K5nKuv1Sm7Czx62W2i0iyYGftJ/edit?usp=sharing)

## Repository Structure
- `Portfolio_Project_1.ipynb`: Main notebook containing data processing, statistical tests, and insights.
- `Portfolio_Project_1.py`: Python script version of the notebook.
- `results.pdf`: PDF report summarizing key results and findings.
- `images/`: Screenshots of Tableau dashboards and visualizations.

## Key Insights
- Differences in conversion rates between test and control groups were evaluated using statistical tests.
- Tableau dashboards highlight trends and patterns, enabling further business analysis.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/lvik7188/A-B-Test
