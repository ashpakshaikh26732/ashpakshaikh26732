[![Stars](https://img.shields.io/github/stars/ashpakshaikh26732/Medical-Segmentation-Decathlon)](https://github.com/ashpakshaikh26732/Medical-Segmentation-Decathlon/stargazers)
[![Forks](https://img.shields.io/github/forks/ashpakshaikh26732/Medical-Segmentation-Decathlon)](https://github.com/ashpakshaikh26732/Medical-Segmentation-Decathlon/network/members)
[![PyTorch](https://img.shields.io/badge/PyTorch-DINOv2%2FViT-orange)](https://pytorch.org)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.15-orange)](https://www.tensorflow.org)

# 👋 Hi, I'm Ashpak Shaikh

**Dense Correspondence & Robotics Perception | Optimizing Foundation Models @ Perceptyne**

Building research-level computer vision — dense pixel correspondence, representation learning, and 6D pose estimation for robotic manipulation.

🔭 **Current Focus:** Systematic DINOv2/DINOv3 ablations at Perceptyne — layer probing, RoPE variants, and DoRA fine-tuning for dense correspondence in robotic manipulation.

⚡ **Headline Result:** Reduced UFM (Unified Flow Matching) dense correspondence EPE by **58%** (3.38 → 1.43) via 20+ systematic ablations — new **SOTA 1.40 EPE** through DoRA + STRING RoPE fine-tuning, at 90%+ parameter reduction vs. full fine-tuning.

🌱 **Open Source:** Keras-Hub contributor (Google) — merged `RandomElasticDeformation3D`, a TPU-compatible 3D medical imaging augmentation layer ([PR #2419](https://github.com/keras-team/keras-hub/pull/2419)).

---

## 🚀 Featured Work

| Project | Description | Key Results |
|---|---|---|
| **UFM Dense Correspondence** @ Perceptyne *(internship — proprietary)* | Transformer-based dense pixel correspondence for robotic manipulation. Discovered the L12 DINOv2 transition layer via linear probing; benchmarked STRING/Spiral/Phase-Learned RoPE variants; DoRA fine-tuning. | 58% EPE reduction • SOTA 1.40 EPE |
| **[Medical-Segmentation-Decathlon](https://github.com/ashpakshaikh26732/Medical-Segmentation-Decathlon)** | TPU-native SOTA framework for MSD (all 10 tasks). UNet++/TransUNet/SwinTransUNet + 3-stage foreground/rare-class/OHEM curriculum. | 94.76% Dice (Heart) • 90.91% Dice (Hippocampus) |
| **6D-Dextrous-Pose-Estimation** *(pushing soon)* | DINOv2 + SAM2 (segmentation) → FFB6D + RandLA-Net (pose) on YCB-Video. Bidirectional RGB-D fusion, SVD solver head, LoRA/DoRA adapters on attention layers. | Hardware-agnostic Hydra config • TensorRT/Triton deployment |

---

## 🛠 Tech Stack

| Dense CV & PEFT | MLOps & Infra | Medical Imaging |
|---|---|---|
| DINOv2/ViT, RoPE variants (STRING/Spiral/Phase-Learned), LoRA/DoRA, Optical Flow, Flash-Attention | PyTorch Lightning, Hydra, MLflow, WandB, Docker, ONNX/TensorRT/Triton, AWS (EC2/S3/EBS) | TensorFlow, Keras, NiBabel, DICOM, Orthanc PACS |

---

## 📫 Connect

- LinkedIn: [ashpak-shaikh-88a7372b0](https://www.linkedin.com/in/ashpak-shaikh-88a7372b0)
- Email: ashpakshaikh26732@gmail.com

Open to research-level CV / robotics perception roles across Pune, Hyderabad, and Bangalore — available immediately.
