# Aerial Autonomy Stacks

Based on [this discussion in Discourse]( https://discourse.ros.org/t/more-aerial-autonomy-stacks/30992/) and [our startup meeting](https://discourse.ros.org/t/start-up-meeting-aerial-robotics-wg/30869), we can define an aerial autonomy stack as follows:

> An aerial autonomy robotics stack is a collection of building blocks that enable the development of autonomous aerial vehicles, by providing a modular and scalable architecture for sensing, perception, planning, and control tasks. It allows unmanned aerial vehicles to perform complex missions without human intervention, while accommodating different hardware configurations and simulation environments.

## Comparison

From the paper 

> Fernandez-Cortizas, Miguel, et al. "Aerostack2: A Software Framework for Developing Multi-robot Aerial Systems." arXiv preprint arXiv:2303.18237 (2023).
  
the following autonomy stack table was extracted and adapted. 

| Flight stack   | OS/OC | Modular | Tested in | Middleware | last  update | MF  | RO  | MA  | MP  | PO  |
| -------------- | ----- | ------- | --------- | ---------- | ------------ | --- | --- | --- | --- | --- |
| Aerostack      | ✓    | ✓      | S,RIL,ROL   | ROS        | 10/2021      | ✗  | ✓  | ✓  | ✓  | ✗  |
| Aerostack2     | ✓    | ✓      | S,RIL,ROL   | ROS 2      | 03/2023      | ✓  | ✓  | ✓  | ✓  | ✓  |
| AerialCore     | ✓    | ✓      | S,RIL,ROL   | ROS        | 03/2023      | ✓  | ✓  | ✓  | ✗  | ✓  |
| Agilicious     | ✓    | ✓      | S,RIL      | ROS        | 03/2023      | ✗  | ✓  | ✗  | ✗  | ✗  |
| KumarRobotics  | ✓    | ✗      | S,RIL,ROL   | ROS        | 12/2022      | ✗  | ✓  | ✗  | ✓  | ✗  |
| CrazyChoir     | ✓    | ✗      | S,RIL      | ROS 2      | 02/2023      | ✗  | ✓  | ✓  | ✗  | ✗  |
| UAL            | ✓    | ✗      | S,RIL,ROL   | ROS        | 12/2022      | ✓  | ✗  | ✗  | ✓  | ✗  |
| XTDrone        | ✓    | ✓      | S         | ROS        | 03/2023      | ✗  | ✓  | ✗  | ✗  | ✗  |
| RotorS         | ✓    | ✓      | S         | ROS        | 07/2021      | ✗  | ✓  | ✗  | ✗  | ✗  |
| GAAS           | ✓    | ✓      | S         | ROS        | 10/2021      | ✗  | ✗  | ✗  | ✗  | ✗  |
| MRS AUV System | ✓    | ✓      | S,RIL,ROL   | ROS        | 09/2023      | ✓  | ✓  | ✓  | ✓  | ✗  |
| Crazyswarm     | ✓    | ✗      | S,RIL      | ROS        | 12/2022      | ✗  | ✓  | ✓  | ✗  | ✗  |
| Crazyswarm2     | ✓    | ✓      | S,RIL      | ROS 2       | 09/2023      | ✗  | ✓  | ✓  | ✗  | ✓  |


**Abbrivations**
* OS/OC: Open source or Open code
* S: Experiments in simulation
* RIL: Experiments in the lab
* ROL: Experiments outside the lab
* MF: Multi-frame 
* RO: Rate output
* MA: Multi agent
* MP: Multi platform
* PO: Plugin oriented 


## Working list autonomy stacks

This is just a list of autonomy stacks with links, such that later we can add them to the overview.

Working list:
* [Aerostack2](https://aerostack2.github.io/)
* [Aerostack(1)](https://github.com/cvar-upm/aerostack/wiki)
* [KumarRobotics Autonomy Stack](https://github.com/KumarRobotics/kr_autonomous_flight)
* [Agilicious](https://agilicious.readthedocs.io/en/latest/index.html)
* [Crazyswarm2](https://imrclab.github.io/crazyswarm2/)
* [Crazyswarm(1)](https://crazyswarm.readthedocs.io/en/latest/)
* [MRS UAV System](https://github.com/ctu-mrs/mrs_uav_system)
* [Hector quadrotor](http://wiki.ros.org/hector_quadrotor)
* [RotorS](https://github.com/ethz-asl/rotors_simulator)
* RISE [paper](https://doi.org/10.55417/fr.2023015)
* [MRS AUV System](https://github.com/ctu-mrs/mrs_uav_system)
