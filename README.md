## Hi, I'm Balakumar 👋

Robotics engineer from India. I build ROS 2 navigation and mapping systems: SLAM, Nav2, and multi-robot exploration in simulation.

### What I'm working on

**Multi-robot exploration.** Three robots map an unknown building together in Gazebo, each running its own SLAM, with a shared merged map and a coordinator that splits up the frontiers. ROS 2 Humble, slam_toolbox, Nav2 (Regulated Pure Pursuit), rmw_zenoh.

### Open-source contributions

- **[m-explore-ros2](https://github.com/robo-friends/m-explore-ros2)** (explore_lite for ROS 2)
  - [#56](https://github.com/robo-friends/m-explore-ros2/pull/56): fixed robots not returning home after exploration (a cancel race with Nav2). With the fix, every robot got home in 5 of 5 runs, against 1 of 5 before.
  - [#54](https://github.com/robo-friends/m-explore-ros2/issues/54), [#57](https://github.com/robo-friends/m-explore-ros2/issues/57): found and reported two bugs in frontier selection (distance units, centroid off by one cell).
- **[slam_toolbox](https://github.com/SteveMacenski/slam_toolbox)**
  - [#906](https://github.com/SteveMacenski/slam_toolbox/issues/906): reproduced a crash on zero-valued scan-matcher parameters and traced it to a division in the matcher.

### Tools

ROS 2 · Nav2 · slam_toolbox · Gazebo · C++ · Python · DDS / Zenoh · Linux

Also: Flutter, Angular / TypeScript (earlier app and web work).
