# Microscopic Railway Network Simulation (Digital Twin) 

## Overview
This repository showcases the development of a highly detailed, microscopic **Digital Twin** of a railway network using **OpenTrack** simulation software. 

Unlike macroscopic models that focus on passenger demand, this project simulates the physical and mechanical realities of railway operations. It rigorously models train kinematics, signalling block sections, and network interlocking to evaluate maximum line capacity and safe train separation under real-world constraints.

## Engineering Architecture & Simulation Workflow

1. **Infrastructure & Topology Modeling:**
   * Engineered a precise track topology graph incorporating nodes, edges, precise gradients, and curve radii.
   * Defined station platforms and complex junction layouts to accurately reflect physical network bottlenecks.

2. **Signalling & Control Systems:**
   * Configured realistic railway signalling systems including fixed block sections, distant/main signals, and speed indicators.
   * Implemented safety constraints and interlocking logic to guarantee safe train separation and prevent routing conflicts.

3. **Rolling Stock Kinematics:**
   * Assigned specific traction and braking force curves to the simulated rolling stock (locomotives and passenger multiple units).
   * Evaluated real-time train performance equations, accounting for rolling resistance, gradient resistance, and aerodynamic drag.

4. **Timetable & Dispatching Operations:**
   * Developed conflict-free timetables and tested network resilience by introducing simulated delays.
   * Analyzed headway distances and junction clearance times to optimize overall network capacity.

## Key Engineering Takeaways
* **Safety & Headway Optimization:** Demonstrates a deep understanding of how signalling distance directly impacts the theoretical and practical capacity of a rail line.
* **Tractive Effort Application:** Proves the ability to translate mechanical physics (tractive effort vs. speed curves) into operational transit models.

## Tech Stack & Domain Expertise
* **Simulation Software:** OpenTrack (Microscopic Railway Simulation)
* **Domain:** Railway Engineering, Operations Planning, Rolling Stock Kinematics, Signalling Systems
