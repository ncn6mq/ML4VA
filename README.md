# ML4VA

The FinalReport.csv file contains the predictions for each school in Virginia that we were able to find data for.

The ML4VA-final.ipynb notebook contains most of the analysis used to generate the that final report.

All other files contain intermediate steps.


**Description of Variables**

Div Name: The name of the school district.
Div Num: The Virginia Department of Education's ID for the school district.
Sch Name: The CamelCase, unpunctuated name of the School
Sch Num: The Virginia Department of Education's ID for the school name.
Sch Type: One of Elementary, Middle, High, or Combined
Low Grade: The lowest grade served by the school
High Grade: The highest grede served by the school
Subject: Which core area test the pass rate is being reported for
Subgroup: Which demographic subgroup the pass rate is being reported for
2016-2017 Pass Rates: Pass Rate on the sol test for the listed subject and subgroup in the 2016-2017 school year
2017-2018 Pass Rates: Pass Rate on the sol test for the listed subject and subgroup in the 2017-2018 school year
2018-2019 Pass Rates: Pass Rate on the sol test for the listed subject and subgroup in the 2018-2019 school year
Salary2017Dist: The average salary teachers receive in that school district for the 2016-2017 school year
Salary2018Dist: The average salary teachers receive in that school district for the 2017-2018 school year
PopulationDist: The population of the school district
MedianageDist: The median age of the school district
PercentWhiteDist: The percentage of people in the school district that identify their race as 'white'
PercentBlackDist: The percentage of people in the school district that identify their race as 'black'
PercentAsianDist: The percentage of people in the school district that identify their race as 'asian'
PercentLatinoDist: The percentage of people in the school district that identify their race as 'latino'
HighSchoolGraduateDist: The percentage of people in the school district that claim to have graduated high school
SomeCollegeDist: The percentage of people in the school district that claim to have received some college
AssociatesDist: The percentage of people in the school district that claim to have earned an associates degree
BachelorsDist: The percentage of people in the school district that claim to have earned a bachelors degree
GraduateDist: The percentage of people in the school district that claim to have earned a graduate degree
MedianIncomeDist: The median income of the district
DistrictCity: The city which the district is located within, if applicable
Latitude: Latitude of the school
Logitude: Longitude of the school
Rating: The rating given by greatschools.com
PercentLowIncome: The percent of low income students in the school
Enrollment: The number of students enrolled in the school
ParentRating: The number of stars given to the school by parents on greatschools.com (0-5 scale)
NumReviews: The number of reviews the school received on greatschools.com
PercentAsianSch: The percentage of students in the school that identify their race as 'asian'
PercentBlackSch: The percentage of students in the school that identify their race as 'black'
PercentHispanicSch: The percentage of students in the school that identify their race as 'hispanic'
PercentWhiteSch: The percentage of students in the school that identify their race as 'white'
PercentMultiethSch: The percentage of students in the school that identify their race as more than one race
PercentNativeSch: The percentage of students in the school that identify their race as 'native american'
StudentsPerTeacher: The number of students at the school divided by the number of teachers at the school
PercentIslanderSch: The number of students at the school that identify their race as 'Pacific Islander'
MissingRatio: 1 if StudentsPerTeacher variable was originally NA, 0 otherwise
MissingEnrollment: 1 if Enrollment variable was originally NA, 0 otherwise
Predicted: The predicted SOL score from the XGBoost model in ML4VA-final notebook
TruePerformance: 2018-2019 Pass Rate - Predicted




