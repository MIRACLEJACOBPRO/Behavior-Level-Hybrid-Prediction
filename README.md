# Behavior-Level-Hybrid-Prediction
Official repository for "Dynamic Action Verification for Embodied Agents via Behavior-Level Hybrid Prediction."

**Look Before You Leap: Dynamic Action Verification for Embodied Agents via Behavior-Level Hybrid Prediction**

It provides dynamic action verification for embodied agents by jointly modeling discrete task semantics and continuous physical dynamics. It maintains hybrid historical knowledge using a hidden semi-Markov model and an unscented Kalman filter, predicts candidate behaviors over a finite horizon, and evaluates semantic and physical risks before action execution.

## Real-World Experiments

We evaluated nine methods on three real-robot tasks: route following, waypoint dwell, and patrol inspection. Each method was tested on 150 task executions, yielding 1,350 method-runs in total.

<p align="center">
  <img src="https://github.com/user-attachments/assets/1d425e7e-2a4d-41fc-94f6-c1f81ae3335e" width="760" alt="Real-world experimental setup and task-attack configuration">
</p>

**Experimental setup and task-attack configuration.** The figure shows the mobile robot platform, marked track, task checkpoints, and the control-hijacking and observation-spoofing attacks used in the experiments.

<p align="center">
  <img src="https://github.com/user-attachments/assets/4d964c16-7d73-4a30-938b-d8475aa5de4d" width="1000" alt="Experimental platform, representative tasks, and physical and semantic threats">
</p>

**Representative tasks and threats.** The figure summarizes the platform and route, waypoint, and patrol scenarios under representative physical disturbances and semantic deviations.

<p align="center">
  <img src="https://github.com/user-attachments/assets/95197d65-0d7b-47c2-8e66-93348fa9e8fd" width="620" alt="Decision latency of all evaluated methods in the real-world experiments">
</p>

**Decision latency in real-world experiments.** Fig. 2-3 reports the mean, median (P50), and 95th-percentile (P95) decision latency of all nine methods measured on the real robot. [Vector PDF](https://github.com/user-attachments/files/32377638/decision_latency.pdf)

## Repository Status

The implementation and experimental artifacts are currently being organized for public release.

Source code, experiment configurations, evaluation scripts, and reproduction instructions will be released after the research artifact is finalized.

## Citation

Citation information will be added after publication.
