# CO₂ Emissions Data Analysis

## Project Overview

This project was completed as part of Module 0 at The Marcy Lab School's Data Analytics Fellowship.

For this assignment, I took on the role of a data analyst working with a climate and energy nonprofit. The organization wanted to use emissions data to determine where climate support and community protection efforts might be needed.

My responsibility was to explore the dataset, understand how the information was structured, and identify potential data quality concerns before drawing conclusions.

## Questions I Set Out to Answer

1. What information is included in the dataset?
2. Are there missing values that could affect our analysis?
3. Do regional emissions totals overlap with the individual country totals?
4. How do Ethiopia and the United States compare in CO₂ emissions relative to their populations?

## Dataset Source and License

The dataset, `co2_emissions_2022.csv`, contains 254 rows of country and regional emissions data from 2022.

It includes six columns: `country`, `iso_code`, `year`, `population`, `gdp`, and `co2`.

**Source:** [Our World in Data, CO₂ and Greenhouse Gas Emissions](https://github.com/owid/co2-data)

**License:** Creative Commons Attribution 4.0 International (CC BY 4.0).

For more information about the dataset, see [data/SOURCE.md](data/SOURCE.md).

## Tools and Skills Used

- Git Bash for navigating directories and exploring data
- Terminal commands including `head`, `tail`, `cut`, `grep`, and pipes
- Git and GitHub for version control
- VS Code for editing and documenting findings
- Markdown for organizing technical documentation

## Data Quality Findings

During my exploration, I found that 36 entries were missing ISO codes and 89 entries were missing GDP values.

I also noticed that the dataset contains individual countries alongside regional totals, which could potentially lead to double counting.

This led me to my primary data quality question:

**How are emissions totals for regions like Africa calculated, and do they include emissions from the individual countries already listed in the dataset?**

My investigation, including terminal commands and recorded output, is documented in [Section 6 of my field notes](starter/field_notes.md#6-data-quality-question-for-the-source).

## Reflection

This project helped me understand that data analysis begins with questioning the information you're given. Before using data to make decisions, it's important to understand its structure, limitations, and source.

I also gained experience using terminal commands to inspect datasets and learned how to document my process using Git and GitHub.

## Documentation

[View my complete Data Literacy Field Notes](starter/field_notes.md)

**Author:** Maasho  
**Program:** The Marcy Lab School, Data Analytics Fellowship  
**Year:** 2026
