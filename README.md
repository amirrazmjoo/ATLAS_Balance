# Introduction

This project is a part of the Legged Robot course at EPFL. The focuse here is on the development of an optimization-based controller for bipedal robots utilizing the divergent component of motion (DCM). The key components required for this goal include DCM planning and optimization, a Foot Trajectory Planner, and Inverse Kinematics. Our specific contribution to the project involves the design of the desired foot location, leveraging the provided tools to influence the robot's behavior. To validate the effectiveness of the controller, a simulation of the Atlas robot using pybullet is employed. 

Three tasks are utilized to validate our method. Firstly, we examin the method with a toy example that aligns with our underlying assumptions. Following this, the real robot is subjected to a one-step push recovery test, evaluating its ability to regain balance in the face of external disturbances. Lastly, the robot undergoes testing in a walking scenario, evaluating its capacity to maintain balance in presence of external disruptions.

# Results
## One-Step Push Recovery
![One_step_push_recovery](https://github.com/amirrazmjoo/ATLAS_balance_EPFL_course/blob/main/gif/push_recovery.gif)
## Push Recovery + Locomotion
![Walking_Scenario](https://github.com/amirrazmjoo/ATLAS_balance_EPFL_course/blob/main/gif/walking.gif)
