# TGPO: Temporal Grounded Policy Optimization for Signal Temporal Logic

[![Conference](https://img.shields.io/badge/Arxiv-Paper-success?logo=arxiv&logoColor=red)](https://arxiv.org/abs/2504.03015)


[<ins>Yue Meng</ins>](https://mengyuest.github.io/), [<ins>Fei Chen</ins>](https://scholar.google.com/citations?user=sq0N9XUAAAAJ&hl=en), and [<ins>Chuchu Fan</ins>](https://chuchu.mit.edu/)

[<ins>Reliable Autonomous Systems Lab @ MIT (REALM)</ins>](https://aeroastro.mit.edu/realm/)


> A hierarchical reinforcement learning (RL) framework to solve general Signal Temporal Logic (STL) tasks for complex systems and nested STLs.

![Figure](figures/fig0_arch.png)
<p align="center"><em>Hierarchical RL framework based on STL decomposition.</em></p>

<table>
  <tr>
    <td style="width: 20%; text-align: center;"><img src="figures/env_0lin.png"></td>
    <td style="width: 20%; text-align: center;"><img src="figures/env_1car.png"></td>
    <td style="width: 20%; text-align: center;"><img src="figures/env_2arm.png"></td>
    <td style="width: 20%; text-align: center;"><img src="figures/env_3drone.png"></td>
    <td style="width: 20%; text-align: center;"><img src="figures/env_4ant.png"></td>
  </tr>
  <tr>
    <td style="width: 20%; text-align: center;">Linear</td>
    <td style="width: 20%; text-align: center;">Nonlinear</td>
    <td style="width: 20%; text-align: center;">Franka Panda</td>
    <td style="width: 20%; text-align: center;">Quadrotor</td>
    <td style="width: 20%; text-align: center;">Ant</td>
  </tr>
</table>


<p align="center"><em>TGPO solves for a wide range of task environments.</em></p>

![Figure](figures/fig1_bar.png)
<p align="center"><em>Strong results in STL success rate especially on complex environments.</em></p>

![Figure](figures/fig2_horizon.png)
<p align="center"><em>Our result performance stay robust over long-horizon.</em></p>

![Figure](figures/fig3_sim.png)
<p align="center"><em>Our method can generate interpretable heatmaps and multi-modal behaviors.</em></p>

## Code and details coming soon