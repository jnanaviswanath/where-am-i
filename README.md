
# Where Am I?

In this project, you will learn to utilize ROS packages to accurately localize a mobile robot inside a provided map in the Gazebo and RViz simulation environments.

Over the course of the project, as part of the Robotics Software Engineer Nanodegree, you will learn about several aspects of robotics with a focus on ROS, including -

- Building a mobile robot for simulated tasks.

- Creating a ROS package that launches a custom r-obot model in a Gazebo world and utilizes packages like AMCL and the Navigation Stack.

- Exploring, adding, and tuning specific parameters corresponding to each package to achieve the best possible localization results.



## Run the Project

After completing the project, you can launch it by running the following commands first -

```bash
$ cd ~/catkin_ws
$ catkin_make
$ source devel/setup.bash
```

And then run the following in *separate* terminals - for udacity_bot

``` bash
$ roslaunch udacity_bot udacity_world.launch
$ roslaunch udacity_bot amcl.launch
$ rosrun udacity_bot navigation goal
```

run the following in *separate* terminals - for udacity_bot

``` bash
$ roslaunch jnana_bot jnana_world.launch
$ roslaunch jnana_bot amcl_jnana.launch
$ rosrun jnana_bot navigation_goal
```
