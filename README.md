# Time-Specialized Event-Image Alignment for Blur-to-Video Decomposition (CVPR2026)
Official code of Time-Specialized Event-Image Alignment for Blur-to-Video Decomposition (TSANet) <a href="https://openaccess.thecvf.com/content/CVPR2026/papers/Sun_Time-Specialized_Event-Image_Alignment_for_Blur-to-Video_Decomposition_CVPR_2026_paper.pdf"><img src="https://img.shields.io/badge/Paper-CVF-blue" alt="Paper"></a>

---

## 📰 News

- **[2024-XX-XX]** Initial code and pretrained models released.
- **[2024-XX-XX]** 【Update description, e.g., Added support for XXX dataset / Fixed bug in YYY.】

---

## 📄 Paper
> **TSANet** is an event-guided framework that decomposes a **single motion-blurred image** into a **high-frame-rate sharp video**. Unlike prior methods that suffer from temporal misalignment between events and images, TSANet **explicitly time-specializes both modalities**: our **Relative Time-Encoded Attention** steers event features toward motion cues at any target timestamp, while **Timesurface Dynamic Warping** spatially warps image features to match that same instant. This enables precise frame reconstruction at arbitrary query times. We also release a new real-world dataset with color events and high-quality videos. TSANet achieves state-of-the-art results on multiple benchmarks with both synthetic and real events.

## 🚀 Quick Start

### Requirements

- Python &gt;= 【e.g., 3.8】
- PyTorch &gt;= 【e.g., 1.12】
- torchvision &gt;= 【e.g., 0.13】
- CUDA &gt;= 【e.g., 11.3】
- Other dependencies: see `requirements.txt`

```bash
# Clone the repository
git clone https://github.com/【your_username】/【repo_name】.git
cd 【repo_name】

# Create a virtual environment (recommended)
conda create -n 【env_name】 python=3.9
conda activate 【env_name】

# Install dependencies
pip install -r requirements.txt
