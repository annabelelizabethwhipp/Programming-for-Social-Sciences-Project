# Programming-for-Social-Sciences-Project
GEOG5995M Planning for Drunks Assessment

The basic concept for this assessment was to build an ABM which models drunk people leaving a pub and returning to their home. 
The drunks leave the pub one at a time, and a new drunk can only leave the oub when the prvious drunk has reached home.The 
model is set to run until all the drunks reach home.
Here is a step by step guide to the code:

1. It reads in drunk.plan.txt. This file is the environment data.

2. It reads the environment data into rows.

3. A new environment called 'mapenvironment' is then created. This provides an environment for the density plot to be drawn on.

4. The agents are told to look for the location of the pub, utilsing X and Y coordinates.

5. The agents are informed their house numbers are their number plus one and multiplied by ten.

6. The code then tells the agents to add one to the environment each time they move within each iteration.

7. If the agents are home they stop moving.

8. If they have not reached their home they carry on moving.

9. The mapenvironment is printed. This produces a density map.

10. The agents tell the user when they have reached their home.

11. The agents are displayed statically on a map, the colour of the agents is turned to white when they reach their home. 

12. The density map saves to a csv file.
