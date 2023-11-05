# libmicroros

NTURacingTeam repository for tracking [micro-ROS/micro_ros_zephyr_module](https://github.com/micro-ROS/micro_ros_zephyr_module).

Since the original repository is not structured to be a zephyr project but was designed to be a one. In order to be included in the west manifest file, a repository restructuring is needed.

Currently, it's tracking the [iron branch](https://github.com/micro-ROS/micro_ros_zephyr_module/tree/iron), but the [serial transport](microros_transports/serial) id from the [humble branch](https://github.com/micro-ROS/micro_ros_zephyr_module/tree/humble) in order for it to work.

## Depencencies

Micro ROS requires colcon as the build system and other python packages, which can be installed by:

```bash
sudo pip3 install catkin_pkg lark-parser empy colcon-common-extensions
```

> Note: Using `sudo` as the default `PATH` environment variable does not have the user's `~/.local/bin` directory.
