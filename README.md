# Transformer-based Text Summarization

## Overview:

This project implements a text summarization model using the Transformer architecture. The model is trained on a dataset of news articles and their corresponding headlines. The goal is to generate concise and relevant summaries for given input articles.

## Prerequisites:

- Python 3.x
- TensorFlow 2.x
- Openpyxl

## Installation:

1. Clone the repository:

```bash
git clone https://github.com/GVHemanth/Transformers-based-Text-Summarization.git
cd transformer-text-summarization
```

2. Install dependencies:

```bash
pip install openpyxl --quiet
```

3. Download the dataset:

    - Download the dataset (news articles and headlines) and place it in the appropriate directory. Ensure the file is in the required format (e.g., Inshorts Cleaned Data.xlsx).

## Usage:

1. Run the main script:

```bash
python transformer_summarization.py
```

2. Monitor training progress:

   - The script will train the Transformer model for a specified number of epochs. You can adjust hyperparameters in the script or through command-line arguments.

3. Evaluate the model:

   - After training, the script provides an example of how to use the trained model to generate summaries for new input articles.

## Customization:

- Adjust hyperparameters such as `num_layers`, `d_model`, `num_heads`, `dff`, and `dropout_rate` in the script to experiment with different configurations.
  
- Modify the training loop to suit your specific use case or integrate the model into your applications.

## Results:

- The model's performance can be evaluated by comparing the generated summaries with the actual headlines from the dataset.

## Model Checkpoints:

- Model checkpoints will be saved during training in the "checkpoints" directory. You can use these checkpoints to restore the trained model.

## Contributing:

- Contributions are welcome! Feel free to submit issues or pull requests.

## License:

- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
