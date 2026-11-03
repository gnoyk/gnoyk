# Automotive System Validation Portfolio

Automotive Engineering student minoring in Automotive IT Convergence  
Autonomous Driving · System Validation · Motion Planning · Vehicle Control

---

I am interested in validating automotive systems under realistic operating conditions. My project work focuses on defining test conditions, reproducing failures, checking sensor–planning–control integration, and comparing results after corrective changes.

## Selected Experience

### F1TENTH Autonomous Racing

- Participated in two 1/10-scale autonomous racing projects using **ROS 1**.
- Worked on SLAM-based mapping, global path generation, path tracking, and Particle Filter localization checks.
- Investigated path deviation and steering oscillation observed during high-speed and cornering tests.
- Checked PID parameters and sensor connections, adjusted the path curvature for the vehicle and map, and repeated physical-vehicle tests.
- Applied lessons from an initial obstacle-avoidance failure to a later competition project.
- **Encouragement Award**, 2026 PNU-HYUNSONG ROBORACE.

### UROP — MAP vs. RRT Path Planning Study

- Compared MAP and RRT path generation and obstacle-avoidance behavior in an RViz-based test environment.
- Tested both algorithms with manually placed obstacles and considered lap time together with avoidance performance.
- Observed that the simulation did not model road friction, tire slip, or full vehicle dynamics; therefore, the results were treated as an algorithm-level comparison rather than proof of real-vehicle safety.

### We Meet Project — Remote Double-Parking System

- Built a shared **ROS 2 + Gazebo** integration and validation environment for remote avoidance and return parking.
- Divided the system objective into double-parking detection, space creation for another vehicle, and return parking.
- Connected team functions in one workspace so interfaces and end-to-end behavior could be checked repeatedly during development.
- Used Hybrid A* for approach planning and Reeds–Shepp paths to support final parking.
- **Bronze Award**, We Meet Project Capstone Design.

## Validation Perspective

- Translate system goals into observable test conditions and expected behavior.
- Separate confirmed evidence from assumptions when analyzing unexpected results.
- Reproduce issues, inspect likely causes, apply changes, and compare retest results.
- State simulation limits explicitly before extending a result to physical-vehicle behavior.
- Consider the complete sensor–planning–control chain, not only an individual algorithm.

## Tech Stack

- **Languages & Data:** Python, C++, data analysis fundamentals
- **Robotics:** ROS 1, ROS 2, RViz, Gazebo, SLAM, Particle Filter localization
- **Planning & Control:** MAP, RRT, Hybrid A*, Reeds–Shepp, PID control
- **Development:** Ubuntu Linux, Git, GitHub
- **Foundations:** V-Cycle, Verification & Validation, test-result analysis

## Education & Qualifications

- Major: Automotive Engineering
- Minor: Automotive IT Convergence
- Hyundai NGV Mobility Data Analytics Project (COSS)
- ADsP · Six Sigma Green Belt · Class 1 Driver's License

## Current Goal

I aim to grow into a system validation engineer who can connect test evidence to safer automotive design decisions. I am particularly interested in test environments that represent real vehicle dynamics and operating constraints, including HIL-based validation.

> Detailed project repositories and evidence-based test documentation are being organized for publication.
