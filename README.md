### DSCI521 Course Project

# Data Analysis and Interpretation

_This project is intended to provide some open-ended experience with exploring datasets for possible associations, relationships, and predictive capacities. This will then be followed up with the execution more complex and intensive analysis that prototypes the function of a potential application or underpin an empirical finding. Specifically, all projects for this course will entail the following two phases:_

1. _A topically-motivated exploration of available pre-processed datasets and providing EDA  (exploratory data analyses)._
2. _Interpreting the outcome of phase (1), the selection and execution of a more in depth analytics project, prototyping an application's function or empirical investigation._
---

### Our Team:
- Harsh Bolakani hvb36@drexel.edu
- Greg Morgan gm655@drexel.edu
- Trevor Pawlewicz tmp365@drexel.edu
---

## Our Topic: _School Grade Analysis_
>
> ### We will explore the area of the activities of a students of a secondary school and what attributes contribute or detract from getting good grades. Concentrating on analyzing the alcohol correlation.
>
> _Attributes in our datasets are taken from a Math course and Portuguese language course in the country of Portugal._
>
> #### We will be asking the questions in our data analysis exporation:
> - Are there any what contributing factors to a good grade?
> - Are there any what contributing factors to a low grade?
> - Does alcholhol play a part in either?
> - Are any other factors found to determine a higher/lower grade?
>
> #### Analytic tools and data-medium we will be working with:
> - CSV
>
> #### During our Exploratory Data Analysis journey we will also try to address the following points:
> - who might be interested in our analysis and why
>
> #### We will also give insight into the following journey during our analysis:
> - Context of Data found/used
> - Data preprocessing if needed
> - Our Exploratory Data Analysis
> - Our Results
> - Conclusion on our analysis
---
## Our Phase 1 Report:
>
> #### 1. Background report on the team's members, their self-identified skills, and individual contributions (Areas of expertise):
> - **Harsh:** Java, Backend-Development, API-Development, Test Automation, API, Library Design
> - **Greg:** Strengths: Python, AWS Cloud Based Architectures, REST API development, Data Streaming Technologies
> - **Trev:** Front-end UI, Evidence-based User Experience, Design Thinking, Team Leadership
>
>
> #### 2. Provide a discussion of what you would like to your analysis to do, who and what it will support by answering the following questions:
>   - try to predict students final grade.
>   - Are there any what contributing factors to a good grade?
>   - Are there any what contributing factors to a low grade?
>   - Does alcholhol play a part in either?
>   - Are any other factors found to determine a higher/lower grade?
>
>
> #### 3. Provide an exhibition of analyses from dataset(s) explored, including visual analyses, captions, and useful descripitions
> ##### _Attrributes analized:_
>   - school - student's school (binary: 'GP' - Gabriel Pereira or 'MS' - Mousinho da Silveira)
>   - sex - student's sex (binary: 'F' - female or 'M' - male)
>   - age - student's age (numeric: from 15 to 22)
>   - address - student's home address type (binary: 'U' - urban or 'R' - rural)
>   - famsize - family size (binary: 'LE3' - less or equal to 3 or 'GT3' - greater than 3)
>   - Pstatus - parent's cohabitation status (binary: 'T' - living together or 'A' - apart)
>   - Medu - mother's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
>   - Fedu - father's education (numeric: 0 - none, 1 - primary education (4th grade), 2 – 5th to 9th grade, 3 – secondary education or 4 – higher education)
>   - Mjob - mother's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
>   - Fjob - father's job (nominal: 'teacher', 'health' care related, civil 'services' (e.g. administrative or police), 'at_home' or 'other')
>   - reason - reason to choose this school (nominal: close to 'home', school 'reputation', 'course' preference or 'other')
>   - guardian - student's guardian (nominal: 'mother', 'father' or 'other')
>   - traveltime - home to school travel time (numeric: 1 - <15 min., 2 - 15 to 30 min., 3 - 30 min. to 1 hour, or 4 - >1 hour)
>   - studytime - weekly study time (numeric: 1 - <2 hours, 2 - 2 to 5 hours, 3 - 5 to 10 hours, or 4 - >10 hours)
>   - failures - number of past class failures (numeric: n if 1<=n<3, else 4)
>   - schoolsup - extra educational support (binary: yes or no)
>   - famsup - family educational support (binary: yes or no)
>   - paid - extra paid classes within the course subject (Math or Portuguese) (binary: yes or no)
>   - activities - extra-curricular activities (binary: yes or no)
>   - nursery - attended nursery school (binary: yes or no)
>   - higher - wants to take higher education (binary: yes or no)
>   - internet - Internet access at home (binary: yes or no)
>   - romantic - with a romantic relationship (binary: yes or no)
>   - famrel - quality of family relationships (numeric: from 1 - very bad to 5 - excellent)
>   - freetime - free time after school (numeric: from 1 - very low to 5 - very high)
>   - goout - going out with friends (numeric: from 1 - very low to 5 - very high)
>   - Dalc - workday alcohol consumption (numeric: from 1 - very low to 5 - very high)
>   - Walc - weekend alcohol consumption (numeric: from 1 - very low to 5 - very high)
>   - health - current health status (numeric: from 1 - very bad to 5 - very good)
>   - absences - number of school absences (numeric: from 0 to 93)
>
>
> #### 4. Provide a discussion of who might be interested in your analysis:
>   - Parents
>   - School officials with legitimate educational interest;
>   - Other schools to which a student is transferring;
>   - Specified officials for audit or evaluation purposes;
>   - Appropriate parties in connection with financial aid to a student;
>   - Organizations conducting certain studies for or on behalf of the school;
>   - Accrediting organizations;
>   - To comply with a judicial order or lawfully issued subpoena;
>   - Appropriate officials in cases of health and safety emergencies; and
>   - State and local authorities, within a juvenile justice system, pursuant to specific State law.
>
>
> #### 5. Provide a discussion of how your analysis might fit into an application or investigation:
>   - How does Portuguel align with United States government statistics: by age 15, nearly 30% of kids have had at least one drink, and by age 18, that figure leaps to almost 60%?
>   - Formulate possible Reasons why teens drink include.
>
>
> #### 6. Provide a discussion of how your analysis is limited and could be improved
>   - Dataset is limited to the Country of Portuguel of seconday students: drinking age (18) is much lower than United States.
>       - The legal drinking age in Portugal is 18 years. Initially, the legal age was 17 years, but it has been raised to 18 since the rise of illegal sales and bad alcoholism influence among young kids. However, in most cases, there is an exception for minors aged 16 and 17 to consume a glass of beer, wine, or cider with a meal in a restaurant if they are with their family.
>
>
> #### 7. Provide a selection of data for continued analysis, including justification
>   - we could expand apon the test subjects and include higher grade levels
>   - we could expand apon the class subjects that are analized
>   - conduct a survey for data anaysis in the United States
>
>
> #### 8. Provide a discussion of how your analysis might be completed and disseminated, i.e., who's the target audience?
>   - this could be public record for Public Service Announcements.
>   - Could also be used to help parents understand the effects of underage drrinking and how it is applied to academic progress.
---
![Drexel logo](images/Drexel-engineering-blue-black.png "Drexel Engineering")
