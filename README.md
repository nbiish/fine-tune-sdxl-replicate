# Copy of Replicate's colab for finetuning SDXL

## Preparing Your Data

Before you start fine-tuning the SDXL model, you need to prepare your training data:

1. Gather all your training photos into one directory.
2. Compress this directory into a ZIP file named `data.zip`.

This `data.zip` file will be used by a shell script in the next step to generate a URL for the Google Colab notebook where the fine-tuning process will take place.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nbiish/fine-tune-sdxl-replicate/blob/main/Fine_tune_SDXL.ipynb)