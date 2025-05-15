# 🖼️ Text-to-Image Converter using Stable Diffusion

This is an academic project built in **Google Colab** that converts a user-provided text prompt into a high-quality image using the **CetusMix V4** model (a fine-tuned version of Stable Diffusion).

## 🚀 Features

- Accepts a **single text prompt** from the user
- Generates a **realistic or artistic image** based on the prompt
- Uses **CetusMix V4**, a powerful Stable Diffusion checkpoint
- Automatically **displays and saves** the generated image
- Runs smoothly on **GPU-enabled Colab environments**

## 🛠️ Requirements

All required Python libraries are installed automatically via pip:

- `diffusers`
- `transformers`
- `accelerate`
- `torch` (with GPU support)
- `PIL` for image handling

## 🧠 Model Information

- **Model**: `redstonehero/cetusmix_v4`
- **Pipeline**: `StableDiffusionPipeline` from Hugging Face 🤗
- **Precision**: `float16` on CUDA for faster and efficient inference

## 📋 How to Use

1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. Enter a **text prompt** when asked (e.g., `"A cat flying through space"`).
4. View and download the generated image.

Example Prompt:
A serene mountain lake at sunrise

## 🖼️ Sample Output

![image](https://github.com/user-attachments/assets/3d3a18c5-df1a-4b11-a453-c7d3f7497223)


## 📁 Output

The generated image is:
- Displayed using `display(image)`


