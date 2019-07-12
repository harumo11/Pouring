# 2019/07/12-13

## Data 

1. time
2. angular velocity[deg/sec]
3. angle[deg]
4. Sv(x length after falling 0.2m)
5. Tip displacement

## Data Frequency

0.02 [sec]

## Target

The target is setting environment that the experiment will be conduct.

## TODO

- Position of robot arm tip.
- Moving the robot with angle without water.
- Moving the robot with angle and angular velocity without water.
- Moving the robot with angle and angular velocity with water.

## Setings

### Netwrok

- robot ip : 10.0.0.2
- Yip ip : 10.0.0.6
- Harumo ip : 10.0.0.8
- Midori : 10.0.0.7

### Initial position

- x : -0.5371
- y : 0.003181
- z : 0.7051
- roll: 3.141592
- pitch: 1.5708
- yaw: 0
- Height between yuguchi and syuttouguchi : 0.455m
- link_s: 0.191253319383
- link_l: -1.77183318138
- link_e: -2.94609546661
- link_u: 2.08333349228
- link_r: 0.154142275453
- link_b: -1.84653306007
- link_t: -2.90557050705

## Commands

### moveit and connection

```sh
roslaunch motoman_sia20d_moveit_config moveit_planning_execution.launch sim:=false robot_ip:=10.0.0.2 controller:=fs100
```

