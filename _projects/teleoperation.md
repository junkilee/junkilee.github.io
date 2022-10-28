---
layout: page
title: teleoperation
description: Teleoperation of robot manipulation through goal specification
img: assets/img/projects/interface.jpg
importance: 6
category: brown
---

<h3>Teleoperation of robot manipulation through goal specification</h3>

<h6>Bringing in Context and Environment awareness.</h6>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/interface_overall.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/projects/templates.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshots of the interfaces inside the ROS.
</div>

Direct teleoperation had been the most prevalent form of humans’ remote operation of robots in completing sophisticated manipulation tasks. When using direct teleoperation tools, due to the complexity of robot motion, human operators mostly focus their attention on solving low-level motion control. This would lead to the operators’ heightened cognitive load. We propose a new approach to programming robots by providing an interface which a human operator can model the world and set goal states for a given task. Operators are able to locate three dimensional (3D) templates on points clouds to set the initial poses, grasp positions and goal positions of objects. We also provide a novel method for a human to designate grasp access points for a complex object like a bookshelf for more effective motion planning. In this work, for comparison we picked two existing frameworks, the interactive marker based direct control and way-point based control systems. While a human operator controls the robot for the pick and place task, the pilot study measured total execution and operation time and execution failure rates. The proposed goal-based interface took the least execution time and has the lowest failure rate among the three interfaces. From the NASA TLX questionnaire results, the goal-based interface requires the least effort in order to complete the tasks.

J. K. Lee (2015), <b>“Teleoperation for Robot Manipulation through Goal Specification”</b>, PhD Forum, the 2015 IEEE International Conference on Robotics and Automation (ICRA), Seattle, Washington.

J. K. Lee, and O. C. Jenkins (2014), <b>"Goal-Based Teleoperation for Robot Manipulation"</b>, presented at AAAI Fall Symposium on Artificial Intelligence for Human-Robot Interaction, Arlington, Va, 2014.