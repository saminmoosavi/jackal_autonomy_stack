# Driving Jackal
### To drive the jackal autonomously from command line with constant speed and yaw rate, run 
```bash
rostopic pub -r 10 /cmd_vel geometry_msgs/Twist "linear:
  x: -0.1
  y: 0.0
  z: 0.0
angular:
  x: 0.0
  y: 0.0
  z: 0.1" 
```

