# Firm Value Diagnostic Scorecard

An interactive web tool for tourism-related firms listed on the Philippine Stock Exchange (PSE). It compares a firm with the 12 listed tourism-related firms studied from 2018 to 2024 on three checks that follow the significant results of the study:

1. **Asset efficiency (ROA)**: return on assets had a positive and significant effect on price-to-book value.
2. **Firm size (total assets)**: firm size strengthened the link between profitability and price-to-book value in most tests.
3. **Debt level (debt-to-equity ratio)**: higher debt relative to equity weakened that link. This is the least stable of the three results.

**Live page:** `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/` *(replace after publishing)*

## How to use

1. Open the page in any browser, on a phone or a computer.
2. Choose the subsector and enter the firm's net income, total assets, total liabilities, and shareholders' equity in **₱ millions**.
3. Read the three checkpoints and the trip summary. Each check shows a status, the related finding of the study, how strong the evidence is, and a suggested action for management to consider.

The values shown when the page opens are an example. Nothing entered is saved or sent anywhere; all calculations run in the browser.

## How the checks work

| Check | Measure | Benchmark used |
|---|---|---|
| Asset efficiency | Net income ÷ total assets | Mean ROA of the chosen subsector (all firms: 0.18%; Hotel and Leisure: -0.06%; Casino and Gaming: 2.55%; Transportation Services: -0.36%) |
| Firm size | Total assets | Lower and upper thirds of total assets across the 84 firm-years (about ₱11,060 million and ₱76,134 million) |
| Debt level | Total liabilities ÷ shareholders' equity | Median (2.66x) and upper quartile (5.16x) of firms with positive equity. If equity is zero or negative, the ratio is reported as not meaningful. |

The benchmarks were calculated from the study data: 12 PSE-listed tourism-related firms (Hotel and Leisure, Casino and Gaming, Transportation Services), 2018 to 2024, 84 firm-years, taken from SEC Form 17-A annual reports.

## Limitations

- The benchmarks describe the sector in 2018 to 2024, a period dominated by the pandemic. They are not targets or predictions.
- The study found relationships, not proof of cause and effect, and is based on 12 firms.
- The tool does not predict price-to-book value. It compares a firm with the sector and points to areas for management to review.
- Net profit margin is not included because it had no significant relationship with price-to-book value.

## Files

- `index.html`: the complete tool (HTML, CSS, and JavaScript in one file; no installation needed).
- `README.md`: this file.

## Run it on your own computer

Download `index.html` and double-click it. No server is needed.

## Credits

[Names of researchers] | [School / Program] | [Year]

Based on the study *The Role of Firm Size and Financial Leverage in Moderating the Relationship between Profitability and Firm Value in Listed Tourism-Related Firms in the Philippines*.
