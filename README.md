# DataVisualization
Udacity Unit on d3.js &amp; dimple.js

## Summary 
This visualization shows the demographics of 891 of the 1317 passengers aboard the Titanic. Specifically, gender, class, port of embarkment, age, and number of family members aboard were explored. There were more men than women, more third class passengers than first class, and the most common age range was between 21 - 30.  Next, survivorhsip within each of these categories was explored.  Unsurprisingly, women, children, and first class passengers were more likely to survive.

## Design 

### Dataset information
This dataset is taken from [Kaggle]( https://www.kaggle.com/c/titanic/data?train.csv#) website.  I cleaned the data by removing categories I was uninterested in (passenger name, cabin number, fare) and creating a new one which combined the number of spouses/siblings and parents/children abroad and a new one which put passengers into age "bins".

### Version 1
My inital idea is to move progressively through the data from simple to more complex. The first set of visualizations will simply show the breakdown of theses passengers in terms of gender, age, ticket class (first, second, or third class), port of embarkment, and number of family members abroad.  Second, will focus on survivorship, first by showing the total number of survivors and non survivors and then breaking down the original visualization into these categories.  Finally, the visualization will show each of these categories as percentages rather than raw numbers.  In the future, I would like users to be able to select certain demographics (First class, single, female, in her 20s, embarked in Southampton) and see what the survival rate for that particular demographic is.

## Feedback 
include all feedback you received from others on your visualization from the first sketch to the final visualization

- What do you notice in the visualization?
- What questions do you have about the data?
- What relationships do you notice?
- What do you think is the main takeaway from this visualization?
- Is there something you don’t understand in the graphic?

## Resources 
(Listed in order of usage)

- Titanic Wikipedia Entry https://en.wikipedia.org/wiki/RMS_Titanic
- Titanic Facts http://www.titanicfacts.net/titanic-passengers.html
- Dimple.js documentation http://dimplejs.org/examples_index.html
- Udacity Forum Discussion https://discussions.udacity.com/t/beginner-help-with-dimple-js-and-javascript-in-general/203196
- Udacity Forum Discussion https://discussions.udacity.com/t/project-6-feedback-and-help-request-titanic-data/198669
- Vverde's repository https://github.com/vverde/Udacity-Data-Analyst-Nanodegree-P6
- Stack Overflow Exchange http://stackoverflow.com/questions/17791926/how-to-rotate-x-axis-text-in-dimple-js
- Stack Overflow Exchange http://stackoverflow.com/questions/33179439/d3-js-dimple-getting-a-title-on-a-graph
- Dimple Wiki on Github https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.series#addOrderRule
