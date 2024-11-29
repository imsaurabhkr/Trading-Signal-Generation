# Combining Principal Component Analysis, Discrete Wavelet Transform, and XGBoost to Trade in the Financial Markets

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Results](#results)
- [Contributing](#contributing)
- [Contact](#contact)

## Project Overview

When investing in financial markets, it is crucial to determine trading signals that provide the best entry and exit points. However, this is a challenging task and a popular research topic in finance. This project presents an expert system that combines Principal Component Analysis (PCA), Discrete Wavelet Transform (DWT), Extreme Gradient Boosting (XGBoost), and a Multi-Objective Optimization Genetic Algorithm (MOO-GA) to achieve high returns with low risk.

### Key Contributions:

- **Dimensionality Reduction:** PCA reduces the dimensionality of the financial input dataset.
- **Noise Reduction:** DWT performs noise reduction on every feature.
- **Classification:** The resultant dataset is fed to an XGBoost binary classifier with hyperparameters optimized by MOO-GA.
- **Performance Improvement:** The combination of PCA and DWT has comparable return with the Buy and Hold (B&H) strategy but with more lower risk in financial markets.

## Features

- **PCA for Dimensionality Reduction:** Efficiently reduces data dimensionality, retaining essential information.
- **DWT for Noise Reduction:** Improves signal clarity by reducing noise in financial data.
- **XGBoost Classifier:** Utilizes a powerful gradient boosting algorithm for accurate trading signal classification.
- **Hyperparameter Optimization:** MOO-GA optimizes XGBoost hyperparameters for better performance.
- **High Return, Low Risk:** Achieves higher returns with reduced risk compared to traditional strategies.

## Tech Stack

- **Programming Languages:** Python
- **Libraries:** 
  - Scikit-learn (for PCA)
  - PyWavelets (for DWT)
  - XGBoost (for classification)
  - DEAP (for MOO-GA optimization)
  - Pandas, NumPy (for data manipulation)
  - Matplotlib, Seaborn (for visualization)

## Results

Achieved **55.3%** accuracy and a **34%** return with a Sharpe ratio of **2.7** on the S&P 500 dataset.

### Performance Highlights:

- **PCA Contribution:** Significantly improved system performance.
- **DWT and PCA Combined:** Enhanced results, demonstrating the system's effectiveness.

## Contributing

We welcome contributions from the community! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or inquiries, please contact:

- **Contact:** [Saurabh Kumar](mailto:saurabh_k@ma.iitr.ac.in)

---

This README file provides a comprehensive overview of your financial trading project, including setup instructions, usage guidelines, and contribution information. Adjust the content as necessary to fit the specific details and requirements of your project.
