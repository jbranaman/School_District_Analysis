# School District Analysis
## Overview of Project
This is an updated analysis of school district data to evaluate school performances.
### Purpose
This report presents an updated analysis of high-level snapshot of the district's key metrics and an overview of the key metrics for each school with ninth graders’ math and reading scores at Thomas High School replaced with null values. Below is the code replacing the ninth graders' scores at Thomas High School with null values.
<img width="1106" alt="Thomas High School Grade Replacement Code" src="https://user-images.githubusercontent.com/96451672/151669853-58454431-7b28-440f-ab94-b278295e2e7d.png">

## Results
* How is the district summary affected?
  * The average math & reading scores were slightly affected by lowering the scores along with the overall passing percentage. The overall passing percentage dropped from 65.2% to 64.9%.
#### Original District Summary
<img width="1130" alt="Module District Summary" src="https://user-images.githubusercontent.com/96451672/151669256-e5f33afd-ec00-422a-8930-a26f93d67256.png">

#### Updated District Summary
<img width="1100" alt="Updated District Summary" src="https://user-images.githubusercontent.com/96451672/151669260-f9512236-2bf7-4b2e-8395-502196cdc216.png">

* How is the school summary affected?
  * The affect on the school summary is a large adjustment in the reading and math passing percentages and consequently the overall passing percentage for Thomas High School. The overall passing percentage for Thomas High School dropped from 90.94% to 65.07%.
#### Original School Summary
<img width="1103" alt="Module School Summary" src="https://user-images.githubusercontent.com/96451672/151669738-53da8778-9123-4a6d-852f-982d03bbfc30.png">

#### Updated School Summary
<img width="1099" alt="Updated School Summary" src="https://user-images.githubusercontent.com/96451672/151669745-8b651d24-17fa-4ab8-9a5d-b06757846313.png">

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Replacing the ninth graders’ math and reading scores at Thomas High School adjusts the school's performance from being a top 5 school relative to the other schools to being towards the bottom.
#### Original Top 5 Schools
<img width="1112" alt="Module Top 5 Schools" src="https://user-images.githubusercontent.com/96451672/151670757-dc1ff77d-06ef-4888-a9eb-fda9e5c48093.png">

#### Updated Top 5 Schools
<img width="1114" alt="Updated Top 5 Schools" src="https://user-images.githubusercontent.com/96451672/151670763-6bf4457f-23b3-4e06-8667-9a96619878e5.png">

* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade: The average math and reading scores by grade are impacted only for ninth grade scores of Thomas High School. They instead show NaN versus the original average scores. The original average math score was 83.59 and the original average reading score was 83.72.
  * Scores by school spending: The scores by school spending were impacted in the $630-644 per student range with the overall passing percentage adjusting originally from 63% to 56%.
  * Scores by school size: The scores by school size were impacted in the medium (1000-2000) range with the overall passing percentage adjusting originally from 91% to 85%.
  * Scores by school type: The scores by school type were impacted in the charter school type with the overall passing percentage adjusting originally from 90% to 87%.

## Summary
Replacing the ninth grade math and reading scores for Thomas High School affected performance in a variety of different areas. The overall performance of the district was impacted slightly dropping the overall passing percentage by .3%. The school summary was greatly impacted by showing Thomas High School overall passing percentage dropping by 25.87%. The performance for Thomas High School relative to other schools dropped greatly where originally they were a top 5 school but instead adjusted to being a school in the lower half. This ultimately impacted all the additional metric groupings of scores by spending, size and type dropping overall passing percentages between 3-6%.
