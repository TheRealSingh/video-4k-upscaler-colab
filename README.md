# 4K Video Upscaling via Hugging Face Model in Google Colab

A Google Colab notebook that pulls an open-weight video upscaling model from Hugging Face and uses Colab's free GPU to upscale video to 4K resolution.

## What it does

Loads a pretrained upscaling model directly from Hugging Face and runs inference on Colab's GPU runtime, avoiding the need for local GPU hardware or paid compute.

## Why I built this

Wanted hands-on experience working with open-source models outside of a plug-and-play interface — pulling weights directly, understanding the inference pipeline, and working within Colab's free-tier GPU limits.

## How to use

1. Open `upscaler.ipynb` in Google Colab
2. Run the setup cells to install dependencies and pull the model from Hugging Face
3. Upload your source video
4. Run the inference cells to generate the 4K output

## Tech stack

- Google Colab (free GPU runtime)
- Hugging Face Hub (model source)
- Python

## Note

No copyrighted video content is included in this repo — only the notebook and setup instructions.
