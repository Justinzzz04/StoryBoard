# COS30045 - T03: Communicating Data Insights

## Data Story
* **Target Audience:** Australian consumers purchasing a new television.
* **Audience Needs:** Clear guidance on how screen size, technology (LCD, LED, OLED), and energy star ratings affect electricity bills.
* **Key Finding:** Larger screens consume significantly more electricity, but high energy star ratings and LED technology help mitigate long-term operating costs.

---

## About the Data
* **Data Source:** Australian Energy Rating Television Dataset (Equipment Energy Efficiency / E3 Program).
* **Data Processing:** Processed using KNIME workflows. Filtered for Australian entries (`SoldIn = Australia`), removed null values, and aggregated metrics (counts, averages) using GroupBy and Scatter Plot nodes.
* **Privacy:** Data consists of public manufacturer technical specifications and star ratings; no personal user data is present.
* **Accuracy and Limitations:** Based on standard laboratory testing conditions. Actual real-world energy consumption varies depending on brightness settings, dynamic contrast, and daily usage hours.
* **Ethics:** Visualizations avoid truncated Y-axes or misleading scales to ensure fair brand and technology comparisons.

---

## AI Declaration
* Generative AI tools (Gemini) were used to assist in formatting project documentation, structuring HTML/CSS templates, and writing step-by-step lab procedures. Data calculations, KNIME workflow execution, visual designs, and lab demonstrations were independently executed and verified.