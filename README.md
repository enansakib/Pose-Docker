# Pose-Docker

Refer to the `https://github.umn.edu/IRVLab/ROS-Docker` repository for details regarding docker container setup. 

## Run a Pose container
```
git checkout <pose-container-branch> (e.g. hrnet)
docker pull rogueraptor7/ros-DISTRO:BRANCHNAME (e.g. ros-noetic-cuda:hrnet)
./run-container.sh noetic-cuda
```
