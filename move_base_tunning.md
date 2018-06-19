# Before
[![Video Label](http://img.youtube.com/vi/aEj4FfYdG10/0.jpg)](https://youtu.be/aEj4FfYdG10?t=0s)  

# After
[![Video Label](http://img.youtube.com/vi/G7gvJs_XhSg/0.jpg)](https://youtu.be/G7gvJs_XhSg?t=0s)  

base parameter is below link  
-> https://github.com/ROBOTIS-GIT/turtlebot3/blob/master/turtlebot3_navigation/param/dwa_local_planner_params_waffle.yaml  

I modify 2 parameter  
acc_lim_theta: 3.2 ->  6.5  
sim_time: 2.0 -> 1.0 

#parameter description  
acc_lim_theta   
 theta축 각가속도 제한 ( radian/sec^2)  
 (double, default: 3.2)  
 The rotational acceleration limit of the robot in radians/sec^2  
 
sim_time (double, default: 1.0)  
 전방향 시뮬레이션 궤적 시간  
 The amount of time to forward-simulate trajectories in seconds 
 The amount of time to roll trajectories out for in seconds

