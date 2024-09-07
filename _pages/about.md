---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently enrolled in a Master's program for Electrical Science and Technology at the School of Electronic Information and Electrical Engineering (电子信息与电气工程学院), Shanghai Jiao Tong University, Shanghai, China, and under the supervision of Professor [Guanghui He](https://dmne.sjtu.edu.cn/dmne/faculty/heguanghui/). 

My current research interests are at the intersection of autonomous driving system, digital circuits and computer architectures. The current focus is efficient ASIC design for AI applications like object detection, point cloud processing and NeRF (<a href='https://scholar.google.com/citations?user=lsL91dsAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- 2024.02:  🎉🎉 One co-authored paper about Deformable Attention Acceleration is accepted by DAC’24 !!! Congratulations to Yansong !!!! See you in San Francisco !!!
- *2024.02*: &nbsp;🎉🎉 Our paper about *data compression engine for NN processors* is accepted by IEEE TCAS-II.
- *2024.01*: &nbsp;🎉🎉 One co-authored paper about *FLN acceleration for large-scale point clouds* is accepted by IEEE TVLSI. Congratulations to Dongxu and Zhenyu !!! 
- *2024.01*: &nbsp;🎉🎉 One co-authored paper about *high-resolution image compressor and decompressor* is accepted by ISCAS 2024. Congratulations to Siqi !!! 
- *2023.07*: &nbsp;🎉🎉 One co-authored paper about *3D sparse convolution accelerator* is accepted by ICCAD 2023. Congratulations to Dongxu !!! 
- *2023.02*: &nbsp;🎉🎉 One co-authored paper about *FLN acceleration for large-scale point clouds* is accepted by DAC 2023. Congratulations to Dongxu !!! 
- *2023.02*: &nbsp;🎉🎉 Our paper about *NMS accelerator* is accepted by ISCAS 2023. See you in Monterey, US ! 

# 📝 Publications 

## Selected Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TCAS-II 2024</div><img src='images/TCASII2024.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078)

**Yuzhou Chen**, Jinming Zhang, Dongxu Lyu, Zhenyu Li, Guanghui He

- a broad-spectrum and high-throughput compression engine for feature maps (fmap) with software-hardware co-design.
- It also demonstrates substantial throughput boost (4$\sim$128x) and compression ratio improvement over the state-of-the-art fmap compression engine while providing superior support of both CNN and Transformer fmaps.
- *IEEE TRANSACTIONS ON CIRCUITS AND SYSTEMS II: EXPRESS BRIEFS (TCAS-II)*
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ISCAS 2023</div><img src='images/ISCAS2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression](https://ieeexplore.ieee.org/abstract/document/10181731)

**Yuzhou Chen**, Jinming Zhang, Dongxu Lyu, Xi Yu, Guanghui He
- A novel non-maximum suppression (NMS) accelerator that enables ultra-low-latency NMS processing. 
- Compared with the state-of-the-art accelerators, our FPGA implementation achieves 2.51x speedup and our ASIC implementation achieves 3.65x speedup.
- *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*
</div>
</div>

## Full Pub List

### Efficient Hardware Accelerators for AI Computing (Jan. 2022 -- Present)
- ``DAC 2024`` [DEFA: Efficient Deformable Attention Acceleration via Pruning-Assisted Grid-Sampling and Multi-Scale Parallel Processing](), Yansong Xu, Dongxu Lyu, Zhenyu Li, **Yuzhou Chen**, Zilong Wang, Gang Wang, Zhican Wang, Haomin Li and Guanghui He, 2024 61th ACM/IEEE Design Automation Conference (DAC), San Francisco, CA, USA, 2024.
- ``TCAS-II 2024`` [A Broad-Spectrum and High-Throughput Compression Engine for Neural Network Processors](https://ieeexplore.ieee.org/document/10433078), **Yuzhou Chen**, Jinming Zhang, Dongxu Lyu, Zhenyu Li, Guanghui He, in *IEEE Transactions on Circuits and Systems II: Express Briefs*.
- ``ISCAS 2024`` [A High-Throughput Lossless Image Compression Engine Optimized for Compression Ratio](), Siqi Cai, **Yuzhou Chen**, Wenhui Zhang, Zeyuan Jin, Gang Wang, Guanghui He, *2024 IEEE International Symposium on Circuits and Systems (ISCAS)*, Singapore, 2024.
- ``TVLSI 2024`` [FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling](https://ieeexplore.ieee.org/document/10416684), Dongxu Lyu, Zhenyu Li, **Yuzhou Chen**, Gang Wang, Weifeng He, Ningyi Xu, Guanghui He, in *IEEE Transactions on Very Large Scale Integration (VLSI) Systems*.
- ``ICCAD 2023`` [SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing](https://ieeexplore.ieee.org/document/10323728), Dongxu Lyu, Zhenyu Li, **Yuzhou Chen**, Jinming Zhang, Ningyi Xu, Guanghui He, *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, San Francisco, CA, USA, 2023, pp. 1-9.
- ``DAC 2023`` [FLNA: An Energy-Efficient Point Cloud Feature Learning Accelerator with Dataflow Decoupling](https://ieeexplore.ieee.org/abstract/document/10247674), Dongxu Lyu, Zhenyu Li, **Yuzhou Chen**, Ningyi Xu, Guanghui He, *2023 60th ACM/IEEE Design Automation Conference (DAC)*, San Francisco, CA, USA, 2023, pp. 1-6.
- ``ISCAS 2023`` [O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression](https://ieeexplore.ieee.org/abstract/document/10181731), **Yuzhou Chen**, Jinming Zhang, Dongxu Lyu, Xi Yu, Guanghui He, *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*, Monterey, CA, USA, 2023, pp. 1-5.


# 🎖 Honors and Awards
- *2023.11* **Rongchang Technology Innovation Scholarship (Top20 in Shanghai Jiao Tong University)** from Shanghai Jiao Tong University.
- *2023.06* **Shanghai Outstanding Graduate** from Shanghai City.
- *2023.06* **Zhiyuan Outstanding Student Scholarship (Top15 in Zhiyuan Honored Program)** from Shanghai Jiao Tong University.
- *2023.06* **Departmental Excellent Undergraduate Thesis (Department of Micro/Nano Electronics)** from Shanghai Jiao Tong University.
- *2020.11* **Zhiyuan Honors Scholarship** from Shanghai Jiao Tong University.

# 📖 Educations
- *2023.09 - 2026.03 (expected)*, MS student in Electronic Science and Technology  (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China.
- *2019.09 - 2023.06*, B.E. in Microelectronics Science and Engineering (*Department of Micro/Nano Electronics*), Shanghai Jiao Tong University, Shanghai, China. 

# 💬 Invited Talks
- *2023.05*, **"O$^3$NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression"** in ISCAS'23, Monterey, CA, USA.

# 💻 Internships
- *2023.03 - now*, **Hardware & Toolchain Intern** in [Huixi Technology (辉羲智能)](https://www.rhino.auto/), Shanghai, China.