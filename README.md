# Mini Project on Online Shoppers Purchasing Intention Analysis

**Project Overview**

This project analyzes online shopping session behaviour to identify patterns associated with purchase conversion. Using **Microsoft Excel** for data cleaning and transformation and **Power BI** for interactive visualization, the project explores how visitor characteristics, browsing engagement, traffic sources, and shopping patterns relate to purchasing intention.

**Objectives**

- Analyze online shopping sessions and purchase conversion patterns.

- Compare purchasing behaviour across visitor segments.

- Understand the relationship between browsing engagement and purchase outcomes.

- Examine bounce rates, exit rates, and page values across purchase statuses.

- Compare conversion patterns across months, traffic types, and weekdays versus weekends.

- Develop actionable business recommendations based on analytical findings.

**Dataset Information**

**Official dataset:** https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset

The dataset contains session-level information such as page visits, browsing duration, bounce rates, exit rates, page values, visitor type, traffic type, weekend activity, and whether a session resulted in a purchase.The `Revenue` variable indicates whether a session resulted in a purchase.

**Data Cleaning and Preparation**

The original CSV was reviewed and prepared for analysis using Microsoft Excel.

The planned data preparation workflow includes:

1. Importing and preserving the original dataset.

2. Checking the number of records and columns.

3. Checking for missing values.

4. Identifying and reviewing exact duplicate records.

5. Validating numerical values and data types.

6. Standardizing categorical values where necessary.

7. Creating calculated fields for analytical use.

8. Validating the final dataset before importing it into Power BI.

**Calculated Columns**

Total_Page_Visits - Total visits across administrative, informational, and product-related pages 

Total_Page_Duration -  Combined duration across the three tracked page categories 

Visitor_Segment - Groups visitors into new, returning, and other categories 

Purchase_Status - Converts the purchase indicator into readable labels 

Conversion_Flag - Represents purchase outcomes as 1 for purchase and 0 for no purchase 

Additional engagement categories was also created to add analytical value and their classification rules to document.

**Power BI Dashboard**

The report is organized into four pages.

### Page 1: Executive Overview

Provides a high-level summary of shopping sessions and purchase conversion.
Key components include:

- Total sessions

- Purchased sessions

- Non-purchased sessions

- Purchase conversion rate

- Average page visits

- Monthly purchase trends

- Visitor composition and conversion comparisons

### Page 2: Customer Behaviour Analysis

Examines browsing behaviour associated with purchase outcomes.
Key components include:

- Average page visits by purchase status

- Average page duration by purchase status

- Bounce rate comparison

- Exit rate comparison

- Page value comparison

### Page 3: Conversion Analysis

Explores differences in conversion patterns across visitor and session characteristics.
Key components include:

- Purchases by traffic type

- Conversion rate by traffic type

- Weekday versus weekend conversion

- Conversion by engagement category, if included

- Special-day conversion patterns

- Customer segment performance

### Page 4: Insights and Recommendations

Summarizes the main findings and translates them into potential business actions.The recommendations focus on:

- Improving the returning-visitor experience

- Enhancing product discovery and browsing engagement

- Investigating pages with high bounce and exit rates

- Understanding high-conversion periods

- Evaluating traffic sources using both volume and conversion rate

**Business Value**

The analysis can help an e-commerce business:

- Understand customer browsing patterns.

- Identify visitor segments for further investigation.

- Compare traffic sources beyond raw visitor volume.

- Identify behavioural patterns associated with purchase conversion.

- Develop data-informed ideas for customer experience and marketing optimization.
