## A comparative case study on the performance of global sensitivity analysis methods on digit classification
This repository includes source codes of the paper "A comparative case study on the performance of global sensitivity analysis methods on digit classification"


## Abstract

Global sensitivity analysis seeks to detect influential input factors contributing to a black-box model’s specific decisions. This aligns with a key objective of AI explainability: Clarifying and interpreting the behavior of machine learning algorithms by identifying the features that influence their decisions-a significant approach for mitigating the computational burden associated with processing high-dimensional data. Various techniques are proposed for sensitivity analysis; however, each of these methods focuses on different mathematical aspects, which can lead to varying conclusions about the impact or importance of each feature. Therefore, it remains unclear which of these algorithms are most suitable for machine learning models and, in particular, deep learning models. Our goal is to examine the influential features identified by each sensitivity analysis algorithm and evaluate their role in helping deep learning models make accurate decisions. In this article, first, we present the mathematical foundations underlying Global Sensitivity algorithms and explain the rationale behind selecting the important features identified by each method. We then provide a comparative case study on global sensitivity analysis methods and propose a methodology to evaluate the efficacy of these methods by conducting a case study on MNIST digit dataset classification. Our study highlights the most effective global sensitivity analysis methods for detecting the key factors influencing the digit data classification.
https://link.springer.com/article/10.1007/s44248-025-00067-x

## Citation
```bibtex
@article{sadeghi2025comparative,
  title={A comparative case study on the performance of global sensitivity analysis methods on digit classification},
  author={Sadeghi, Zahra and Matwin, Stan},
  journal={Discover Data},
  volume={3},
  number={1},
  pages={38},
  year={2025},
  publisher={Springer}
}
