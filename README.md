# ml-bidirection-compression

## Overview

This project focuses on implementing various methods for bidirectional compression in machine learning. The main techniques explored include:

- **CGD** (Compressed Gradient Descent)
- **EF21-P + DIANA**
- **EF21-P + DCGD**

These methods are based on the research paper titled "Improved Theoretical Communication Complexity for Distributed Optimization with Bidirectional Compression."

## Experimental Setup

### Dataset

We utilize the following datasets for our experiments:

- **Mushrooms Dataset**: [Download Mushrooms.txt](https://github.com/aigoncharov/ml-bidirection-compression/blob/79085464cc08622856f5f2d2c0bfad4cf895757f/mushrooms.txt)
- **MNIST Dataset**: A well-known dataset for image classification tasks.

## How to Run the Experiment

To run the experiments, follow these steps:

1. **Download the Jupyter Notebook**: [bd_compression_report.ipynb](https://github.com/aigoncharov/ml-bidirection-compression/blob/79085464cc08622856f5f2d2c0bfad4cf895757f/bd_compression_report.ipynb).
   
2. **Modify the Dataset Directory**: Update the path to your dataset in the notebook while keeping other configurations unchanged.

3. **Run the Comparison**:
   - Add a new cell in the notebook.
   - Insert your comparison notebook code[https://github.com/aigoncharov/ml-bidirection-compression/blob/main/comparison.ipynb].
   - Execute the cell to see results.

## Results
![DIANA Method Plot](https://github.com/aigoncharov/ml-bidirection-compression/blob/main/plots/diana.PNG)
![https://github.com/aigoncharov/ml-bidirection-compression/blob/main/plots/DC%2Bdiana.png]
## References

For further reading and detailed methodology, refer to the following paper:
- [Improved Theoretical Communication Complexity for Distributed Optimization with Bidirectional Compression](https://github.com/aigoncharov/ml-bidirection-compression/blob/79085464cc08622856f5f2d2c0bfad4cf895757f/Improved%20Theoretical%20Communication%20Complexity%20for%20Distributed%20Optimization%20with%20Bidirectional%20Compression.pdf)

---


Citations:
[1] https://github.com/aigoncharov/ml-bidirection-compression/blob/79085464cc08622856f5f2d2c0bfad4cf895757f/mushrooms.txt
