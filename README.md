# [High-Resolution Underwater Camouflaged Object Detection:GBU-UCOD Dataset and Topology-Aware and Frequency-Decoupled Network][![Project Page](https://img.shields.io/badge/Project-Page-green)](your_link)
[![arXiv](https://img.shields.io/badge/arXiv-2601.XXXXX-B31B1B.svg)](https://github.com/K1NSA/Test/tree/main)
[![Dataset](https://img.shields.io/badge/Dataset-Baidu%20Netdisk-06A7FF.svg?logo=baidu&logoColor=white)](https://github.com/K1NSA/Test/tree/main)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)


---

## 📣 News
* **[2026-07]** Our paper was accepted！🎉🎉🎉
* **[2026-02]** Code and Dataset labels are released.



---

## 💡 Abstract
> In this paper, we propose DeepTopo-Net, a novel framework that integrates topology-aware modeling with frequency-decoupled perception. To address phys
ical degradation, we design the Water-Conditioned Adaptive Perceptor (WCAP), which employs Riemannian metric tensors to dynamically deform convolutional sampling fields. Furthermore, the Abyssal-Topology Refinement Module (ATRM) is developed to maintain the structural connectivity of spindly targets through skeletal priors. Specifically, we first introduce GBU-UCOD, the first high
resolution (2K) benchmark tailored for marine vertical zonation, filling the data gap for hadal and abyssal zones. Extensive experiments on MAS3K, RMAS, and our proposed GBU-UCOD datasetsdemonstrate that DeepTopo-Net achieves state-of-the-art performance, particularly in preserving the morphological integrity of complex underwater patterns.

---




## 🖼️ Method Overview

<p align="center">
  <img width="1850" height="1088" alt="image" src="https://github.com/user-attachments/assets/dcf29c82-a229-4751-a7f8-a77e2f9d064b" />

</p>


---

## 📂 Dataset

The **[GBU-UCOD]** dataset is hosted on Baidu Netdisk. Access to the dataset is granted upon request for academic research purposes only.

### 📥 How to Access
1. **Download the Data**: Download the encrypted dataset file from Baidu Netdisk and Google Drive.
   * **Baidu Netdisk Link**: [https://pan.baidu.com/s/1scU8JEguoFBvQ7-eoYAavQ]
   * **Password**: [****]
   *(Note: We will release it as soon as the paper is accepted.)*

   * **Google Drive Link**: [****]
   *(Note: We will send it to your e-mail after we recived your Agreement)*

2. **Sign the Agreement**:

   * Download the [End User License Agreement for GBU UCOD Dataset.pdf](https://github.com/user-attachments/files/25032343/End.User.License.Agreement.for.GBU.UCOD.Dataset.pdf).
   * Fill in your information. **A signature from your Principal Investigator (PI) is required.**

3. **Request Password**:
   * Send the signed agreement (scanned PDF) to **wuwenji@hrbeu.edu.cn**.
   * Please use the email subject: **"Application for [GBU UCOD] - [Your Institution]"**.

4. **Get Access**:
   * We will verify your request and reply with the **unzip password** or **Google Drive link** within 3-5 working days.


### 🏗️ Structure
```text
/data/YourDataset/
  ├── train/
  │   ├── JPEGImages/        # Video frames
  │   └── Annotations/       # Binary masks
  └── test/
      ├── JPEGImages/
      └── Annotations/

```
## 🛡️ License

This project is released under the **MIT License** for the code and **CC BY-NC 4.0** for the dataset.

* **Code**: The source code of this project is released under the [MIT License](LICENSE.txt).
* **Dataset**: The [Your Dataset Name] dataset is used for academic research only and is subject to the [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/).

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

> **Notice**: No commericial purpose for datasets.


## ✒️ Citation

If you find our code or dataset useful for your research, please consider citing our paper. In addition, you can also read and cite our other creative work.

```bibtex
@misc{wu2026highresolutionunderwatercamouflagedobject,
      title={High-Resolution Underwater Camouflaged Object Detection: GBU-UCOD Dataset and Topology-Aware and Frequency-Decoupled Networks}, 
      author={Wenji Wu and Shuo Ye and Yiyu Liu and Jiguang He and Zhuo Wang and Zitong Yu},
      year={2026},
      eprint={2602.03591},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2602.03591}, 
}

@misc{liu2026yuv20kcomplexitydrivenbenchmarktrajectoryaware,
      title={YUV20K: A Complexity-Driven Benchmark and Trajectory-Aware Alignment Model for Video Camouflaged Object Detection}, 
      author={Yiyu Liu and Shuo Ye and Chao Hao and Zitong Yu},
      year={2026},
      eprint={2604.09985},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2604.09985}, 
}

@misc{hao2024simpleeffectivenetworkbased,
      title={A Simple yet Effective Network based on Vision Transformer for Camouflaged Object and Salient Object Detection}, 
      author={Chao Hao and Zitong Yu and Xin Liu and Jun Xu and Huanjing Yue and Jingyu Yang},
      year={2024},
      eprint={2402.18922},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2402.18922}, 
}

@misc{hao2025distributionspecificlearningjointsalient,
      title={Distribution-Specific Learning for Joint Salient and Camouflaged Object Detection}, 
      author={Chao Hao and Zitong Yu and Xin Liu and Yuhao Wang and Weicheng Xie and Jingang Shi and Huanjing Yue and Jingyu Yang},
      year={2025},
      eprint={2508.06063},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2508.06063}, 
}
