# Project 2: Open Data App - an RShiny app development project

## Project Title: Medic -- Find your perfect hospital
Term: Spring 2019


### **App description:** ###
#### Welcome ####
The welcome page of the app briefly gives an overview of the key features of the app in finding the perfect hospital for you: key statistics and hospital recommendations.

#### About ####
##### About Team #####
This page introduces team members of Group 7 along with their photos and contact information.

##### Data #####
This page lists the two data sources from which the key insights and hospital recommendations are based on. Moreover, it defines the data columns or keywords for clarity into what each indicates.

#### Key Statistics ####
This page is about the key statistics of the hospital situation in the United States. It contains three parts. The first part is 'Hospital Heatmaps', which contains three heat maps, describing the number of hospitals in each state, hospital quality (ratings) and Medicare coverage percentage in each state. Users can use the scroll down button to see the three different maps. In the second part '7 Measurements', users can choose a state from the scroll down button and see the Radar Chart clearly representing hospital performance on the seven measurements: Mortality, Medical Image Effectiveness, Timeliness, Effectiveness, Patient experience, Readmission and Safety. The third part 'Rating VS Payment' presents grouped scatter plots of hospital rating and payment situations. The colors represent different region in the United States and the size of the dot represents the number of hospitals.

#### Hospital Recommendation ####
This is the page where users can use our app to search for spcific hospitals. The search criteria on the left enables users to narrow the search results down by location, cost, emergency services or distance. Additionally, if one enters a zipcode, the website locates the user by the zipcode and calculate the distance between all hospitals to the given zipcode. Once given all the search criteria, the website automatically ranks the results to decide which results come on top of the list, based on an algorithem that takes strength, weakness and cost into accounts.  


### **Reference**:
1. Basic design was inspired by the project 2 of Spring Semester 2018 Group 8. Author: Xiaxiao Guo, Shan He, Michael Utomo, Lan Wen, and Jingtian Yao.
2. https://www.w3schools.com/howto/howto_css_team.asp


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
