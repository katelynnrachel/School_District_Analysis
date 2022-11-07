# School_District_Analysis

## Overview
The purpose of this analysis was to analyze and create insights based on data from a school district so that they could make decisons at the school and district level. Through jupyter notebook and the use of the pandas library, I was able to find the average math score, average reading score, % passing math, % passing reading, and the % of students who passed both tests for each school within the school district. For the purpose of the module assingment, I was told that the reading and math grades for Thomas High School ninth graders appear to have been altered. I then replaced the scores for those students with NaNs and repeated the school district analysis with the new data.

## Results
### How the District Summary Was Affected
- The Orginal Analysis
<img width="763" alt="Screen Shot 2022-11-06 at 10 51 24 PM" src="https://user-images.githubusercontent.com/107594280/200243696-6f247f77-09b9-4656-a458-0933bbc602b5.png">


- After Changing the Thomas High School Grades
<img width="690" alt="Screen Shot 2022-11-06 at 10 52 06 PM" src="https://user-images.githubusercontent.com/107594280/200243790-d8d4701c-1573-494c-a87f-bb87ec5c7f56.png">

As we can see, by removing the ninth graders from Thomas High School, every category except for the average reading score among the district dropped, with the highest being by 0.3%.

### How the School Summary was Affected
- The Original Analysis
<img width="823" alt="Screen Shot 2022-11-06 at 11 46 46 PM" src="https://user-images.githubusercontent.com/107594280/200254050-b1002afa-ff56-46af-bc80-de7e1fab50e3.png">

- After Changing the Thomas High School Grades
<img width="723" alt="Screen Shot 2022-11-07 at 12 17 26 AM" src="https://user-images.githubusercontent.com/107594280/200259836-ff6817bf-bd5e-4598-bd97-953d8cafef46.png">

There was also little impact on the overall School Summary once the ninth graders from Thomas High School were not taken into consideration.

### How Replacing the Ninth Graders' Scores affected the School's Performance Relative to Other Schools
Looking at the School Summary, we can see that replacing the scores did little in terms of its standing relative to other schools in the district. This is not a surprise, since removing the ninth graders did little to the actual metrics of the school itself. At first when we had replaced the ninth graders' scores with NaNs, the percentages for the scores had dropped drastically, with some being in the 60% range (as seen below). Once we had removed the ninth grade from our data set, the percentages went back up and showed little difference.

<img width="716" alt="Screen Shot 2022-11-07 at 12 34 34 AM" src="https://user-images.githubusercontent.com/107594280/200263148-e8606568-c84d-439e-aec9-31cb898f6547.png">

### How Replacing the Ninth Graders' Scores Affected:
#### Math and Reading Scores By Grade
Replacing the ninth graders' score did not affect the math and reading scores because we had gotten rid of them in the final analysis.

#### Scores By School Spending
Replacing the ninth graders' score showed us the same information as it did in the original analysis. Overall there was little change in the $631-645 range at .1%

#### Scores By School Size
When looking at school size as the factor, we can see that replacing the ninth graders' scores also created little change. The "Medium" category that Thomas High School falls into only had a change of .1%

#### Scores By School Type
The scores by school type presented no change when the ninth graders' scores were removed. Thomas High School is a Charter School, and both before and after the updated analysis presented the same numbers rounded to the nearest tenths place. 

## Summmary 
Overall, removing the ninth graders score did little to Thomas High School's overall ranking and test scores. When looking at the overall district, the percentage of students who passed reading was affected the most from the removal going from a 86% to a 85.7%. All other changes for the district were a less than .3% decrease. When looking solely at Thomas High School, all three percentages dropped at a .5% decrease or less. The average scores also dropped at .1% or less. We also see little change when looking at factors such as school spending, school size, and school type -- which all showed a decrease of only .1% or less. Despite the removal of the ninth grade due to academic misconduct, the high school remains in second place in the school district. 
