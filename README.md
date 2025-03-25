# <p align="center"><strong>Benchmarking Multi-modal Semantic Segmentation under Sensor Failures: Missing and Noisy Modality Robustness</strong></p>
<div align="center">
Chenfei Liao<sup>1,*</sup>, Kaiyu Lei<sup>2,*</sup>, Xu Zheng<sup>1,3</sup> (Project lead), Junha Moon<sup>1</sup>, Zhixiong Wang<sup>1</sup>, 
    
Yixuan Wang<sup>1</sup>, Danda Pani Paudel<sup>3</sup>, Luc Van Gool<sup>3</sup>, Xuming Hu<sup>1,4</sup><sup></sup> (Corresponding author)

<div align="center">
<sup>1</sup>HKUST(GZ), <sup>2</sup>XJTU, <sup>3</sup>INSAIT, Sofia University “St. Kliment Ohridski”, <sup>4</sup>CSE, HKUST
</div>

<div align="center">

[![arXiv](https://img.shields.io/badge/arXiv-2503.18445-brown?style=flat-square)](https://arxiv.org/abs/2503.18445)

</div>

<div align="left">
  
## Abstract

Multi-modal semantic segmentation (MMSS) addresses the limitations of single-modality data by integrating complementary information across modalities. 
Despite notable progress, a significant gap persists between research and real-world deployment due to variability and uncertainty in multi-modal data quality. 
Robustness has thus become essential for practical MMSS applications. However, the absence of standardized benchmarks for evaluating robustness hinders further advancement.
To address this, we first survey existing MMSS literature and categorize representative methods to provide a structured overview. 
We then introduce a robustness benchmark that evaluates MMSS models under three scenarios: Entire-Missing Modality (EMM), Random-Missing Modality (RMM), and Noisy Modality (NM). 
From a probabilistic standpoint, we model modality failure under two conditions: (1) all damaged combinations are equally probable; (2) each modality fails independently following a Bernoulli distribution. 
Based on these, we propose four metrics—mIoU<sup>Avg</sup><sub>EMM</sub>, mIoU<sup>E</sup><sub>EMM</sub>, mIoU<sup>Avg</sup><sub>RMM</sub>, and mIoU<sup>E</sup><sub>RMM</sub>—to assess model robustness under EMM and RMM. 
This work provides the first dedicated benchmark for MMSS robustness, offering new insights and tools to advance the field. 



  
## News
⭐ If you find any problems in our code, please contact us! We will fix them as soon as possible! 

📧 lcfgreat624@gmail.com, cliao127@connect.hkust-gz.edu.cn

🚩 2025/3/25 Our paper has been online on Arxiv: https://arxiv.org/pdf/2503.18445

🚩 2025/3/25 We release the first version of our souce code! 


## Quick Start

The entire project is based on [DELIVER](https://github.com/jamycheung/DELIVER). 

You only need to git clone [DELIVER](https://github.com/jamycheung/DELIVER), and replace the val_mm.py file with val_mm_EMM.py, val_mm_RMM.py, or val_mm_NM.py.


## References

If you find this project helpful, please consider citing the following paper:
```
@misc{liao2025benchmarkingmultimodalsemanticsegmentation,
      title={Benchmarking Multi-modal Semantic Segmentation under Sensor Failures: Missing and Noisy Modality Robustness}, 
      author={Chenfei Liao and Kaiyu Lei and Xu Zheng and Junha Moon and Zhixiong Wang and Yixuan Wang and Danda Pani Paudel and Luc Van Gool and Xuming Hu},
      year={2025},
      eprint={2503.18445},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2503.18445}, 
}
```












</div align="left">
