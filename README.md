#############################################################################################

            				Fine-grained AQI Dataset	  				    
							 
			State Key Laboratory of Advanced Optical Communication System and Networks 
 
					   Peking University         	                 
#############################################################################################


Introduction
===================================================
The Fine-grained AQI dataset was captured using a mobile sensing system which consists of corresponding sensors and an UAV,
in typical 2D (i.e., a roadside park) and 3D (i.e., a vertical enclosed space inside a tall building) scenario, respectively.


Annotations
===================================================
The dataset contains TWO PARTS:

### Data for typical 2D scenario (in folder 'data_for_2d')

In 2D (a roadside park) scenario, the height is assumed as __z=0__. All .txt file contains 40 measuring locations.

The first point's coordinate is (0,0), and the interval of each point (either in x-axis or y-axis) is 5m.

The whole 2D space is hence (45m * 15m).

### Data for typical 3D scenario (in folder 'data_for_3d')

In 3D (a vertical enclosed space inside a tall building) scenario, all .txt file contains 45 measuring locations.

Every col in these files represents a fixed height, increasing from 0m to 40m with an interval of 5m:

__Col number from 1 to 9__
1. z = 0
2. z = 5
3. z = 10
4. z = 15
5. z = 20	
6. z = 25
7. z = 30
8. z = 35
9. z = 40

Every row contains 5 points, their coordinates in 2-dimensional is (x, y):

__Row number from 1 to 5__
1. (10, 0)
2. (25, 0)
3. (25, 30)
4. (10, 30)
5. (0, 20)

The whole 3D space is (40m * 40m * 40m).


Raw Data
===================================================
All data for two scenarios contains 60 consecutive days' measurment, and can be used either as training data or testing data.


Questions?
===================================================
Contact Yuzhe Yang at yuzhe.yang@pku.edu.cn


June 2017