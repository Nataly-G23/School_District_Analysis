# School_District_Analysis
## Overview
A school district employee has asked for help with cleaning, sorting, and analyzing data in regards to the 15 high schools in the district. The analyis provided should give the district a better idea how things like budgeting and school size may affect students academic performance. After an initial analysis the district employee lets you know that the grades for 'Thomas High School' 9th grade have been tampered with. I new analysis needed to be made excluding the tampered data for an acurate/honest analysis.

## Resources
- Data Source: schools_complete.csv, student_complete.csv
- Software: Python 3.9.12, Jupyter Notebook 6.4.11

## Results
### How is the district summary affected?
![PCS DistS](https://user-images.githubusercontent.com/104810450/171719584-cefb9853-1981-4306-9269-9fbf14167a6c.png)
(Original district analysis)

![PCSC DisA](https://user-images.githubusercontent.com/104810450/171718621-d4eac566-2508-4d0e-b9bf-4a4dd3ceec52.png)
(Updated district analysis)

Removing the 9th grade data barely made any difference for the district analysis. The greatest impact it made was on the "% Passing Reading" total. Which was only a 0.3% difference. The 9th grade class grades removed accounted to a little over 400 students, which in comparison to the whole district at almost 40,000, doesn't make a big impact. 

### How is the school summary affected?
![PCS School sum](https://user-images.githubusercontent.com/104810450/171722935-87d2efc0-d229-40f2-8158-30d1b5a85b10.png)
(Original school summary)

![PCSC School sum](https://user-images.githubusercontent.com/104810450/171723071-dacaa6f5-d87d-494b-9cfa-3d0e8249e324.png)
(Updated school summary)

Like the district summary the changes to the school summary is very small. The differences are less than a whole number. It is interesting that Thomas High schools academic performance has barely changed. The 9th grade class does make up about a third of the schools population. It does show that the remaining three classes (10th-12th) has an impressive enough academic performance to make up for the missing grades. 

### How does replacing the nith graders math/reading scores affect Thomas High School's performance relative to the other schools?
![PCS top5](https://user-images.githubusercontent.com/104810450/171725622-8a8a6903-20ff-4bda-9eb3-1524a81fba18.png)
(Original Top 5 performing schools)

![PCSC Top 5](https://user-images.githubusercontent.com/104810450/171725763-cb5c583d-793e-491c-a305-4e412b3795b7.png)
(Updated Top 5 performing schools)

In both analysis Thomas High schools position is the same. It holds its position as second highest performing school of the district even after removing the 9th grade. As stated above, the rest of the schools academic performance is high enough to make up for the missing grades. 

### How does replacing the ninth-grade scores affect the following:
There may be other factors to consider outside removing Thomas High schools 9th grade grades. At the end of the day we want to look at the district as a whole. Every school is diffrent, different budgets, student populations, school types. Looking at these factors might be able to high light schools that may need a larger budget, more teachers for schools with more students, etc..
- Math and reading scores by grade

![PCS Math](https://user-images.githubusercontent.com/104810450/171728745-54915373-a39f-4304-a246-40b514ec3c41.png)
(Original math score by grade)
![PCS Reading](https://user-images.githubusercontent.com/104810450/171728920-8c6b1fcb-53a5-4b01-85f1-2d05b7124569.png)
(Original reading score by grade)

![PCSC math](https://user-images.githubusercontent.com/104810450/171729048-308cd0a0-239f-451a-b9d0-a15093cc15c6.png)
(Updated math score by grade)
![PCSC Reading](https://user-images.githubusercontent.com/104810450/171729111-78161321-a4e1-430b-8e7d-8ec42588b0ab.png)
(Updated reading score by grade)

The only differences between the original and updated analysis for both math and reading is the obvious lack of data for Thomas High schools 9th grade. Other then that remaining data is exacly the same. the differences between the schools isn't drastict, but there is definite room for improvement. 
- Scores by school spending

![PCS scorexspend](https://user-images.githubusercontent.com/104810450/171731113-6a731704-6787-4324-9852-3ec27d2077cd.png)
(Original school spending) 

![PCSC scorexspending](https://user-images.githubusercontent.com/104810450/171731247-6e14c7b5-4fea-4c60-8572-ff304dcc40b1.png)
(Updated school spending)

There is no difference in the two analysis in regards to academic performance based on schools budgets. It is interesting to point that that the schools with the smaller spending amount per student has a higher overall passing percentage than the schools with the larger budgets. The diffeence being about 34%. That would require a more detailed look into how the schools are using those funds per student, making changes as needed.

- Scores by school size

![PCS scorexsize](https://user-images.githubusercontent.com/104810450/171732714-5ebaec34-c882-465f-b144-660cd9b71962.png)
(Original school size)

![PCSC scorexsize](https://user-images.githubusercontent.com/104810450/171732812-e4e5993d-834a-4736-96ab-812315b912b7.png)
(Updated school size)

The tables above shows again, there is no differences made between the two analysis after removing Thomas High schools 9th grade class. it does however show in both that the smaller the student population the better the academic performance. Possible reason being that schools with a higher teacher-student ratio would mean that teachers are able to be more attentive and supportive to their students. Schools with a greater student-teacher ratio, the teachers might be spread too thin. Which unfortunately makes it easier to have kids slip through the cracks.  
- Scores by school type

![PCS scorextype](https://user-images.githubusercontent.com/104810450/171734061-3f2ecc4a-0483-4c80-b9e6-3a33adeb8ec1.png)
(Original school type)

![PCSC scorextype](https://user-images.githubusercontent.com/104810450/171734165-0482dc1b-45c4-4e34-bb39-15a150060020.png)
(Updated school type)

The two analysis again show no differences after removing Thomas Hish schools 9th grade class. The thing that stays the same is the differences in academic performance between public district schools vs. private charter schools. The charter schools does score better than the district schools.

# Summary
To finalize everything. Although it was necassary to remove the tampered grades so that a honest/fair analysis could be made. The results are virtually the same. The results showing, schools with smaller student populations and smaller budgets perform better then larger sized schools and budgets. Ways to possibly fix that? Off the bat I can think of two.
- Hire more teachers for the schools with a larger student populations:
More attention and guidance given may give the students more opportunity and desire to do better.
### OR
- Adjust the schools boundaries and open a new high school that can pull portions of the populations of the more congested schools:
Although it is a more expensive option it give opportunity to be able to practice what the data shows. It creates smaller school sizes which will not need as high budgets per student. Hopefully in doing so there would be higher academic performances across multiple schools. 

Hopefully this analysis can give the districts board a greater idea on what works and what doesn't. And what ares may need to be investigated further. Giving them better insight on how to improve for the school years to come.
