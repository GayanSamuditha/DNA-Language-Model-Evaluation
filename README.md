# DNA-Language-Model-Evaluation
Unsupervised evaluation of pre-trained DNA language model embeddings


DNA language models (DLMs) have generated significant excitement for their potential to revolutionize genetics tasks, including gene finding, enhancer annotation, and histone modification. Despite their successes, these models face challenges in capturing individual-level transcriptome variation, underscoring the need for more comprehensive evaluation methods. Existing evaluation approaches often rely on computationally intensive downstream tasks and may not adequately assess a model's generalist capabilities.

This repository presents an unsupervised evaluation framework for pre-trained DNA language model embeddings. It aims to address the limitations of current evaluation methods by providing robust and efficient metrics to gauge model performance and generalization. Our approach emphasizes the assessment of models beyond specific tasks, focusing on their ability to learn and generalize across a range of genetic contexts.

Explore the code and methodologies for evaluating DLMs, and contribute to advancing the field of DNA language modeling through unsupervised evaluation techniques.

![image](https://github.com/user-attachments/assets/fd43e189-2fcf-4b03-b173-22c1c615d460)


## Key Features

- **Broad Evaluation Metrics:** Move beyond task-specific assessments to evaluate DLMs' overall generalization capabilities.
- **Efficient Framework:** Reduce the need for computationally expensive downstream tasks by utilizing unsupervised evaluation techniques.
- **Comprehensive Analysis:** Assess model performance across a wide range of genetic contexts using innovative metrics like RankMe, NESum, and r(M).
- **Visualization Tools:** Integrated tools for visualizing evaluation metrics and model performance, including correlation analysis between different metrics.

# Methodology

Our evaluation framework focuses on unsupervised metrics that offer a more holistic view of model performance:

1. **RankMe:** Measures the entropy of model embeddings to evaluate the diversity and informativeness of the learned representations.
2. **NESum (Normalized Eigenvalue Sum):** Assesses the stability and generalizability of embeddings by analyzing the spectrum of the embedding matrix.
3. **r(M):** Evaluates the rank of the embedding matrix relative to its Frobenius norm, providing insights into the model's ability to capture meaningful genetic features.


## Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- **Python 3.8** or higher: You can download the latest version of Python from the [official Python website](https://www.python.org/downloads/).
  

## Usage

1. **Setup:**
   - Clone the repository: 
     ```bash
     git clone https://github.com/your-repo/dna-language-model-evaluation.git
     ```
   - Install the required dependencies:
     ```bash
     pip install -r requirements.txt
     ```

2. **Run Evaluations:**
   - Prepare your DNA sequence datasets.
   - Use the provided scripts to generate embeddings using pre-trained DLMs.
   - Run the unsupervised evaluation using the provided framework.

3. **Visualization:**
   - Visualize the evaluation results with the integrated plotting tools to understand model performance across different metrics.



