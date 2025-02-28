# GPT-from-scratch

## Project Description
GPT-from-scratch is a project that aims to implement a GPT (Generative Pre-trained Transformer) model from scratch using PyTorch. The project provides a step-by-step guide to building a GPT model, including data preprocessing, model architecture, training, and text generation.

## Installation
To install the required dependencies and set up the environment, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/m-gopichand/GPT-from-scratch.git
   cd GPT-from-scratch
   ```

2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To run the model and generate text, follow these steps:

1. Prepare the input data:
   - Place your input text file in the project directory and name it `input.txt`.

2. Train the model:
   ```bash
   python model.py
   ```

## Quantization
To enable quantization, use the `--quantize` command line argument when running the model. This will apply dynamic quantization to the model, reducing its size and improving inference speed.

```bash
python model.py --quantize
```
