## Hi there 👋 I'm Afonso, a robotics engineer and PhD researcher working on autonomous navigation and field robotics for UGVs in unstructured outdoor environments.

Most of my work lives in private repositories pending paper acceptance, which will be made public upon acceptance. In the meantime, I'm happy to discuss robotics, autonomy systems, and software design in general.

### Current state of pending publications:

- Under preparation:
  - Final PhD journal paper describing a complete end-to-end UGV autonomy system. The system accepts goals via GNSS (when available) or relative (X, Y) coordinates, automatically estimates Z from observed terrain, and performs goal-oriented navigation from an arbitrary starting position in unknown environments — with continuous path validation and a high-frequency dynamic obstacle avoidance module.
- Under review:
  - 1 IEEE IROS article on an end-to-end, open-source (upon acceptance) system for autonomous UGV navigation in harsh, GNSS-deprived environments, such as forests, without prior maps. Results demonstrate over 20 collision-free trajectories executed in 2 different unstructured scenarios totalling over 1.5 km of autonomous navigation, with the entire pipeline running online in the robot's onboard computer.
- Accepted (pending publication):
  - 2 IEEE ICARSC articles — one, describing the earlier stages of deployment and validation of the IROS article, particularly in simulation, as well as path generation using a real-world dataset, with planned paths exceeding 280 meters; the second, describing a self-supervised proprioceptive-based traversability estimation system using only RGB images as input, producing pixel-wise traversability masks with continuous values as output.
  - 1 Springer book chapter, providing details of an ablation study performed to assess the variation in output quality of the self-supervised traversability system described above when using different proprioceptive signals to generate the pseudo ground-truth masks.
  - 3 Springer book chapters (as co-author) on topics such as mobile apparatus for multi-modal dataset collections, a comparative study of different LiDAR-based odometry estimation methods with two different LiDAR sensors, especially on outdoor settings, and a comparative study between state-of-the-art, deep learning segmentation methods in natural settings, as well as the fine-tuning of the most promising one to solve some of the encountered issues and increase its performance in these settings.

### Preview of the self-supervised traversability estimation system

[![YouTube](http://i.ytimg.com/vi/pCfJkjTjWHM/hqdefault.jpg)](https://www.youtube.com/watch?v=pCfJkjTjWHM)
