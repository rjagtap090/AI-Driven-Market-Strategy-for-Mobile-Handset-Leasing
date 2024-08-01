# AI-Driven Market Strategy for Mobile Handset Leasing

## Overview

This project was part of the BCG Strategy Consulting Virtual Experience Program, completed between June 2023 and August 2023. It involved practical tasks such as market research, data analysis, financial modeling, understanding consumer needs, and providing client recommendations. The project culminated in a comprehensive recap summarizing key findings and outcomes for a mobile handset leasing proposal. Both Python and Excel were utilized to perform data analysis and develop strategic insights.

## Features

- **Market Research:** Conducted in-depth market research to understand industry trends and consumer behavior.
- **Data Analysis:** Analyzed large datasets to extract meaningful insights using Python and Excel.
- **Financial Modeling:** Developed financial models to assess the viability of the mobile handset leasing proposal.
- **Client Recommendations:** Provided actionable recommendations based on data-driven insights.
- **Project Recap:** Presented a comprehensive summary of key findings and conclusions.

## Skills Demonstrated

- **Client Relations:** Effectively communicated with clients to understand their needs and provide tailored solutions.
- **Market Research:** Conducted thorough research to gather relevant market data.
- **Project Management:** Managed project timelines and deliverables efficiently.
- **Data Analysis:** Utilized Python and Excel for detailed data analysis.
- **Business Development:** Developed strategies to drive business growth.
- **Financial Analysis:** Performed financial analysis to evaluate business proposals.

## Methodology

1. **Market Research:**
   - Collected and analyzed market data to identify trends and opportunities.
   - Used Python for web scraping and data cleaning.

2. **Data Analysis:**
   - Imported data into Python and Excel for analysis.
   - Applied statistical methods and visualizations to extract insights.

3. **Financial Modeling:**
   - Built financial models in Excel to evaluate the feasibility of the handset leasing proposal.
   - Used Python for advanced data manipulation and scenario analysis.

4. **Client Recommendations:**
   - Summarized findings and developed strategic recommendations.
   - Created visual presentations to communicate results effectively.

## Example Python Code

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

# Load dataset
data = pd.read_excel('BCG_Telco_Data.xlsx')

# Data Cleaning
data.dropna(inplace=True)

# Data Analysis
# Example: Analyzing customer segments
customer_segments = data['CustomerSegment'].value_counts()

# Plotting customer segments
plt.figure(figsize=(10, 6))
sns.barplot(x=customer_segments.index, y=customer_segments.values, palette='viridis')
plt.title('Customer Segments Distribution')
plt.xlabel('Customer Segment')
plt.ylabel('Number of Customers')
plt.show()

# Financial Modeling in Excel (example concept, not executable code)
# Assuming a function to calculate Net Present Value (NPV)
def calculate_npv(cash_flows, discount_rate):
    npv = np.sum([cf / (1 + discount_rate)**i for i, cf in enumerate(cash_flows)])
    return npv

cash_flows = [1000, 2000, 3000, 4000, 5000]
discount_rate = 0.1
npv = calculate_npv(cash_flows, discount_rate)
print(f'Net Present Value (NPV): {npv}')
```

## Results

- **Market Insights:** Identified key market trends and consumer preferences.
- **Strategic Recommendations:** Developed actionable strategies for the client.
- **Financial Viability:** Demonstrated the financial feasibility of the mobile handset leasing proposal through robust modeling.

## Authors

- **Rishabh Jagtap**  [Email](mailto:rjagtap9299@gmail.com))
