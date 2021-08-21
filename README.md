# AU-Calibrated Facial Expression Recognition (AUC-FER)

This repo contains the code accompanying the paper, [Understanding and Mitigating Annotation Bias in Facial Expression Recognition (Chen and Joo, ICCV 2021)](https://arxiv.org/abs/2108.08504). 

## Code Navigation
- `annotation_bias_evaluation` folder contains the code that calculates the annotation bias across gender, age, and race and plots the figures in the paper and the appendix.
-  `auc_fer` folder contains the code for AUC-FER and various baseline methods shown in Table 4 of the paper.

## Dataset Used
- FairFace: https://github.com/dchen236/FairFace
- Expression in-the-Wild (ExpW): https://mmlab.ie.cuhk.edu.hk/projects/socialrelation/
- EmotioNet: https://cbcsl.ece.ohio-state.edu/enc-2020/index.html
- Real-world Affective Faces Database (RAF-DB): http://www.whdeng.cn/raf/model1.html
- AffectNet: http://mohammadmahoor.com/affectnet/
- Karolinska Directed Emotional Faces (KDEF): https://www.kdef.se/
- Chicago Face Database (CFD): https://www.chicagofaces.org/

## Acknowledgements
OpenFace: <https://github.com/TadasBaltrusaitis/OpenFace>

The code for AUC-FER and its baseline methods is adapted from the CVPR paper:
[Towards Fairness in Visual Recognition: Effective Strategies for Bias Mitigation](https://arxiv.org/abs/1911.11834v2), [Code](https://github.com/princetonvisualai/DomainBiasMitigation)
