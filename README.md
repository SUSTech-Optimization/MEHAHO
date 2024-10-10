# MEHAHO

**MEHAHO** is an R package designed for hyper-parameter optimization in machine learning methods. This package includes support for:

- Elastic Net
- Sparse Group Lasso
- Low-Rank Matrix Completion
- Support Vector Machines (SVM)

The package provides the option to automatically adjust MEHA (LV-HBA) hyper-parameters using simulated annealing algorithms, improving the performance of these machine learning models.

## Installation

To install the `MEHAHO` package from GitHub, you can use the `devtools` package:

1. Install the `devtools` package if you haven't already:

    ```r
    install.packages("devtools")
    ```

2. Use `devtools::install_github()` to install `MEHAHO` from the GitHub repository:

    ```r
    library(devtools)
    install_github("SUSTech-Optimization/MEHAHO")
    ```

3. Load the `MEHAHO` package:

    ```r
    library(MEHAHO)
    ```

Function usage details can be found in the R package help documentation. You can also adjust the function's architecture to modify hyper-parameters and initial values of the algorithm in folder `R/` as needed.

## References

- Gao, L., Ye, J. J., Yin, H., Zeng, S., & Zhang, J. (2022).["Value function based difference-of-convex algorithm for bilevel hyper-parameter selection problems"](https://proceedings.mlr.press/v162/gao22j.html). ICML, 2022.
- Liu, R., Liu, Z., Yao, W., Zeng, S., & Zhang, J. ["Moreau Envelope for Nonconvex Bi-Level Optimization: Single-Loop and Hessian-Free Solution Strategy"](https://arxiv.org/abs/2405.09927). ICML, 2024.
- Yao, W., Yu, C., Zeng, S., & Zhang, J. ["Constrained Bi-Level Optimization: Proximal Lagrangian Value Function Approach and Hessian-free Algorithm"](https://openreview.net/forum?id=xJ5N8qrEPl).  ICLR, 2024.

## Contact

If you have any questions about the code, please feel free to email:

- **Pengyu Zhu:** [12332853@mail.sustech.edu.cn](mailto:12332853@mail.sustech.edu.cn)
- **Zhiheng Tan:** [12111603@mail.sustech.edu.cn](mailto:12111603@mail.sustech.edu.cn)
