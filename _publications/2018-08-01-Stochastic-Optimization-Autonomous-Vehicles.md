---
title: "Stochastic Optimization for Autonomous Vehicles with Limited Control Authority"
collection: publications
permalink: /publication/2018-08-01-Stochastic-Optimization-Autonomous-Vehicles
excerpt: 'In this work, we present a Stochastic Gradient Ascent (SGA) algorithm for multi-vehicle information gathering that accounts for limitations on a vehicle’s control authority caused by external forces.'
date: 2018-08-01
venue: 'Proc. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
paperurl: 'http://research.engr.oregonstate.edu/rdml/sites/research.engr.oregonstate.edu.rdml/files/iros_18_final_v2.pdf'
citation: 'D. Jones, M. Kuhlman, D. Sofge, S. Gupta, and G. Hollinger, &quot;Stochastic optimization for autonomous vehicles with limited control authority,&quot; in <i>Proc. IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)</i>, Madrid, Spain, Oct. 2018, to appear.'
---
In this work, we present a Stochastic Gradient Ascent (SGA) algorithm for multi-vehicle information gathering that accounts for limitations on a vehicle’s control authority caused by external forces. By representing vehicle paths using a novel action space representation, rather than a state space representation, we remove the need to perform feasibility calculations on the vehicle’s path. Our algorithm uses a stochastic optimization scheme by sampling perturbed action sequences around the current best known sequence to estimate the gradient of a state space information function with respect to the action sequence. Additionally, we use sequential greedy allocation to plan for multiple vehicles. Results are shown using a Navy Coastal Ocean Model (NCOM) for the Gulf of Mexico (GoM). SGA shows improvement in the amount of information gained over a greedy baseline. Additionally, we compare to Monte Carlo Tree Search (MCTS) Method, which is able to gather competitive amounts of information but is more computationally intensive than our approach.

[Download paper here](http://research.engr.oregonstate.edu/rdml/sites/research.engr.oregonstate.edu.rdml/files/iros_18_final_v2.pdf)