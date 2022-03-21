
# Project 1: Standardized Test Analysis  
  
## Problem Statement  
  
*The College Board released a new format of the SAT in March 2016 with the hope that the new format would be more connected to the work done in high school classrooms **(1)**. This project will explore trends in SAT and ACT participation from 2017-2019 across the United States and seeks to identify states that have decreasing SAT participation rates as opportunity areas for the SAT College Board.*    
  
    
## File Directory/table of contents  
* README.md   
* starter_code_morgan.ipynb  
* data  
    * cleaned data  
        * df_act_all_columns.csv    
        * df_act.csv  
        * df_sat_all_columns.csv  
        * df_sat.csv  
    * original data  
        * act_2017.csv  
        * act_2018.csv  
        * act_2019.csv  
        * sat_2017.csv  
        * sat_2018.csv  
        * sat_2019.csv  
* presentation  
    * project_1_presentation.pdf  
  
## Data and Data Dictionary  
Data Sources:  
* [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State  
* [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State  
* [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State  
* [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State  
* [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State  
* [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State  
The above data sources have been provided by General Assembly instructors.  

Each ACT dataset listed directly above includes information on ACT participation, ACT composite scores (2017 data includes scores by test section - English, Math, Reading, Science), and each piece of information is listed by state (all 50 states including Washington DC and national information).    

Each SAT dataset includes information on SAT participation, SAT scores by test section (Evidence-Based Reading and Writing, and Math) and a total score, and each piece of information is listed by state (all 50 states including Washington DC, and the 2019 data includes US territories).   

Features contained in the final csv's:  

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|df_act|The physical body that represents each of the states and single district of the United States| 
|2017_participation|float|df_act|The percent of high school aged students eligible to take the ACT exam in the year 2017| 
|2018_participation|float|df_act|The percent of high school aged students eligible to take the ACT exam in the year 2018| 
|2019_participation|float|df_act|The percent of high school aged students eligible to take the ACT exam in the year 2019|
|state|object|df_sat|The physical body that represents each of the states and single district of the United States| 
|2017_participation|float|df_sat|The percent of high school aged students eligible to take the SAT exam in the year 2017| 
|2018_participation|float|df_sat|The percent of high school aged students eligible to take the SAT exam in the year 2018| 
|2019_participation|float|df_sat|The percent of high school aged students eligible to take the SAT exam in the year 2019| 
    
## Executive Summary  
*The data from 2017, 2018, and 2019 shows that the ACT is losing populaity and the SAT is gaining popularity among test takers. There's a negative correlation between participation in the ACT vs. SAT for each state, revealing that most people prefer to take one test over taking both. Certain states that offer free testing for one test verse another, have high participation rates (at or near 100%) for the test that's offered at no charge. In these states, the more popular test is the free one.*  
  
*I didn't find any states with a significant decrease in SAT participation. In fact, many states had increasing participation in the SAT from 2017 to 2019. One state did stand out as an obvious candidate for growing the SAT. That state is Alaska! Coupled with research, it's obvious that there's room to grow the SAT in Alaska because there's a low awareness of testing in the state, there are barriers to physically access and pay for testing, and Alaska regularly has the lowest or one of the lowest college-going rates in the US.*  
  
## Conclusions and Recommendations  
*My recommendation to the College Board is to work with Alaska to offer free and accessible testing to increase SAT rates in the state. The College Board is “dedicated to promoting excellence and equity in education” and Alaska is a great state for expanding this mission.*  


## Sources
**(1):** https://www.cnn.com/2014/03/05/living/sat-test-changes-schools/index.html  
**(2):** https://about.collegeboard.org/  
**(3):** https://www.collegeraptor.com/getting-in/articles/act-sat/states-act-sat-given-free/  
**(4):** http://www.higheredinfo.org/dbrowser/?year=2018&level=nation&mode=data&state=&submeasure=63  
**(5):** https://www.alaskapublic.org/2021/04/06/ fewer-alaskan-students-qualifying-for-or-using-state-scholarship-fund-review-finds/  