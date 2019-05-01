# Project 2: Health Intelligence: Interactive Hospital Recommendation System 

![image](figs/screen_ui.png)


+ **Shiny App link**: [https://grandeur-wang.shinyapps.io/healthcare_intelligence/]( https://grandeur-wang.shinyapps.io/healthcare_intelligence/)

### Background
Nowadays, it could be wearisome for patients to decide which hospital to go when they are ill. From patients' perspective, they may have many concerns of hospitals such as safety, patient experience and timeliness of care. To help patients find the hospitals that satisfy their needs, we used the data collected by US government as our database and designed an online app based on Shiny app. 

### Team members (Group 12):
+ team member  Wang, Guanren (gw2380@columbia.edu)
+ team member  Zhong, Ming (mz2692@columbia.edu)
+ team member  Cai, Zongbo (zc2455@columbia.edu)
+ team member  Li, Jingyue (jl5283@columbia.edu)


### Project summary: 
Since ancient times, people have faced the problem of being old and sick. Hospitals often play a very important role in this matter. There are many differences in the hospital. For example, some hospitals are good at surgery, and some hospitals are good at internal medicine. Therefore, how to choose a hospital suitable for patients becomes a key issue. Inspired by this problem, we combined the advantages of past projects and developed a software that allows patients to search for maps based on their type of illness and the needs of the hospital. To be more specific, the hospital's choice is determined by the patient's preference to mortality, safety of care, readmission rate, patient experience, effectiveness of care, timeliness of care and efficient use of medical imaging, and their type of disease. At the same time, we consider that price is also one of the important factors for patients to choose a hospital, so we also analyzed the estimated cost of medical, without insurance, in different states.

### Contribution statement:
In the initial discussion of programming, all team members reached a consensus on the final design. Ming Zhong was responsible for the development of the UI. He later joined Guanren Wang to do some development in "Find Your Hospital" section. They also collaborated on completing the data table below the map. Guanren Wang was responsible for the data cleaning required for the "Find Your Hospital" section, implementing personalized ranking calculation, connecting data table to server and all functionality of leaflet map.Plus, Guanren also did some fine-tuning of UI. Zongbo Cai and Jingyue Li collaborated on data cleaning in the "Hospital Statistics" section. Zongbo Cai implemented three maps in the "Hospital Statistics" section. Jingyue Li converted the the first map from static to interactive.

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── app/
├── lib/
├── data/
├── doc/
└── output/
```

Please see each subfolder for a README file.

