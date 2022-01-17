# ps1_mab405
Takes code given by Professor Newman online and alters it to move robot from initial position to top left corner

To launch run 'roslaunch my_stdr_controller open_loop.launch"
  First launches 'server_with_map_and_gui_plus_robot.launch'
  Then there is a delay so that when the node is run the robot won't miss any commands
  Then runs the 'open_loop_commander_node'
  
Uses stationary turns and moving forward to reach destination

No logic from enviorment, goes along set path
