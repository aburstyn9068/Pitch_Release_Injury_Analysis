# Pitch_Release_Injury_Analysis
This repository contains the code and data sets used to analyze trends between changes in pitch release points and injury.

This study set out to investigate trends in changes of a pitchers release point in the x, z, and y  axes around the time of a UCL injury. Trends were compared to a baseline time period where there were no known injuries.

Three players with known UCL injuries were selected to investigate: Drew Hutchinson, Randy Wolf, and Brandon Beachy.

Data was collected on the pitch relase points in the x, y, and z axes. The data was collected from Baseball Savant, which uses the Statcast tracking system.
    -https://baseballsavant.mlb.com/

Variable definitions:
release_pos_x: Horizontal Release Position of the ball measured in feet from the catcher's perspective.
release_pos_z: Vertical Release Position of the ball measured in feet from the catcher's perspective.
release_pos_y: Release position of pitch measured in feet from the catcher's perspective.
    -https://baseballsavant.mlb.com/statcast_search
    
The means of the pitch release point in the each plane for each type of pitch were analyzed for a given time period. Linear regression analysis was used to compare the trends.

A similar trend of change in the x-axis release point leadig up to injury was found in two of the pitchers. Examining these patterns in a pitcher may give insight into thier risk of injury. While it was noted that there was a similar trend in two of the players, this is not enough evidnece to determine a cause and effect relationship to determine injury probability. Further invesitgation into more players may result in a more predictable pattern.

Limitations:
The main limitation in this investigation is the lack of access to information. Outside variables such as workout protocols/volumes and injury status (a player playing through an injury) are unkown. Another unkown varaible that can alter the pitch release point would be a player changing thier technqiue/mechanics.
The small sample size of this investigation limits its ability to make broad conclusions.

Futher Questions:
1. Is there a quantifiable degree of change which signifies danger to a players health?
2. Is there a maximal degree of changes in movement mechanics during a certain time period that increases a players risk for injury. Is there an optimal degree of variation for an individual to change thier movement patterns during a given time window that allows for adequate tissue adapataion to handle the change in stress vectors/levels?
