# Fine-tuning microsoft/trocr_small_stage1 for OCR

This repository provides a Jupyter Notebook for fine-tuning the trocr_small_stage1 model for OCR using the Hugging Face Transformers library.

## Overview

The notebook provides step-by-step instructions to set up the environment, preprocess data, train the model, and evaluate its performance. It leverages popular libraries like:

- transformers
- datasets
- torch
- torchvision
- streamlit
- uvicorn
- accelerate
- sentencepiece
- 
## Setup

To get started with the notebook, make sure you have the necessary dependencies installed. You can install them using the following commands:

\`\`\`bash
pip install -r libraries.txt
\`\`\`

## Usage

1. **Clone the repository:**
    \`\`\`bash
    git clone https://github.com/youzaina001/fine_tuned_trocr_small_stage1_OCR.git
    cd fine_tuned_trocr_small_stage1_OCR
    \`\`\`
   
2. **Open the Jupyter notebook:**
    \`\`\`bash
    jupyter notebook model_training_notebook.ipynb
    \`\`\`

3. **Follow the steps in the notebook** to set up the environment, load data, train your model, and evaluate its performance.

## Key Sections

- **Environment Setup:** Instructions for installing necessary libraries and configuring the environment.
- **Data Preprocessing:** Loading and preprocessing the dataset for model training.
- **Model Training:** Defining the model architecture, training, and fine-tuning.
- **Evaluation:** Evaluating the model performance using various metrics.
- **Deployment:** Options for deploying the trained model using tools like FastAPI or Streamlit.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Author

- Yassine Ouzaina
