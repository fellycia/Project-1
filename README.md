# Project-1 ACT and SAT 2017/2018 Analysis

### Problem Statement
With a change in the format of SAT in March 2016. This report aims to analyse SAT and ACT participation rate for 2017 and 2018 and how to improve the SAT participation rate.

### Executive Summary
This report provides an analysis and evaluation of the American College Testing (ACT) and Scholastic Aptitude Test (SAT) dataset, consisting of the participation rates and aggregate scores for each state in the United States.

Recommendations discussed include:
- Listing the benefits of the new SAT format and how it would benefit students, working towards making it mandatory for high school students to take the SAT as a graduating requirement.
- Providing more resources like food and vouchers or working with the state to ease the finanical burden of students.
- Equipping pre-test preparation in school or online to prepare students for SAT, increasing their confidence level and maximising their capabilities.

Several data visualisation like histograms, scatter plot, box plot and heatmaps were used to understand the data better, show trends and outliers.

Some trends observed are that most of the scores have an inverse relationship with participation rate. In addition, an increase in participation rate for SAT led to the decrease in participation rate for ACT.

### Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state**|*object*|final|The states in US|
|**sat_2017_participation_rate**|*integer*|final|The percentage of graduates who took the SAT test in 2017
|**sat_2017_reading_writing**|*integer*|final|Average evidence-based reading and writing score for that state (min score is 200 and max score is 800)
|**sat_2017_math**|*integer*|final|Average math score for that state (min score is 200 and max score is 800)
|**sat_2017_total**|*integer*|final|Average SAT total score (evidence based reading and writing and math) for that state 
|**act_2017_participation_rate**|*integer*|final|The percentage of graduates who took the ACT test in 2017
|**act_2017_eng**|*float*|final|Average english score for that state (min score is 1 and max score is 36)
|**act_2017_math**|*float*|final|Average math score for that state (min score is 1 and max score is 36) 
|**act_2017_reading**|*float*|final|Average reading score for that state (min score is 1 and max score is 36)
|**act_2017_science**|*float*|final|Average science score for that state (min score is 1 and max score is 36)
|**act_2017_composite**|*float*|final|Average of all ACT tests (eng, math, reading ,science)
|**sat_2018_participation_rate**|*integer*|final|The percentage of graduates who took the SAT test in 2018
|**sat_2018_reading_writing**|*integer*|final|Average evidence-based reading and writing score for that state (min score is 200 and max score is 800)
|**sat_2018_math**|*integer*|final|Average math score for that state (min score is 200 and max score is 800)
|**sat_2018_total**|*integer*|final|Average SAT total score (evidence based reading and writing and math) for that state 
|**act_2018_participation_rate**|*integer*|final|The percentage of graduates who took the ACT test 2018
|**act_2018_eng**|*float*|final|Average english score for that state (min score is 1 and max score is 36)
|**act_2018_math**|*float*|final|Average math score for that state (min score is 1 and max score is 36) 
|**act_2018_reading**|*float*|final|Average reading score for that state (min score is 1 and max score is 36)
|**act_2018_science**|*float*|final|Average science score for that state (min score is 1 and max score is 36)
|**act_2018_composite**|*float*|final|Average of all ACT tests (eng, math, reading ,science)

### Outside Research

From 2017 to 2018:
- Illinois showed the largest increase in SAT participation rate of 90% and the second largest decrease in ACT participation rate of 50%.
- Florida is one of the state with a high participation of more than 50% in both SAT and ACT.
- Ohio had both increase in SAT and ACT participation rate of 25% and 6% respectively.

Illinois switched the compulsory test from ACT to SAT. Hence, an increase in participation for SAT was observed together with a decrease in participation in ACT. The Illinois State Board of Education (ISBE) reviewed both examinations and concluded that the SAT suits the learning outcome for students better.

[Illinois_reference](https://www.chicagotribune.com/news/ct-illinois-chooses-sat-met-20160211-story.html)

Central Florida allowed students to take the ACT or SAT during a typical school day with the cost borned by the school.
The state made it compulsory for students to partake in either the ACT or SAT examination if they want to enter Florida's state college. Having it fully subsidized and given the choice to take either test resulted in high participation rates above 50% for both SAT and ACT.

[Florida_reference](https://www.orlandosentinel.com/news/education/os-ne-act-sat-florida-scores-20181024-story.html)

Ohio introduced the legislation for 11th graders to complete either the ACT or SAT. This caused an increase in both the participation rate in SAT and ACT. Furthermore, the state would sponsor every student for either test.

[Ohio_reference](https://www.dispatch.com/news/20170228/ohio-schools-must-now-give-act-or-sat-to-all-juniors)

### Conclusions and Recommendations
Alaska has a participation rate below 50% for both ACT and SAT 2017 and 2018.<br>
Alaska's ACT participation rate dropped from 65 to 33% and SAT participation rate increased slightly from 38 to 43%.<br>
Alaska Legislature abolished the requirement of sitting for the SAT or ACT test. Previously, students were funded by the state when they took the test. The intent was for students to concentrate on their high school curriculum. Without the encouragement from the state, participation rate naturally dwindled.

[Alaska_reference](https://www.adn.com/alaska-news/education/2016/06/30/students-no-longer-need-national-tests-to-graduate/)

[Alaska_reference_2](https://www.alaskapublic.org/2016/07/01/alaska-changes-hs-diploma-requirements-no-more-sat-act/)

<br>

- College Board can have a discussion with Alaska to implement SAT as a mandatory requirement for graduating high school students. Benefits of taking the SAT exam should be made known clearly. For example, improving students higher level logical and reasoning skills, gearing them towards solving real-world problems and less on formula based questions. This would prepare them better at transitioning from school to the working world.
<br>From the above data, it can be seen that states having a required test of either ACT or SAT have a larger participation rate in the examination. For example, Michigan had a participation rate of 100% for 2017 and 2018 SAT because it was compulsory for students to take the SAT.
<br><br>
- College Board can work with Alaska to lower the cost of SAT, reducing students' financial burden. Either by providing resources like meals to supply students with energy before the commencement of the test or vouchers upon completion of the test.
<br><br>
- College Board can help to increase the confidence level of students by them achieving their maximum potential. A way could be providing free classes and mock tests either in their school or online to hone their problem solving and filling any gaps in their understanding of the individual section of the test This would help greatly with their motivation and also to look forward to taking the examination.
<br>

### Data sources
[ACT 2017/2018 data](https://www.act.org/content/dam/act/unsecured/documents/cccr2017/ACT_2017-Average_Scores_by_State.pdf)

[SAT 2017/2018 data](http://ipsr.ku.edu/ksdata/ksah/education/6ed16.pdf)
