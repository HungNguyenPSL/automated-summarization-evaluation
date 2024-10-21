# Automated Summarization Evaluation

This repository contains the implementation of **Automated Summarization Evaluation** based on the **BLANC metric**. You can find more information about the BLANC metric in the paper: [BLANC: A New Evaluation Metric for Text Summarization](https://arxiv.org/pdf/2002.09836).

## Overview

This project is part of the final project for the Large Languages Models course, which is a collaboration between the Master MASH program ([Mathematics, Machine Learning, Sciences, and Humanities](https://dauphine.psl.eu/en/training/masters-degrees/mathematics-and-applied-mathematics/masters-year-2-mathematics-deep-learning-and-humanities/program)) and the Master IASD program ([Artificial Intelligence Systems and Data](https://dauphine.psl.eu/en/training/masters-degrees/computer-science/m2-artificial-intelligence-systems-data)) at PSL University.

### Target

The primary goal of this project is to investigate the BLANC metric to automate the evaluation process of document summaries and to develop a more adaptable approach to enhance the BLANC metric.

### Dataset

- **Billsum**: The BillSum dataset is the first corpus for automatic summarization of US legislation.

### Pretrained Model

- **t5-small**: The implementation uses the T5 small model provided by Hugging Face.

### Approaches

1. **Reimplementation of the BLANC Metric**: This project includes a reimplementation of the BLANC metric for evaluating summary quality.
2. **Incorporation of Cosine Similarity**: To enhance the flexibility and reasonableness of the BLANC metric, cosine similarity is incorporated, allowing for the evaluation of semantically similar words that are not identical.

## Usage

Provide your Hugging Face token and run the file on Google Colab.

## Contributors

- [@HungNguyen](https://github.com/HungNguyenPSL) 

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Thanks to the authors of the BLANC metric and the creators of the Billsum dataset for their foundational contributions to the field of summarization evaluation.
