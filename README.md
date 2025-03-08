# Indonesia College Entrance Examination UTBK 2019

## Project Description

- UTBK SBMPTN is the annual college entrance exam held by and for state universities in Indonesia. This data was collected from a ranking site where exam takers could submit their score in order to gauge how well they did in comparison to others. 

- There are about 147 thousand samples (out of 1.1 million total scores) and this data is not indicative of the whole 1.1 million dataset as it is collected from a third-party sources (with maybe some invalid data strewn in). This dataset also contains the major picked by those exam-takers. * 

- Dataset source : https://www.kaggle.com/datasets/ekojsalim/indonesia-college-entrance-examination-utbk-2019

Every year, a press conference on the results of the UTBK selection is held by the Ministry of Education and Culture and the Ministry of Research and Technology. This analysis and report are intended to convey information to users (the public) for various purposes. Here is the example of press reference from year 2023. Full video can be found [here](https://youtu.be/wJh3vXyIKfA?t=3712).

![Reference Conference Report Data](Assets/Reference%20format.png)

Based on the reference format, there are several important pieces of information that can be presented, including:

1. The top 10 participants with the highest average UTBK scores, along with their majors and universities (science & humanities).

2. The top 10 universities with the highest average UBTK scores (science & humanities).

3. The top 10 universities preferred by participants who took the test or the most applicants (science & humanities).

4. The top 10 universities that received the most applicants (science & humanities).

5. The top 10 majors preferred by participants who took the test or the most applicants (science & humanities).

6. The top 10 most competitive programs (number of applicants/acceptance quota).

7. The ranking of provinces based on the number of applicants (province, number of applicants, acceptance quota, competitiveness).

> **One of the problem that needs to be solved is that the access to the complete data where the people could explore on their own is quite hard to find or there are none. So I believe that there needs to be a single source of information that could be used for the public. This helps students, schools, and even institutions with interests in education to conduct further studies to improve education in Indonesia.**

## Goal

To analyze and compile a reporting dashboard on the results of the 2019 UTBK (Academic Potential Test for State Universities) for both the Science & Technology (SAINTEK) and Social Humanities (SOSHUM) clusters that the people can easily access and explore.

## Repository Explanation and Personal Notes

- The raw data for this project are stored in the Original Data folder.

- This was my first personal project after 2.5 months of starting to learn data-related fields from scratch. So I tried to make the analysis using both python and SQL. I mainly used python for the EDA and data preparation process while for the SQL I just follow the same analysis process after I done using python for learning purposes. 

- As for the project, I chose the education field because it is one of the domain I have a passion and interest in, and if given the opportunity, I would like to experience what's it like to work in that domain in the future, though I also want to learn about other domains as well like e-commerce, retail, finance, etc.

- There are several shortcomings in this project, but I did my best and learned many technical and non-technical aspects, one of which is the difficulty of finding raw data in Indonesia compared to English-language data. Most of the data is confined within government or private institutions, and very little is available as open-source data.

## Dashboard Preview

**Tableau Dashboard** : [Link to Tableau Public Dashboard](https://public.tableau.com/app/profile/cikal.merdeka/viz/IndonesiaCollegeEntranceExamination-UTBK2019Result/IndonesiaCollegeEntranceExamination-UTBK2019ResultScience?publish=yes)

**Dashboard Explanation**: All the visualizations in the dashboard follows the conference reference tables with additional visualization of Indonesia geomap. By clicking on the `Change Cluster` button on the upper right corner, user can change the cluster between `Science` or `Humanities` examination result. The colour palette in the visualization that connect to the universities information refer to the distict color for each province. The geomap here acts as the filter for the whole visualization components in the dashboard.

![Dashboard Preview Science](https://raw.githubusercontent.com/mcikalmerdeka/Indonesia-College-Entrance-Examination-UTBK-2019/refs/heads/main/Assets/Indonesia%20College%20Entrance%20Examination%20-%20UTBK%202019%20Result%20(Science).png)

![Dashboard Preview Humanities](https://raw.githubusercontent.com/mcikalmerdeka/Indonesia-College-Entrance-Examination-UTBK-2019/refs/heads/main/Assets/Indonesia%20College%20Entrance%20Examination%20-%20UTBK%202019%20Result%20(Humanities).png)