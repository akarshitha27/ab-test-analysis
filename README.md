# ab-test-analysis
A statistical analysis of an A/B test for a checkout page redesign, confirming a significant lift in conversion rates.

## Business Objective
The product team designed a new checkout page to reduce friction and improve user experience. The goal of this analysis was to determine if the new design (Variant B) resulted in a statistically significant increase in conversion rates compared to the original design (Variant A).

## Methodology
- **Data:** Simulated A/B test data for 10,000 users (5,000 per variant).
- **Tools:** Python (Pandas, SciPy, Matplotlib), Jupyter Notebook.
- **Statistical Analysis:** Performed a Chi-Squared test to determine the statistical significance of the difference in conversion rates between the two groups.

## Key Results
- **Conversion Rate (Variant A):** 9.58%
- **Conversion Rate (Variant B):** 11.34%
- **Relative Lift from New Design:** **+18.37%**
- **Statistical Significance (p-value):** 0.0045 (p < 0.05)

## Conclusion & Recommendation
The analysis confirms that the new checkout page design (Variant B) provides a **statistically significant improvement** in conversion rates. The p-value of 0.0045 is well below the 0.05 threshold, meaning there is less than a 0.5% probability that this result occurred by random chance.

**Recommendation:** Roll out the new design to 100% of users. This change is projected to increase conversions by over 18%.

## Project Structure
ab-test-analysis/
├── ab_test_analysis.ipynb  # Full analysis code
├── data/
│   └── ab_test_data.csv    # Dataset used
└── README.md               # This file
