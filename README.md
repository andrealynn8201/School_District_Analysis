# School_District_Analysis
Testing analysis with Pandas and Jupyter Notebook

## PyCitySchools Updated Report

### Overview of Ask
Due to evidence of academic dishonesty, the school board decided to remove math/reading scores of Thomas High School’s 9th graders using NaN, and repeat the analysis previously done, with the updated data.

### Results
I was asked to replace all the reading and math grades with NaN, which means Not a Number.  It doesn’t have a value, so you can’t do anything with it.  Because of this, the data didn’t change in any significant way. If you look at the screen shot below (and any of the future screen shots), the top page is the updated data, and the page underneath, at the bottom, is the original data that was collected.

![Screen Shot 2021-12-19 at 10 39 19 PM (2)](https://user-images.githubusercontent.com/93801125/146805216-db818b44-2c18-42ac-8712-87d608f26c3c.png)

In the district summary, there is minimal effect to the scores or overall percentages. In face, if we were to format and round to the nearest whole number, as was done in the first analysis, there seems to be no change at all, except in Average Math Score.

In the next screen shot, where both pages meet, you can see a slight change in Thomas High Schools. Not even a 0.5% drop in averages.  In fact, the Average reading score even goes up, but not by much.

![Screen Shot 2021-12-19 at 10 15 14 PM (2)](https://user-images.githubusercontent.com/93801125/146805293-980cdd2d-7cc9-4c41-8c18-7ad190003904.png)

By replacing the math and reading scores with NaN, and the minimal affect it had on the overall view of the data, Thomas High School is still in the top schools in the district, at Number 2!

![Screen Shot 2021-12-19 at 10 15 48 PM (2)](https://user-images.githubusercontent.com/93801125/146805330-ef0e9fab-609a-4a3b-9d57-f58733ff716d.png)

Since we only replaced the Math and Reading scores, and no other data was changed (including how many students were represented at Thomas High School), all other data sets remain the same and were not changed in any way. 

* Math and reading scores by grade were all represented independently by each school and not as a whole district. 
* Scores by school spending still counted on the total number of students at each school. So there was no decrease in spending since there wasn’t a decrease in students.  
*  The total students was never changed, as that would have caused red flags if each student that is recorded in the school was not represented. So all 9th grade information is intact, except the math and reading scores.
* Scores by school type, district vs charter, remains relatively the same.  District schools had no impact as Thomas High School was a charter school.  Since the scores changes were so minute, it had no impact, as seen here:

![Screen Shot 2021-12-19 at 10 11 14 PM (2)](https://user-images.githubusercontent.com/93801125/146805366-a6f4fe59-e37f-46c0-819c-e7eb66234e94.png)

### Summary
If zeros were placed instead of NaN’s the data would have changed dramatically.  Approximately 1/4 of the high school’s scores would have given the school of no more than 75% scores.  That wouldn’t have been a fair representation to the other grades, who had no reporting of misconduct.  Also, it would have affected skewed the overall district data as a quarter of a 15th of schools would have failed.  By using NaN, it allowed all other data to remain in tact.  This allowed the school board to see just how big of a problem they were facing by seeing how drastic the change was.  Since it was minimal, the students who falsified their grades was a minimal number, and had a practically insignificant change to the school, and the district as a whole.
