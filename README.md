# mpc_ros_model 

## Overview

- This repository supports the `mpc_ros` repository for controlling various model like differential drive model, ackermann, holonomic model. This integrates the different models from other public packages, therefore you can clone the references separately.

## Requirements
``` sudo apt-get install ros-melodic-hector-gazebo-plugins ros-melodic-ackermann-steering-controller ros-melodic-rqt-robot-steering```

## Laucnch the Models 

### Differential Drive model

```roslaunch mpc_ros_description differential_model.launch```

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef45e537-291a-4fee-80bd-acacb4118c13/Screenshot_from_2021-02-08_13-16-13.png](./assets/diff_model.gif)

### Ackermann model

```roslaunch mpc_ros_description ackermann_model.launch```

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/ef45e537-291a-4fee-80bd-acacb4118c13/Screenshot_from_2021-02-08_13-16-13.png](./assets/ackermann_model.gif)

### Bicycle model
```roslaunch mpc_ros_description bicycle_model.launch```

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/fd751637-0aae-49da-ad90-e07a13ad4369/bicycle.gif](./assets/bicycle_model.gif)

### Holonomic model
```roslaunch mpc_ros_description holonomic_model.launch```

![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/5fddeff9-52f5-4a36-a245-4fdb19538759/Untitled.png](./assets/holonomic_model.gif)


### Can select the model according to argument

```roslaunch mpc_ros_description models.launch```


## References

- [serving_bot](https://github.com/CzJaewan/servingbot)
- [differential_drive](http://wiki.ros.org/differential_drive)
- [steer_drive_controller](http://wiki.ros.org/steer_drive_controller)
- [steer_drive_ros](http://wiki.ros.org/steer_drive_ros)
- [hector_gazebo_plugins](http://wiki.ros.org/hector_gazebo_plugins)

