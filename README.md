# Final-Project: Analysis of Colleges in the U.S
## By Miranda Calacsan

*The datasets I will be looking at are the salaries_by_college_type and salaries_by_region* 

### Data Analysis Process
1. How does each school type rank in starting median salaries? (Highest starting salary to lowest by average)
2. Which region of the U.S has the highest average of the median starting salary?
3. What is the percent change of the from starting median salary to mid-career median salary of liberal arts schools? (Dollar amount)
4. What is the average mid-career salary of people that graduated from Ivy League schools? 
5. What is the average starting median salary of party schools and how does it compare to the average starting median salary of engineering schools?

#### STEPS OF EACH QUESTION
_**Question 1: How does each school type rank in starting median salaries? (highest - lowest by average)**_ <br>
1. Create a pivot table of the salaries_by_college_type dataset
2. Set the Rows function to "School Type" <br>
!['Question 1 Step 2', 'Step 2'](/Q1_step2.png)
3. Set the Values function to "Starting Median Salary" and select "AVERAGE" <br>
!['Question 1 Step 3', 'Step 3'](/Q1_step3.png)
4. Get pivot table and answer

_**ANSWER**_ : Ivy League, Engineering, Liberal Arts, Party, State (highest - lowest) <br>

_**Question 2: Which region of the U.S has the highest average of the median starting salary?**_
1. Create a pivot table of salaries_by_region dataset
2. Set the Rows function to "Region" <br>
!['Question 2 Step 2', 'Step 2'](/Q2_step2.png)
3. Set the Values function to "Starting Median Salary" and select "AVERAGE" <br>
![Question 2 Step 3', 'Step 3'](/Q2_step3.png)
4. Get pivot table and answer

_**ANSWER**_ : California with $51, 032.14 as the average starting salary

_**Question 3: What is the average percent change of the starting median salary to mid-career median salary of liberal arts schools? (Dollar amount) **_
1. Create filter of just liberal art schools from the salaries_by_college_type dataset <br>
!['Question 3 Step 1', 'Step 1'](/Q3_step1.png)
2. Turn off filter and find the percent change in a new column of the data set <br>
!['Question 3 Step 2', 'Step 2'](/Q3_step2.png)
3. Create a pivot table and filter only liberal arts schools
4. Set the Values function to "PCHANGE_1.0" and get answer <br>
!['Question 3 Step 4', 'Step 4'](/Q3_step4.png)

_**ANSWER**_ : The average percent change in dollar amount is $89,278.72 from liberal arts schools

_**Question 4: What is average mid-career salary of people that graduated from Ivy League schools?**_
1. Create a pivot table of the salaries_by_college_type dataset
2. Set the Rows function to "School Type"
3. Set the Values function to "Mid-Career Starting Salary" and select "AVERAGE" <br>
!['Question 4 Step 3', 'Step 3'](/Q4_step3.png)
4. Add a filter for "School Type" and select "Ivy League" only
5. Get answer <br>
![Question 4 Step 4', 'Step 4'](/Q4_step4.png) 

_**ANSWER**_ : The average mid-career salary of Ivy League graduates is about $120,125

_**Question 5: What is the average starting median salary of party schools and how does it compare to the average starting median salary of engineering schools?**_
1. Create a pivot table of the salaries_by_college_type dataset
2. Set the Rows function to "School Type" 
3. Set the Values functuin to "Starting Median Salary" and select "AVERAGE"
4. Add a filter for "School Type" and select "Party" 
5. Get median average starting median salary of party schools which is $45,715
!['Question 5 Step 5', 'Step 5'](/Q5_step5.png)
6. Change filter for "School Type" to "Engineering"
7. Get median average starting median salary of engineering schools which is $59,057
!['Question 5 Step 7', 'Step 7'](/Q5_step7.png)

_**ANSWER**_ : Engineering schools have a higher median starting salary than party schools



### Data Visualization

### Story Summary
