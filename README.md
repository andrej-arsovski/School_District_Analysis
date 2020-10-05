# School_District_Analysis

## Overview of the Analysis
This analysis is a follow up to previous work examining the performance of 15 High Schools. The original study looked are reading and math scores, student demographics, and school budget amongst other variables in order to generate a performace summary at the district and individual school level. This work builds upon that study by removing student scores associated with a academic improprienty. Below, the effects of removing these grades are discussed as they pertain to the High School in question and the District as a whole.  In this analysis, the reading and math grades for Thomas High School have been replaced and the analysis carried out as previous.

## Results

### 1. Effects on the district. 
As a result of removing the math and reading scores from grade 9 students at Thomas High School, almost all measured categories showed small decreases. Betwwen the orginal study and this updated analysis the average math score for the district decreased from 79.0 to 78.9 while the average reading score did not change. The percent of students apssing math decreased from 75% to 74.8%, and the percentage passing reading from 85.8% to 85.7%. These in turn resulted in the overall passing rate decreasing from 65.2% to 64.9%.

District summary from original study
![original_distric_summary](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/original_district_summary.png)

New District Summary


![new_district_summary](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/new_district_summary.png)

### 2. Effect on Thomas High School and ranking. 
In the original stduy Thomas High School was the second highest performing school by overall passing percentage with 90.95%. In the new analysis Thomas High School is still ranked 2nd with 90.63% of students passing both math and reading, a slight decrease. Average math and reading scores and passing percentages also show small decreases as a result of removing the 9th graders math and reading scores. These decreases are on the order of fractions of percentage points, see tables below.

Original School summary
![original_school_summary](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/original_school_summary.png)

New School summary
![new_school_summary](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/new_school_summary.png)

### 3. Effect on math and reading scores by grade. 
Removing the math and reading scores from the Thomas High School 9th graders does not affect the scores from the 10th, 11th and 12th grades. However, the districts average 9th grade scores will likely be lower because the 9th grade math and reading scores were amongst the highest in the district. More analysis is required to confirm this hypothesis.

### 4. Effect on scores by school spending, size, and type. 
Removing the math and reading scores from Thomas High School 9th graders has no effect on scores by school spending. The statistics are unchanged from the original study where spending per student was negatively correlated with overall passing percentage.

Scores by school spending


![score_budget](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/score_budget.png)

Scores by school size were similarly unchanged in the new analysis. Medium size schools had the highest overall passing percentage (91%), followed closely by small schools (90%). Large schools had significantly lower overall passing percentages (58%).

Scores by school size


![score_size](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/score_size.png)

Finally as in the original analysis charter schools outperformed district schools in every metric. Removing the tainted math and reading scores had no effect.

Scores by school type


![score_type](https://github.com/andrej-arsovski/School_District_Analysis/blob/master/resources/score_type.png)

## Summary

Removing the 9th grade math and reading scores from Thomas High School and replacing them with NaNs had small effects on district performance, slightly lowering the average math, reading, and overall passing percentages. There was also an effect on the overall scores from Thomas High School with small drops in average math and reading scores as well as passing percentages in each subject and overall. However, the school's ranking was unaffected. There was also no effect on scores by budged, school type, and size.

