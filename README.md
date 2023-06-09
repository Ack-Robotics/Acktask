# Five Finger - 9 DOF Arm controlled using moveit and mediapipe 

Formal approach to manipulating the Schunk SVH 5-finger,9 dof hand based on real-world hand poses captured through a monocular camera. By combining computer vision techniques with robotics control from MoveIt, we demonstrate the ability to replicate hand gestures on the robotic hand. To achieve this, we leverage Google's MediaPipe package for accurate finger gesture identification and pose estimation. The proposed system enables intuitive and seamless control of the robotic hand, enhancing its usability in various applications requiring dexterous manipulation. Through experimentation, we showcase the feasibility and effectiveness of our approach, opening new avenues for gesture-based human-robot interaction and collaboration.


# Our Result
![alt text](https://github.com/Ack-Robotics/Acktask/blob/main/assets/9_dof_using_moveit.jpg)

## Rock
https://drive.google.com/file/d/1b_jf83BvcyDce4bHIU9XQ47kgylGAIKr/view?usp=drive_link

## Peace
https://drive.google.com/file/d/1ciGaIb8fhNe574949x5b7XpTnqRNBdvB/view?usp=drive_link

## Stop
https://drive.google.com/file/d/14L-cI_Go09OoK4eDI-InlFKM7wRfAew-/view?usp=drive_link

## Demonstration Setup
1. Clone this repository

   ```bash
   mkdir -p ~/arm_ws/src
   cd ~/arm_ws/src
   git clone https://github.com/Ack-Robotics/Acktask.git
   
   ```
   
 2. Catkin_make
  ```bash
    cd ~/arm_ws
    catkin_make_isolated   
   ```
 3. Rviz for visualization 
```bash
    cd ~/arm_ws
    source devel/setup.bash 
    roslaunch demo.launch
    
   ```
 4. Python script for arm movement
 ```bash
    cd ~/arm_ws/
    source devel/setup.bash 
    roslaunch demo.launch
    
   ```
