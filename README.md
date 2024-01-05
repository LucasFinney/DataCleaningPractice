# DataCleaningPractice
A little practice space for applying the datacleaning techniques from the Data Analysis in Python course from Coursera

## 12/13/2023
First day of messing around with this, and I've realized I ended pre-empting most of what I would end up doing in the course module. Whoops! Anyway, I started cleaning the data. 
- The original file had all of the missing values as "?" so I converted them into np.nan values. One of the columns, normalized-losses, had a lot of missing data, so I replaced those with the mean.
- The dataframe types were wrong, a lot of numerical columns were "objects", so I changed them to floats.
- One of the columns, num-of-cylinders, had "three", "six", etc, rather than numerical values. I replaced those and then corrected the type.

To do:
- Address the rest of the missing data. Other columns have some missing values, but not as many as that "normalized-losses" column.


## 1/5/2024
Whoops... didn't update this for a while. The notebook has been expanded significantly. I continued from the last entry by cleaning the data, doing exploratory data analysis to determine the significant features, and eventually creating and testing a linear model. Overall results are fairly good, though the R^2 varies significantly from test to test. This may be due to the large portion being reserved as the "testing" set, but my money is on the problem being the lack of data in the higher price ranges. That's where the model seems to perform the worst.
