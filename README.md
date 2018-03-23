# graze
This is the supplementary repository to the paper "GRAZE: Reactive Stochastic Functional Gradient Path Planning Using Multimodal Robot Skin and Hilbert Maps"

## Source Code
The submodules are currently private. Please contact the authors for access.
### Python Code
[Python proof-of-concept](https://github.com/cuhde/occupy)
### C++ Code
[GRAZE planner plugin](https://github.com/cuhde/graze_plugin)  
[GRAZE controller](https://github.com/cuhde/graze_controller)
## Videos

### Compliant exploration planner comparison
This is a playlist of a planner comparison between the presented GRAZE planner and RRT, PRM, STOMP and CHOMP. The goal is to plan inside the loop from three different starting positions. The main performance criteria are total execution time and number of required contacts.
[![Loop goal planning comparison](https://img.youtube.com/vi/YQoM_yYdHWY/0.jpg)](https://www.youtube.com/watch?v=YQoM_yYdHWY&list=PLFfiC0AL7M4wdfjNei8DvQpZzAR8HsBQv)

### Further testing
After establishing the GRAZE planner as suitable plugin for the setup, three more experiments are conducted with the proposed planner.
### New obstacle
This experiment showcases the ability of the proposed system to react to new obstacles in previously covered workspace.
[![New obstacle avoidance planning](https://img.youtube.com/vi/2-DXcPCJ9ZE/0.jpg)](https://www.youtube.com/watch?v=2-DXcPCJ9ZE)

### Hilbert map remapping
This experiment showcases the behavior change through Hilbert map remapping, to achieve exploration.
[![Explorative planning](https://img.youtube.com/vi/Gq7MypOmJ-4/0.jpg)](https://www.youtube.com/watch?v=Gq7MypOmJ-4)

### Narrow goal
This experiment showcases the performance of the proposed systems in difficult (narrow) environments.
[![Narrow goal planning](https://img.youtube.com/vi/h7d_gMeDMLo/0.jpg)](https://www.youtube.com/watch?v=h7d_gMeDMLo)
