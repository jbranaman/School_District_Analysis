# School_District_Analysis
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
  * Math and reading scores by grade
   * The average math and reading scores by grade are impacted only for ninth grade scores of Thomas High School. They instead show NaN versus the original average scores.
#### Original Average 9th Grade Math and Reading Scores
<img width="1107" alt="Module Average 9th Grade Math Scores" src="https://user-images.githubusercontent.com/96451672/151671472-5f2bad61-ff52-4cdd-b4dd-159d03a5211f.png"> <img width="1106" alt="Module Average 9th Grade Reading Scores" src="https://user-images.githubusercontent.com/96451672/151671483-44d750fe-9694-4831-a015-cb930921b78e.png">

#### Updated Average 9th Grade Math and Reading Scores
<img width="1113" alt="Updated Average 9th Grade Math Scores" src="https://user-images.githubusercontent.com/96451672/151671505-79ef5466-3a3e-472b-b2a1-15e5a4791f07.png"> <img width="1108" alt="Updated Average 9th Grade Reading Scores" src="https://user-images.githubusercontent.com/96451672/151671510-99b38c36-83dd-409a-b78f-4e3aea855515.png">


  * Scores by school spending
  * Scores by school size
  * Scores by school type
