# Ford GoBike Analysis
In a world of ever-changing options for transportation, it's evident that the traditional method of driving a car from point A to point B isn't the only thing we have to do anymore. This is evident with the growth of things like ride-sharing with Uber, scooter rentals with Lime, and of course, bicycle rental with Ford GoBike.
In this Udacity project, we'll be taking a look at some data provided to us by Ford's GoBike project. Ford has kindly made this data available to us [at this provided URL](https://www.fordgobike.com/system-data).


## Summary
It contains very few quantitative and categorical features to glean insights from. As I note in the slide deck, there are a number of ways in which this dataset could be augmented, and it appears through searches online that this dataset may have been more robust at one point in time.

Here are a few examples in which I would have hoped to see more information:

 - How did repeat users account for the rides in the dataset?
 - What impact does the electric vs. non-electric bike types have on this dataset?
 - How might knowing some historical weather patterns add additional insights for us?

We did get a decent understanding at the disparity between rider age and rider membership. Let's highlight a few of those in the next section.


## Dataset
As already shared above, Ford kindly provided us with the data we'll need for this project.
Here are the fields provided to us within the primary source data sets. We won't necessarily be working with all of these, but it's still good to know what's in here.
```
 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type (Subscriber or Customer - "Subscriber" = Member or "Customer" = Casual)
 - Member Year of Birth
 - Member Gender
```


## Summary of Findings
1. Univariate exploration: During the day, there are more trips in the morning and afternoon than the night. It makes sense that there are more subscribers than customers. For the gender groups, the number of trips in male riders is 3 times more than the number of trips in females. It needs to be investigated more. Most of riders are 30 to 40 years old and the duration of trips is around 500 seconds.
2. Bivariate exploration: there is a slightly negative correlation between age and duration of trips.
3. Multivariate exploration: separating user types, customers and subscribers, gives more insights.


## Key Insights for Presentation
 - Folks in their early 30's comprise the bulk of the rides.This one is the one that surprised me the most. Knowing that people as young as 18 can rent one of these bikes, I definitely expected to see the dataset to have a much stronger right skew. While a right skew does exist, isn't extreme given that people in their 30's tend to ride more often than people in their 20's or even in their teens.
 - Gender has no real effect on ride duration. One might expect that males would be taking the longest rides, but the data doesn't indicate this at all. Across all ages, the differences between duration of male riders vs. female & other riders is negligible. In fact, it wasn't uncommon that females and those who marked their gender as "Other" would often ride longer than male riders.
 - The stations with the most trips are located in San Francisco and connect to public transportations including Caltrain, Bart and Ferry. User types play a key factor on the number of trips in each location and time group. 

Thus, collecting more information individually from these two user types is important for the future analysis.
