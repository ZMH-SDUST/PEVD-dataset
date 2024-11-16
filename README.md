

# 物理实验监控数据集-PEVD

<img src="README.assets/pevd.png" alt="pevd" style="zoom: 45%;" />

<div align="center"><img src="https://img.shields.io/badge/Version-1.0--alpha-brightgreen"> 

## 🌐项目简介

本项目构建并开源了业界首个集成多模态和多场景应用的物理实验监控数据集——PEVD。该数据集覆盖多个关键研究领域，包括行为识别、目标检测、实例分割、人机交互检测以及场景图生成，并针对每个领域进行了全面而精细的数据标注工作。

PEVD数据集包含4个精心构建的子集，每个子集都支持一系列特定的研究领域。具体介绍如下：

- PEVD-AR：记录了四项物理实验的620个长视频，涵盖了32类动作的3873个动作片段，平均每个片段时长20秒，视频帧数为30FPS。这一子集为动作识别、动作分割、行为预测等视频行为研究提供了宝贵的资源。

  <img src="README.assets/Fig. 1.jpg" alt="Fig. 1" style="zoom:25%;" />

- PEVD-DET：包含16936张实验图片，涵盖了13.7万个物体实例常规样本、2万个遮挡样本以及1万个交互样本。这一子集支持目标检测、遮挡检测、人机交互检测、场景图生成以及图像修复等计算机视觉任务。

  <img src="README.assets/图4-1.jpg" alt="图4-1" style="zoom: 25%;" />

- PEVD-SG：包含约5千张图片，这些图片进行了细粒度的实例分割标注，涉及操作学生的人体部位以及物理实验器材的像素级类别信息，支持实例分割、语义分割等研究。

  <img src="README.assets/Fig. 3.jpg" alt="图4-1" style="zoom: 5%;" />

- PEVD-MM：目前正在开发中，目标是整合实验过程的文本和图像数据，以支持多模态研究，包括图像描述生成、文本描述生成、跨模态对齐等高级视觉任务。

  <img src="README.assets/Fig. 2.jpg" alt="Fig. 2" style="zoom:15%;" />



## 免责声明

本项目提供的物理实验数据集基于特定实验场景和方法进行采集与标注，但数据集可能包含一定程度的偏差、不完整性或错误信息。因此，该数据集仅供参考和研究使用，不保证其绝对准确性和适用性。使用该数据集进行分析、建模或其他研究活动所产生的结果可能存在误差或偏差，不可直接用于实际应用或决策。本项目不对因使用数据集而产生的任何后果或损失承担责任。使用者在使用数据集时应自行承担风险，并对数据和研究结果进行必要的验证和校验。



## 引用

如果你使用了本项目的数据或者代码，请声明引用

```latex
@article{zou2024weakly,
  title={Weakly-supervised Action Learning in Procedural Task Videos via Process Knowledge Decomposition},
  author={Zou, Minghao and Zeng, Qingtian and Zhang, Xue},
  journal={IEEE Transactions on Circuits and Systems for Video Technology},
  year={2024},
  publisher={IEEE}
}
```

