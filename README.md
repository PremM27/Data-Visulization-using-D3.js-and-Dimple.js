# P6: Make Effective Data Visualization

## Summary
This project has been developed as a Part of the Udacity Data Analyst Nanodegree course: P6. Make Effective Data Visualization. This is a Visualization developed with the implementation of D3.js and Dimple.js. This is a Visualization of the Survival Rate of Passengers in Each passenger class grouped by Sex.


## Design
The Dataset has been carefully analyzed and explored. As I have a clear idea about my visualization, I have cleaned all the unnecessary Data and Variables like Name, Age, SibSp, Parch, Ticket, Fare, Cabin, Embarked have been dropped. Columns with Null values have been Removed. Data in the Survival column has been altered from 0 to Dead and 1 to Survived.

Through various feedbacks over the plot, The plot and Data has been altered over time. For the Final Plot there has been Data Cleaning done using Python using a Jupyter Notebook and The Process involved has been Detailed using Comments in the Jupyter Notebook.

## Findings:
Passenger Class 1 has fewer Mortality Rate when compared with other Passenger Classes. Passenger class 1 had higher price followed by Passenger Class 2 and Passenger Class 3. It is evident that the Females and Richer Class were given higher Priority in Lifeboats Allocation. Females of PassengerClass 1 had a very high chance of Survival i.e 96%.

## Feedback
The Index_Initial Visualization has been shared with 3 of my friends and the feedback follows
#### Feedback 1
The visualization is Pretty self-explanatory, It would have been even Nicer to look at the plot on a Percentage Scale instead of Measuring Scale

#### Feedback 2
The Visualization is Very Clean and Easy to Understand.

#### Feedback 3
The Visualization could be at it's best if the Sex variable could be added to the Plot So as to imply the Survival of Passengers based on Sex Per Passenger Class.

#### Feedback from Previous Reviewer
survived v dead - do you need both variables? Either your talking about Survival Rate or Death Rate which is less positive. You don't need to display both now you are showing percentage. Remember, you can override the Y axis to make sure you show 0-100% even if it defaults to less - see link here for how to do this.
colour coding - with only one variable - survived - you could consider an additional colour coding? Either for Gender or Class?
Pclass - Passenger Class would be a more accessible label? You don't need to repeat it on the bar labels if you include it on the X-Axis label instead of "Pclass/Sex".
tooltip labels - these could be more accessible too - survived won't be necessary if you only show survival, PClass (see above) and Count should be "Survival Rate" or whatever caption you choose for the Y-axis.

## Additional Work:
The Reviewer Feedback is carefully considered and Executed by Grouping the Data using Python and the grouped data is written to a new file (clean_Final.csv) and the varible Sex is Added to the Data.

## Final Plot
1. The Feedback has been appreciated and Necessary Improvements have been Done.
2. The Y Axis Scale has been Modified from Measure to Percentile.
3. Data has been cleaned and Grouped using Python.
4. A new varible "Sex" is added.
5. Sex is plotted as a Series to present color and Exhibit Visual Difference agianst Gender Category.

## Resources
https://github.com/d3/d3/wiki/Gallery
https://www.kaggle.com/c/titanic
