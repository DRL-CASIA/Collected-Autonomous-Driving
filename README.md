# Collected-Autonomous-Driving-algorithm

**Some forked from https://github.com/jiachenli94/Awesome-Decision-Making-Reinforcement-Learning**

Please feel free to pull request to add new resources or send emails to us for questions, discussion and collaborations.

Also welcome to check the current research in our [**MSC Lab**](https://msc.berkeley.edu/research/autonomous-vehicle.html) at UC Berkeley.

**Research Intern**: Please read [**this**](https://jiachenli94.github.io/Research_Intern_Opportunities_at_UC_Berkeley.pdf) if you want to apply for research intern opportunities in our group.

**Note**: [**Here**](https://github.com/jiachenli94/Awesome-Interaction-aware-Trajectory-Prediction) is also a collection of research materials for interaction-aware trajectory (behavior) prediction.

## Path Planning
- A  Real-Time Motion Planner with Trajectory Optimization for Autonomous Vehicles， 2012， [[paper](https://ieeexplore.ieee.org/document/6225063)]
- A Review of Motion Planning Techniquesfor Automated Vehicles, 2016, [[paper](https://users.cs.duke.edu/~pdinesh/sources/07339478.pdf)]



## RL & IRL & GAIL

- Maximum Entropy Deep Inverse Reinforcement Learning, 2015, [[paper](https://arxiv.org/abs/1507.04888)]
- Guided Cost Learning: Deep Inverse Optimal Control via Policy Optimization, ICML 2016, [[paper](https://arxiv.org/abs/1603.00448)]
- Generative Adversarial Imitation Learning, NIPS 2016,  [[paper](https://arxiv.org/abs/1606.03476)]
- A Connection between Generative Adversarial Networks, Inverse Reinforcement Learning, and Energy-Based Models, NIPS 2016,  [[paper](https://arxiv.org/abs/1611.03852)]
- InfoGAIL: Interpretable Imitation Learning from Visual Demonstrations, NIPS 2017, [[paper](https://arxiv.org/pdf/1703.08840.pdf)] [[code](https://github.com/YunzhuLi/InfoGAIL)]
- Self-Imitation Learning, ICML 2018, [[paper](https://arxiv.org/abs/1806.05635)] [[code](https://github.com/wudongming97/self-imitation-learning)]
- Data-Efficient Hierarchical Reinforcement Learning, NIPS 2018, [[paper](https://arxiv.org/abs/1805.08296)]
- Learning Robust Rewards with Adversarial Inverse Reinforcement Learning, ICLR 2018, [[paper](https://arxiv.org/abs/1710.11248)]
- Multi-Agent Generative Adversarial Imitation Learning, ICLR 2018, [[paper](https://arxiv.org/abs/1807.09936)]
- Multi-Agent Adversarial Inverse Reinforcement Learning, ICML 2019, [[paper](https://arxiv.org/abs/1907.13220v1)]

## Autonomous Driving

- A Survey of Deep Learning Applications to Autonomous Vehicle Control, IEEE Transaction on ITS 2019, [[paper](https://arxiv.org/pdf/1912.10773v1.pdf)]
- Imitating Driver Behavior with Generative Adversarial Networks, IV 2017,  [[paper](https://arxiv.org/abs/1701.06699)] [[code](https://github.com/sisl/gail-driver)]
- Multi-Agent Imitation Learning for Driving Simulation, IROS 2018, [[paper](https://arxiv.org/pdf/1803.01044v1.pdf)] [[code](https://github.com/sisl/ngsim_env)]
- Simulating Emergent Properties of Human Driving Behavior Using Multi-Agent Reward Augmented Imitation Learning, ICRA 2019, [[paper](https://arxiv.org/pdf/1903.05766v1.pdf)] [[code](https://github.com/sisl/ngsim_env)]
- Learning from Demonstration in the Wild, ICRA 2018, [[paper](http://arxiv.org/abs/1811.03516v2)]
- Multi-Agent Connected Autonomous Driving using Deep Reinforcement Learning, NeurIPS 2019, [[paper](https://arxiv.org/abs/1911.04175)] [[code](https://github.com/praveen-palanisamy/macad-gym)]
- Model-free Deep Reinforcement Learning for Urban Autonomous Driving, ITSC 2019, [[paper](https://arxiv.org/abs/1904.09503v2)]
- End-to-end driving via conditional imitation learning, ICRA 2018,  [[paper](https://arxiv.org/abs/1710.02410)]
- CIRL: Controllable Imitative Reinforcement Learning for Vision-based Self-driving, ECCV 2018, [[paper](http://openaccess.thecvf.com/content_ECCV_2018/html/Xiaodan_Liang_CIRL_Controllable_Imitative_ECCV_2018_paper.html)] [[code](https://github.com/HubFire/Muti-branch-DDPG-CARLA)]
- A reinforcement learning based approach for automated lane change maneuvers, IV 2018, [[paper](https://arxiv.org/abs/1804.07871)]
- Adversarial Inverse Reinforcement Learning for Decision Making in Autonomous Driving, ICRA 2020, [[paper](https://arxiv.org/abs/1911.08044v1)]
- Deep hierarchical reinforcement learning for autonomous driving with distinct behaviors, IV 2018, [[paper](https://www.researchgate.net/profile/Jianyu_Chen22/publication/328454880_Deep_Hierarchical_Reinforcement_Learning_for_Autonomous_Driving_with_Distinct_Behaviors/links/5be340a0299bf1124fc2dc59/Deep-Hierarchical-Reinforcement-Learning-for-Autonomous-Driving-with-Distinct-Behaviors.pdf)]
- A Hierarchical Architecture for Sequential Decision-Making in Autonomous Driving using Deep Reinforcement Learning, ICML 2019, [[paper](https://arxiv.org/abs/1906.08464v1)]
- End-to-end Interpretable Neural Motion Planner, CVPR 2019,  [[paper](http://www.cs.toronto.edu/~wenjie/papers/cvpr19/nmp.pdf)]
- Jointly Learnable Behavior and Trajectory Planning for Self-Driving Vehicles, IROS 2019,  [[paper](https://arxiv.org/abs/1910.04586)]
- Dynamic Input for Deep Reinforcement Learning in Autonomous Driving, IROS 2019, [[paper](https://arxiv.org/abs/1907.10994v1)]
- Learning to Navigate in Cities Without a Map, NIPS 2018, [[paper](https://arxiv.org/abs/1804.00168)]
- Scalable End-to-End Autonomous Vehicle Testing via Rare-event Simulation, NIPS 2018, [[paper](https://arxiv.org/abs/1811.00145)]
- Towards Learning Multi-agent Negotiations via Self-Play, ICCV 2019, [[paper](http://openaccess.thecvf.com/content_ICCVW_2019/papers/ADW/Tang_Towards_Learning_Multi-Agent_Negotiations_via_Self-Play_ICCVW_2019_paper.pdf)]

### Simulator \& Dataset

- CARLA: An Open Urban Driving Simulator, [[paper](http://proceedings.mlr.press/v78/dosovitskiy17a/dosovitskiy17a.pdf)]
- TORCS: The open racing car simulator, [[paper](http://www.cse.chalmers.se/~chrdimi/papers/torcs.pdf)]
- Comma.ai: Learning a Driving Simulator, [[paper](https://arxiv.org/pdf/1608.01230.pdf)]
- NGSIM: US Highway 101 Dataset, [[docs](https://www.fhwa.dot.gov/publications/research/operations/07030/07030.pdf)]
