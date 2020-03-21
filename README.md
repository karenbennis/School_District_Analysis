# School_District_Analysis
## Project Overview
The following analysis looks at the performance of 15 schools within a school district.

The following is the list of deliverables that were completed for the analysis of the school district: 

* A high-level snapshot of the district's key metrics, presented in a table format
* An overview of the key metrics for each school, presented in a table format
* Tables presenting each of the following metrics:
	* Top 5 and bottom 5 performing schools, based on the overall passing rate
	* The average math score received by students in each grade level at each school
	* The average reading score received by students in each grade level at each school
	* School performance based on the budget per student
	* School performance based on the school size 
	* School performance based on the type of school

After delivering the above, the team became aware that the reading and math scores for 9th graders at Thomas High School had been changed. Since the extent of the academic dishonesty was not known, the team requested that the analysis be rerun with the 9th grade reading and math scores from Thomas High School replaced (while keeping all other associated data in tact).

The analysis that follows in this report compares the initial analysis with the rerun corrected analysis.

## Resources
Data Source: schools_complete.csv, students_complete.csv
Software: Python 3.7.6, Jupyter Notebook 6.0.3
Libraries: Pandas, Numpy

## District Summary
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/DistrictSummary.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/DistrictSummaryChallenge.png)

### Interpretation
The correction for the academic dishonesty impacted the District Summary as summarized below:
* Average math score dropped by 0.1% from 79.0% to 78.9%.
* Average reading score did not change significantly to a tenth of a percent.
* Percentage of students who passed math dropped by 1% from 75% to 74%.
* Percentage of students who passed reading dropped by 1% from 86% to 85%.
* Overall passing percentage dropped by 1% from 65% to 64%.

## School Summary
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/SchoolSummary.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/SchoolSummaryChallenge.png)

### Interpretation
The correction for the academic dishonesty impacted the District Summary as summarized below: