# Reflective Report for PDS Assignment 

## PART 1 Python Without Imports

This section focused on processing data using only core Python features. The statistical functions produced minimum, maximum and median values for both rows and columns with results showing that some columns had wider ranges than others, indicating greater variation within certain age groups. Calculating the median was particularly useful because it provided a clearer measure of the centre of the data when compared to the maximum values, which were sometimes affected by unusually large observations.
Working without libraries meant handling the CSV file manually, including reading each line, splitting values, and storing the results in lists and dictionaries. This approach made the structure of the data clearer and highlighted how much work libraries usually handle in the background.

The most insightful part was that the tasks were progressive, which meant that a mistake in an earlier function affected the later questions, so I often had to go back, correct the code, and rerun everything. Converting numeric data types also took time, especially when the dataset contained missing or non-numeric entries. These steps were necessary to ensure that later calculations worked correctly.

Overall, this part strengthened my ability to debug code and understand error messages more quickly. It also improved my confidence in writing simple, functional Python, and using of version control sofwares without complete reliance on external tools.

## PART 2 Data Analysis With Libraries

This section focused on analysing the dataset using pandas, matplotlib, seaborn and scipy. The work here felt more familiar because I could draw on knowledge from other modules, particularly Statistical Inference (Exploratory Data Analysis). Using these libraries made it easier to clean the data, combine datasets, and create variables that supported the analysis. The visualisations highlighted clear differences between weekday and weekend bike usage, and statistical testing helped confirm that these differences were meaningful. Overall, this part reinforced my understanding of applied data analysis and how to interpret results using established analytical tools.

### Key insigts
1. The visualisations showed that weekday bike usage followed a more predictable commuting pattern, with noticeable peaks during morning and evening hours. Weekend usage appeared more evenly distributed across the day, suggesting that usage during weekends is less connected to work or commuting routines. Seasonal and temperature-based charts also suggested that bike usage generally increased during warmer conditions.

2. Outlier detection was carried out using the Interquartile Range (IQR) method because it is simple to apply and works well for identifying unusually high or low values without being heavily affected by extreme observations. The boxplots before and after cleaning showed that removing outliers reduced the spread of extreme values and produced a cleaner dataset for analysis.

3. For the hypothesis testing stage, a two-sample t-test was selected because the analysis involved comparing the average bike usage of two separate groups: weekdays and weekends. The p-value from the test indicated whether the observed difference was statistically significant or likely due to random variation. This helped support the findings from the visualisations with statistical evidence rather than relying only on observation.

## References 
ChatGPT (2026). ChatGPT AI assistant. ChatGPT AI assistant response to the prompt [ breakdown the question and suggest the best approach using an examiners lens] (Personal Communication, April).

Hunt, J. (2023) A beginners guide to python 3 Programming[online]. 2nd ed.Cham : Springer International Publishing. [Accessed: March-May 2026]. 

Nick Walter(2024) Python for Non-Programmers [LinkedIn Learning].Available at: https://www.linkedin.com/learning/python-for-non-programmers?u=56744785 [Accessed: April]. 

Microsoft Copilot (2026). Copilot AI assistant. Copilot AI assistant response to the prompt [ debug and explain the error message and suggest a possible fix] (Personal Communication, May).

Python Cheat Sheets #1-4 (2026). UFCFVQ-15-M Programming for Data Science. Available at: https://blackboard.uwe.ac.uk/ultra/courses. [Accessed: March-May 2026].