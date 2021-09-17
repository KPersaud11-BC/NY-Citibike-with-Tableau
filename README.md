# NY-Citibike-with-Tableau by Kieran Persaud

## Overview of the Tableau Challenge
In this Challenge, we want to establish a Bikeshare business for Des Moines, Iowa. To best understand the business model, we first analyze Citi Bike data from New York using Tableau. In the module, we created several visualizations to hone our Tableau skills. Now for the proposal, one of the key stakeholders would like to see a bike trip analysis, and we are tasked with creating five new visualizations.

## Resources
**Data Sources:** ```201908-citibike-tripdata.csv.zip```

**Software:** Anaconda 4.10.1, Pandas Library, PythonData kernel; Jupyter Notebook; Tableau

## Results
[Link to Dashboard](https://public.tableau.com/views/Challenge_16316076887690/ChallengeStory?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

### Deliverable 2 Visualizations
**Checkout Times for Users:**
![image](https://user-images.githubusercontent.com/84286467/133825716-8525562a-5d3f-4413-a641-a028f2abdbd1.png)
This visualization shows the length of time that bikes are checked out for all riders. The graphic shows that most bikes are checked out for 20 minutes or less.

**Checkout Times by Gender:**
![image](https://user-images.githubusercontent.com/84286467/133825929-cd0cbc61-912d-4043-856a-924ad5437fc1.png)
This graph shows the the length of time that bikes are checked out for each gender. From the data, mostly men use the bikes.

**Trips by Weekday for Each Hour:**
![image](https://user-images.githubusercontent.com/84286467/133826239-6cf8bd0a-9e17-402f-90e6-c68e475eee7f.png)
This is a heatmap that shows the number of bike trips by weekday for each hour of the day. The data shows that most bikes are used to commute to and from work, as noted in the darker 8am-9am and 4pm-6pm areas.

**Trips by Gender (Weekday per Hour):**
![image](https://user-images.githubusercontent.com/84286467/133826476-25838a91-3284-4b66-8759-4a2a3665df01.png)
This heat map shows the number of bike trips by gender for each hour of each day of the week.

**User Trips by Gender by Weekday:**
![image](https://user-images.githubusercontent.com/84286467/133826656-bacb385b-69dc-4b45-bc35-1c39b0cc46e5.png)
This visualization depicts the number of bike trips by gender for each hour for each day of the week. Male subscribers use the bikes consistently throughout the week, while other usertype/gender combinations vary.

### Module Visualizations
**Top Starting and Ending Locations**
***Starting***
![image](https://user-images.githubusercontent.com/84286467/133827376-e9e7003d-93e0-4eb8-8ee6-b9d037d4210a.png)

***Ending***
![image](https://user-images.githubusercontent.com/84286467/133827477-a1dbcf84-f4e3-4852-aa9f-33261ebb8925.png)

These two visualizations were from the module. From the maps, most of the trips began and ended in Manhattan.
## Summary
The following points can be summarized from the data:
1. Most bikes are checked out for 20 minutes or less.
2. Mostly men use the bikes.
3. Most bikes are used to commute to and from work.
4. Most of the trips began and ended in Manhattan, and thus most trips are short distance trips. To note, Des Moines is over 3 times the square mileage as Manhattan.

### Additional Visualizations
**Key Stats:**
![image](https://user-images.githubusercontent.com/84286467/133828430-84618ef8-e9fd-4ea2-95c1-f175b3631ecb.png)
This table provides a quick look at factors like tripduration, bike fleet size, distance travelled, etc.

**Distance Histogram:**
![image](https://user-images.githubusercontent.com/84286467/133828559-0e1bfd20-47a8-44a3-baf3-8aab1923f27a.png)
This histogram shows the distance in miles in bins and where the data falls within those bins. Since the data is mostly in the smaller bins, one can infer that most trips are short trips. This information could be used to forecast how and where to stage bikesharing racks, as well as determine a mean distance to do preventative maintenance and upkeep on the bike fleet.

**Rides Tree Map**
![image](https://user-images.githubusercontent.com/84286467/133828719-803f1d47-aa43-4911-84d7-7d57f2549fdd.png)
This tree map was created in the module but the color scale was modified. This information could be used to forecast how many bikes would be needed in the fleet, as well as determine a mean number of trips to do preventative maintenance and upkeep on the bike fleet.

An additional visualization to use would be ridership over the course of a year. This would indicate any increases or decreases in particular months.
