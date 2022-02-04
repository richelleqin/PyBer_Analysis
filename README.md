# PyBer_Analysis
## Overview of the analysis
### Purpose
The purpose of this analysis is to create a summary DataFrame of the ride sharing data by city type, and using it, create multiple-line graph to show the total weekly fares for each city type. Using these visuals and DataFrame, we can then help PyBer strategize for their business goals. 
## Results
### From summary table
Looking into the summary DataFrame, it may be deceptive to think that Urban does much better than Suburban or Rural. Calculating the rides per driver reveals that Urban has 0.67 rides per driver, whereas Suburban has 1.27 rides per driver, and Rural has 1.6 rides per driver. Also considering the fact that the average fare for the urban population is less (most likely due to shorter distance) and that there is a low likelihood of a high fare rider occurring like in the Rural area as suggested by the high Average Fares per Driver metric, we can confidently propose that the Urban setting is not as profitable to the driver as the Rural or Suburban settings. To be brief, the Urban area has less profitable rides and more competition for drivers, the Suburban area has more consistent riders with consistent fares, and the Rural area has more profitable riders with high value and high distance rides. 
![1](https://user-images.githubusercontent.com/67567087/152464185-949680e9-2967-4498-924d-280f5819c519.PNG)

### From graph
The graph shows seasonality for the areas. 
 - For Urban, the beginning of January brings travel away from Rural for the holidays. As February approaches, people come back to the Rural and travel goes back to its normal levels. As Valentines and Family day approaches at the end of February, travel increases again to travel away from Rural. Then it dies down as March Break/Reading week passes towards Easter holidays. These holidays in Rural provides more high value travel as riders move away long distances to their families. 
 - For Suburban, the holidays are where people tend to do less travelling, as families come to their homes in the area. This is why the beginning of January is a low rider time, and it goes back to the normal ridership as the holidays cool. There is a spike towards Valentines and Family day, as people travel outside their homes to celebrate. Ridership also lowers during Easter as people spend time at home. 
 - For Urban, like Suburban, ridership is low at the beginning of January as shops are closed and people don’t need to travel. It cools back to normal level until around valentines and family day, in which like Suburban, people travel out of their home to celebrate. The bumps in March showcases that reading week and March break causes less riders to have to go to school. 
![pyber](https://user-images.githubusercontent.com/67567087/152464280-ffbcf050-b245-41d1-b625-22cb94c710af.png)

## Summary
1) Reduce the number of drivers in the Suburban area to allow at least an average of 1 driver per ride. This means reducing the competition and providing more profitable rides per driver. 
2) Provide deals to promote ridership during the Valentines and Family Day period as ridership is higher during that time for all 3 areas.
3) Allow a student fare during March Break/Reading week to promote ridership during the holidays for students at home in urban areas. 
