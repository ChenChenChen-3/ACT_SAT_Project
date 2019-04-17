1. Problem Statement:<br>
SAT Test and ACT Test are the keys for high school student approach college and career path which make the tests essential. College Board, the organization that creates SAT Test, believed the test can help the student better understand their ability and approach to the ideal major. In 2018, more than 2 million students in the class took the test. <br>
Therefore, the goal of this project is to know how to improve the participation rate of the SAT Test. Based on the analysis, visualize data, and do some research. We will be able to seek for the possible issue and find the solutions.   


2. Data Dictionary

|Feature              |Type    |Dataset |Description|
|---------------------|--------|------- |-----------|
|participation_sat17  |float   |SAT 2017|The probability of participation rate of SAT Test Score for each state.|
|reading_writing_sat17|float   |SAT 2017|Evidence-Based Reading and Writing Section Score of 2017 SAT Test for each state.|  
|math_sat17           |float   |SAT 2017|Math Section Score of 2017 SAT Test for each state.|
|total_sat17          |float   |SAT 2017|Total Score of 2017 SAT Test for each state.|
|participation_act17  |float   |ACT 2017|The probability of participation rate of ACT Test Score for each state.|
|english_act17        |float   |ACT 2017|English Section Score of 2017 ACT Test for each state.|
|math_act17           |float   |ACT 2017|Math Section Score of 2017 ACT Test for each state.|
|reading_act17        |float   |ACT 2017|Reading Section Score of 2017 ACT Test for each state.|
|science_act17        |float   |ACT 2017|Science Section Score of 2017 ACT Test for each state.|
|total_act17          |float   |ACT 2017|Total Score of 2017 ACT Test for each state.|
|xxx_xxx18            |---     |SAT 2018|Infomation of Tests hold in 2018 for each state.|

3. Executive Summary <br>
- Methodology
    Collecting the data is first to do. Secondly, clean the data by identify the missing data, remove the unnecessary line, correct the errors, and change the data types for forward merge and analyze. Third, visualize the data. Finally, make conclusion based on what I found.  
- Issues encountered
    Missing data, incorrect data type, unnecessary columns/rows are the issues happened.  
- Results
    Overcome the issues and find some possible problems and answers. 
    
4. Final Conclusions & Recommendations<br>
**Conclusions**<br>
SAT test has increased in the past year, due to the policy change since 2016. It is helpful to improve the participation rate by continuously release benefit, working with high school for pretest project, and test in student's own school.     

**Recommendations**<br>
- The SAT should sign the contract with more states. The purpose increases the participation rate and reduces the abnormal high score for those states that have participation rate lower than 5%. 
- SAT test holds on Saturday, but some of the students are busy on the weekend. It might be helpful to change the test day to the normal school day.
- Push college to accept both SAT and ACT and cooperate with high school country wild. Most students choose to take the test based on what college required, what the teacher recommends and what his/her classmate taking. 

5. Source Documentation

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- https://docs.google.com/spreadsheets/d/1r27abreGHAWh-7_IWJeHoEzjKAJtzuxxHSmDRTc8Ykk/edit#gid=0
(./data/sat_2018.csv)  (./data/act_2018.csv)
- Zhang, D. (2019). Average SAT & ACT Scores by State (Participation Adjusted). Blog.prepscholar.com. Retrieved 8 March 2019, from https://blog.prepscholar.com/average-sat-and-act-scores-by-stated-adjusted-for-participation-rate
-(Six Reasons Not To Get Excited About The New SAT Scores. (2019). Forbes.com. Retrieved 8 March 2019, from https://www.forbes.com/sites/petergreene/2018/10/25/six-reasons-not-to-get-excited-about-the-new-sat-scores/#7f5064395b0d)
- (Genota, L. (2019). SAT Scores Rise as Number of Test-Takers Tops 2 Million. Education Week. Retrieved 8 March 2019, from https://www.edweek.org/ew/articles/2018/10/31/sat-scores-rise-as-number-of-test-takers.html)
- Important Dates. (2016). SAT Suite of Assessments. Retrieved 11 March 2019, from https://collegereadiness.collegeboard.org/sat-subject-tests/important-dates 
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_csv.html
- https://stackoverflow.com/questions/32400867/pandas-read-csv-from-url
- https://www.w3schools.com/python/python_lambda.asp
- https://www.geeksforgeeks.org/difference-between-map-applymap-and-apply-methods-in-pandas/
- https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Working%20With%20Markdown%20Cells.html
- https://pandas.pydata.org/pandas-docs/stable/user_guide/merging.html
- https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.merge.html
- https://www.geeksforgeeks.org/saving-a-pandas-dataframe-as-a-csv/
- https://matplotlib.org/users/pyplot_tutorial.html#working-with-multiple-figures-and-axes
- https://www.mathsisfun.com/data/standard-deviation-formulas.html
- https://stackoverflow.com/questions/34706845/change-xticklabels-fontsize-of-seaborn-heatmap
- https://matplotlib.org/api/_as_gen/matplotlib.pyplot.hist.html
- https://matplotlib.org/api/_as_gen/matplotlib.pyplot.scatter.html#matplotlib.pyplot.scatter
- https://seaborn.pydata.org/generated/seaborn.pairplot.html
- https://en.wikipedia.org/wiki/List_of_regions_of_the_United_States
- https://matplotlib.org/api/_as_gen/matplotlib.pyplot.pie.html