# Analysis on Comcast Telecom Consumer Complaints 

<b>Description:</b>
Comcast is an American global telecommunication company. The firm has been providing terrible customer service. They continue to fall short despite repeated promises to improve. Only last month (October 2016) the authority fined them a $2.3 million, after receiving over 1000 consumer complaints. 

In this project I tried to pin down what is wrong with Comcast's customer service by analyzing data with help of some visualization.

<b>Analysis:</b>
To perform analysis I have used different python libraries (Pandas, matplotlib, scikit-learn).
1.	First I have imported data into Python environment.
2.	Then worked on some data cleaning task (Renaming few columns, dropping unused columns and splitting date-month column).
3.	Next calculated monthly complaints table. 
4.	To plot the trend chart for the number of complaints at monthly granularity levels used line chart.
5.	And to plot the trend chart for the number of complaints at daily granularity levels used bar chart.
6.	Next plotted Month-wise complaints chart using a bar chart.  
7.	Calculated a table with the frequency of complaint types.
8.	Also plotted same table result using line chart to find which complaint types are maximum.
9.	Then created a new categorical variable with value as Open (for Open & Pending) and Closed (for Closed & Solved)categories. Plotted same values using bar and pie chart for better understanding. 
10.	Calculated state wise status of complaints table and then plotted it in a stacked bar chart.

<b>Findings:</b>
1.	Which state has the maximum complaints.
2.	Which state has the highest percentage of unresolved complaints.
3.	The total count of Complaints resolved till date, which was meeting certain criteria.
4.	The percentage of Complaints resolved till date again, which were meeting certain criteria.
