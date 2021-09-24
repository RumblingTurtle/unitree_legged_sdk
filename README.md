## Unitree legged sdk as a python package

### Install python package
    
```
pip3 install .
```

### Add original legged sdk libs to ~/.bashrc
```
export LD_LIBRARY_PATH=~/unitree_legged_sdk/lib:${LD_LIBRARY_PATH}
```

### Usage
```
from robot_interface import RobotInterface
robot_interface = RobotInterface()
```