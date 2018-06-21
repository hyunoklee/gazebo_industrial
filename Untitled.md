Industrial Mobile Robot
2018sus 6월 20일

**이번주 Target 
Gazebo 상에 Turtlbot3개 동시에 올려서 multi AGV 하는 package 제작**

1.기본 move base(dwa_planner)로 움직이다 세대간 충돌이나 길이 꼬임이 감지되면 TB3 control을 move_base에서 뺏어와서 정지, cmd_vel control, 혹은 다른 planner 변경, 특정 위치로 이동 시키는 기능을함. 
결론은 move_base만 사용시 충돌 날수 있기 때문에 3대가 원활하게 움직일수 있는 기능을 하는 컨트롤러, 직진성 planner를 포함한 packages 제작

충돌 관련해서는 이전 공유된 맵기반 고민해봅세다 ?
![](https://github.com/hyunoklee/gazebo_industrial/blob/master/picture/KakaoTalk_20180620_232344047.png?raw=true)

일주안에 하기엔 무리가 있지만 일단 해보는걸로 한것 같습니다. 