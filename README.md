# **Kickstarting with Excel**

## **Overview of Project**

### **Purpose**
The purpose of this analysis was to guide new campaigns based on trends drawn from previously successful Kickstarter campaigns. The following Excel workbook focuses on Plays within the Theater parent category using data from 2011 to 2017. Charts and graphs were created to determine when to launch the fundraiser and what the realistic goals of the campaign should be.

## **Analysis and Challenges**
Statistical analysis was performed to reveal the best time to launch and what a reasonable fundraising goal looked like while pivot tables and graphs were utilized to visually organize the results.

### **Analysis of Outcomes Based on Launch Date**
Unix time stamps were converted using Excel functions in order to extract launch dates. Outcomes were then organized into outcomes and tallied by month.
![ Screenshot 1.1 Unix Convert](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/Screenshot%201.1%20Unix%20Convert.png)
![ Screenshot 1.2 Pivot Table Outcome](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/Screenshot%201.2%20Pivot%20Table%20Outcome.png)

### **Analysis of Outcomes Based on Goals**
Measures of central tendency and measures of spread were calculated to analyze trends in the goals and pledged donations of the campaigns. A graph of *Outcomes vs Goals* was created to help determine the best launch date of the campaign. 
![ Screenshot 1.3 Stats](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/Screenshot%201.3%20Stats.png)

Using the COUNTIF equation in Excel, the goals of campaigns were subdivided into ranges and outcomes tallied for insight into were to set the fundraising goal.
![ Screenshot 1.4 COUNTIF 1](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/Screenshot%201.4%20COUNTIF%201.png)

### **Challenges and Difficulties Encountered**
Possible challenges include inconsistent labeling from the parent/subcategories. This would make sorting the data an arduous or inaccurate process.

## **Results**
- The months that launched the highest number of successful Theater campaigns were May and June. There were no months that launched significantly more failed projects.
![Theater_Outcomes_vs_Launch](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/1.%20Theater_Outcomes_vs_Launch.png)

- The campaigns whose goals were $5,000 or under had the highest success rates with around 75% of campaigns being fully funded. Additionally, the average goal of the successful campaign was around $3,000 (with around 
$3,000 eventually pledged.)
![Outcomes_vs_Goals](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/2.%20Outcomes_vs_Goals.png)

- A limitation of the analysis of this dataset would be that some of the data is almost a decade old and therefore does not accurately reflect current trends.

- Other possible tables and/or graphs that could illuminate more trends would be a graph analyzing *Percentage of Outcomes by Month* (instead of absolute values) which would create a better idea of how the months did relative to each other. For example, October had more successful campaigns (65) than November (54) however, October also had 115 campaigns compared to November’s 88. When the months are compared based on percentage of outcomes, November had more of its campaigns become successful (Oct 56% vs Nov 61%).
![Outcome Percentage Based on Dates](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/3.%20Outcome%20Percentage%20Based%20on%20Dates.png)

- Another graph that would be helpful would be to narrow down the *Theater Outcomes vs Launch* to within campaigns with a goal of $5,000 or less. There was a success rate of about 75%, for those campaigns under $5,000 with a sharp decline to 50% for campaigns between $5,000-$15,000 so narrowing the data into this subset would help further dial in when the best launch date would be.
![Outcome Percentages Based on Launch Dates for Under 5000](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/4.%20Outcome%20Percentages%20Based%20on%20Launch%20Dates%20for%20Under%205000.png)
![Screenshot 1.5 COUNTIF 2](https://github.com/K10Huff/Kickstarter_Analysis/blob/2c84284f09e46ece610f72edf1ae2e2dfbe2a988/Resources/Graphs%20and%20Screenshots/Screenshot%201.5%20COUNTIF%202.png)
- If there was more information regarding what type of play is being produced, a data set of comparable plays could be organized to find trends occurring among similar situations.

