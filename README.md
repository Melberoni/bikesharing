# Bikesharing
## Overview
This analysis is to review the available Citi bike data from NY in order to convince investors that a bike-sharing program in Des Moines is a solid business proposal.
To see the full Tableau workbook see the tableau public file:
[link to Dashboard](https://public.tableau.com/views/challenge_16416699793400/CitiBike?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)


## Results
![Trip_Duration](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/Durationof%20usage.png)
The above graph shows the distribution of the length of a ride. This shows that the majority of the time people use a bike for less than an hour

![trip_duration_by_gender](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/duration%20of%20usage%20by%20gender%20under%201%20hour.png)
If we filter down to a duration of one hour or less, and split by gender, you can see more clearly that the peak usage is just under 10 minutes for all genders.

![usagebyweek](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/weekly%20usage.png)
The above heatmap will help us identify when the bikes are used the most often during the week. It seems that Monday through Friday the bikes are used most often between 5am-9am and then again between 4 and 8 pm. This is most likely due to people using them to comute to and from work. Saturday and Sunday however the bikes seem to be used more during the day between 9 am and 7 pm

![usagebyweekFemales](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/female_usage_week.png)
We can filter the week heatmap by gender to see if there are any major differences in usage between males and females, the above is filtered to feamles only and it appears very similar to the pattern described above

![usagebyweekMale](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/male_usage_week.png)
When we filter to Males only again we see a very similar pattern to the usage however it seems that the deepest colors are for commuting to and from work rather than weekend usage while the females seem to have more weekend usage

![usertypebyGender](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/usertypes_by_gender.png)
Next we can look at the types of users split by gender. You can see there are a lot more male useres that are subscribers than anyone else. This seems to fit with the narritave that they use the bikes to commute to work.

![usertypefemale](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/usertypes_female.png)
We can filter it only to females in order to see the colors more clearly to get a better idea of what the female usertypes are. the subscribers tend to use the bikes on every day of the week while the customers tend to use them on saturdays and sundays.

![start_location](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/top_starting_locations.png)
Above we mapped the starting locations of the bike rides, with the circle size and color indicating the number of trips that originiated in the area. you can see the majority of htem originate in lower Manhattan 

![end_location](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/top_ending_locations.png)
this map indicates where the ending locations of the bike rides are and the distribution looks very similar to the starting locations, with the majority of the rides ending in lower Manhattan and fewer into outlying areas.

![bike_usage](https://github.com/Melberoni/bikesharing/blob/dee14818a895ca67f03b243f2aef0fd3ece0999d/Story/bikes_by_number_of_trips.png)
in the above graph each circle represents a bike, the size and the color of the cirle indicate how many trips the bike has had. You can see there are a handfull that get used more than the larger proportion in the middle.

## Summary
In summary from the analysis above we can conclude that the bikes have been used in New York City mainly for commuting to and from work, and those that use them tend to be subscribers. however there is usage on the weekends more often for females. the bikes tend to be picked up and dropped off in a small area of the city. the majority of the rides are less than 30 minutes each with many under 10 minutes. We noted that a small number of bikes get used more often than others and one if the next analysis i would do is to find out if those bikes are in the main starting and ending locations or if they are outside of Manhattan. Another graph that i would be interested in creating would be to identify how many rides a nonsubscriber would normally have compared to a subscriber and if there is a difference in average distance per ride between the two groups 
