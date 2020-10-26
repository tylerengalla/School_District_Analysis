# School_District_Analysis

# Overview 
The school board has suspected academic dishonesty from 9th graders at Thomas High School. To uphold school testing standards we must go in and remove the math and reading scores for Thomas High School 9th graders while keeping the rest of the data intact. Then perform a new round of anlalysis where we account for the removal of those grades and how it affects:

- The district summary
- The school summary
- The top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score for each grade level from each school
- The average rading score for each grade level from each school
- The scores by school spending per student, by school size, and by shcool type 

# Results
- **How is district summary affected?**

- Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing decreased 
  
  - Original Results
  
  ![](/original_district_summary.png)
  
  - Revised Results 
  
  ![](/revised_district_summary.png)

- **How is the school summary affected?**

  - No other school than Thomas High School was affected. But within THS you can see that Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing all decreased, while Average Reading Score actually increased. 
  
  - Orginal Restuls
  
  ![](original_school_summary.png)
  
  - Revised Results 
  
  ![](revised_school_summary.png)

- **How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?**

  - Unchanged - accounting for the scandal and removing those scores kept Thomas High School as the second best performing school. 


- **How does replacing the ninth-grade scores affect the following**:
  - Math and reading scores by grade
    - Scores remain the same for all schools except for 9th Graders at THS where their score is now represented by "nan"
  - Scores by school spending
    - Unchanged 
  - Scores by school size
    - Unchanged 
  - Scores by school type
    - Unchanged
  
  # Summary
  The overall results of removing the 9th grade scores from Thomas High School largely left much unchanged. It did however affect the overall school district report when it came to: Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing. Decreasing all of them ever so slightly.  
  
