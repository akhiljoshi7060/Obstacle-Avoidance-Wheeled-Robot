### **Project Setup and Execution Guide**

1. **Integrate the Project into Your Workspace:**  
   Copy the project folder into your existing catkin workspace directory.

2. **Compile the Project Files:**  
   Open a terminal and run the following command to build the project:
   ```bash
   catkin_make
   ```
   This will compile all the C++ source files.

3. **Initiate the Simulation Environment:**  
   Launch the Gazebo and RViz simulation by executing:
   ```bash
   roslaunch final_project_809y multiple_robots.launch
   ```

4. **Start the Main Node:**  
   Run the primary control node with:
   ```bash
   rosrun final_project_809y final_project_809y_node
   ```

5. **Assign Navigation Goals:**  
   Use the **2D Nav Goal** feature in RViz to set destination points for the robots.

---

Follow these steps to ensure a smooth setup and execution of the obstacle avoidance project.
