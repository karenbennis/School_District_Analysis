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
* Average math score decreased by 0.1%, from 79.0% to 78.9%.
* Average reading score did not change significantly to a tenth of a percent.
* Percentage of students who passed math decreased by 1%, from 75% to 74%.
* Percentage of students who passed reading decreased by 1%, from 86% to 85%.
* Overall passing percentage decreased by 1%, from 65% to 64%.

## School Summary
The following is a rendering of the Thomas High School row within the School Summary DataFrame for the original and corrected datasets.

### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/SchoolSummary.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/SchoolSummaryChallenge.png)

### Interpretation
The correction for the academic dishonesty impacted the School Summary as summarized below:
* Average math score decreased by 0.07%, from 83.42% to 83.35%.
* Average reading score increased by 0.05% from 83.85% to 83.90%.
* Percentage of students who passed math decreased by 26.4%, from 93.3% to 66.9%.
* Percentage of students who passed reading decreased by 27.6%, from 97.3% to 69.7%.
* Overall passing percentage decreased by 25.8%, from 90.9% to 65.1%.

These results are to be expected since it follows that approximately a quarter of the students at Thomas High School are 9th grade students. The respective scores were removed from the dataset; therefore, these students would appear as though they did not pass math or reading.

## High-performing and low-performing schools
The following is a rendering of the entire DataFrame which sorts the school performance in descending order, meaning, the top performing school appears first, and the bottom performing school appears last.

### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/TopSchools.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/TopSchoolsChallenge.png)

### Interpretation
The correction for the academic dishonesty impacted the Thomas High School's, moving down six places, from 2nd to 8th.

This is not surprising for the same reasons described in the School Summary analysis, above.

## Math Scores by Grade
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/MathScoresByGrade.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/MathScoresByGradeChallenge.png)

### Interpretation


## Reading Scores by Grade
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ReadingScoresByGrade.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ReadingScoresByGradeChallenge.png)

### Interpretation

## Scores by School Spending
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolSpending.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolSpending.png)

### Interpretation


## Scores by School Size
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolSize.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolSizeChallenge.png)

### Interpretation


## Scores by School Type
### Original Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolType.png)

### Corrected Analysis
![](https://github.com/karenbennis/School_District_Analysis/blob/master/ScoresBySchoolTypeChallenge.png)

### Interpretation