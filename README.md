# 3.1_kimjeongyeon
작업 공간에 rrbot_pushing_object_basic 패키지를 다운로드 했습니다.

```$ cd ~/catkin_ws/src git clone https://github.com/srebroa/rrbot_pushing_object.git```

이후 작업공간에서 catkin make를 실행합니다.

```$ cd ~/catkin_ws $ catkin_make```

패키지 경로로 이동하여 rrbotsimstart.sh를 실행합니다.

```$ cd ~/catkin_ws/src/rrbot_pushing_object/rrbot_pushing_object_basic```

```$ bash rrbotsimstart.sh```


이 스크립트는 네 개의 파일을 한번에 실행시킵니다.

```rrbot_gazebo_launch.sh```
```rrbot_ros_control.sh```
```rrbot_pushing_object.sh```
```rrbot_camera_view.sh```

실행되면 로봇 팔이 상자를 밀어냅니다.
![gazebo](https://user-images.githubusercontent.com/84000076/119892091-b5138900-bf74-11eb-8a83-55a8e254a6d5.png)

또한 카메라로 바라보는 방향을 촬영합니다.
![camera](https://user-images.githubusercontent.com/84000076/119892152-cbb9e000-bf74-11eb-859a-0076d33d628b.png)



3.1 예제 구동 완료 하였고 다음은 .  
![Screencast from 2021년 05월 17일 19시 59분 53초](https://user-images.githubusercontent.com/84000076/118479522-13a65f00-b74c-11eb-8d66-5781a6030fdb.gif)
