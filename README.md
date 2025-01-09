# DataVisualization_challenge

**Pymaceuticals' Clinical Study Analysis Project**
This project involved analyzing and visualizing data from Pymaceuticals’ animal study to evaluate the effectiveness of its anti-cancer drug, Capomulin, compared to other treatments for squamous cell carcinoma (SCC). Using Matplotlib and Python, various statistical analyses and visualizations were performed to present key findings to the executive team.

Outcomes

**Data Preparation:**

Merged the mouse_metadata and study_results datasets into a single comprehensive DataFrame.
Identified and removed duplicate entries based on mouse ID and time point, resulting in a clean dataset.
Verified the number of unique mice for accurate analysis.

**Summary Statistics:**

Generated a summary table with key statistics (mean, median, variance, standard deviation, and SEM) for tumor volume across all drug regimens.
Organized data by treatment regimen to facilitate comparisons.

**Bar Charts and Pie Charts:**

Created bar charts using both Pandas and Matplotlib to display the total number of time points recorded for each drug regimen.
Generated pie charts to illustrate the distribution of male and female mice in the study using both Pandas and Matplotlib.

**Quartiles, Outliers, and Box Plot:**

Analyzed the final tumor volumes for the most promising treatments: Capomulin, Ramicane, Infubinol, and Ceftamin.
Calculated quartiles, interquartile range (IQR), and identified potential outliers for each treatment group.
Created a combined box plot to visualize the distribution of tumor volumes and highlighted any outliers.

**Line Plot and Scatter Plot:**

Generated a line plot to track tumor volume over time for a mouse treated with Capomulin, showcasing the drug's effectiveness over time.
Created a scatter plot showing the relationship between mouse weight and average tumor volume for the Capomulin regimen.

**Correlation and Regression:**

Calculated the correlation coefficient between mouse weight and average tumor volume for Capomulin-treated mice, revealing a positive correlation.
Plotted a linear regression model over the scatter plot to highlight this relationship.
Key Findings

**Capomulin’s Effectiveness:**

Capomulin demonstrated significant tumor reduction over time for individual mice.
Tumor volume showed a notable negative trend over time, indicating the drug's efficacy.

**Correlation Insights:**

A strong positive correlation (coefficient > 0.8) between mouse weight and average tumor volume suggests that tumor size may be influenced by mouse weight for Capomulin-treated subjects.

**Comparative Analysis:**

Capomulin and Ramicane were the most effective regimens, showing smaller tumor volumes and fewer outliers compared to Infubinol and Ceftamin.

**Balanced Study Design:**

The male-to-female distribution was nearly equal, ensuring no gender bias in the study results.

**Conclusion**
This analysis provided clear evidence of Capomulin's effectiveness in reducing tumor size, supported by both statistical measures and visualizations. The inclusion of detailed charts, box plots, and regression models enhanced the study's interpretability and impact. The findings will aid Pymaceuticals' executive team in making informed decisions about the drug’s potential as a leading SCC treatment.






