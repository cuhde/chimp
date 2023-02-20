# CHiMP
This is the supplementary repository to the paper [CHiMP: Contact based Hilbert Map Planner](https://ieeexplore.ieee.org/abstract/document/8794013)
```
@inproceedings{uhde2019chimp,
  title={CHiMP: A Contact based Hilbert Map Planner},
  author={Uhde, Constantin and Dean-Leon, Emmanuel and Cheng, Gordon},
  booktitle={2019 International Conference on Robotics and Automation (ICRA)},
  pages={8381--8387},
  year={2019},
  organization={IEEE}
}
```
## Source Code
The submodules are currently private. Please contact the authors for access.
### Python Code
[Python proof-of-concept](https://github.com/cuhde/occupy)
### C++ Code
[CHiMP planner plugin](https://github.com/cuhde/graze_plugin)  
[CHiMP controller](https://github.com/cuhde/graze_controller)
## Videos

### Compliant exploration planner comparison
This is a playlist of a planner comparison between the presented CHiMP planner and RRT, PRM, STOMP and CHOMP. The goal is to plan inside the loop from three different starting positions. The main performance criteria are total execution time and number of required contacts.  
[![Loop goal planning comparison](https://img.youtube.com/vi/YQoM_yYdHWY/0.jpg)](https://www.youtube.com/watch?v=YQoM_yYdHWY&list=PLFfiC0AL7M4wdfjNei8DvQpZzAR8HsBQv)

### Further testing
After establishing the CHiMP planner as suitable plugin for the setup, three more experiments are conducted with the proposed planner.
### New obstacle
This experiment showcases the ability of the proposed system to react to new obstacles in previously covered workspace.  
[![New obstacle avoidance planning](https://img.youtube.com/vi/2-DXcPCJ9ZE/0.jpg)](https://www.youtube.com/watch?v=2-DXcPCJ9ZE)

### Hilbert map remapping
This experiment showcases the behavior change through Hilbert map remapping, to achieve exploration.  
[![Explorative planning](https://img.youtube.com/vi/Gq7MypOmJ-4/0.jpg)](https://www.youtube.com/watch?v=Gq7MypOmJ-4)

### Narrow goal
This experiment showcases the performance of the proposed systems in difficult (narrow) environments.  
[![Narrow goal planning](https://img.youtube.com/vi/h7d_gMeDMLo/0.jpg)](https://www.youtube.com/watch?v=h7d_gMeDMLo)
