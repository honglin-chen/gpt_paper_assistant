# Personalized Daily Arxiv Papers 01/22/2024
Total relevant papers: 9

Paper selection prompt and criteria at the bottom

Table of contents with paper titles:

0. [Dense 3D Reconstruction Through Lidar: A Comparative Study on Ex-vivo Porcine Tissue](#link0)
**Authors:** Guido Caccianiga, Julian Nubert, Marco Hutter, Katherine J. Kuchenbecker

1. [SCENES: Subpixel Correspondence Estimation With Epipolar Supervision](#link1)
**Authors:** Dominik A. Kloepfer, João F. Henriques, Dylan Campbell

2. [G.O.G: A Versatile Gripper-On-Gripper Design for Bimanual Cloth Manipulation with a Single Robotic Arm](#link2)
**Authors:** Dongmyoung Lee, Wei Chen, Xiaoshuai Chen, Nicolas Rojas

3. [Aerial Field Robotics](#link3)
**Authors:** Mihir Kulkarni, Brady Moon, Kostas Alexis, Sebastian Scherer

4. [Safe Offline Reinforcement Learning with Feasibility-Guided Diffusion Model](#link4)
**Authors:** Yinan Zheng, Jianxiong Li, Dongjie Yu, Yujie Yang, Shengbo Eben Li, Xianyuan Zhan, Jingjing Liu

5. [A Wind-Aware Path Planning Method for UAV-Asisted Bridge Inspection](#link5)
**Authors:** Jian Xu, Hua Dai

6. [Understanding Video Transformers via Universal Concept Discovery](#link6)
**Authors:** Matthew Kowal, Achal Dave, Rares Ambrus, Adrien Gaidon, Konstantinos G. Derpanis, Pavel Tokmakov

7. [Learning to Visually Connect Actions and their Effects](#link7)
**Authors:** Eric Peh, Paritosh Parmar, Basura Fernando

8. [Agricultural Object Detection with You Look Only Once (YOLO) Algorithm: A Bibliometric and Systematic Literature Review](#link8)
**Authors:** Chetan M Badgujar, Alwin Poulose, Hao Gan

---
## 0. [Dense 3D Reconstruction Through Lidar: A Comparative Study on Ex-vivo Porcine Tissue](https://arxiv.org/abs/2401.10709) <a id="link0"></a>
**ArXiv ID:** 2401.10709
**Authors:** Guido Caccianiga, Julian Nubert, Marco Hutter, Katherine J. Kuchenbecker

**Abstract:** New sensing technologies and more advanced processing algorithms are transforming computer-integrated surgery. While researchers are actively investigating depth sensing and 3D reconstruction for vision-based surgical assistance, it remains difficult to achieve real-time, accurate, and robust 3D representations of the abdominal cavity for minimally invasive surgery. Thus, this work uses quantitative testing on fresh ex-vivo porcine tissue to thoroughly characterize the quality with which a 3D laser-based time-of-flight sensor (lidar) can perform anatomical surface reconstruction. Ground-truth surface shapes are captured with a commercial laser scanner, and the resulting signed error fields are analyzed using rigorous statistical tools. When compared to modern learning-based stereo matching from endoscopic images, time-of-flight sensing demonstrates higher precision, lower processing delay, higher frame rate, and superior robustness against sensor distance and poor illumination. Furthermore, we report on the potential negative effect of near-infrared light penetration on the accuracy of lidar measurements across different tissue samples, identifying a significant measured depth offset for muscle in contrast to fat and liver. Our findings highlight the potential of lidar for intraoperative 3D perception and point toward new methods that combine complementary time-of-flight and spectral imaging.

**Comment:** This paper presents a comparative study on 3D reconstruction using Lidar, which is relevant to criterion 5 (new approaches in inferring 3D scenes from real-world image or video data).
**Relevance:** 7.0
**Novelty:** 6.0

---

## 1. [SCENES: Subpixel Correspondence Estimation With Epipolar Supervision](https://arxiv.org/abs/2401.10886) <a id="link1"></a>
**ArXiv ID:** 2401.10886
**Authors:** Dominik A. Kloepfer, João F. Henriques, Dylan Campbell

**Abstract:** Extracting point correspondences from two or more views of a scene is a fundamental computer vision problem with particular importance for relative camera pose estimation and structure-from-motion. Existing local feature matching approaches, trained with correspondence supervision on large-scale datasets, obtain highly-accurate matches on the test sets. However, they do not generalise well to new datasets with different characteristics to those they were trained on, unlike classic feature extractors. Instead, they require finetuning, which assumes that ground-truth correspondences or ground-truth camera poses and 3D structure are available. We relax this assumption by removing the requirement of 3D structure, e.g., depth maps or point clouds, and only require camera pose information, which can be obtained from odometry. We do so by replacing correspondence losses with epipolar losses, which encourage putative matches to lie on the associated epipolar line. While weaker than correspondence supervision, we observe that this cue is sufficient for finetuning existing models on new data. We then further relax the assumption of known camera poses by using pose estimates in a novel bootstrapping approach. We evaluate on highly challenging datasets, including an indoor drone dataset and an outdoor smartphone camera dataset, and obtain state-of-the-art results without strong supervision.

**Comment:** This paper matches criteria 5. It presents a new approach for extracting point correspondences from multiple views of a scene, which is a method for inferring 3D scenes from real-world image data. However, it does not involve video data.
**Relevance:** 5.0
**Novelty:** 7.0

---

## 2. [G.O.G: A Versatile Gripper-On-Gripper Design for Bimanual Cloth Manipulation with a Single Robotic Arm](https://arxiv.org/abs/2401.10702) <a id="link2"></a>
**ArXiv ID:** 2401.10702
**Authors:** Dongmyoung Lee, Wei Chen, Xiaoshuai Chen, Nicolas Rojas

**Abstract:** The manipulation of garments poses research challenges due to their deformable nature and the extensive variability in shapes and sizes. Despite numerous attempts by researchers to address these via approaches involving robot perception and control, there has been a relatively limited interest in resolving it through the co-development of robot hardware. Consequently, the majority of studies employ off-the-shelf grippers in conjunction with dual robot arms to enable bimanual manipulation and high dexterity. However, this dual-arm system increases the overall cost of the robotic system as well as its control complexity in order to tackle robot collisions and other robot coordination issues. As an alternative approach, we propose to enable bimanual cloth manipulation using a single robot arm via novel end effector design -- sharing dexterity skills between manipulator and gripper rather than relying entirely on robot arm coordination. To this end, we introduce a new gripper, called G.O.G., based on a gripper-on-gripper structure where the first gripper independently regulates the span, up to 500mm, between its fingers which are in turn also grippers. These finger grippers consist of a variable friction module that enables two grasping modes: firm and sliding grasps. Household item and cloth object benchmarks are employed to evaluate the performance of the proposed design, encompassing both experiments on the gripper design itself and on cloth manipulation. Experimental results demonstrate the potential of the introduced ideas to undertake a range of bimanual cloth manipulation tasks with a single robot arm. Supplementary material is available at https://sites.google.com/view/gripperongripper.

**Comment:** This paper matches criteria 7 and 8. It presents a novel gripper design for bimanual cloth manipulation using a single robotic arm, which is an application of robotics. However, it does not involve video generation, world modelling, or self-supervised learning.
**Relevance:** 5.0
**Novelty:** 7.0

---

## 3. [Aerial Field Robotics](https://arxiv.org/abs/2401.10837) <a id="link3"></a>
**ArXiv ID:** 2401.10837
**Authors:** Mihir Kulkarni, Brady Moon, Kostas Alexis, Sebastian Scherer

**Abstract:** Aerial field robotics research represents the domain of study that aims to equip unmanned aerial vehicles - and as it pertains to this chapter, specifically Micro Aerial Vehicles (MAVs)- with the ability to operate in real-life environments that present challenges to safe navigation. We present the key elements of autonomy for MAVs that are resilient to collisions and sensing degradation, while operating under constrained computational resources. We overview aspects of the state of the art, outline bottlenecks to resilient navigation autonomy, and overview the field-readiness of MAVs. We conclude with notable contributions and discuss considerations for future research that are essential for resilience in aerial robotics.

**Comment:** This paper is related to criterion 8 (Cool new results on robotics). It discusses the development of autonomous Micro Aerial Vehicles (MAVs) for safe navigation in challenging real-life environments.
**Relevance:** 5.0
**Novelty:** 6.0

---

## 4. [Safe Offline Reinforcement Learning with Feasibility-Guided Diffusion Model](https://arxiv.org/abs/2401.10700) <a id="link4"></a>
**ArXiv ID:** 2401.10700
**Authors:** Yinan Zheng, Jianxiong Li, Dongjie Yu, Yujie Yang, Shengbo Eben Li, Xianyuan Zhan, Jingjing Liu

**Abstract:** Safe offline RL is a promising way to bypass risky online interactions towards safe policy learning. Most existing methods only enforce soft constraints, i.e., constraining safety violations in expectation below thresholds predetermined. This can lead to potentially unsafe outcomes, thus unacceptable in safety-critical scenarios. An alternative is to enforce the hard constraint of zero violation. However, this can be challenging in offline setting, as it needs to strike the right balance among three highly intricate and correlated aspects: safety constraint satisfaction, reward maximization, and behavior regularization imposed by offline datasets. Interestingly, we discover that via reachability analysis of safe-control theory, the hard safety constraint can be equivalently translated to identifying the largest feasible region given the offline dataset. This seamlessly converts the original trilogy problem to a feasibility-dependent objective, i.e., maximizing reward value within the feasible region while minimizing safety risks in the infeasible region. Inspired by these, we propose FISOR (FeasIbility-guided Safe Offline RL), which allows safety constraint adherence, reward maximization, and offline policy learning to be realized via three decoupled processes, while offering strong safety performance and stability. In FISOR, the optimal policy for the translated optimization problem can be derived in a special form of weighted behavior cloning. Thus, we propose a novel energy-guided diffusion model that does not require training a complicated time-dependent classifier to extract the policy, greatly simplifying the training. We compare FISOR against baselines on DSRL benchmark for safe offline RL. Evaluation results show that FISOR is the only method that can guarantee safety satisfaction in all tasks, while achieving top returns in most tasks.

**Comment:** This paper presents a method for safe offline reinforcement learning, which could be relevant to criterion 3 (general self-supervised representation learning from video or images data) if the method is applied to video or image data. However, the abstract does not specify the type of data used.
**Relevance:** 4.0
**Novelty:** 7.0

---

## 5. [A Wind-Aware Path Planning Method for UAV-Asisted Bridge Inspection](https://arxiv.org/abs/2401.10519) <a id="link5"></a>
**ArXiv ID:** 2401.10519
**Authors:** Jian Xu, Hua Dai

**Abstract:** In response to the gap in considering wind conditions in the bridge inspection using unmanned aerial vehicle (UAV) , this paper proposes a path planning method for UAVs that takes into account the influence of wind, based on the simulated annealing algorithm. The algorithm considers the wind factors, including the influence of different wind speeds and directions at the same time on the path planning of the UAV. Firstly, An environment model is constructed specifically for UAV bridge inspection, taking into account the various objective functions and constraint conditions of UAVs. A more sophisticated and precise mathematical model is then developed based on this environmental model to enable efficient and effective UAV path planning. Secondly, the bridge separation planning model is applied in a novel way, and a series of parameters are simulated, including the adjustment of the initial temperature value. The experimental results demonstrate that, compared with traditional local search algorithms, the proposed method achieves a cost reduction of 30.05\% and significantly improves effectiveness. Compared to path planning methods that do not consider wind factors, the proposed approach yields more realistic and practical results for UAV applications, as demonstrated by its improved effectiveness in simulations. These findings highlight the value of our method in facilitating more accurate and efficient UAV path planning in wind-prone environments.

**Comment:** This paper proposes a path planning method for UAVs that takes into account the influence of wind, which is a part of world modelling (criterion 6). However, it does not focus on video generation or self-supervised learning.
**Relevance:** 5.0
**Novelty:** 6.0

---

## 6. [Understanding Video Transformers via Universal Concept Discovery](https://arxiv.org/abs/2401.10831) <a id="link6"></a>
**ArXiv ID:** 2401.10831
**Authors:** Matthew Kowal, Achal Dave, Rares Ambrus, Adrien Gaidon, Konstantinos G. Derpanis, Pavel Tokmakov

**Abstract:** This paper studies the problem of concept-based interpretability of transformer representations for videos. Concretely, we seek to explain the decision-making process of video transformers based on high-level, spatiotemporal concepts that are automatically discovered. Prior research on concept-based interpretability has concentrated solely on image-level tasks. Comparatively, video models deal with the added temporal dimension, increasing complexity and posing challenges in identifying dynamic concepts over time. In this work, we systematically address these challenges by introducing the first Video Transformer Concept Discovery (VTCD) algorithm. To this end, we propose an efficient approach for unsupervised identification of units of video transformer representations - concepts, and ranking their importance to the output of a model. The resulting concepts are highly interpretable, revealing spatio-temporal reasoning mechanisms and object-centric representations in unstructured video models. Performing this analysis jointly over a diverse set of supervised and self-supervised representations, we discover that some of these mechanism are universal in video transformers. Finally, we demonstrate that VTCDcan be used to improve model performance for fine-grained tasks.

**Comment:** This paper matches criteria 3. It presents a new algorithm for concept-based interpretability of transformer representations for videos, which is a method for self-supervised representation learning from video data.
**Relevance:** 5.0
**Novelty:** 6.0

---

## 7. [Learning to Visually Connect Actions and their Effects](https://arxiv.org/abs/2401.10805) <a id="link7"></a>
**ArXiv ID:** 2401.10805
**Authors:** Eric Peh, Paritosh Parmar, Basura Fernando

**Abstract:** In this work, we introduce the novel concept of visually Connecting Actions and Their Effects (CATE) in video understanding. CATE can have applications in areas like task planning and learning from demonstration. We propose different CATE-based task formulations, such as action selection and action specification, where video understanding models connect actions and effects at semantic and fine-grained levels. We observe that different formulations produce representations capturing intuitive action properties. We also design various baseline models for action selection and action specification. Despite the intuitive nature of the task, we observe that models struggle, and humans outperform them by a large margin. The study aims to establish a foundation for future efforts, showcasing the flexibility and versatility of connecting actions and effects in video understanding, with the hope of inspiring advanced formulations and models.

**Comment:** This paper does not match any of the criteria closely. It introduces the concept of visually connecting actions and their effects in video understanding, which is not directly related to video generation, vision foundation models, self-supervised learning, text to video generation, 3D scene inference, world modelling, or robotics.
**Relevance:** 3.0
**Novelty:** 6.0

---

## 8. [Agricultural Object Detection with You Look Only Once (YOLO) Algorithm: A Bibliometric and Systematic Literature Review](https://arxiv.org/abs/2401.10379) <a id="link8"></a>
**ArXiv ID:** 2401.10379
**Authors:** Chetan M Badgujar, Alwin Poulose, Hao Gan

**Abstract:** Vision is a major component in several digital technologies and tools used in agriculture. The object detector, You Look Only Once (YOLO), has gained popularity in agriculture in a relatively short span due to its state-of-the-art performance. YOLO offers real-time detection with good accuracy and is implemented in various agricultural tasks, including monitoring, surveillance, sensing, automation, and robotics. The research and application of YOLO in agriculture are accelerating rapidly but are fragmented and multidisciplinary. Moreover, the performance characteristics (i.e., accuracy, speed, computation) of the object detector influence the rate of technology implementation and adoption in agriculture. Thus, the study aims to collect extensive literature to document and critically evaluate the advances and application of YOLO for agricultural object recognition. First, we conducted a bibliometric review of 257 articles to understand the scholarly landscape of YOLO in agricultural domain. Secondly, we conducted a systematic review of 30 articles to identify current knowledge, gaps, and modifications in YOLO for specific agricultural tasks. The study critically assesses and summarizes the information on YOLO's end-to-end learning approach, including data acquisition, processing, network modification, integration, and deployment. We also discussed task-specific YOLO algorithm modification and integration to meet the agricultural object or environment-specific challenges. In general, YOLO-integrated digital tools and technologies show the potential for real-time, automated monitoring, surveillance, and object handling to reduce labor, production cost, and environmental impact while maximizing resource efficiency. The study provides detailed documentation and significantly advances the existing knowledge on applying YOLO in agriculture, which can greatly benefit the scientific community.

**Comment:** This paper is about the application of the YOLO algorithm in agriculture for object detection and recognition. It does not match any of the criteria closely but it does mention the application of the algorithm in robotics in the agricultural field.
**Relevance:** 3.0
**Novelty:** 4.0

---


---

## Paper selection prompt
1. New methodological improvements to video generation approaches, especially methods that generate more object dynamics
2. New approaches for training pure vision foundation model
3. General self-supervised representation learning from video or images data
4. New approaches in text to video generation
5. New approaches in inferring 3D scenes from real-world image or video data
6. World modelling
7. Application of video generation, World modelling, or self-supervised learning in robotics
8. Cool new results on robotics
 
