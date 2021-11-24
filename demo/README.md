# Running micro-ROS agent

Docker Images for micro-ROS: https://github.com/micro-ROS/docker

## Running

```
docker run -it --net=host microros/micro-ros-agent:galactic udp4 -p 9999
```