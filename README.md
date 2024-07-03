

## Introduction
This repo is the official implementation of [MICCAI-2024](https://conferences.miccai.org/2024/en/default.asp) paper "QueryNet: A Unified Framework for Accurate Polyp Segmentation and Detection"

<img src="/Figures/query_net.png">

**Abstract.** Recently, deep learning-based methods have demonstrated effectiveness in the diagnosing of polyps, which holds clinical significance in the prevention of colorectal cancer. These methods can be broadly categorized into two tasks: Polyp Segmentation (PS) and Polyp Detection (PD). The advantage of PS lies in precise localization, but it is constrained by the contrast of the polyp area. On the other hand, PD provides the advantages of global perspective but is susceptible to issues such as false positives or missed detections. Despite substantial progress in both tasks, there has been limited exploration of integrating these two tasks. To address this problem, we introduce QueryNet, a unified framework for accurate polyp segmentation and detection. Specially, our QueryNet is  constructed on top of Mask2Former, a query-based segmentation model. It conceptualizes object queries as cluster centers and constructs a detection branch to handle both tasks. Extensive quantitative and qualitative experiments on five public benchmarks verify that this unified framework effectively mitigates the task-specific limitations, thereby enhancing the overall performance. Furthermore, QueryNet achieves comparable performance against state-of-the-art PS and PD methods.

## Visualization
<img src="/Figures/comparison.png">

## 📯 news
-[24 - 6] Our QueryNet was accepted by [MICCAI2024](https://conferences.miccai.org/2024/en/default.asp)

## To-Do list 🔥:
the paper codes and more research results will be released.
- [ ] Release the codes & usage
- [ ] Datasets description and link
- [ ] Results on SUN-SEG dataset
......

## Thanks for the codes provided by:
- PraNet: https://github.com/DengPingFan/PraNet
- UACABet: https://github.com/plemeri/UACANet
- SSFormer: https://github.com/Qiming-Huang/ssformer
- Polyp-PVT: https://github.com/DengPingFan/Polyp-PVT
- CASCADE: https://github.com/SLDGroup/CASCADE
- MMDetection: https://github.com/open-mmlab/mmdetection
