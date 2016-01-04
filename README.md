# Data-Visualization-using-Dimple.js-D3.js
Data Visualization of baseball players performance using D3.js and Dimple.js

## Summary

This data visualization helps a reader to gain insights on player's performance, which has been affected by several 
other charaterstics of player. The reader can interact with the visualization by selecting the handedness and height 
of players from the dataset. The main graph between weight and average of player along with total number of Home-runs 
as distinguishing feature helps the reader to get an idea of player's good or bad performance factors.


## Design

I started my assignment by plotting the players distribution according to their heights respectively. But this turn out 
to be only one of the several features of my final visualization where I used the findings from my inital graph as an 
indicator to show the players' average by selecting each height bar.

I started my final visualization with handedness and heights as legends to toggle for showing the average of players with 
respect to their weights. Later onward I put the handedness in the legends and made another chart with the same visualization to provide animation based on heights of players. I faced an issue in animation on click of a given parameter. After stopping animation by clicking once on any given height, the animation starts again during subsequent selection of handedness. 

I find really difficult resolving this issue. However, I did find a temporary solution which I have mentioned in the 
directions on the visualization. By selecting first handedness and then height of player, we can stop the animation and 
analyze the visualization.



## Resources

Documentation of d3.js and dimple.js was used for reference.
