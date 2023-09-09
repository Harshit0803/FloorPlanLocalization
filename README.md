<!--# FloorPlanLocalization-->
# Real-Time Visually Assisted System for Indoor Localization and Navigation From Unknown Start Locations

## 📄 Abstract
<div align="justify">
A novel methodology is developed to navigate an agent (e.g., a robot or a visually impaired person) to target locations specified in an *a priori* architectural floor plan starting from unknown locations. An active global localization method is proposed to create semantically aware *a priori* map based real-time goals for the agent to safely and intelligently explore the local environment while simultaneously constructing a semantic point cloud (SPCL) to globally localize the agent. The agent navigates to the target on successful localization by planning the shortest path from the estimated current location. Furthermore, a method is proposed to dynamically correct the time-varying odometry drift without knowing the global pose of the agent. The efficacy of the proposed algorithm is shown by conducting experiments in an indoor environment.
</div>

| Floor Plan                         | Point Cloud                 | Semantic Cloud              |
| :--------------------------------:| :--------------------------:| :--------------------------:|
| <img src="assets/Floor_Plan.png" alt="Floor Plan" style="width: 600px; height: 400px;" /> | <img src="assets/point_cloud.gif" width="400" height="350" />  | <img src="assets/semantic_cloud.gif" width="400" height="350" />  |


## TEST BLOCK                                                                                                                                                           
![image](https://github.com/raktimgg/FloorPlanLocalization/assets/139596157/11c71a41-4f3c-4928-ab86-c67ff0c7cd31)  

*Figure 1: Basement FloorMap for Ground Truth*

<a href="#" style="float: right;"> <!-- An anchor tag with a right float style -->

| Index | Starting Point (X) | Starting Point (Y) | End Point (X) | End Point (Y) |
| ----- | ------------------- | ------------------- | -------------- | -------------- |
| 1     | 95                  | 390                 | 10             | 270            |
| 2     | 250                 | 77                  | 10             | 270            |
| 3     | 250                 | 250                 | 10             | 270            |
| 4     | 50                  | 70                  | 10             | 270            |
| 5     | 26                  | 390                 | 10             | 270            |
| 6     | 115                 | 320                 | 50             | 70             |
| 7     | 210                 | 450                 | 50             | 70             |
| 8     | 195                 | 70                  | 50             | 70             |
| 9     | 277                 | 70                  | 50             | 70             |
| 10    | 127                 | 392                 | 50             | 70             |
| 11    | 275                 | 70                  | 115            | 330            |
| 12    | 10                  | 385                 | 115            | 330            |
| 13    | 248                 | 248                 | 115            | 330            |
| 14    | 70                  | 70                  | 115            | 330            |
| 15    | 210                 | 450                 | 115            | 330            |
| 16    | 50                  | 390                 | 250            | 200            |
| 17    | 230                 | 70                  | 250            | 200            |
| 18    | 250                 | 250                 | 250            | 200            |
| 19    | 118                 | 70                  | 250            | 200            |
| 20    | 10                  | 240                 | 250            | 200            |


</a>

![image](https://github.com/raktimgg/FloorPlanLocalization/assets/139596157/35654757-1905-400e-bc42-7a646b7a448e)
               
*Figure 2: Second Floor FloorMap for Ground Truth*

<a href="#" style="float: right;"> <!-- An anchor tag with a right float style -->

| Index | Starting Point (X) | Starting Point (Y) | End Point (X) | End Point (Y) |
| ----- | ------------------- | ------------------- | -------------- | -------------- |
| 1     | 198                 | 135                 | 155            | 470            |
| 2     | 225                 | 465                 | 155            | 470            |
| 3     | 8                   | 131                 | 155            | 470            |
| 4     | 220                 | 133                 | 175            | 75             |
| 5     | 266                 | 382                 | 175            | 75             |
| 6     | 10                  | 255                 | 175            | 75             |
| 7     | 219                 | 490                 | 175            | 75             |
| 8     | 170                 | 135                 | 219            | 490            |
| 9     | 268                 | 219                 | 219            | 490            |
| 10    | 8                   | 415                 | 219            | 490            |


</a>




