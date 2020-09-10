# Using Machine Learning and Citizen Scientists to Navigate Mars


NASA recently launched the Perseverance Rover which will land on Mars in 2021. As with all Mars rovers, one of the main concerns after landing is navigating the terrain of Mars. Three different rovers have gotten caught in sand while on Mars and while Opportunity and Curiosity were able to escape, Spirit's seven year mission was ended by a sand pit. This concern is why Nasa will be equipping Perseverance with the Soil Property and Object Classification (SPOC) algorithm. This machine learning program will help the rover navigate around large sand pits and avoid an untimely end to the mission.

SPOC is a linear support-vector machine (SVM) this is a type of machine learning algorithm similar to what is used by self-driving cars to recognize and avoid obstacles. The difference is that self-driving cars can pull from a large database of images of obstacles they may encounter in order to inform their algorithms. SPOC does not have that kind of database. To address this issue, NASA has created a website (<https://www.zooniverse.org/projects/hiro-ono/ai4mars>) where volunteers can look at images of the Martian landscape captured by older rovers and identify objects within them. The more data that SPOC is able to collect, the more effective it will be at identifying potentially dangerous terrain. While the current goal of SPOC is just to identify features within the Martian landscape, the hope is that it will one day be able to provide other information about the landscape including how likely the rover’s wheels are to slip on each surface to create even safer paths for Perseverance. 

Sources:
<https://mars.nasa.gov/news/8689/nasas-mars-rover-drivers-need-your-help/>
<https://www.zooniverse.org/projects/hiro-ono/ai4mars/about/research>
 
