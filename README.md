# How many streets in Lisbon have short-term rentals apartments?

This study seeks to understand the distribution of short-term accommodation in Lisbon through a data-driven approach. There are frequent news reports and articles discussing how the old neighborhoods of Lisbon have the highest concentrations, but what does this concentration look like? How many streets in Lisbon have local accommodation? How is it distributed by neighborhood? How has it been distributed over the years?


# Python libraries used

| **Library** | **Workflow** | **Description** |
|-------------|--------------|-----------------|
| FuzzyWuzzy | Data Cleaning | Capable of comparing addresses provided at license application time with official Lisbon streets, enabling address standardization |
| Regex (re) | Data Cleaning | Used to improve the DataFrame by eliminating unnecessary columns and creating new ones |
| Pandas | Data Analysis | Used for statistical analysis and data manipulation |
| Matplotlib | Data Analysis | Used for creating support visualizations during the analysis phase |


**Additional tools:**
- **QGIS**: Used for visual observation of records (geographic data visualization)
- **Adobe Illustrator**: Used to enhance visualizations created in QGIS
