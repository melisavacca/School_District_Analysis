# School_District_Analysis

## Overview of School District Analysis
We are continuing to help Maria and the school board sort, organize, and analyze the standardized tests scores and funding from the high schools in a city school district. 


### Purpose
Our purpose is to show trends in the data to present to the school board to help them make decisions regarding the school budgets and priorities. We are able to find the overall passing 
percentage and average on standardized tests in math and reading for each school in relation to the size of the school and the school budget.  To do academic dishonesty in reading and math scores 
of ninth graders at Thomas High School, the original analysis skewed.  We replaced these scores with NaNs but kept the rest of the data intact.  Once we repalced these specific scores, we repeated
the entire analysis and reflected on the effects. 

## Analysis and Challenges

- How is the district summary affected?

The average math score, average reading score, % passing math, % passing reading, and % overall passing all slightly decreased with the adjustments in the data and the addition of the NaNs.

Original distrct summary:

![image](https://user-images.githubusercontent.com/64279232/126576095-e6a4649d-7b52-421c-bb7b-0b9d0296c117.png)

Adjusted district summary:

![image](https://user-images.githubusercontent.com/64279232/126575962-cff82e84-e277-4f0a-8a0e-e14e468e6569.png)




- How is the school summary affected?  How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

The summary for every school remained the same with the excpetion of Thomas High School.  The average reading and math scores and passing rates decreased slightly.

Original School Summary:

![image](https://user-images.githubusercontent.com/64279232/126576419-bae115db-c55f-4dc6-b0cf-5488ad501352.png)

Adjsuted School Summary for Thomas High School:

![image](https://user-images.githubusercontent.com/64279232/126576867-76a933a4-5c6c-424c-8cf2-4c3c02895c51.png)



- How does replacing the ninth-grade scores affect math and reading scores by grade?

The math and reading scores by grade did not change for any school besides Thomas High School. 

Math scores for top 5 schools:

![image](https://user-images.githubusercontent.com/64279232/126577164-7cf9cb20-5d44-44e4-96b9-72b670d50878.png)

Reading scores for top 5 schools:

![image](https://user-images.githubusercontent.com/64279232/126577189-c4c1592b-f04d-4e63-b3ab-7d922b4209ba.png)



- How does replacing the ninth-grade scores affect scores by school spending?

The scores based on student spending stayed the same for every category excpet for the $630-644 spending range per student category.  This is also the category that Thomas High School falls under, demonstarting that the change was due to the adjustments in the data with this particular school. The passing percentages slightly decreased. 

Before:

![image](https://user-images.githubusercontent.com/64279232/126577457-c20aca0d-2cac-4ac6-b2f0-9055a472a0fc.png)

After:

![image](https://user-images.githubusercontent.com/64279232/126577476-06346668-3dd0-49af-9ded-fb0cf37ca265.png)



- How does replacing the ninth-grade scores affect scores by school size?

The small and large schools had no change, but the medium schools decreased slightly.  Thomas High School falls under the medium school category, again causing a change in the data.

Before:

![image](https://user-images.githubusercontent.com/64279232/126577612-a3f7c3a4-908b-475a-82d9-543818a93b7a.png)

After:

![image](https://user-images.githubusercontent.com/64279232/126577624-f91e2b28-36a1-47d8-981f-60615ded9604.png)



- How does replacing the ninth-grade scores affect scores by school type?

District data stayed the same and charter data decreased slightly, again, due to Thomas High School being a charter school.

Before:

![image](https://user-images.githubusercontent.com/64279232/126577738-17cd7e2f-98e8-474a-bca9-83540ffac6ae.png)

After:

![image](https://user-images.githubusercontent.com/64279232/126577753-bd7ec5a9-2e76-44b3-8a19-3aadc6773c99.png)



## Summary
As described above, there were slight changes in the data including Thomas High School due to the reading and math scores for 9th graders being replaced with NaNs.  Because these replaced scores were quite high, once they were removed, the data for math and reading scores decreased for the new analysis.  Below are some examples:

1. The overall passing rate for Thomas High School decreased from 90.948012% to 90.630324%. 
2. The % Passing Math scores decreased from 73.484209% to 73.462589% for schools with a spending range from $630-644 per student.
3. The % Passing Reading scores decreased from 96.790680% to 96.732654% for medium sized schools (1000-2000 students).
4. The overall passing rate for charter schools decreased from 90.432244% to 90.392533%.
