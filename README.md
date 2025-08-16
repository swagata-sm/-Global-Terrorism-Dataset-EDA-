terr1
EDA : Global Terrorism Dataset.
Industry Context:
The Global Terrorism Dataset analysis is highly relevant to multiple industries, including Security and Defense, Government and Public Administration, Research and Academia, and International Relations. Understanding terrorism patterns and trends helps in devising strategic policies, improving public safety, and conducting in-depth academic research. Governments and security agencies can leverage such insights to enhance counter-terrorism measures and allocate resources effectively.

Objective:
The objective of this project is to perform exploratory data analysis (EDA) on the Global Terrorism Dataset to pinpoint global hotspots of terrorism and understand the changing trends in terrorist activities.
Through this analysis, we aim to extract insights pertinent to security concerns, which could play a crucial role in formulating effective counter-terrorism strategies.
The business objective of this project is to leverage the data contained within the Global Terrorism Database (GTD) to derive actionable insights into terrorist activities worldwide from 1970 to 2017.
About the Data:
Dataset Size: The dataset is quite large, containing 181,691 entries or rows.

Feature Quantity: The dataset contains 135 features or columns.

Data Types: The dataset has a mix of data types. There are 55 features with floating point numbers (float64), 22 features with integers (int64), and 58 features with objects (object). The object datatype in pandas typically means the column contains string (text) data.

Memory Usage: The dataset uses over 187.1 MB of memory.

Missing Values: There are some columns with a large number of missing values. For example, the 'approxdate' column has 172,452 missing. Values and the 'related' column has 156,653 missing values. However, several columns do not have any missing values, such as 'eventid', 'iyear', 'imonth', 'iday', 'INT_LOG', 'INT_IDEO', 'INT_MISC', and 'INT_ANY'.

Duplicate Values: There are no duplicate values in the dataset.

Data Wrangling & Initial Insights:
Selected 19 important columns from 135 columns for our analysis.

Created a new column by name " Casualty".

The data consists of terrorist activities ranging from the year: 1970 to 2017

Maximum number of people killed in an event were: 1570

Maximum number of people wounded in an event were: 8191

Maximum number of total casualties in an event were: 9574

Data Visualization, Storytelling & Experimenting with charts :
The storytelling and visualizations in this project will be based on these parameters:
Year Wise Attacks.

Region wise Attacks.

Country Wise Attacks - Top 10.

City Wise Attacks - Top 10.

Terrorist Group wise Attacks.

'Attack Type' wise Attacks.

Target Type Wise Attacks.

Group + Country wise Attacks - Top 10.

Humanity affected(World-wide) by Terrorist Attacks from 1970 - 2017.

All of the above parameters are calculated and visualized on the basis of:
Number of Attacks.

Total Casualty.

Total people Killed.

Total people Wounded.

Sample Charts:
Top 10 Terrorist Groups. Screenshot (213)

Wounded over the years. Screenshot (210)

Region Wise Attacks. Screenshot (211)

Types of Attacks. Screenshot (214)

For more insights refer to the .ipynb file.
Conclusion:
By performing EDA on the Global Terrorism Dataset, we gain valuable insights into the patterns and trends of terrorism activities worldwide. These insights can help in improving public safety, informing policy decisions, and guiding further research in terrorism studies.
