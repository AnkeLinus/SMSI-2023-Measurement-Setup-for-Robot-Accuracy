# SMSI-2023-Measurement-Setup-for-Robot-Accuracy

## Data set
The data was used to calculate the pose repeatability and path accuracy of robots. It consists of 2 different measurement sets per robot. The data set for path accuracy are 2D laser data measured along an edge. In the below mentioned publication are more details to the calculation of the path error. The start and end point data (mean of measured position while the robot did not move) are used to determine the location of the robot at the beginning and end. The robot was programmed to move along the edge on a linear path.
The data sets for pose repeatability were measured at one sphere per robot, more then 30 times. Circle fitting and the ISO 9283 calculations have been used to derive pose repeatability. Some measurements include peaks and have been excluded in the calculation of below mentioned publication.

Data for path accuracy:
- HIWIN_calc_path_08_22_49.txt - start and end position
- HIWIN_path_08_22_49.asc - measured data
- KUKA_calc_path_10_13_25.txt - start and end position
- KUKA_path_10_13_25.asc - measured data

Pose repeatability:
- Pose HIWIN.zip - all measurements executed at one sphere
- Pose KUKA.zip - all measurements executed at one sphere

The coloumns represent the  x, y, z coordinates of the 2D laser sensor. X corresponds to the movement of the robot along the linear path. Data of the same x-value (in path accuracy calculation) represent one profile.

## Authors and acknowledgment
Markus Gapp conducted the data acquisition. Anke Fischer-Janzen hosts the git. 

## License
You may use this data for scientific, non-commercial purposes, provided that you give credit to the owners when publishing any work based on this data. We would also be very interested to hear back from you if you use our data in any way and are happy to answer any questions or address any remarks related to it. For citation use:

Thomas M. Wendt, Markus Gapp, Anke Fischer. 'Innovative and cost-effective Measurement Setup to determine Robot Accuracy' SMSI 2023 Conference, doi: 10.5162/SMSI2023/D4.4
