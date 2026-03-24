# RFDGNet

Official PyTorch implementation of the paper **"A Robust Frequency Domain-Generalized Network for Multispectral Pansharpening"** (IEEE JSTSP 2025).

## Overview
Multispectral pansharpening aims to fuse high-resolution panchromatic (PAN) images with low-resolution multispectral (LRMS) images to generate high-resolution multispectral (HRMS) images. Most existing deep learning-based methods suffer from significant performance degradation when applied to different satellites (domain shift problem).

To address this issue, we propose **RFDGNet (Robust Frequency Domain-Generalized Network)**, a frequency-domain-guided network for cross-satellite domain generalization pansharpening. The network leverages wavelet decomposition to separate domain-invariant high-frequency details and satellite-specific low-frequency components, and employs adversarial training with label misleading to learn generalized representations. RFDGNet achieves robust and stable performance in both in-dataset and cross-satellite test scenarios.


## Supported Datasets
- QuickBird (QB)
- Gaofen-2 (GF2)
- WorldView-3 (WV3)
- WorldView-2 (WV2)




## Citation
If you use this code for your research, please cite our paper:
```bibtex
@ARTICLE{11201025,
  author={Xu, Shen and Zhong, Shengwei and Gong, Chen},
  journal={IEEE Journal of Selected Topics in Signal Processing},
  title={A Robust Frequency Domain-Generalized Network for Multispectral Pansharpening},
  year={2025},
  volume={19},
  number={8},
  pages={1724-1738},
  doi={10.1109/JSTSP.2025.3620709}
}


## Contact
Email: shenxu@njust.edu.cn
