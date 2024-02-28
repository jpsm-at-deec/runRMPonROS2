# runRMPonROS2 (provisional)


    git clone https://github.com/jpsm-at-deec/runRMPonROS2.git
.    

    chmod u+x ./src/test.sh
        
.   

    ./src/test.sh

.

    .
    ├── ...
    ├── src                    
    │   ├── libsegwayrmp [a]
    │   ├── ros2_segway_rmp [b]    
    │   ├── segway_interfaces [c]
    │   └── serial [d]
    └── ...

[a] [jpsm-at-deec/libsegwayrmp](https://github.com/jpsm-at-deec/libsegwayrmp) (jammy branch)

[b] [jpsm-at-deec/ros2_segway_rmp](https://github.com/jpsm-at-deec/ros2_segway_rmp/)

[c] [jpsm-at-deec/segway_interfaces](https://github.com/jpsm-at-deec/segway_interfaces)

[d] [RoverRobotics-forks/serial-ros2](https://github.com/RoverRobotics-forks/serial-ros2)

.

    source ~/ros2_humble_install_path_of_choice/setup.bash

