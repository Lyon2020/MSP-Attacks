
<!--# **Adversarial Attacks on Autonomous Driving Perception Systems: A Multi-Sensor Perspective**-->

# **A Survey on Adversarial Attacks on Autonomous Vehicles: A Multi-Sensor Perspective**

## **📌 Overview**

MSP-Attacks is a curated repository of research papers on adversarial attacks targeting autonomous driving perception systems.
This project focuses on vulnerabilities across single-sensor modalities and multi-sensor fusion frameworks, aiming to provide the community with a structured reference for understanding, comparing, and tracking the latest research trends.

## **🎯 Research Scope**


<!-- Coming soon...... -->
<!-- ## Table of Contents...... -->


## **🚗🎭 Table of Contents**

- [Methods: A Survey](#methods-a-survey)
  - [Adversarial Attacks Surveys](#adversarial-attacks-surveys)

  - [Adversarial Attacks on Camera](#adversarial-attacks-on-camera)
    - [Adversarial Attacks on 2D Tasks——Classification and Detection](#adversarial-attacks-on-2d-tasksclassification-and-detection)
    - [Adversarial Attacks on 2D Tasks——Semantic Segmentation](#adversarial-attacks-on-2d-taskssemantic-segmentation)
    - [Adversarial Attacks on 2D Tasks——Lane Detection](#adversarial-attacks-on-2d-taskslane-detection)
    - [Adversarial Attacks on 3D Tasks——Classification and Detection](#adversarial-attacks-on-3d-tasksclassification-and-detection)
    - [Adversarial Attacks on 3D Tasks——Depth Estimation](#adversarial-attacks-on-3d-tasksdepth-estimation)

  - [Adversarial Attacks on LiDAR](#adversarial-attacks-on-lidar)
    - [Adversarial Attacks on LiDAR——Classification and Detection](#adversarial-attacks-on-lidarclassification-and-detection)
    - [Adversarial Attacks on LiDAR——Semantic Segmentation](#adversarial-attacks-on-lidarsemantic-segmentation)

  - [Adversarial Attacks on Radar](#adversarial-attacks-on-radar)

  - [Adversarial Attacks on GPS](#adversarial-attacks-on-gps)

  - [Adversarial Attacks on Multi-Sensor Fusion](#adversarial-attacks-on-multi-sensor-fusion)

## Methods: A Survey

### Adversarial Attacks Surveys
| Year | Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | ACM-TSEM | [A Taxonomy of System-Level Attacks on Deep Learning Models in Autonomous Vehicles][P1] | - |
| 2025 | T-ITS | [A State-of-the-Art Review on Attacks and Defense Mechanisms for LiDAR on Autonomous Vehicles][P2] | - |
| 2025 | T-IV | [Adversarial Attacks on Autonomous Driving Systems in the Physical World: a Survey][P4] | - |
| 2024 | T-PAMI | [Physical Adversarial Attack Meets Computer Vision: A Decade Survey][P3] | [Code][C3] |
| 2024 | T-ITS | [Adapting Image Classification Adversarial Deceptions for Road Sign Misclassification in Autonomous Vehicles: A Comparative Study][P5] | - |
| 2024 | T-ITS | [Toward Robust 3D Perception for Autonomous Vehicles: A Review of Adversarial Attacks and Countermeasures][P6] | - |
| 2024 | arXiv | [SoK: On the Semantic AI Security in Autonomous Driving][P7] | [Code][C7] / [Project Page][PP7] |
| 2023 | OJVT | [Cybersecurity of Autonomous Vehicles: A Systematic Literature Review of Adversarial Attacks and Defense Models][P9] | - |
| 2023 | Neurocomputing | [Adversarial Examples Based on Object Detection Tasks: A Survey][P10] | - |
| 2023 | arXiv | [A Survey on Physical Adversarial Attack in Computer Vision][P11] | [Code][C11] |
| 2022 | T-ITS | [A Survey on Cyber-Security of Connected and Autonomous Vehicles (CAVs)][P8] | - |
| 2022 | IEEE OJITS | [Countering Adversarial Attacks on Autonomous Vehicles Using Denoising Techniques: A Review][P12] | - |
| 2022 | Computers & Security | [A Survey on Adversarial Attacks in Vision: Taxonomy, Visualization and Future Directions][P13] | - |
| 2022 | arXiv | [Adversarial Patch Attacks and Defences in Vision-Based Tasks: A Survey][P14] | - |
| 2021 | T-II | [Deep Learning-Based Autonomous Driving Systems: A Survey of Attacks and Defenses][P15] | - |
| 2021 | IEEE Signal Processing Magazine | [The Vulnerability of Deep Networks to Adversarial Attacks in Autonomous Driving][P16] | - |
| 2021 | Applied Computer Systems | [Adversarial Attacks and Defense Technologies on Autonomous Vehicles: A Review][P17] | - |
| 2021 | Computers & Security | [Cybersecurity for Autonomous Vehicles: Review of Attacks and Defense][P18] | - |
| 2020 | IEEE Signal Processing Magazine | [Toward Robust Sensing for Autonomous Vehicles: An Adversarial Perspective][P19] | - |
| 2020 | ICSE | [A Comprehensive Study of Autonomous Vehicle Bugs][P20] | - |









### Adversarial Attacks on Camera
#### Adversarial Attacks on 2D Tasks——Classification and Detection
| Year | Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | ICCV | [Towards Powerful and Practical Patch Attacks for 2D Object Detection in Autonomous Driving][P21] | - |
| 2025 | ICCV | [Adversarial Attention Perturbations for Large Object Detection Transformers][P22] | [Code][C22] |
| 2024 | NeurIPS | [Revisiting Adversarial Patches for Designing Camera-Agnostic Attacks against Person Detection][P23] | [Code][C23] |
| 2024 | IJCV | [Infrared Adversarial Patches with Learnable Shapes and Locations in the Physical World][P24] | [Code][C24] |
| 2024 | T-IFS | [Stealthy and Effective Physical Adversarial Attacks  in Autonomous Driving][P25] | [Project Page][PP25] |
| 2024 | T-PAMI | [Unified Adversarial Patch for Visible-Infrared Cross-Modal Attacks in the Physical World][P26] | [Code][C26] |
| 2024 | T-ITS | [CARLA-GEAR: ADataset Generator for a Systematic Evaluation of Adversarial Robustness of Vision Models][P27] | [Code][C27] |
| 2024 | Neural Networks | [Adversarial Infrared Curves: An Attack on Infrared Pedestrian Detectors in the Physical World][P28] | - |
| 2024 | Neural Networks | [Adversarial infrared blocks: A mul...black-box attack to thermal infrared detectors in physical world][P29] | [Code][C29] |
| 2024 | NDSS | [Invisible Reflections: Leveraging Infrared Laser Reflections to Target Traffic Sign Perception][P30] | [Project Page][PP30] |
| 2024 | IOT | [OptiCloak: Blinding Vision-Based Autonomous Driving Systems Through Adversarial Optical Projection][P31] | - |
| 2023 | IV | [Adversarial Driving: Attacking End-to-End Autonomous Driving][P32] | [Code][C32] |
| 2023 | Computers & Security | [Light can be Dangerous: Steal...y and Effective Physical-world Adversarial Attack by Spot Light][P33] | - |
| 2023 | AAAI | [HOTCOLD Block: Fooling Thermal Infrared Detectors with a Novel Wearable Design][P34] | [Code][C34] / [Project Page][PP34] |
| 2023 | ICCV | [Unified Adversarial Patch for Cross-modal Attacks in the Physical World][P35] | [Code][C35] |
| 2023 | ICCV | [REAP: ALarge-Scale Realistic Adversarial Patch Benchmark][P36] | [Code][C36] |
| 2023 | ICCV | [Does Physical Adversarial Example Really Matter...Towards System-Level Effect of Adversarial Object Evasion Attack][P37] | [Project Page][PP37] |
| 2023 | CVPR | [Physically Adversarial Infrared Patches with Learnable Shapes and Locations][P38] | - |
| 2023 | PMLR | [Adversarial Laser Spot: Robust and Covert Physical-World Attack to DNNs][P39] | [Code][C39] |
| 2023 | USENIX | [TPatch: A Triggered Physical Adversarial Patch][P40] | [Code][C40] |
| 2022 | NDSS | [Fooling the Eyes of Autonomous Vehicles: Robust...al Adversarial Examples Against Traffic Sign Recognition Systems][P41] | [Project Page][PP41] |
| 2022 | CVPR | [Give me your attention: Dot-product attention considered harmful for adversarial patch robustness][P42] | - |
| 2022 | T-PAMI | [Adversarial Stickers: A Stealthy Attack Method in the Physical World][P43] | [Code][C43] |
| 2022 | CVPR | [Shadows can be Dangerous: Stealthy and Effective Physical-world Adversarial Attack by Natural Phenomenon][P44] | [Code][C44] |
| 2021 | CVPR | [Adversarial Laser Beam: Effective Physical-World Attack to DNNs in a Blink][P45] | [Code][C45] |
| 2021 | IEEE SP | [Poltergeist: Acoustic Adversarial Machine Learning against Cameras and Computer Vision][P46] | [Code][C46] |
| 2021 | USENIX | [SLAP: Improving Physical Adversarial Examples with Short-Lived Adversarial Perturbations][P47] | [Code][C47] |
| 2021 | JIOT | [Adaptive Square Attack: Fooling Autonomous Cars With Adversarial Traffic Signs][P48] | [Code][C48] |
| 2021 | AAAI | [Fooling Thermal Infrared Pedestrian Detectors in Real World Using Small Bulbs][P49] | - |
| 2021 | ICCV | [Naturalistic Physical Adversarial Patch for Object Detectors][P50] | [Code][C50] |
| 2021 | CVPR | [The Translucent Patch: A Physical and Universal Attack on Object Detectors][P51] | - |
| 2020 | arXiv | [Dynamic Adversarial Patch for Evading Object Detection Models][P52] | - |
| 2020 | CVPR | [PhysGAN: Generating Physical-World-Resilient Adversarial Examples for Autonomous Driving][P53] | [Code][C53] |
| 2020 | CVPR | [Adversarial Camouflage: Hiding Physical-World Attacks with Natural Styles][P54] | [Code][C54] |
| 2020 | ICLR | [FOOLING DETECTION ALONE IS NOT ENOUGH: ADVERSARIAL ATTACK AGAINST MULTIPLE OBJECT TRACKING][P55] | [Code][C55] |
| 2020 | TPS-ISA | [Adversarial Objectness Gradient Attacks in Real-time Object Detection Systems][P56] | [Code][C56] |
| 2019 | CCS | [Seeing isn’t Believing: Towards More Robust Adversarial Attack Against Real World Object Detectors][P57] | [Project Page][PP57] |
| 2019 | JSA | [Attacking Vision-based Perception in End-to-End Autonomous Driving Models][P58] | [Code][C58] |
| 2019 | AAAI | [Perceptual-sensitive gan for generating adversarial patches][P59] | - |
| 2019 | PMLR | [Adversarial camera stickers: A physical camera-based attack on deep learning systems][P60] | [Code][C60] |
| 2018 | CVPR | [Robust Physical-World Attacks on Deep Learning Visual Classification][P61] | [Code][C61] |
| 2017 | CVPR | [NO Need to Worry about Adversarial Examples in Object Detection in  Autonomous Vehicles][P62] | - |



#### Adversarial Attacks on 2D Tasks——Semantic Segmentation
| Year | Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | T-M | [Black-Box Targeted Adversarial Attack on Segment Anything (SAM)][P88] | - |
| 2025 | IEEE RAL | [Semantic Hierarchy-Guided Adversarial Attack for Autonomous Driving][P89] | - |
| 2025 | IEEE SPW | [Do Adversarial Patches Generalize? Attack Transferability Study Across Real-time Segmentation Models in Autonomous Vehicles][P90] | [Code][C90] |
| 2025 | AAAI | [Robust SAM: On the Adversarial Robustness of Vision Foundation Models][P91] | - |
| 2024 | TNNLS | [On the Real-World Adversarial Robustness of Real-Time Semantic Segmentation Models for Autonomous Driving][P92] | [Code][C92] |
| 2024 | WACV | [Uncertainty-weighted Loss Functions for Improved Adversarial Attacks on Semantic Segmentation][P93] | [Code][C93] |
| 2024 | CVPR | [Practical Region-level Attack against Segment Anything Models][P94] | - |
| 2024 | ACM MM | [Cascaded Adversarial Attack: Simultaneously Fooling Rain Removal and Semantic Segmentation Networks][P95] | - |
| 2024 | Pattern Recognition | [Time-aware and Task-transferable Adversarial Attack for Perception of Autonomous Vehicles][P96] | - |
| 2024 | ECCV | [Towards Reliable Evaluation and Fast Training of Robust Semantic Segmentation Models][P97] | [Code][C97] |
| 2023 | ACM MM | [PAIF: Perception-Aware Infrared-Visible Image Fusion for Attack-Tolerant Semantic Segmentation][P98] | [Code][C98] |
| 2023 | T-CSVT | [Adversarial Attacks on Video Object Segmentation With Hard Region Discovery][P99] | - |
| 2023 | TNNLS | [On the Real-World Adversarial Robustness of Real-Time Semantic Segmentation Models for Autonomous Driving][P100] | [Code][C100] |
| 2023 | CVPR | [Proximal Splitting Adversarial Attack for Semantic Segmentation][P101] | [Code][C101] |
| 2022 | ECCV | [SegPGD: An Effective and Efficient Adversarial Attack for Evaluating and Boosting Segmentation Robustness][P102] | [Code][C102] |
| 2022 | WACV | [Evaluating the Robustness of Semantic Segmentation for Autonomous Driving against Real-World Adversarial Patch Attacks][P103] | [Code][C103] |
| 2022 | WACV | [Semantically Stealthy Adversarial Attacks against Segmentation Models][P104] | - |
| 2022 | Computers & Security | [Adversarial Attacks on YOLACT Instance Segmentation][P105] | - |
| 2021 | T-II | [Adversarial Attack Against Urban Scene Segmentation for Autonomous Vehicles][P106] | - |
| 2020 | RAL | [Deceiving Image-to-Image Translation Networks for Autonomous Driving With Adversarial Perturbations][P107] | - |
| 2018 | ECCV | [Characterizing Adversarial Examples Based on Spatial Consistency Information for Semantic Segmentation][P108] | - |
| 2018 | CVPR | [On the Robustness of Semantic Segmentation Models to Adversarial Attacks][P109] | [Code][C109] |
| 2018 | CVPR | [On the Robustness of Semantic Segmentation Models to Adversarial Attacks (Extended Version)][P110] | [Code][C110] |
| 2017 | ICCV | [Universal Adversarial Perturbations Against Semantic Image Segmentation][P111] | - |


#### Adversarial Attacks on 2D Tasks——Lane Detection
| Year | Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2024 | arXiv | [Discovering New Shadow Patterns for Black-Box Attacks on Lane Detection of Autonomous Vehicles][P112] | [Code][C112] |
| 2022 | MM | [Physical Backdoor Attacks to Lane Detection Systems in Autonomous Driving][P113] | [Code][C113] |
| 2021 | USENIX | [Dirty Road Can Attack: Security of Deep Learning based Automated Lane Centering under Physical-World Attack][P114] | [Code][C114] / [Project Page][PP114] |
| 2021 | USENIX | [Too Good to Be Safe: Tricking Lane Detection in Autonomous Driving with Crafted Perturbations][P115] | [Code][C115] / [Project Page][PP115] |





#### Adversarial Attacks on 3D Tasks——Classification and Detection
| Year | Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | T-CSVT | [A Unified Framework for Adversarial Patch Attacks Against Visual 3D Object Detection in Autonomous Driving][P63] | - |
| 2025 | T-IP | [Physically Realizable Adversarial Creating Attack Against Vision-Based BEV Space 3D Object Detection][P64] | - |
| 2025 | T-DSC | [Toward Robust and Accurate Adversarial Camouflage Generation against Vehicle Detectors][P65] | [Code][C65] |
| 2025 | ICCV | [3D Gaussian Splatting Driven Multi-View Robust Physical Adversarial Camouflage Generation][P66] | [Code][C66] |
| 2024 | NeurIPS | [CNCA: Toward Customizable and Natural Generation of Adversarial Camouflage for Vehicle Detectors][P67] | [Code][C67] |
| 2024 | arXiv | [Adv3D: Generating 3D Adversarial Examples for 3D Object Detection in Driving Scenarios with NeRF][P68] | [Code][C68] |
| 2024 | IROS | [Adv3D: Generating 3D Adversarial Examples for 3D Object Detection in Driving Scenarios with NeRF][P69] | [Code][C69] |
| 2024 | CVPR | [Towards Transferable Targeted 3D Adversarial Attack in the Physical World][P70] | [Code][C70] |
| 2024 | CVPR | [Infrared Adversarial Car Stickers][P71] | - |
| 2024 | TMLR | [On the Adversarial Robustness of Camera-based 3D Object Detection][P72] | [Code][C72] |
| 2024 | ICML | [RAUCA: A Novel Physical Adversarial Attack on Vehicle Detectors via Robust and Accurate Camouflage Generation][P73] | [Code][C73] |
| 2024 | IJCV | [Generate Transferable Adversarial Physical Camouflages via Triplet Attention Suppression][P74] | - |
| 2023 | ICCV | [ACTIVE: Towards Highly Transferable 3D Physical Camouflage for Universal and Robust Vehicle Evasion][P75] | [Project Page][PP75] |
| 2023 | CVPR | [Understanding the Robustness of 3D Object Detection with Bird’s-Eye-View Representations in Autonomous Driving][P76] | [Code][C76] |
| 2023 | CVPR | [Towards Benchmarking and Assessing Visual Naturalness of Physical World Adversarial Attacks][P77] | [Code][C77] |
| 2023 | Pattern Recognition | [Boosting Transferability of Physical Attack Against Detectors by Redistributing Separable Attention][P78] | [Code][C78] |
| 2022 | AAAI | [FCA: Learning a 3D Full-coverage Vehicle Camouflage for Multi-view Physical Adversarial Attack][P79] | [Code][C79] |
| 2022 | CVPR | [DTA: Physical Camouflage Attacks using Differentiable Transformation Network][P80] | [Project Page][PP80] |
| 2022 | IJCAI | [Learning Coated Adversarial Camouflages for Object Detectors][P81] | - |
| 2021 | CVPR | [Dual Attention Suppression Attack: Generate Adversarial Camouflage in Physical World][P82] | [Code][C82] |
| 2021 | JIOT | [Evaluating Adversarial Attacks on Driving Safety in Vision-Based Autonomous Vehicles][P83] | - |
| 2020 | CVPR | [Universal Physical Camouflage Attacks on Object Detectors][P84] | [Code][C84] |
| 2020 | arXiv | [Physical Adversarial Attack on Vehicle Detector in the Carla Simulator][P85] | - |
| 2019 | ICLR | [CAMOU: LEARNING A VEHICLE CAMOUFLAGE FOR PHYSICAL ADVERSARIAL ATTACK ON OBJECT DETECTORS IN THE WILD][P86] | [Code][C86] |
| 2018 | ICML | [Synthesizing Robust Adversarial Examples][P87] | - |


#### Adversarial Attacks on 3D Tasks——Depth Estimation
| Year |  Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2024 | CVPR | [Physical 3D Adversarial Attacks against Monocular Depth Estimation in Autonomous Driving][P116] | [Code][C116] |
| 2024 | T-PAMI | [Self-supervised Adversarial Training of Monocular Depth Estimation against Physical-World Attacks][P117] | [Code][C117] |
| 2024 | ICML | [BadPart: Unified Black-box Adversarial Patch Attacks against Pixel-wise Regression Tasks][P118] | [Code][C118] |
| 2024 | USENIX | [π-Jack: Physical-World Adversarial Attack on Monocular Depth Estimation with Perspective Hijacking][P119] | [Code][C119] |
| 2024 | NeurIPS | [Beware of Road Markings: A New Adversarial Patch Attack to Monocular Depth Estimation][P120] | [Code][C120] |
| 2024 | IEEE Sensors | [Physical Adversarial Attack on Monocular Depth Estimation via Shape-Varying Patches][P121] | - |
| 2024 | IROS | [SSAP: A Shape-Sensitive Adversarial Patch for Comprehensive Disruption of Monocular Depth Estimation in Autonomous Navigation Applications][P122] | [Code][C122] |
| 2024 | ACM ICM | [DepthCloak: Projecting Optical Camouflage Patches for Erroneous Monocular Depth Estimation of Vehicles][P123] | - |
| 2023 | ICLR | [Adversarial Training of Self-supervised Monocular Depth Estimation against Physical-World Attacks][P124] | [Code][C124] |
| 2022 | ECCV | [Physical Attack on Monocular Depth Estimation with Optimal Adversarial Patches][P125] | [Code][C125] |
| 2022 | IROS | [Adversarial Attacks on Monocular Pose Estimation][P126] | [Code][C126] |
| 2020 | NeurIPS | [Targeted Adversarial Perturbations for Monocular Depth Prediction][P127] | - |
| 2020 | arXiv | [Adversarial Attacks on Monocular Depth Estimation][P128] | - |



### Adversarial Attacks on LiDAR
#### Adversarial Attacks on LiDAR——Classification and Detection
| Year |  Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | NDSS | [On the Realism of LiDAR Spoofing Attacks against Autonomous Driving Vehicle at High Speed and Long Distance][P129] | [Project Page][PP129] |
| 2024 | NDSS | [LiDAR Spoofing Meets the New-Gen: Capability Improvements, Broken Assumptions, and New Attack Strategies][P132] | [Project Page][PP132] |
| 2024 | NDSS | [Automated Tracking System for LiDAR Spoofing Attacks on Moving Targets][P133] | [Project Page][PP133] |
| 2024 | CVPR | [Hide in Thicket: Generating Imperceptible and Rational Adversarial Perturbations on 3D Point Clouds][P134] | [Code][C134] |
| 2024 | T-ITS | [Sr-adv: Salient Region Adversarial Attacks on 3D Point Clouds for Autonomous Driving][P135] | - |
| 2023 | CVPR | [SlowLiDAR: Increasing the Latency of LiDAR-Based Detection Using Adversarial Examples][P136] | [Code][C136] |
| 2023 | T-GRS | [EVAA—Exchange Vanishing Adversarial Attack on LiDAR Point Clouds in Autonomous Vehicles][P137] | - |
| 2023 | SP | [PLA-LiDAR: Physical Laser Attacks against LiDAR-based 3D Object Detection in Autonomous Vehicle][P138] | [Project Page][PP138] |
| 2023 | USENIX | [You Can’t See Me: Physical Removal Attacks on LiDAR-based Autonomous Vehicles Driving Frameworks][P139] | [Project Page][PP139] |
| 2023 | WACV | [Explainability-aware One Point Attack for Point Cloud Neural Networks][P140] | [Code][C140] |
| 2022 | AUTOSEC | [Generating 3D Adversarial Point Clouds under the Principle of LiDARs][P143] | - |
| 2021 | ICCV | [Fooling LiDAR Perception via Adversarial Trajectory Perturbation][P144] | [Code][C144] |
| 2021 | CCS | [Robust Roadside Physical Adversarial Attack Against Deep Learning in LiDAR Perception Modules][P145] | [Project Page][PP145] |
| 2021 | Neurocomputing | [Adversarial Point Cloud Perturbations Against 3D Object Detection in Autonomous Driving Systems][P146] | - |
| 2021 | CCS | [Can We Use Arbitrary Objects to Attack LiDAR Perception in Autonomous Driving?][P147] | - |
| 2020 | USENIX | [Towards Robust LiDAR-based Perception in Autonomous Driving: General Black-box Adversarial Sensor Attack and Countermeasures][P149] | [Project Page][PP149] |
| 2020 | ECCV | [Adversarial Shape Perturbations on 3D Point Clouds][P150] | [Code][C150] |
| 2020 | ECCV | [AdvPC: Transferable Adversarial Perturbations on 3D Point Clouds][P151] | [Code][C151] |
| 2020 | CVPR | [Physically Realizable Adversarial Examples for LiDAR Object Detection][P152] | - |
| 2019 | ACM CCS | [Adversarial Sensor Attack on LiDAR-based Perception in Autonomous Driving][P153] | [Project Page][PP153] |
| 2019 | CVPR | [Generating 3D Adversarial Point Clouds][P154] | [Code][C154] |
| 2019 | CVPR | [Robustness of 3D Deep Learning in an Adversarial Setting][P155] | [Code][C155] |
| 2019 | arXiv | [Adversarial Objects Against LiDAR-Based Autonomous Driving Systems][P156] | [Project Page][PP156] |

##### Adversarial Attacks on LiDAR——Semantic Segmentation
| Year |  Venue  | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | CVPR | [Explaining 3D Point Cloud Semantic Segmentation Models Through Adversarial Attacks][P130] | [Code][C130] |
| 2025 | IEEE RA-L | [Robust Unsupervised Domain Adaptation for 3D Point Cloud Segmentation Under Source Adversarial Attacks][P131] | - |
| 2023 | DSN | [On Adversarial Robustness of Point Cloud Semantic Segmentation][P142] | [Code][C142] |
| 2023 | CVPR | [Open-set Semantic Segmentation for Point Clouds via Adversarial Prototype Framework][P141] | - |
| 2021 | SenSys | [Adversarial Attacks Against LiDAR Semantic Segmentation in Autonomous Driving][P148] | - |


### Adversarial Attacks on Radar
| Year | Venue | Paper Title | Link |
|:----:|:------:|-------------|:----:|
| 2025 | MobiSys | [Toward Spoofing-Resilient and Communication-Integrated MmWave Radar Sensing][P157] | - |
| 2025 | IV | [Deep Sensor Fusion for Detection and Localization of Automotive Radar Spoofing Attacks][P158] | - |
| 2025 | EEE Communications Surveys & Tutorials | [A Survey of mmWave Radar-Based Sensing in Autonomous Vehicles, Smart Homes and Industry][P159] | - |
| 2025 | RadarConf25 | [Adversarial Attack on Automotive Radar Point Cloud Classifiers][P160] | - |
| 2023 | CCS | [TileMask: A Passive-Reflection-based Attack against mmWave Radar Object Detection in Autonomous Driving][P161] | - |
| 2023 | IEEE SP | [mmspoof: Resilient Spoofing of Automotive Millimeterwave Radars Using Reflect Array][P162] | [Code][C162] |
| 2023 | arXiv | [Madradar: A Black-box Physical Layer Attack Framework on mmWave Automotive FMCW Radars][P163] | [Project Page][PP163] |
| 2022 | ITSM | [Comparative Analysis of Radar and LiDAR Technologies for Automotive Applications][P164] | - |
| 2022 | arXiv | [Adversarial Attack on Radar-based Environment Perception Systems][P165] | - |
| 2021 | T-IFS | [Who Is in Control? Practical Physical Layer Attack and Defense for mmWave-Based Sensing in Autonomous Vehicles][P166] | [Code][C166] |
| 2021 | JCE | [Low-cost Distance-spoofing Attack on FMCW Radar and Its Feasibility Study on Countermeasure][P167] | - |
| 2021 | ASHES | [Spoofing Attacks Against Vehicular FMCW Radar][P168] | - |
| 2020 | Information Sciences | [Adversarial Attacks on Deep-learning-based Radar Range Profile Target Recognition][P169] | - |
| 2020 | IEEE SPM | [Toward Robust Sensing for Autonomous Vehicles: An Adversarial Perspective][P170] | - |



### Adversarial Attacks on GPS
| Year | Venue | Paper Title | Link |
|:----:|:-----:|-------------|:----:|
| 2025 | IoTJ  | [GPS Attack Detection and Defense for Secure Localization of Automated Vehicles Based on Vehicle-to-Vehicle Technology][P171] | - |
| 2025 | ojvt  | [Detection of Multiple Small Biased GPS Spoofing Attacks on Autonomous Vehicles Using Time Series Analysis][P172] | - |
| 2025 | arXiv | [GPS Spoofing Attack Detection in Autonomous Vehicles Using Adaptive DBSCAN][P173] | - |
| 2025 | T-PS   | [Safe Driving Adversarial Trajectory Can Mislead: Toward More Stealthy Adversarial Attack Against Autonomous Driving Prediction Module][P174] | - |
| 2025 | IEEE  | [Detection of multiple small biased GPS spoofing attacks on autonomous vehicles][P175] | - |
| 2024 | T-VT   | [Robust Indoor Positioning of Automated Guided Vehicles in Internet of Things Networks With Deep Convolution Neural Network Considering Adversarial Attacks][P176] | - |
| 2024 | T-VT   | [Anomaly Detection and Secure Position Estimation Against GPS Spoofing Attack: A Security-Critical Study of Localization in Autonomous Driving][P177] | - |
| 2024 | IEEE  | [GPS Spoofing Detection on Autonomous Vehicles with XGBoost][P178] | - |
| 2023 | T-ITS  | [Anomaly Detection Against GPS Spoofing Attacks on Connected and Autonomous Vehicles Using Learning From Demonstration][P179] | - |
| 2023 | T-ITS  | [Infrastructure-Enabled GPS Spoofing Detection and Correction][P180] | - |
| 2023 | IEEE  | [A machine learning approach for detecting gps location spoofing attacks in autonomous vehicles][P181] | - |
| 2023 | IEEE  | [Securing Autonomous Vehicles Against GPS Spoofing Attacks: A Deep Learning Approach][P182] | - |
| 2021 | T-M    | [Covert Attacks Through Adversarial Learning: Study of Lane Keeping Attacks on the Safety of Autonomous Vehicles][P183] | - |
| 2021 | IEEE  | [GPS location spoofing attack detection for enhancing the security of autonomous vehicles][P184] | - |
| 2020 | T-VT   | [Localizing Spoofing Attacks on Vehicular GPS Using Vehicle-to-Vehicle Communications][P185] | - |
| 2019 | SP    | [Security of GPS/INS Based On-road Location Tracking Systems][P186] | - |
| 2019 | IEEE  | [Security of GPS/INS based on-road location tracking systems][P187] | - |
| 2018 | USENIX| [All Your GPS Are Belong To Us: Towards Stealthy Manipulation of Road Navigation Systems][P188] | - |
| 2018 | USENIX| [All your $\{GPS\}$ are belong to us: Towards stealthy manipulation of road navigation systems][P189] | - |


### Adversarial Attacks on Multi-Sensor Fusion
| Year |  Venue  | Paper Title | Link |
|:----:|:-------:|-------------|:----:|
| 2025 | CVPRW  | [Probing Vulnerabilities of Vision-LiDAR Based Autonomous Driving Systems][P190] | - |
| 2024 | MobiCom | [Malicious Attacks against Multi-Sensor Fusion in Autonomous Driving][P191] | - |
| 2024 | ICLR   | [FUSION IS NOT ENOUGH: SINGLE MODAL ATTACKS ON FUSION MODELS FOR 3D OBJECT DETECTION][P192] | [Code][C192] / [Project Page][PP192] |
| 2024 | IEEE TR | [UniAda: Universal Adaptive Multiobjective Adversarial Attack for End-to-End Autonomous Driving Systems][P193] | [Code][C193] |
| 2023 | arXiv  | [Uncertainty-Encoded Multi-Modal Fusion for Robust Object Detection in Autonomous Driving][P194] | - |
| 2022 | NeurIPS | [SafeBench: A Benchmarking Platform for Safety Evaluation of Autonomous Vehicles][P195] | [Code][C195] / [Project Page][PP195] |
| 2022 | USENIX | [Security Analysis of Camera-LiDAR Fusion Against Black-Box Attacks on Autonomous Vehicles][P196] | - |
| 2021 | IEEE S\&P | [Invisible for both Camera and LiDAR: Security of Multi-Sensor Fusion based Perception in Autonomous Driving Under Physical-World Attacks][P197] | [Code][C197] / [Project Page][PP197] |
| 2021 | T-DSC  | [“Seeing is Not Always Believing”: Detecting Perception Error Attacks Against Autonomous Vehicles][P198] | - |
| 2021 | CoRL  | [Exploring Adversarial Robustness of Multi-sensor Perception Systems in Self Driving][P199] | - |
| 2021 | IROS  | [Adversarial Attacks on Camera-LiDAR Models for 3D Car Detection][P200] | - |
| 2021 | T-VT   | [Multi-Source Adversarial Sample Attack on Autonomous Vehicles][P201] | - |
| 2021 | IJIS  | [Camdar-adv: Generating adversarial patches on 3D object][P202] | - |
| 2020 | USENIX | [Drift with Devil: Security of Multi-Sensor Fusion based Localization in High-Level Autonomous Driving under GPS Spoofing][P203] | [Project Page][PP203] |













































































































































[P1]: https://dl.acm.org/doi/pdf/10.1145/3769009
[P2]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10747748
[P3]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10602786
[C3]: https://github.com/weihui1308/PAA

[P4]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10723812
[P5]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10623847
[P6]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10682109

[P7]: https://www.semanticscholar.org/reader/3cd3d227d55f661a38248428827f13992f9bfb41
[C7]: https://github.com/ASGuard-UCI/pass
[PP7]: https://sites.google.com/view/av-ioat-sec/pass

[P8]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9447840
[P9]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10097455

[P10]: https://pdf.sciencedirectassets.com/271597/1-s2.0-S09252
[P11]: https://arxiv.org/pdf/2209.14262
[C11]: https://github.com/winterwindwang/Physical-Adversarial-Attacks-Survey

[P12]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9678365
[P13]: https://pdf.sciencedirectassets.com/271887/1-s2.0-S01674

[P14]: https://arxiv.org/pdf/2206.08304
[P15]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9397393
[P16]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9307309
[P17]: https://reference-global.com/article/10.2478/acss-2021-0012
[P18]: https://pdf.sciencedirectassets.com/271887/1-s2.0-S01674

[P19]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9127857
[P20]: https://jgarcia.ics.uci.edu/wp-content/uploads/icse2020_avbugs.pdf

<!-- 第二个表的 -->
[P21]: https://arxiv.org/pdf/2508.10600

[P22]: https://openaccess.thecvf.com/content/ICCV2025/papers/Yah...ions_for_Large_Object_Detection_Transformers_ICCV_2025_paper.pdf
[C22]: https://github.com/zacharyyahn/AFOG

[P23]: https://www.proceedings.com/content/079/079017-0259open.pdf
[C23]: https://github.com/weihui1308/CAP

[P24]: https://rd.springer.com/content/pdf/10.1007/s11263-023-01963-y.pdf
[C24]: https://github.com/shighghyujie/infrared_patch_attack

[P25]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10583962
[PP25]: https://anonymous.4open.science/r/7003

[P26]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10310159
[C26]: https://github.com/Aries-iai/Cross-modal_Patch_Attack

[P27]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10576049
[C27]: http://carlagear.retis.santannapisa.it

[P28]:  <!-- 原表中未给出链接，可留空或后续自行补充 -->

[P29]: https://pdf.sciencedirectassets.com/271125/1-s2.0-S089360...EUCIFMDZ7ORnaprsIdY28jxP%2FE8qYnC0g4CUbNMUSInuGSyAiEA3G52PeMBI95
[C29]: https://github.com/ChengYinHu/AdvIB.git

[P30]: https://www.ndss-symposium.org/wp-content/uploads/2024-1053-paper.pdf
[PP30]: https://sites.google.com/view/av-ioat-sec/ilr-attack

[P31]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10538370

[P32]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10186386
[C32]: https://github.com/wuhanstudio/adversarial-driving

[P33]: https://pdf.sciencedirectassets.com/271887/1-s2.0-S016740...34e397051c23a7cabe6e1a5f19650724c151a492ec6dd993224c7dc4f81ea6f5

[P34]: https://ojs.aaai.org/index.php/AAAI/article/download/26777/26549
[C34]: https://github.com/wagner-group/reap-benchmark
[PP34]: https://github.com/weihui1308/HOTCOLDBlock

[P35]: https://openaccess.thecvf.com/content/ICCV2023/papers/Wei...or_Cross-Modal_Attacks_in_the_Physical_World_ICCV_2023_paper.pdf
[C35]: https://github.com/Aries-iai/Cross-modal_Patch_Attack

[P36]: https://openaccess.thecvf.com/content/ICCV2023/papers/Hin...-Scale_Realistic_Adversarial_Patch_Benchmark_ICCV_2023_paper.pdf
[C36]: https://github.com/wagner-group/reap-benchmark

[P37]: openaccess.thecvf.com/content/ICCV2023/papers/Wang_Does_P..._Really_Matter_to_Autonomous_Driving_Towards_ICCV_2023_paper.pdf
[PP37]: https://sites.google.com/view/av-ioat-sec/sysadv

[P38]: https://openaccess.thecvf.com/content/CVPR2023/papers/Wei..._Patches_With_Learnable_Shapes_and_Locations_CVPR_2023_paper.pdf

[P39]: https://proceedings.mlr.press/v189/hu23b/hu23b.pdf
[C39]: https://github.com/ChengYinHu/AdvLS

[P40]: https://www.usenix.org/system/files/usenixsecurity23-zhu.pdf
[C40]: https://github.com/USSLab/TPatch

[P41]: https://www.ndss-symposium.org/wp-content/uploads/2022-130-paper.pdf
[PP41]: https://seczone.cn/contents/422/1024.html

[P42]: https://openaccess.thecvf.com/content/CVPR2022/papers/Lov...Attention_Considered_Harmful_for_Adversarial_CVPR_2022_paper.pdf

[P43]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9779913
[C43]: https://github.com/jinyugy21/Adv-Stickers_RHDE

[P44]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9878995
[C44]: https://github.com/hncszyq/ShadowAttack

[P45]: https://openaccess.thecvf.com/content/CVPR2021/papers/Dua...Effective_Physical-World_Attack_to_DNNs_in_a_CVPR_2021_paper.pdf
[C45]: https://github.com/RjDuan/Advlight

[P46]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9519394
[C46]: https://github.com/USSLab/PoltergeistAttack

[P47]: https://www.usenix.org/system/files/sec21-lovisotto.pdf
[C47]: https://github.com/ssloxford/short-lived-adversarial-perturbations

[P48]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9165820
[C48]: https://github.com/git-disl/TOG

[P49]: https://cdn.aaai.org/ojs/16477/16477-13-19971-1-2-20210518.pdf

[P50]: https://openaccess.thecvf.com/content/ICCV2021/papers/Hu_...sical_Adversarial_Patch_for_Object_Detectors_ICCV_2021_paper.pdf
[C50]: https://github.com/aiiu-lab/Naturalistic-Adversarial-Patch

[P51]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9577511

[P52]: https://openaccess.thecvf.com/content/CVPR2024/papers/Gue...versarial_Patch_for_Evading_Person_Detectors_CVPR_2024_paper.pdf

[P53]: https://openaccess.thecvf.com/content_CVPR_2020/papers/Ko..._Adversarial_Examples_for_Autonomous_Driving_CVPR_2020_paper.pdf
[C53]: https://github.com/lz3450/physgan

[P54]: https://openaccess.thecvf.com/content_CVPR_2020/papers/Du...g_Physical-World_Attacks_With_Natural_Styles_CVPR_2020_paper.pdf
[C54]: https://github.com/RjDuan/AdvCam-Hide-Adv-with-Natural-Styles

[P55]: https://openreview.net/pdf?id=rJl31TNYPr
[C55]: https://github.com/anonymousjack/hijacking

[P56]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9325397
[C56]: https://github.com/git-disl/TOG

[P57]: https://kaichen.org/paper/conference/CCS2019_zhaoyue.pdf
[PP57]: https://sites.google.com/view/ai-tricker

[P58]: https://arxiv.org/pdf/1910.01907
[C58]: https://github.com/xz-group/AdverseDrive

[P59]: https://ojs.aaai.org/index.php/AAAI/article/download/3893/3771

[P60]: https://arxiv.org/pdf/1904.00759
[C60]: https://github.com/yoheikikuta/adversarial-camera-stickers

[P61]: https://openaccess.thecvf.com/content_cvpr_2018/papers/Eykholt_Robust_Physical-World_Attacks_CVPR_2018_paper.pdf
[C61]: https://github.com/evtimovi/robust_physical_perturbations

[P62]: https://www.semanticscholar.org/reader/31fcc9db03db98481f6ae9fffaef67d20480cba6



<!-- 第三个表的 -->
[P63]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10824853

[P64]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10838314

[P65]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11119058
[C65]: https://github.com/SeRAlab/RAUCA-E2E.

[P66]: https://openaccess.thecvf.com/content/ICCV2025/papers/Lou_3D_Gaussian_Splatting_Driven_Multi-View_Robust_Physical_Adversarial_Camouflage_Generation_ICCV_2025_paper.pdf
[C66]: https://github.com/TRLou/PGA

[P67]: https://neurips.cc/media/neurips-2024/Slides/94545.pdf
[C67]: https://github.com/SeRAlab/CNCA

[P68]: https://arxiv.org/pdf/2309.01351
[C68]: https://github.com/EnVision-Research/Adv3D

[P69]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10801323
[C69]: https://github.com/EnVision-Research/Adv3D

[P70]: https://openaccess.thecvf.com/content/CVPR2024/papers/Huang_Towards_Transferable_Targeted_3D_Adversarial_Attack_in_the_Physical_World_CVPR_2024_paper.pdf
[C70]: https://github.com/aries-iai/tt3d

[P71]: https://openaccess.thecvf.com/content/CVPR2024/papers/Zhu_Infrared_Adversarial_Car_Stickers_CVPR_2024_paper.pdf

[P72]: https://openreview.net/pdf?id=6SofFlwhEv
[C72]: https://github.com/Daniel-xsy/BEV-Attack

[P73]: https://openreview.net/pdf?id=pBTLGM9uWx
[C73]: https://github.com/SeRAlab/Robust-and-Accurate-UV-map-based-Camouflage-Attack

[P74]: https://doi.org/10.1007/s11263-024-02098-4

[P75]: https://openaccess.thecvf.com/content/ICCV2023/papers/Suryanto_ACTIVE_Towards_Highly_Transferable_3D_Physical_Camouflage_for_Universal_and_ICCV_2023_paper.pdf
[PP75]: https://islab-ai.github.io/active-iccv2023/

[P76]: https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_Understanding_the_Robustness_of_3D_Object_Detection_With_Birds-Eye-View_Representations_CVPR_2023_paper.pdf
[C76]: https://github.com/zzj403/BEV_Robust

[P77]: https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Towards_Benchmarking_and_Assessing_Visual_Naturalness_of_Physical_World_Adversarial_CVPR_2023_paper.pdf
[C77]: https://github.com/zhangsn-19/PAN

[P78]: https://www.sciencedirect.com/science/article/pii/S003132032300136X
[C78]: https://github.com/zhangyu13a/transPhyAtt

[P79]: https://ojs.aaai.org/index.php/AAAI/article/download/20141/19900
[C79]: https://github.com/idrl-lab/Full-coverage-camouflage-adversarial-attack?tab=readme-ov-file

[P80]: https://openaccess.thecvf.com/content/CVPR2022/papers/Suryanto_DTA_Physical_Camouflage_Attacks_Using_Differentiable_Transformation_Network_CVPR_2022_paper.pdf
[PP80]: https://islab-ai.github.io/dta-cvpr2022/

[P81]: https://www.ijcai.org/proceedings/2022/0125.pdf

[P82]: https://openaccess.thecvf.com/content/CVPR2021/papers/Wang_Dual_Attention_Suppression_Attack_Generate_Adversarial_Camouflage_in_Physical_World_CVPR_2021_paper.pdf
[C82]: https://github.com/nlsdesafety-team/DualAttentionAttack

[P83]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9493770

[P84]: https://openaccess.thecvf.com/content_CVPR_2020/papers/Huang_Universal_Physical_Camouflage_Attacks_on_Object_Detectors_CVPR_2020_paper.pdf
[C84]: https://github.com/mesunhlf/UPC-tf

[P85]: https://arxiv.org/pdf/2007.16118

[P86]: https://openreview.net/pdf?id=SJgEl3A5tm
[C86]: https://github.com/naufalso/camou-iclr2019-tf

[P87]: https://proceedings.mlr.press/v80/athalye18b/athalye18b.pdf





<!-- 第四个表的 -->
[P88]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10814684

[P89]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11039705

[P90]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11050023
[C90]: https://github.com/p-shekhar/adversarial-patch-transferability

[P91]: https://ojs.aaai.org/index.php/AAAI/article/view/32616

[P92]: https://retis.santannapisa.it/~giorgio/paps/2024/Rossolini-NNLS24.pdf
[C92]: https://github.com/retis-ai/SemSegAdvPatch

[P93]: https://openaccess.thecvf.com/content/WACV2024/papers/Maag_Uncertainty-Weighted_Loss_Functions_for_Improved_Adversarial_Attacks_on_Semantic_Segmentation_WACV_2024_paper.pdf
[C93]: https://github.com/kmaag/Uncertainty-weighted-Loss

[P94]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10677988

[P95]: https://dl.acm.org/doi/pdf/10.1145/3664647.3681475

[P96]: https://www.sciencedirect.com/science/article/abs/pii/S0167865524000102

[P97]: https://arxiv.org/pdf/2306.12941
[C97]: https://github.com/nmndeep/robust-segmentation.

[P98]: https://dl.acm.org/doi/pdf/10.1145/3581783.3611928
[C98]: https://github.com/LiuZhu-CV/PAIF

[P99]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10352148

[P100]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10268597
[C100]: https://github.com/retis-ai/SemSegAdvPatch

[P101]: https://openaccess.thecvf.com/content/CVPR2023/papers/Rony_Proximal_Splitting_Adversarial_Attack_for_Semantic_Segmentation_CVPR_2023_paper.pdf
[C101]: https://github.com/jeromerony/alma_prox_segmentation

[P102]: https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136890306.pdf
[C102]: https://github.com/asif-hanif/segpgd

[P103]: https://openaccess.thecvf.com/content/WACV2022/papers/Nesti_Evaluating_the_Robustness_of_Semantic_Segmentation_for_Autonomous_Driving_Against_WACV_2022_paper.pdf
[C103]: https://github.com/retis-ai/SemSegAdvPatch

[P104]: https://openaccess.thecvf.com/content/WACV2022/papers/Chen_Semantically_Stealthy_Adversarial_Attacks_Against_Segmentation_Models_WACV_2022_paper.pdf

[P105]: https://www.sciencedirect.com/science/article/abs/pii/S0167404822000803

[P106]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9200583

[P107]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8962221

[P108]: https://openaccess.thecvf.com/content_ECCV_2018/papers/CHAOWEI_XIAO_Characterize_Adversarial_Examples_ECCV_2018_paper.pdf

[P109]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8578197
[C109]: https://github.com/anuragarnab/adversarial-attacks

[P110]: https://www.robots.ox.ac.uk/~aarnab/projects/cvpr_2018/On_the_Robustness_of_Semantic_Segmentation_Models_to_Adversarial_Attacks_PAMI_2019.pdf
[C110]: https://github.com/anuragarnab/adversarial-attacks

[P111]: https://openaccess.thecvf.com/content_ICCV_2017/papers/Metzen_Universal_Adversarial_Perturbations_ICCV_2017_paper.pdf




<!-- 第四个表的 -->
[P112]: https://arxiv.org/pdf/2409.18248v2
[C112]: https://github.com/pedram-mohajer/Negative-Shadow-Attack

[P113]: https://dl.acm.org/doi/pdf/10.1145/3503161.3548171
[C113]: https://sites.google.com/view/lane-detection-attack/lda

[P114]: https://www.usenix.org/system/files/sec21-sato.pdf
[C114]: https://github.com/ASGuard-UCI/DRP-attack
[PP114]: https://sites.google.com/view/av-ioat-sec/drp-attack

[P115]: https://www.usenix.org/system/files/sec21-jing.pdf
[C115]: https://github.com/ASGuard-UCI/DRP-attack
[PP115]: https://sites.google.com/view/av-ioat-sec/drp-attack

<!-- 第四个表的 -->
[P116]: https://openaccess.thecvf.com/content/CVPR2024/papers/Zheng_Physical_3D_Adversarial_Attacks_against_Monocular_Depth_Estimation_in_Autonomous_CVPR_2024_paper.pdf
[C116]: https://github.com/Gandolfczjh/3D2Fool

[P117]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10559903
[C117]: https://github.com/Bob-cheng/DepthModelHardening

[P118]: https://openreview.net/pdf?id=uGoi3nY62g
[C118]: https://github.com/Bob-cheng/BadPart

[P119]: https://www.usenix.org/system/files/usenixsecurity24-zheng.pdf
[C119]: https://github.com/pi-Jack/pi-Jack

[P120]: https://proceedings.neurips.cc/paper_files/paper/2024/file/7d26958422928e08465d5dd6cf0cb4cb-Paper-Conference.pdf
[C120]: https://github.com/a-c-a-c/AdvRM

[P121]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10709850

[P122]: https://pureadmin.qub.ac.uk/ws/portalfiles/portal/610549825/IROS24_1859_FI.pdf
[C122]: https://github.com/NeurAI-Lab/mono-pose-attack

[P123]: https://dl.acm.org/doi/pdf/10.1145/3664647.3681474

[P124]: https://openreview.net/pdf?id=LfdEuhjR5GV
[C124]: https://github.com/Bob-cheng/DepthModelHardening

[P125]: https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980504.pdf
[C125]: https://github.com/Bob-cheng/MDE_Attack

[P126]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9982154
[C126]: https://github.com/NeurAI-Lab/mono-pose-attack

[P127]: https://proceedings.neurips.cc/paper_files/paper/2020/file/609e9d4bcc8157c00808993f612f1acd-Paper.pdf

[P128]: https://arxiv.org/pdf/2003.10315


<!-- 第四个表的 -->
[P129]: https://www.ndss-symposium.org/wp-content/uploads/2025-628-paper.pdf
[PP129]: https://sites.google.com/view/av-ioat-sec/real-av-lidar-attack

[P130]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11147568
[C130]: https://github.com/Solacex/CVPR23_ASM

[P131]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11197666

[P132]: https://www.ndss-symposium.org/wp-content/uploads/2024-350-paper.pdf
[PP132]: https://sites.google.com/view/av-ioat-sec/new-gen-lidar-sec

[P133]: autosec2021_23019_paper.pdf
[PP133]: https://sites.google.com/view/lidarspoofingattack

[P134]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10655506
[C134]: https://github.com/TRLou/HiT-ADV

[P135]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10552176

[P136]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10204043
[C136]: https://github.com/WUSTL-CSPL/SlowLiDAR

[P137]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10173629

[P138]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10179458
[PP138]: https://sites.google.com/view/physical-lidar-attack

[P139]: https://www.usenix.org/system/files/sec23summer_349-cao-prepub.pdf
[PP139]: https://cpseclab.github.io/youcantseeme/

[P140]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10030275
[C140]: https://github.com/Explain3D/Exp-One-Point-Atk-PC

[P141]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10204183

[P142]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10202642
[C142]: https://github.com/C0ldstudy/PointSecGuard

[P143]: autosec2022_23026_paper.pdf

[P144]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9710897
[C144]: https://github.com/ai4ce/FLAT

[P145]: https://dl.acm.org/doi/pdf/10.1145/3433210.3453106
[PP145]: https://sites.google.com/view/roadsideadversary

[P146]: https://www.sciencedirect.com/science/article/pii/S0925231221013850?ref=pdf_download&fr=RR-2&rr=9a585a2f6c6f848d

[P147]: https://dl.acm.org/doi/pdf/10.1145/3460120.3485377

[P148]: https://dl.acm.org/doi/pdf/10.1145/3485730.3485935

[P149]: https://www.usenix.org/system/files/sec20-sun.pdf
[PP149]: https://sites.google.com/view/av-ioat-sec/adv-lidar-defense

[P150]: https://arxiv.org/pdf/1908.06062
[C150]: https://github.com/Daniel-Liu-c0deb0t/Adversarial-point-perturbations-on-3D-objects

[P151]: https://arxiv.org/pdf/1912.00461
[C151]: https://github.com/ajhamdi/AdvPC

[P152]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9156447

[P153]: https://dl.acm.org/doi/pdf/10.1145/3319535.3339815
[PP153]: http://tinyurl.com/advlidar

[P154]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953645
[C154]: https://github.com/xiangchong1/3d-adv-pc

[P155]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8953599
[C155]: https://github.com/matthewwicker/IterativeSalienceOcclusion

[P156]: https://arxiv.org/pdf/1907.05418
[PP156]: https://sites.google.com/view/lidar-adv



<!-- 第四个表的 -->
[P157]: https://dl.acm.org/doi/pdf/10.1145/3711875.3729155

[P158]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11097490

[P159]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10554983

[P160]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11205103

[P161]: https://dl.acm.org/doi/pdf/10.1145/3576915.3616661

[P162]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10179371
[C162]: https://github.com/cuge1995/awesome-3D-point-cloud-attacks

[P163]: https://arxiv.org/pdf/2311.16024
[PP163]: https://sites.google.com/view/madradar

[P164]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9760734

[P165]: https://arxiv.org/pdf/2211.01112

[P166]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9417240
[C166]: https://github.com/cuge1995/awesome-3D-point-cloud-attacks

[P167]: https://doi.org/10.1007/s13389-020-00252-5

[P168]: https://dl.acm.org/doi/pdf/10.1145/3474376.3487283

[P169]: https://www.sciencedirect.com/science/article/pii/S0020025520308180

[P170]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9127857

<!-- 第四个表的 -->
[P171]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10587201
[P172]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10959070
[P173]: https://arxiv.org/pdf/2510.10766
[P174]: https://dl.acm.org/doi/pdf/10.1145/3705611
[P175]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10849307

[P176]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10415265
[P177]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10669078
[P178]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835306

[P179]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10109166
[P180]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10208233

[P181]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10200857
[P182]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10264063

[P183]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9373943
[P184]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9625567

[P185]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9226611
[P186]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835306
[P187]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8835306

[P188]: https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-zeng.pdf
[P189]: https://www.usenix.org/system/files/conference/usenixsecurity18/sec18-zeng.pdf



<!-- 第四个表的 -->
[P190]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11148047&utm_source=scopus&getft_integrator=scopus

[P191]: https://dl.acm.org/doi/pdf/10.1145/3636534.3649372

[P192]: https://arxiv.org/pdf/2304.14614
[C192]: https://github.com/Bob-cheng/CL-FusionAttack
[PP192]: https://youtu.be/xhXtzDezeaM

[P193]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10546476
[C193]: https://github.com/UniAdaRepo/UniAda/

[P194]: https://arxiv.org/pdf/2307.16121

[P195]: https://papers.nips.cc/paper_files/paper/2022/file/a48ad12d588c597f4725a8b84af647b5-Paper-Datasets_and_Benchmarks.pdf
[C195]: https://github.com/trust-ai/SafeBench
[PP195]: https://safebench.github.io/

[P196]: https://www.usenix.org/system/files/sec22-hallyburton.pdf

[P197]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9519442
[C197]: https://github.com/ASGuard-UCI/MSF-ADV
[PP197]: https://sites.google.com/view/cav-sec/msf-adv

[P198]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9425012

[P199]: https://openreview.net/pdf?id=m5k1XdK5nI2

[P200]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9636638

[P201]: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9360457

[P202]: https://onlinelibrary.wiley.com/doi/pdf/10.1002/int.22349?getft_integrator=scopus&utm_source=scopus

[P203]: https://www.usenix.org/system/files/sec20-shen.pdf
[PP203]: https://sites.google.com/view/av-ioat-sec/fusionripper


