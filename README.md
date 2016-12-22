# raspimouse_sim_installer
Installer for raspimouse_sim

## how to use

```
$ chmod +x ./install.bash
$ ./install.bash
```

## how to check

Launch the simulator by
```
$ roslaunch raspimouse_gazebo raspimouse_with_samplemaze.launch 
```
and do
```
$ rosrun raspimouse_control controller_vel_publisher.py
```
on another terminal.
