# Titanic-dataset
Introduction

This dataset contains demographics and passenger information from 891 of the 2224 passengers and crew on board the Titanic. You can view a description of this dataset on the Kaggle website (https://www.kaggle.com/c/titanic), where the data was obtained.
Questions

In this analysis, I would like to explore the following questions.
A

    Who were the passengers on the Titanic? (Ages,Gender,Class,..etc)
    What deck were the passengers on and how does that relate to their class?
    Where did the passengers come from?
    Who was alone and who was with family?
    What factors helped someone survive the sinking?

B

    Was age a factor in determining the chances of survival?

    Did women had a better survival rate than men?

    How was children's survival rate as compared to men or women?

    Was Socio-economic status or paasenger class a factor in determining the survival rate?

Data Dictionary

    survival: Survival (0 = No, 1 = Yes)
    pclass: Ticket class(1 = 1st, 2 = 2nd, 3 = 3rd)
    sex: Sex
    Age: Age in years
    sibsp: Number of siblings / spouses aboard the Titanic
    parch: Number of parents / children aboard the Titanic
    ticket: Ticket number
    fare:Passenger fare
    cabin:Cabin number
    embarked:Port of Embarkation(C = Cherbourg, Q = Queenstown, S = Southampton)

pclass: A proxy for socio-economic status (SES) -1st = Upper -2nd = Middle -3rd = Lower

Age: Age is fractional if less than 1. If the age is estimated, it is in the form of xx.5

sibsp: The dataset defines family relations in this way...

    Sibling = brother, sister, stepbrother, stepsister
    Spouse = husband, wife (mistresses and fiancés were ignored)

parch: The dataset defines family relations in this way...

    Parent = mother, father
    Child = daughter, son, stepdaughter, stepson
    Some children travelled only with a nanny, therefore parch=0 for them
