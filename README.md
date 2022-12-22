# Women-power_-vs_Abortions
✅ Completed ✅
​
Description and Background
​

The goal of this project was to take data about the percentage of women in leadership positions by country and compare them with the prevalence of abortion in said country. This analysis was done in an attempt to validate vice president Kamala Harris' assertion that medical reproductive rights are vital for a woman's ability to succeed in a professional environment.

For this analysis, I decided on using a country's % change rather than the % of women in leadership positions because the assertion is not that countries that facilitate abortions are more conducive to women succeeding rather the assertion is abortion itself facilitates more women succeeding. To abide by this assertion we will be looking at how much the women in leadership changed in a country through the legalization and prevalence of abortion. I would like to clarify that this analysis is only aiming to prove correlation and not causation seeing as there are plenty of factors that may affect the % of women in leadership positions. For example in the graph below there seems to be a harsh outlier on the left side of the graph. That outlier is India, while they were not outliers before covid after covid many women chose to stop working and stay home to take care of their families which caused a step decrease in the % of women in leadership positions.

​

Process
​

Step 1: Preparing The Data

​

The project began with importing and cleaning the data. There are 2 datasets that we needed to import for this project, the first was the % women in leadership positions (WILP) by country dataset which contained 2 ID columns (Country Name and Country Code) and columns representing the % WILP with each column representing a year from 1970 - 2021. The second dataset was much simpler it contained 2 columns 1 representing the country and another representing the abortion rate as of 2021 (the abortion rate is abortions per 1000 pregnancies). The data did need a lot of cleaning seeing as dataset 1 had a lot of null values and the 2 datasets did not have identical country lists or names.

​

Step 2: Exploratory Analysis

​

During the exploratory analysis, I focused on getting a grasp of the dataset and seeing if there are any new columns/metrics I could create to find a better correlation however sometimes simple is best and I figured an abortion rate to % WILP change comparison would be the best approach.

​

Step 3: Visualization

​

After all the data was in order it was time to decide how I wanted to represent the data. While the bar chart in the 'Project Descriptions and Background' section looked nice it didn't convey the information very well. After trying the histogram below and a Pareto chart not included in this summary I decided the best course of action was a dot-plot with a trend line to visualize the possible correlation.

Results​
​
After analysis, the best 2 representations of the data are the 2 dot plots below. The first represents the change in %WILP (1980 - 2021) as a function of the abortion rate and the second plot represents the change in %WILP over the last 10 years as a function of the abortion rate. The first chart has a downward trend implying that as abortion rates go up change in %WILP goes down nearly 30%. While the second chart illustrates that in the last 10 years countries with higher abortion rates outpace those with lower ones by ~0.6 percentage points.
