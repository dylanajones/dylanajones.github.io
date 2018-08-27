---
title: "Planning Energy-Efficient Trajectories in Strong Disturbances"
collection: publications
permalink: /publication/2017-06-26-paper-Planning-Energy-Efficient-Trajectories
excerpt: 'We present a framework for planning energy-efficient trajectories through strong and uncertain disturbances, such as ocean currents and wind fields.'
date: 2017-06-26
venue: 'IEEE Robotics and Automation Letters'
paperurl: 'https://ieeexplore.ieee.org/document/7959079/'
citation: 'D. Jones and G. Hollinger, &quot;Planning energy-efficient trajectories in strong disturbances&quot; <i>IEEE Robotics and Automation Letters</i>, vol. 2, no. 4, pp. 2080-2087, Oct. 2017'
---
We present a framework for planning energy-efficient trajectories through strong and uncertain disturbances, such as ocean currents and wind fields. First, we develop an iterative optimization algorithm for path planning. The algorithm samples smoothly deformed paths around the current best path estimate. Using these samples the best path guess is updated based upon a user-defined cost function. Second, we present a number of different trajectory comparison metrics that allow a vehicle to intelligently choose when to switch to newly planned paths based on new information gathered about uncertain environmental disturbances. Results are shown for a simulated environment, for a regional ocean modeling system ocean current dataset, and for field trials conducted on a windy lake with a Platypus Lutra autonomous boat. These results show that 1) our path planning algorithm is able to plan more energy-efficient paths than STOMP and A-based methods, 2) our replanning method plans paths that are more energy-efficient in the presence of uncertainty than planning only on the ocean current forecast, and 3) our algorithm is robust enough to deal with environments where limited amounts of data are available.

[Download paper here](https://ieeexplore.ieee.org/document/7959079/)