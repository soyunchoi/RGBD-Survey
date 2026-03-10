# RGB-D Semantic Segmentation Survey Resources

This repository collects **papers and datasets related to RGB-D semantic segmentation**, based on our survey paper:

> **Comprehensive Survey on Advances and Challenges in RGB-D Semantic Segmentation**

The goal of this repository is to organize key resources for researchers working on **RGB-D semantic segmentation and multimodal scene understanding**.

---

# Papers

## CNN-based Methods

| Year | Venue | Method | Code |
|-----|------|------|------|------|
| 2016 | ECCV | [LSTM-CF](https://arxiv.org/abs/1604.01793) | https://github.com/zhezh/faster-rcnn.pytorch |
| 2017 | ICCV | [RDFNet](https://arxiv.org/abs/1711.07027) | https://github.com/shujiepark/RDFNet |
| 2017 | TMM | [Multimodal RNN](https://ieeexplore.ieee.org/document/8022921) | - |
| 2018 | ECCV | [D-CNN](https://arxiv.org/abs/1804.04545) | https://github.com/laughtervv/DepthAwareCNN |
| 2019 | ICIP | [ACNet](https://arxiv.org/abs/1905.10089) | https://github.com/KeyanChen1012/ACNet |
| 2020 | ECCV | [SA-Gate](https://arxiv.org/abs/2007.09913) | https://github.com/charlesCXK/RGBD_Semantic_Segmentation_PyTorch |
| 2020 | NeurIPS | [CEN](https://arxiv.org/abs/2007.05578) | https://github.com/yikaiw/CEN |
| 2021 | TIP | [SGNet](https://arxiv.org/abs/2009.13159) | https://github.com/Yangzhangcst/SGNet |
| 2021 | SPL | [NANet](https://ieeexplore.ieee.org/document/9390373) | - |
| 2021 | SPL | [TCD](https://ieeexplore.ieee.org/document/9392356) | - |
| 2021 | ICRA | [ESANet](https://arxiv.org/abs/2101.06961) | https://github.com/TUI-NICR/ESANet |
| 2021 | ICCV | [ShapeConv](https://arxiv.org/abs/2108.08386) | https://github.com/charlesCXK/ShapeConv |
| 2022 | TMM | [PGDENet](https://ieeexplore.ieee.org/document/9733146) | - |
| 2022 | PR | [CANet](https://arxiv.org/abs/2108.03679) | - |
| 2022 | IJCNN | [EMSANet](https://arxiv.org/abs/2203.04876) | https://github.com/TUI-NICR/EMSANet |
| 2022 | ACCV | [FFCANet](https://link.springer.com/chapter/10.1007/978-3-031-26390-3_74) | - |
| 2022 | SPL | [MGCNet](https://ieeexplore.ieee.org/document/9945322) | - |
| 2025 | PR | [DCANet](https://doi.org/10.1016/j.patcog.2025.111379) | - |

---

## Transformer-based Methods

| Year | Venue | Method | Paper | Code |
|-----|------|------|------|------|
| 2022 | CVPR | [OMNIVORE](https://arxiv.org/abs/2205.08318) | https://github.com/facebookresearch/omnivore |
| 2022 | CVPR | [TokenFusion](https://arxiv.org/abs/2204.08721) | https://github.com/yikaiw/TokenFusion |
| 2022 | ECCV | [MultiMAE](https://arxiv.org/abs/2204.01678) | https://github.com/EPFL-VILAB/MultiMAE |
| 2022 | ECCV | [UCTNet](https://arxiv.org/abs/2207.10736) | - |
| 2023 | T-ITS | [CMX](https://arxiv.org/abs/2203.04838) | https://github.com/huaaaliu/RGBX_Semantic_Segmentation |
| 2023 | CVPR | [CMNeXt](https://arxiv.org/abs/2301.00800) | https://github.com/jamycheung/CMNeXt |
| 2024 | WACV | [LF](https://arxiv.org/abs/2309.14645) | https://github.com/ramdrop/lf |
| 2024 | WACV | [OmniVec](https://arxiv.org/abs/2311.04005) | - |
| 2024 | WACV | [PolyMax](https://arxiv.org/abs/2311.04027) | https://github.com/google-research/polymask |
| 2024 | WACV | [SMMCL](https://arxiv.org/abs/2310.18702) | https://github.com/yuanma/SMMCL |
| 2024 | ICLR | [DFormer](https://arxiv.org/abs/2309.14969) | https://github.com/VCIP-RGBD/DFormer |
| 2024 | CVPRW | [AsymFormer](https://arxiv.org/abs/2403.10635) | https://github.com/duseokkim/AsymFormer |
| 2024 | ICML | [GeminiFusion](https://arxiv.org/abs/2404.09954) | https://github.com/GeminiFusion/GeminiFusion |
| 2024 | MM | [PrimKD](https://arxiv.org/abs/2405.02736) | https://github.com/PRIMKD/PRIMKD |
| 2024 | CVIU | [TransD-Fusion](https://doi.org/10.1016/j.cviu.2024.104174) | - |
| 2025 | CVPR | [DFormerv2](https://arxiv.org/abs/2409.13472) | https://github.com/VCIP-RGBD/DFormer |

---

## Transformer + Prompt Learning

| Year | Venue | Method | Paper | Code |
|-----|------|------|------|------|
| 2023 | IROS | [DPLNet](https://arxiv.org/abs/2308.03235) | https://github.com/DPLNet/DPLNet |
| 2024 | AAAI | [GoPT](https://arxiv.org/abs/2310.17661) | - |

---

# Datasets

## Indoor RGB-D Datasets

| Dataset | Year | Scene | Classes | Images | 
|------|------|------|------|------|------|
| [B3DO](https://rgbd-dataset.cs.washington.edu) | 2011 | Indoor | 50 | 849 |
| [NYUDv1](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v1.html) | 2011 | Indoor | 13 | 2,347 | 
| [RGB-D Object Dataset](https://rgbd-dataset.cs.washington.edu) | 2011 | Indoor | 51 | 250k |
| [NYUDv2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html) | 2012 | Indoor | 40 | 1,449 |
| [SUN3D](http://sun3d.cs.princeton.edu) | 2013 | Indoor | - | 415 |
| [SUN-RGBD](https://rgbd.cs.princeton.edu) | 2015 | Indoor | 37 | 10,335 |
| [2D-3D-S](http://buildingparser.stanford.edu/dataset.html) | 2017 | Indoor | 13 | - |
| [ScanNet](http://www.scan-net.org) | 2017 | Indoor | 20 | 2.5M frames | 
| [Matterport3D](https://niessner.github.io/Matterport) | 2017 | Indoor | 40 | 194k |
| [Taskonomy](https://taskonomy.stanford.edu) | 2018 | Indoor | - | 4M | 
| [ARKitScenes](https://github.com/apple/ARKitScenes) | 2021 | Indoor | - | 5k |
| [LLRGBD](https://github.com/zhangnina/LLRGBD) | 2021 | Indoor | 13 | 58k |

---

## Outdoor / Driving RGB-D Datasets

| Dataset | Year | Scene | Classes | Images |
|------|------|------|------|------|------|
| [Cityscapes](https://www.cityscapes-dataset.com) | 2016 | Driving | 30 | 25k |
| [NuScenes](https://www.nuscenes.org) | 2019 | Driving | 23 | 1.4M |
| [WoodScape](https://woodscape.dataset) | 2019 | Driving | 40 | 100k |
| [Waymo Open Dataset](https://waymo.com/open) | 2020 | Driving | 28 | 100k |
| [KITTI-360](https://www.cvlibs.net/datasets/kitti-360) | 2022 | Driving | 19 | 332k |
| [DELIVER](https://github.com/jamycheung/DELIVER) | 2023 | Driving | 25 | 7k |

---

# Contribution

If you find missing papers or datasets, please open an **issue** or submit a **pull request**.
