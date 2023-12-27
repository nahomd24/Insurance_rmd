Medical Charges Analysis
Author: Nahom Diress
Date: Current Date

Overview
This repository contains an analysis of medical charges data using R and R Markdown. The analysis explores various factors such as distribution of charges, charges by age, charges by BMI, charges by smoker status, and charges by region. The goal is to derive insights into the relationships between these factors and medical charges.

Getting Started
Clone this repository to your local machine.
Ensure you have R and RStudio installed.
Open the R Markdown file (medical_analysis.Rmd) in RStudio.
Install the required R packages if not already installed:
R
Copy code
install.packages(c("tidyverse", "ggplot2"))
Run the code chunks in the R Markdown file.
Analysis Highlights
1. Distribution of Charges
Most charges are below $20,000, with a significant number falling between $20,000 and $50,000.

2. Charges by Age
Medical charges generally increase with age. A line plot illustrates the relationship between age and mean charges.

3. Charges by BMI
Higher BMI is associated with higher medical charges. BMI is categorized into four groups, and a bar plot shows the mean charges for each category.

4. Charges by Smoker Status
Smokers tend to have significantly higher average medical charges than non-smokers. A bar plot visualizes the contrast in average charges between the two groups.

5. Charges by Region
Average charges are fairly similar across different regions, with the southeast region showing slightly higher charges.

Additional Information
The raw data is stored in the insurance.csv file.
Detailed code and visualizations are available in the R Markdown file (medical_analysis.Rmd).
Feel free to explore, modify, and use the code for your own analysis.
Conclusion
This analysis provides valuable insights into the factors influencing medical charges. For more detailed information, refer to the complete R Markdown document.
