## Hi, I'm Balakumar 👋

Robotics engineer from India with 3+ years building perception, navigation and manipulation for real robots with ROS and ROS 2, from Gazebo simulation to field deployment on outdoor and agricultural robots.

### What I've built

- **Outdoor navigation:** GPS + IMU + wheel-odometry EKF fusion, TEB tuning for non-holonomic robots, and a custom slope-aware costmap layer from point-cloud surface normals.
- **Vision-guided manipulation:** a grape-harvesting arm: YOLOv5 instance segmentation → RealSense depth → 3D grasp point → MoveIt on a Dobot Nova 5 with an OctoMap collision scene.
- **Semantic navigation:** "Navigate to the man in a white shirt": a Moondream VLM and Qdrant memory pick the goal, and Nav2 drives there (TurtleBot4 sim).
- **Multi-robot exploration (current):** three robots map an unknown building together in Gazebo, each running its own SLAM, with a merged map and a frontier coordinator. ROS 2 Humble, slam_toolbox, Nav2, rmw_zenoh.

### Tools

ROS / ROS 2 · Nav2 · MoveIt · slam_toolbox · Cartographer · robot_localization · Gazebo

Python · C++ · OpenCV · PCL · YOLOv5 · RealSense · NVIDIA Jetson · Linux
