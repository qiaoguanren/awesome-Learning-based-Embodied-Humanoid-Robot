# awesome-Learning-based-Embodied-Humanoid-Robot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Humanoid robots have significant potential to master a wide range of tasks under human workspaces, making them essential embodiments of artificial intelligence in real-world environments. In the recent development of control algorithms for humanoid robots, considerable attention has been given to learning-based methods, primarily due to their superior flexibility and generalizability compared to traditional model-based control approaches. 

To help more people stay informed about the latest progress in humanoid robots, I have systematically collected and classified papers on locomotion, manipulation, loco-manipulation, and human-robot interaction tasks; learning-based approaches (e.g., RL, IL, VLA); and related surveys, simulators, and benchmarks.


## 📑 Papers

### ⭐️ Reinforcement Learning / Imitation Learning

#### Locomotion

- [2025 Unitree H1] SMAP: Self-supervised Motion Adaptation for Physically Plausible Humanoid Whole-body Control [[paper](https://arxiv.org/pdf/2505.19463)]

- [2025 Unitree G1] General Motion Tracking for Humanoid Whole-Body Control [[project](https://gmt-humanoid.github.io/)] [[paper](https://arxiv.org/abs/2506.14770)]
  
- [2025 Unitree G1] Hold My Beer: Learning Gentle Humanoid Locomotion and End-Effector Stabilization Control [[paper](https://lecar-lab.github.io/SoFTA/resources/Main-Paper.pdf)] [[project](https://lecar-lab.github.io/SoFTA/)]

- [2025 Unitree H1 (simulation)] One Policy but Many Worlds: A Scalable Unified Policy for Versatile Humanoid Locomotion [[paper](https://arxiv.org/pdf/2505.18780)] [[project](https://dreampolicy.github.io/)]
  
- [2025 Unitree H1 (simulation)] TD-GRPC: Temporal Difference Learning with Group Relative Policy Constraint for Humanoid Locomotion [[paper](https://arxiv.org/pdf/2505.13549)]

- [2025 Unitree G1] HuB: Learning Extreme Humanoid Balance [[paper](https://arxiv.org/pdf/2505.07294)]

- [2025 Unitree H1 (simulation)] Let Humanoids Hike! Integrative Skill Development on Complex Trails [[paper](https://arxiv.org/pdf/2505.06218)] [[project](https://lego-h-humanoidrobothiking.github.io/)]

- [2025 Unitree H1] Towards Embodiment Scaling Laws Robot Locomotion [[paper](https://arxiv.org/pdf/2505.05753)]

- [2025 Unitree G1] Visual Imitation Enables Contextual Humanoid Control [[paper](https://arxiv.org/pdf/2505.03729)] [[project](https://videomimic.net/)]

- [2025 Unitree G1] LangWBC: Language-directed Humanoid Whole-Body Control via End-to-end Learning [[paper](https://arxiv.org/pdf/2504.21738)] [[video](https://youtu.be/9AN0GulqWwc)]

- [2025 HRP-5P] Robust Humanoid Walking on Compliant and Uneven Terrain with Deep Reinforcement Learning [[paper](https://arxiv.org/pdf/2504.13619)] [[project](https://github.com/rohanpsingh/LearningHumanoidWalking)]

- [2025 CASBOT SE] Teacher Motion Priors: Enhancing Robot Locomotion over Challenging Terrain [[paper](https://arxiv.org/pdf/2504.10390)]

- [2025 NAVIAI] Natural Humanoid Robot Locomotion with Generative Motion Prior [[paper](https://arxiv.org/pdf/2503.09015)] [[project](https://sites.google.com/view/humanoid-gmp)]

- [2025 Unitree H1 (simulation)] NIL: No-data Imitation Learning by Leveraging Pre-trained Video Diffusion Models [[paper](https://arxiv.org/pdf/2503.10626)]

- [2025 Tiangong] Distillation-PPO: A Novel Two-Stage Reinforcement Learning Framework for Humanoid Robot Perceptive Locomotion [[paper](https://arxiv.org/abs/2503.08299)]

- [2025 TienKung] LiPS: Large-Scale Humanoid Robot Reinforcement Learning with Parallel-Series Structures [[paper](https://arxiv.org/abs/2503.08349)]

- [2025 Unitree G1] Learning Perceptive Humanoid Locomotion over Challenging Terrain [[paper](https://arxiv.org/pdf/2503.00692)]

- [**RSS** 2025 Unitree G1] Learning Getting-Up Policies for Real-World Humanoid Robots [[paper](https://arxiv.org/pdf/2502.12152)] [[project](https://humanoid-getup.github.io/)]

- [2025 Unitree H1 & G1] VB-Com: Learning Vision-Blind Composite Humanoid Locomotion Against Deficient Perception [[paper](https://arxiv.org/pdf/2502.14814)]

- [2025 Booster T1] HiFAR: Multi-Stage Curriculum Learning for High-Dynamics Humanoid Fall Recovery [[paper](https://arxiv.org/pdf/2502.20061)]

- [2025 Unitree G1] Learning Humanoid Locomotion with World Model Reconstruction [[paper](https://arxiv.org/pdf/2502.16230)]

- [2025 Unitree H1] Humanoid Whole-Body Locomotion on Narrow Terrain via Dynamic Balance and Reinforcement Learning [[paper](https://arxiv.org/pdf/2502.17219)] [[project](https://whole-body-loco.github.io/)]

- [**RSS** 2025 Unitree G1] BeamDojo: Learning Agile Humanoid Locomotion on Sparse Footholds [[paper](https://arxiv.org/abs/2502.10363)] [[project](https://why618188.github.io/beamdojo/)]

- [**RSS** 2025 Unitree G1] ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills [[project](https://agile.human2humanoid.com/)] [[github](https://github.com/LeCAR-Lab/ASAP)]

- [2025 Unitree G1] Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions [[paper](https://arxiv.org/abs/2502.01465)]

- [**ICRA** 2025 Unitree H1] HOVER: Versatile Neural Whole-Body Controller for Humanoid Robots [[paper](https://hover-versatile-humanoid.github.io/resources/HOVER_paper.pdf)] [[project](https://hover-versatile-humanoid.github.io/)]

- [2025 Unitree H1] HWC-Loco: A Hierarchical Whole-Body Control Approach to Robust Humanoid Locomotion [[paper](https://arxiv.org/abs/2503.00923)] [[project](https://simonlinsx.github.io/HWC_Loco/)]

- [2025 Fourier GR1] Learning Smooth Humanoid Locomotion through Lipschitz-Constrained Policies [[project](https://lipschitz-constrained-policy.github.io/)] [[paper](https://arxiv.org/abs/2410.11825)] [[code](https://github.com/zixuan417/smooth-humanoid-locomotion)]

- [2024 Unitree H1 & Talos & Atlas (Simulation)] RILe: Reinforced Imitation Learning [[paper](https://arxiv.org/pdf/2406.08472)]

- [2024 Unitree G1] Exbody2: Advanced Expressive Humanoid Whole-Body Control [[paper](https://exbody2.github.io/resources/exbody2.pdf)] [[project](https://exbody2.github.io/)]

- [2024 Unitree H1] Learning Humanoid Locomotion with Perceptive Internal Model [[paper](https://junfeng-long.github.io/PIM/static/pdfs/PIM.pdf)] [[project](https://junfeng-long.github.io/PIM/)]

- [2024 Digit] Learning Humanoid Locomotion over Challenging Terrain [[paper](https://arxiv.org/pdf/2410.03654)]

- [2024 Unitree H1] Stage-Wise Reward Shaping for Acrobatic Robots: A Constrained Multi-Objective Reinforcement Learning Approach [[paper](https://arxiv.org/pdf/2409.15755)]

- [**CoRL** 2024 Unitree H1] OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning [[project](https://omni.human2humanoid.com/)] [[paper](https://omni.human2humanoid.com/resources/OmniH2O_paper.pdf)]

- [2024 Unitree H1] Humanoid Parkour Learning [[paper](https://arxiv.org/abs/2406.10759)] [[project](https://humanoid4parkour.github.io/)]

- [**CoRL** 2024 Unitree H1] WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts [[project](https://lecar-lab.github.io/wococo/)] [[paper](https://arxiv.org/abs/2406.06005)]

- [**ICRA Workshop** 2024 XBot-S & XBot-L] Humanoid-Gym: Reinforcement Learning for Humanoid Robot with Zero-Shot Sim2Real Transfer [[paper](https://arxiv.org/abs/2404.05695)]

- [**IROS** 2024 Unitree H1] Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation [[paper](https://arxiv.org/abs/2403.04436)] [[video](https://www.youtube.com/watch?v=0W4N2q7xtcQ)]

- [**RSS** 2024 Unitree H1] Expressive Whole-Body Control for Humanoid Robots [[project](https://expressive-humanoid.github.io/)] [[paper](https://arxiv.org/abs/2402.16796)]

- [**RSS** 2024 Xbot] Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning [[paper](https://arxiv.org/pdf/2408.14472)]

- [2024 Wukong-IV] Toward Understanding Key Estimation in Learning Robust Humanoid Locomotion [[paper](https://arxiv.org/abs/2403.05868)]

- [2024 Adam] Whole-body Humanoid Robot Locomotion with Human Reference [[project](https://greatsjk.github.io/Adam-PNDbotics/)] [[paper](https://arxiv.org/abs/2402.18294)]

#### Manipulation

- [2024 Fourier GR1] ARMOR: Egocentric Perception for Humanoid Robot Collision Avoidance and Motion Planning [[paper](https://arxiv.org/pdf/2412.00396v1)]

- [2024 Fourier GR1] Generalizable Humanoid Manipulation with Improved 3D Diffusion Policies [[paper](https://arxiv.org/abs/2410.10803)]

- [**CoRL** 2024 Fourier GR1] OKAMI: Teaching Humanoid Robots Manipulation Skills through Single Video Imitation [[paper](https://arxiv.org/pdf/2410.11792)]

- [**CoRL** 2024 Fourier GR1] Open-TeleVision : Teleoperation with Immersive Active Visual Feedback [[project](https://robot-tv.github.io/)]

#### Loco-Manipulation

- [2025 Unitree G1 & H1] Unleashing Humanoid Reaching Potential via Real-world-Ready Skill Space [[project](https://zzk273.github.io/R2S2/)] [[paper](https://www.arxiv.org/pdf/2505.10918)]

- [2025 Unitree G1] CLONE: Closed-Loop Whole-Body Humanoid Teleoperation for Long-Horizon Tasks [[project](https://humanoid-clone.github.io/)]

- [2025 Unitree G1] FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation [[paper](https://arxiv.org/pdf/2505.06776)] [[project](https://lecar-lab.github.io/falcon-humanoid/)] 

- [2025 Unitree G1] TWIST: Teleoperated Whole-Body Imitation System [[paper](https://arxiv.org/pdf/2505.02833)] [[project](https://yanjieze.com/TWIST/)] 

- [2025 Unitree G1] AMO: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control [[paper](https://arxiv.org/pdf/2505.03738)] [[project](https://amo-humanoid.github.io/)]

- [2025 Unitree H1] Adversarial Locomotion and Motion Imitation for Humanoid Policy Learning [[paper](https://arxiv.org/pdf/2504.14305)] [[project](https://almi-humanoid.github.io/)]

- [2025 Unitree H1 (simulation)] FLAM: Foundation Model-Based Body Stabilization for Humanoid Locomotion and Manipulation [[paper](https://arxiv.org/pdf/2503.22249)] [[project](https://xianqi-zhang.github.io/FLAM/)]

- [2025 TienKung] Trinity: A Modular Humanoid Robot AI System [[paper](https://arxiv.org/abs/2503.08338)]

- [**RSS** 2025 Unitree G1] HOMIE: Humanoid Loco-Manipulation with Isomorphic Exoskeleton Cockpit [[paper](https://arxiv.org/abs/2502.13013)] [[project](https://homietele.github.io/)]

- [**ICRA** 2025 Unitree H1] Mobile-TeleVision: Predictive Motion Priors for Humanoid Whole-Body Control [[paper](https://mobile-tv.github.io/resources/pmp.pdf)] [[project](https://mobile-tv.github.io/)]

- [**CoRL** 2024 Unitree H1] HumanPlus: Humanoid Shadowing and Imitation from Humans [[project](https://humanoid-ai.github.io/)] [[paper](https://humanoid-ai.github.io/HumanPlus.pdf)]

#### Human-Robot Interaction

- [2025 Unitree H1] SignBot: Learning Human-to-Humanoid Sign Language Interaction [[paper](https://arxiv.org/abs/2505.24266)] [[project](https://qiaoguanren.github.io/SignBot/)]

- [2025 Unitree H1] RHINO: Learning Real-Time Humanoid-Human-Object Interaction from Human Demonstrations [[paper](https://humanoid-interaction.github.io/resources/paper.pdf)] [[project](https://humanoid-interaction.github.io/)]

### 🌟 End-to-End Transformer / Diffusion Model

#### Locomotion

- [2025 Tiangong] HumanoidPano: Hybrid Spherical Panoramic-LiDAR Cross-Modal Perception for Humanoid Robots [[paper](https://arxiv.org/abs/2503.09010)]

- [2024 Digit] Humanoid Locomotion as Next Token Prediction [[paper](https://arxiv.org/abs/2402.19469)]

#### Manipulation

- [2025 Unitree H1] Humanoid Policy ~ Human Policy [[paper](https://arxiv.org/pdf/2503.13441)] [[project](https://human-as-robot.github.io/)] 

#### Loco-Manipulation

- [2025 Unitree G1 (simulation)] Physically Consistent Humanoid Loco-Manipulation using Latent Diffusion Models [[paper](https://arxiv.org/pdf/2504.16843)]

### 💫 Humanoid VLA

#### Locomotion

- [2025 Unitree G1] Humanoid-VLA: Towards Universal Humanoid Control with Visual Integration [[paper](https://arxiv.org/pdf/2502.14795)]

- [2025 Unitree G1] LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction [[paper](https://arxiv.org/pdf/2506.13751)]

#### Manipulation

- [2025 Fourier GR1] GR00T N1: An Open Foundation Model for Generalist Humanoid Robots [[paper](https://arxiv.org/pdf/2503.14734)] [[project](https://github.com/NVIDIA/Isaac-GR00T)]

- [2025 Figure] Helix: A Vision-Language-Action Model for Generalist Humanoid Control [[report](https://www.figure.ai/news/helix)]

 
## 📘 Survey
  
- [2025] Humanoid Locomotion and Manipulation: Current Progress and Challenges in Control, Planning, and Learning [[paper](https://arxiv.org/abs/2501.02116)]

- [**IJRR** 2025] Foundation Models in Robotics: Applications, Challenges, and the Future [[paper](https://arxiv.org/pdf/2312.07843)] [[project](https://github.com/robotics-survey/Awesome-Robotics-Foundation-Models)]

- [2025] Embodied Intelligent Industrial Robotics: Concepts and Techniques [[paper](https://arxiv.org/pdf/2505.09305)] [[project](https://github.com/jackeyzengl/Embodied_Intelligent_Industrial_Robotics_Paper_List)] 

- [2025] A Survey of Robotic Navigation and Manipulation with Physics Simulators in the Era of Embodied AI [[paper](https://arxiv.org/pdf/2505.01458)]

- [**ACM Computing Surveys** 2025] Embodied Intelligence: A Synergy of Morphology, Action, Perception and Learning [[paper](https://dl.acm.org/doi/full/10.1145/3717059)]

- [2024] Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI [[paper](https://arxiv.org/abs/2407.06886)]


## 📊 Benchmark

- [2025] RoboVerse: Towards a Unified Platform, Dataset and Benchmark for Scalable and Generalizable Robot Learning [[project](https://roboverseorg.github.io/)]

- [2024] HumanoidBench: Simulated Humanoid Benchmark for Whole-Body Locomotion and Manipulation [[project](https://humanoid-bench.github.io/)] [[paper](https://arxiv.org/abs/2403.10506)]

- [2024] Mimicking-Bench: A Benchmark for Generalizable Humanoid-Scene Interaction Learning via Human Mimicking [[project](https://mimicking-bench.github.io/)]

- [2024] ManiSkill3: GPU Parallelized Robotics Simulation and Rendering for Generalizable Embodied AI [[project](https://www.maniskill.ai/)]


## 🌊 Simulators

- **MuJoCo**: A physics engine for model-based control [[code](https://github.com/google-deepmind/mujoco)] [[document](https://mujoco.readthedocs.io/en/stable/)]

- **Isaac Gym**: High Performance GPU-Based Physics Simulation For Robot Learning [[code](https://github.com/isaac-sim/IsaacGymEnvs)] [[paper](https://arxiv.org/abs/2108.10470)]

- **Isaac Lab**: A Unified Simulation Framework for Interactive Robot Learning Environments [[code](https://github.com/isaac-sim/IsaacLab)] [[document](https://github.com/isaac-sim/IsaacLab)]

- **Genesis**: A Generative and Universal Physics Engine for Robotics and Beyond [[code](https://github.com/Genesis-Embodied-AI/Genesis)] [[project](https://genesis-embodied-ai.github.io/)]

- **SAPIEN**: A SimulAted Part-based Interactive ENvironment [[code](https://github.com/haosulab/SAPIEN)]


## ❤️ Acknowledgment

Many thanks to [JonyZhang](https://github.com/jonyzhang2023/awesome-humanoid-learning?tab=readme-ov-file)'s repository for providing these valuable resources. For those interested in humanoid robot hardware, news, and developments, this serves as an excellent reference.

