# Time-Specialized Event-Image Alignment for Blur-to-Video Decomposition (CVPR2026)
Official code of Time-Specialized Event-Image Alignment for Blur-to-Video Decomposition (TSANet) <a href="https://openaccess.thecvf.com/content/CVPR2026/papers/Sun_Time-Specialized_Event-Image_Alignment_for_Blur-to-Video_Decomposition_CVPR_2026_paper.pdf"><img src="https://img.shields.io/badge/Paper-CVF-blue" alt="Paper"></a>

---

## 📄 Paper
> **TSANet** is an event-guided framework that decomposes a **single motion-blurred image** into a **high-frame-rate sharp video**. Unlike prior methods that suffer from temporal misalignment between events and images, TSANet **explicitly time-specializes both modalities**: our **Relative Time-Encoded Attention** steers event features toward motion cues at any target timestamp, while **Timesurface Dynamic Warping** spatially warps image features to match that same instant. This enables precise frame reconstruction at arbitrary query times. We also release a new real-world dataset with color events and high-quality videos. TSANet achieves state-of-the-art results on multiple benchmarks with both synthetic and real events.
> ![image](https://github.com/ZhijingS/TSANet/blob/main/network.png)
