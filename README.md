# School_District_Analysis

## Overview: 
There is reason to believe there has been academic dishonesty regarding the testing scores for reading and math for the ninth graders at Thomas High School. This analysis sets to uphold state-testing standards by replacing all the reading and math test scores for this demographic with NaN results. A repeat school district analysis will need to be completed with the new data. 

## Results: 
* How is the district summary affected?
  *  District Summary: Original <img width="903" alt="Original_school_district" src="https://user-images.githubusercontent.com/106630710/188328130-f7a950e6-e425-4f67-b077-6c114478c4c0.png">
  *  District Summary: Updated <img width="921" alt="updated_district_analysis" src="https://user-images.githubusercontent.com/106630710/188328195-611be101-7ba3-4ca8-9174-29f48e4508a0.png">
  *  The effect that changing all the Ninth-Grade test scores to NaN did not greatly impact the District Analysis. The test scores in question are a small portion of the overall student population and minutely change the average. 

* How is the school summary affected?
  * School Summary: Original <img width="996" alt="school_summary_original" src="https://user-images.githubusercontent.com/106630710/188328283-c393e8e1-71d5-4bc3-8f5c-3b7c7daf57b1.png"> 
  * School Summary: Updated <img width="995" alt="school_summary_update" src="https://user-images.githubusercontent.com/106630710/188328316-d0d56f85-447a-40f1-8c66-94af175cab70.png">
  * Overall, the School Summary was not affected other than a small change in averages for Thomas High School. 

* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Thomas High School: Original <img width="991" alt="original_top_five" src="https://user-images.githubusercontent.com/106630710/188328377-87057d80-7f4b-4242-acef-4686cca5f6d8.png">
  * Thomas High School: Updated <img width="992" alt="update_top_five" src="https://user-images.githubusercontent.com/106630710/188328394-8bcafe3e-32fe-4ca8-99a8-f444e39aadb4.png">
  * Changing the questionable test results to NaN values did not change ranking for Thomas High School. 

## How does replacing the ninth-grade scores affect the following:
* Math and Reading Scores by Grade
  * Math Scores by Grade: Original <br>
    <img width="291" alt="original_math_by_grade" src="https://user-images.githubusercontent.com/106630710/188328696-606e18ed-1986-461f-b338-9204965bc121.png">
  * Reading Scores by Grade: Original <br>
    <img width="286" alt="original_reading_by_grade" src="https://user-images.githubusercontent.com/106630710/188328718-1ca7fa18-18d8-478e-8088-5f909c039700.png">
  * Math Scores by Grade: Update <br> 
    <img width="301" alt="update_math_by_grade" src="https://user-images.githubusercontent.com/106630710/188328737-3517ff8b-042f-4326-9923-3ebf4faf3ca1.png">
  * Reading Scores by Grade: Update <br> 
    <img width="305" alt="update_reading_by_grade" src="https://user-images.githubusercontent.com/106630710/188328750-487db838-aca9-4386-94a8-12e17533ba39.png">
  * The only difference seen is that there are now NaN values for 9th graders. 
  
* Scores by School Spending
  * School Spending: Original <br>  
   <img width="823" alt="original_spending" src="https://user-images.githubusercontent.com/106630710/188328857-b6b126e1-3b41-4618-8e66-5c4309142414.png"><br>
  * School Spending: Update <br>
    <img width="828" alt="update_spending" src="https://user-images.githubusercontent.com/106630710/188328859-8ee4040d-deb0-4c0b-919f-406c34e2baea.png">

* Scores by School Size
  * School Size: Original <br>
    <img width="749" alt="original_size" src="https://user-images.githubusercontent.com/106630710/188328945-aff090ef-2bb0-484e-9441-3396f6f0eabf.png">
  * School Size: Update <br>
    <img width="745" alt="update_size" src="https://user-images.githubusercontent.com/106630710/188328946-7f377825-4a97-4fcf-ab24-86e037cae9fa.png">

* Scores by School Type
  * School Type: Original <br>
    <img width="708" alt="original_type" src="https://user-images.githubusercontent.com/106630710/188328997-14398e45-bb3e-48d1-9ceb-4427dffe076c.png">
  * School Type: Update <br>
    <img width="704" alt="update_type" src="https://user-images.githubusercontent.com/106630710/188329001-54ff6806-9422-4d8e-b9fd-b6c3a49ac7d7.png">

## Summary: 
1. The changes brought forth from updating the Ninth-Grade reading and math scores with NaN values are insignificant. 
2. The changes did not affect the rankings of the schools. 
3. The changes are less than 0.1% overall.
