# RGB-D Semantic Segmentation Survey Resources

This repository collects **papers and datasets related to RGB-D semantic segmentation**, based on our survey paper:

> **Comprehensive Survey on Advances and Challenges in RGB-D Semantic Segmentation**

The goal of this repository is to organize key resources for researchers working on **multimodal semantic segmentation using RGB and depth information**.

---

# Papers

## CNN-based Methods

| Year | Venue | Method | Training Dataset | Code |
|-----|------|------|------|------|
| 2016 | ECCV | LSTM-CF | NYUDv2, SUN-RGBD | LSTM-CF |
| 2017 | ICCV | RDFNet | NYUDv2, SUN-RGBD | RDFNet |
| 2017 | TMM | Multimodal RNN | NYUDv1, NYUDv2 | - |
| 2018 | ECCV | D-CNN | NYUDv2, SUN-RGBD, 2D-3D-S | D-CNN |
| 2019 | ICIP | ACNet | NYUDv2, SUN-RGBD | ACNet |
| 2020 | ECCV | SA-Gate | NYUDv2, Cityscapes | SA-Gate |
| 2020 | NeurIPS | CEN | NYUDv2, SUN-RGBD | CEN |
| 2021 | TIP | SGNet | NYUDv2, SUN-RGBD | SGNet |
| 2021 | SPL | NANet | NYUDv2, SUN-RGBD | - |
| 2021 | SPL | TCD | NYUDv2, SUN-RGBD | - |
| 2021 | ICRA | ESANet | NYUDv2, SUN-RGBD, Cityscapes | ESANet |
| 2021 | ICCV | ShapeConv | NYUDv2, SUN-RGBD, 2D-3D-S | ShapeConv |
| 2022 | TMM | PGDENet | NYUDv2, SUN-RGBD | - |
| 2022 | PR | CANet | NYUDv2, SUN-RGBD | - |
| 2022 | IJCNN | EMSANet | NYUDv2, SUN-RGBD | EMSANet |
| 2022 | ACCV | FFCANet | NYUDv2 | - |
| 2022 | SPL | MGCNet | NYUDv2, SUN-RGBD | - |
| 2025 | PR | DCANet | NYUDv2, SUN-RGBD | - |

---

## Transformer-based Methods

| Year | Venue | Method | Training Dataset | Code |
|-----|------|------|------|------|
| 2022 | CVPR | OMNIVORE | NYUDv2 | OMNIVORE |
| 2022 | CVPR | TokenFusion | NYUDv2, SUN-RGBD | TokenFusion |
| 2022 | ECCV | MultiMAE | NYUDv2, Hypersim | MultiMAE |
| 2022 | ECCV | UCTNet | NYUDv2, SUN-RGBD | - |
| 2023 | T-ITS | CMX | NYUDv2, SUN-RGBD, 2D-3D-S, ScanNetV2, Cityscapes | CMX |
| 2023 | CVPR | CMNeXt | NYUDv2, KITTI-360, DELIVER | CMNeXt |
| 2024 | WACV | LF | 2D-3D-S, SUN-RGBD | LF |
| 2024 | WACV | OmniVec | NYUDv2 | - |
| 2024 | WACV | PolyMax | NYUDv2, Taskonomy | PolyMax |
| 2024 | WACV | SMMCL | LLRGBD | SMMCL |
| 2024 | ICLR | DFormer | NYUDv2, SUN-RGBD | DFormer |
| 2024 | CVPRW | AsymFormer | NYUDv2, SUN-RGBD | AsymFormer |
| 2024 | ICML | GeminiFusion | NYUDv2, SUN-RGBD, DELIVER | GeminiFusion |
| 2024 | MM | PrimKD | NYUDv2, SUN-RGBD | PrimKD |
| 2024 | CVIU | TransD-Fusion | NYUDv2, SUN-RGBD | - |
| 2025 | CVPR | DFormerv2 | NYUDv2, SUN-RGBD | DFormerv2 |

---

## Transformer + Prompt Learning

| Year | Venue | Method | Training Dataset | Code |
|-----|------|------|------|------|
| 2023 | IROS | DPLNet | NYUDv2, SUN-RGBD | DPLNet |
| 2024 | AAAI | GoPT | NYUDv2, SUN-RGBD | - |

---

# Datasets

## Indoor RGB-D Datasets

| Dataset | Year | Scene Type | Classes | Labeled Images | Resolution |
|------|------|------|------|------|------|
| B3DO | 2011 | Indoor | 50 | 849 | 640x480 |
| NYUDv1 | 2011 | Indoor | 13 | 2347 | 640x480 |
| RGB-D Object Dataset | 2011 | Indoor | 51 | 250000 | 640x480 |
| NYUDv2 | 2012 | Indoor | 40 | 1449 | 640x480 |
| SUN3D | 2013 | Indoor | - | 415 | 640x480 |
| SUN-RGBD | 2015 | Indoor | 37 | 10335 | variable |
| 2D-3D-S | 2017 | Indoor | 13 | 11 | 1080x1080 |
| ScanNet | 2017 | Indoor | - | 2500000 frames | 640x480 |
| Matterport3D | 2017 | Indoor | 40 | 194400 | 1280x1024 |
| Taskonomy | 2018 | Indoor | - | 4000000 | - |
| ARKitScenes | 2021 | Indoor | - | 5407 | 640x480 |
| LLRGBD | 2021 | Indoor | 13 | 58515 | 640x480 |

---

## Driving / Outdoor RGB-D Datasets

| Dataset | Year | Scene Type | Classes | Images | Resolution |
|------|------|------|------|------|------|
| Cityscapes | 2016 | Driving | 30 | 25000 | 2048x1024 |
| NuScenes | 2019 | Driving | 23 | 1400000 | 1600x900 |
| WoodScape | 2019 | Driving | 40 | 100000 | 1280x966 |
| Waymo Open Dataset | 2020 | Driving | 28 | 100000 | variable |
| KITTI-360 | 2022 | Driving | 19 | 332000 | 1408x376 |
| DELIVER | 2023 | Driving | 25 | 7885 | 1042x1042 |

---

# Contribution

If you find missing papers or datasets, feel free to open an **issue** or **pull request**.

---
