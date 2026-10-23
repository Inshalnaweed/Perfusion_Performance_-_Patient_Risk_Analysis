# CPB Performance & Patient Risk Analysis

## Project Overview
This project analyzes cardiopulmonary bypass (CPB) performance and patient risk factors to explore their association with ICU stay and postoperative complications after cardiac surgery.

## Objective
To investigate whether CPB time, lactate levels, hematocrit, blood flow rate, and other clinical variables are associated with patient outcomes.

## Tools Used
- **Excel:** Data organization, cleaning, formulas, and charts
- **SQL (MySQL):** Data querying, grouping, and complication-rate analysis
- **Statistics:** Descriptive statistics, correlation, and hypothesis testing
- **Python:** Data analysis and visualization using Pandas and Matplotlib

## Dataset
The project uses a synthetic cardiac surgery dataset containing the following variables:

- Case ID
- Age and Weight
- Surgery Type
- Body Surface Area (BSA)
- CPB Time and Cross-Clamp Time
- Flow Rate and Mean Arterial Pressure (MAP)
- Lowest Temperature
- Hematocrit Nadir and Peak Lactate
- Urine Output
- ICU Stay and Ventilation Hours
- Complications and Patient Outcomes

## Analysis Performed

### Excel
- Data organization and validation
- Descriptive statistics
- Correlation analysis
- Charts and visual summaries

### SQL
- Grouping patients by CPB time categories
- Calculating postoperative complication rates
- Comparing patient outcomes across groups
- Summarizing clinical variables

### Statistics
- Examining relationships between clinical variables and ICU stay
- Comparing outcomes between patient groups
- Interpreting statistical results

### Python
- Scatter plots for CPB time versus ICU stay
- Bar charts for surgery type distribution
- Histograms for ICU stay
- Box plots comparing CPB time by complication status
- Scatter plots for peak lactate versus ICU stay

## Key Research Questions & findings
**Does higher peak lactate correlate with longer ICU stay?**
There is a very weak positive relationship between peak lactate and ICU stay (r=0.11). This means patients with higher lactate levels tended to have slightly longer ICU stays. The relationship is statistically significant based on the calculated p-value, but it is very weak.

**Does prolonged CPB increase complication probability?**
CPB time has a moderate positive correlation with ICU stay (r=0.411). This suggests that patients with longer bypass times tended to stay longer in the ICU. However, we need to compare complication rates by CPB time to determine whether longer CPB is associated with more complications.                                                                                                                                                                **Does low hematocrit correlate with complications?**
The analysis showed no statistically significant difference in hematocrit levels between patients with and without complications (p = 0.0779). This suggests that, in our dataset, we do not have enough evidence to conclude that low hematocrit is associated with complications.                                                                                                                                                                           **Is there a statistically significant difference in ICU stay between low-CPB and high-CPB groups?**
The analysis showed a statistically significant difference in ICU stay between the low-CPB and high-CPB groups (p = 2.99 × 10⁻¹⁵). Since the p-value is far below 0.05, the difference is highly statistically significant. This suggests that ICU stay differs between patients with shorter and longer CPB times.

## Conclusion
This project demonstrates the application of Excel, SQL, statistics, and Python to a healthcare analytics problem. It highlights how data analysis can help explore relationships between perfusion parameters and postoperative outcomes.

## Important Note
This project uses **synthetic data for educational and portfolio purposes**. The results are illustrative and should not be interpreted as clinical evidence or used to guide patient care.

## Skills Demonstrated
- Healthcare data analysis
- SQL querying and aggregation
- Data organization and validation
- Statistical analysis
- Python visualization
- Analytical thinking and interpretation
