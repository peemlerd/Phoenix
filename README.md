# About this project
Which format of the Fall 2020 semester do Swarthmore students prefer? Which factors inform the preference? What are the pros-cons-repercussions of each reopening plan? These are the three questions I sought to explore through this project to shed light on the the 'Fall 2020 reopening plan' conversation. Many articles on Fall 2020 reopening plan rely heavily either on survey results or stories, but not both. In reality, numbers and stories complement each other: stories make numbers stick to people, whereas numbers make stories more robust. Hence, my goal is to combine clear-cut data analysis with powerful stories to convey the complexity of the Fall 2020 reopening plans, which culminates in this longform piece titled [Survey: Awaiting Fall 2020 plan, students face housing uncertainty, safety concerns](https://swarthmorephoenix.com/2020/06/30/students-weigh-in-on-fall-2020/). 

# Goals
1. *Convey the complexity of reopening plans across demographics*. Whether the fall semester is entirely online, hybrid, or fully on-campus has different repercussions for students on different demograpic groups. For instance, an international student may be less likely to take a semester off due to visa concerns. 
2. *Systematically survey which factors weigh onto students' preference*. Students receiving a lot of financial aid might prefer a hybrid option because they rely on on-campus housing, whereas more financially-independent students might care more about timely graduation and networking opportunities.
3. *Promote an informed, data-driven Fall 2020 discussion* by weaving poignant stories, insightful infographics, and data altogether. 

# Tools used 
1. Google Forms. 
2. Jupyter Notebook.
3. Python libraries — numpy, pandas, scipy. 
3. Datawrapper.

# Skills
1. Survey Design.
2. Longform Journalism. 
3. Data Manipulation.
4. Data Visualization

# Work process

1. **Define the goals and the scope of this article (see above).** Because we were interested in whether students from different demographic groups have different preference on the reopening plan AND whether they weigh each factor differently, we made it a point to include demographic questions in the survey.

2. **Create a survey**. Surveys should be brief yet meaningful. Bayliss and I edited the survey multiple times to ensure every question is clear. Questions on how confident students were/are in securing stable, sufficient housing during Spring/Fall 2020 were added as many students expressed anxiety on the issue. A few questions on demographics, housing situation, and preference on Fall 2020 were mandatory. Other questions, all of which are optional, include factors weighing onto students' preference and their experience with COVID-19/thoughts on the reopening plan. 

To ensure students answer freely, the survey does not collect any email and explicitly ask for consent if students are interested in being further interviewed.

3. **Analyze the data**. Overall, we aggregated 254 responses and performed analysis on those data. The analysis validates several claims on the effects of Fall 2020 format, such as:
- International students are concerned with timezone difference and travel restrictions.
- Many students were dissatisfied with online classes during Spring 2020 and yearn for face-to-face interactions.

However, many unexpected trends emerged as well, such as:
- The more financial aid a student receives, the less likely they are to consider a leave of absence. Moreover, these students tend to weigh "abstract factors" (think: networking opportunity, academic rigor) less in comparison to students receiving little to no financial aid. 
- Incoming first-year students overwhelmingly prefer hybrid or on-campus options, but responses from other students are mixed. 
- International students are significantly less likely to consider a leave of absence — regardless of the format. This can be partially attributed to visa concerns. 

See the .ipnyb file for details on the analysis and the Phoenix article for other findings.

4. **Visualize the data**. The .ipnyb file contains functions that generates a dataframe showing how many students in a given demographic prefer each reopening format or heavily weigh certain factors. Bayliss and I experimented with visualizing both the raw and the normalized data. In the end, we chose to:

- Normalize the data for the *format preference* and *the likelihood of absence if Fall 2020 is completely online* because **comparing proportion of students favoring different options** provides greater clarity on what the majority prefer/how most people will react to an online semester.
- 



5. **Cross-check findings and find pertinent anecdotes**.

6. **Publish the article**.

# Acknowledgement
This project is a collaboration between Peem Lerdputtipongporn '21 and Bayliss Wagner '21 from Swarthmore College. The article is wordpressed by Bayliss and edited by the Editorial Board of The Phoenix.
