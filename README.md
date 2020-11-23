# Laser Scan Matcher for ROS2
Ported to ros2 version of laser-scan-matcher by [scan_tools](https://github.com/ccny-ros-pkg/scan_tools).


## Installation
* Install modified version of [csmlib](https://github.com/AlexKaravaev/csm)

## Topics

### Subscribed topics
- `/scan` ([sensor_msgs/LaserScan](http://docs.ros.org/melodic/api/sensor_msgs/html/msg/LaserScan.html))
- `/tf` ([tf2_msgs/TFMessage](http://docs.ros.org/melodic/api/tf2_msgs/html/msg/TFMessage.html))
### Published topics
- `/tf` ([tf2_msgs/TFMessage](http://docs.ros.org/melodic/api/tf2_msgs/html/msg/TFMessage.html)) with transform odom->base_link


## Will be released features:
- [x] Support of pure laserscan
- [ ] Support of IMU
- [ ] Support of odometry
- [ ] Support of PointCloud msgs
