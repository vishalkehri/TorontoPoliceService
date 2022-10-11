# TorontoPoliceService - Assignment
The project was an assignment for testing analytical skills in a fast paced environment. The links to a dataset was provided and the problem was to attach dataset to another relevant dataset to present 3-5 findings and 2-3 recommendations ina report format with at least 2 maps and 2 charts/figures. The assignment was to be completed within the time limit of 2 hours and should be received by the recipient within the given time frame.

# Data Explanation
Bicycle theft data of the Greater Toronto Area was used to analyze the thefts of bicycles in the region for the period of 2014 to 2018.

# Approach
The assignment was supposed to be completed for the ground staff to take necessary measures for prevention of this crime therefore, the second dataset used was the Patrol Zone boundaries. This dataset was chosed over the municipal boundaries as the ground staff was following the patrol zone boundaries to monitor the area and would be easier to navigate through the crime locations. Further to provide detailed data, hotspot analysis was performed in order to determine the required number of staff members based on the number of incidents that took place in particular areas. The intent was to provide the hotspots to ensure optimum coverage throughout GTA and increase the efficiency of patrolling.

# Analysis
The analysis was performed using FME (Feature Manipulation Engine) using transformers to perform hotspot analysis. Moreover, a buffer of 10 metres was created around the theft locations to determine if the bicycles were parked in the designated parking locations. The results showed that 90% of the bicycles were parked outside of the buffer zone, indicating that 90% of the bicycles were stoled as a result of negligence and lack of the use of bike locks. 

# Recommendations
Recommendations were made to create an allocation plan for the ground staff to patrol based on the hotspots created along with spreading awareness regarding the importance of proper use of bike lick and designated bike parking locations.
