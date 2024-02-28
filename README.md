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

[a] https://github.com/jpsm-at-deec/libsegwayrmp (jammy branch)

[b] https://github.com/jpsm-at-deec/ros2_segway_rmp/

[c] https://github.com/jpsm-at-deec/segway_interfaces

[d] https://github.com/jpsm-at-deec/serial

.

    source ~/ros2_humble_install_path_of_choice/setup.bash

