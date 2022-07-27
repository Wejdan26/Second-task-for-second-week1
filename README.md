# Second-task-for-second-week1

How to install Ros on ubinto..

##Installation..

1.1/ Configure your Ubuntu repositories

Configure your Ubuntu repositories to allow "restricted," "universe," and "multiverse."

1.2/ Setup your sources.list

$sudo sh -c 'echo "deb http://packages.ros.org/ros/ubuntu $(lsb_release -sc) main" > /etc/apt/sources.list.d/ros-latest.list'

1.3/ Set up your keys

$sudo apt install curl # if you haven't already installed curl
curl -s https://raw.githubusercontent.com/ros/rosdistro/master/ros.asc | sudo apt-key add -

1.4/ Installation

$sudo apt update

Desktop-Full Install:

$sudo apt install ros-noetic-desktop-full

1.5/ Environment setup

$source /opt/ros/noetic/setup.bash









