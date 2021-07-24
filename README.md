## Kedai Runcit & Tiago

### Contributor 
Natasya Khoo A177696
Amal Majida Binti Munir A174807

### Instructions 
- Launch world : 
- cd tiago_public_ws
- source ./devel/setup.bash
- roslaunch tiago_gazebo empty_world.launch public_sim:=true world:=project10
                 
- Grasping :     
- roslaunch tiago_pick_demo pick_demo.launch
- rosservice call /pick_pringles
                 
- Move Robot :  
- rosrun simple_controller controller2.py
