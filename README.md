# rp_ultrasonic_sensor

A ROS 2 package designed to integrate and publish HC-SR04 ultrasonic sensor data using the `sensor_msgs/Range` message type. This package was built from scratch to facilitate obstacle detection for robotic applications.

## Features

- Publishes ultrasonic sensor readings in ROS 2.
- Supports multiple HC-SR04 sensors.
- Provides real-time distance measurements for obstacle avoidance.
- Compatible with ROS 2 Humble Hawksbill.

## Installation

### Prerequisites

Ensure you have ROS 2 Humble installed. If not, follow the [ROS 2 installation guide](https://docs.ros.org/en/humble/Installation.html).

### Clone the Repository

```bash
cd ~/ros2_ws/src
git clone https://github.com/jovanj91/rp_ultrasonic_sensor.git
cd ~/ros2_ws
colcon build --packages-select rp_ultrasonic_sensor
source install/setup.bash
