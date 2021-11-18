# PyCitySchools

## Overview
The purpose of this analysis is to determine whether or not the omission of math and reading scores for ninth graders attending Thomas High School affects the school’s academic standing.

## Results
The school board reported a suspicion of dishonesty amongst the ninth-grade students of Thomas High School. The first portion of the analysis, found in the file PyCitySchools, includes all of the student data from each school. The second portion of the analysis, found in PyCitySchools_Challenge, features the same structure, only the ninth-grade students have been omitted. 

- How is the district summary affected?
  - The overall passing percentage for the district fell to 64.9%
  - <img width="900" alt="Overall Passing Original" src="https://user-images.githubusercontent.com/85713470/142332224-0b024a0d-6dfc-432e-bb58-5c4fdc7af7e5.png">
  - <img width="900" alt="Overall Passing Updated" src="https://user-images.githubusercontent.com/85713470/142332248-61475126-1849-45e6-b48d-81aa82819b0c.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  - The top five performing schools still included Thomas High School, even with the ninth-grade students omitted.
  - <img width="900" alt="Top 5 Schools Original" src="https://user-images.githubusercontent.com/85713470/142332369-68933109-c7aa-42d9-976d-afbba00643c4.png">
  - <img width="900" alt="Top 5 Schools Updated" src="https://user-images.githubusercontent.com/85713470/142332380-a5bd8ac4-b311-436d-b2bb-1a893a72155e.png">

- How does replacing the ninth-grade scores affect the following:
  - Scores by school spending: The analysis found that performance in schools is not dependent on spending; removing the ninth-grade students did not impact the result. 
  - <img width="867" alt="Spending original" src="https://user-images.githubusercontent.com/85713470/142332660-2d2d3aa3-bc38-4a37-9608-2de39e7ffe25.png">
  - <img width="873" alt="Spending Updated" src="https://user-images.githubusercontent.com/85713470/142332681-fa047ac8-56e6-4b78-a866-6f71749e930e.png">
 
  - Scores by size: In both of the analyses, students performed better in smaller schools; removing the ninth-graders did not impact the result. 
  - <img width="801" alt="Size Original" src="https://user-images.githubusercontent.com/85713470/142332723-0a7a7550-499f-485f-a776-b9b0b0cac903.png">
  - <img width="803" alt="Size Updated" src="https://user-images.githubusercontent.com/85713470/142332776-0609640f-4237-4325-8984-2177ad6b5dc7.png">
  
  - Scores by type: Charter schools did perform better than district schools, and like the above, removal of the ninth-grade students did not have an impact.
  - <img width="752" alt="Type Original" src="https://user-images.githubusercontent.com/85713470/142332851-89c1d658-510f-4019-b506-cfbf652b172d.png">
  - <img width="750" alt="Type Updated" src="https://user-images.githubusercontent.com/85713470/142332836-f490e006-de68-4ae4-b68a-7cdc806fa1ff.png">

    
## Summary
Although the purpose of the analysis was to determine whether or not academic dishonesty impacted Thomas High School's standing, it appears that the difference between the original findings and those after removing the ninth-grades are within 1-2% of eachother. Additionally, removing the grade from the data set did not significantly impact any of the other performance metrics including school capita, size and type of school. Also, Thomas High School remained in the top 5 performing schools in both analyses. 
