# AI Image Caption Generator

A simple web application that automatically generates descriptive captions for your images using AI.

## Overview

This tool leverages the BLIP (Bootstrapping Language-Image Pre-training) model to analyze images and produce relevant textual descriptions. Simply upload an image, and the system will generate a caption describing what it sees.

## Features

- **User-friendly interface**: Easily upload images through a simple web interface
- **AI-powered captioning**: Utilizes Salesforce's BLIP image captioning model
- **Quick results**: Get descriptive captions in seconds
- **No sign-up required**: Use the tool directly from your browser

## How It Works

The application uses:
- **BLIP model**: A powerful vision-language model designed for image understanding
- **Gradio**: For the intuitive web interface
- **Transformers library**: To handle the AI model implementation

## Live Demo

You can try the live demo at: [https://amohaa-simple-image-caption-tool-by-amo.hf.space/?__theme=system&deep_link=ch9jDRTRylM](https://amohaa-simple-image-caption-tool-by-amo.hf.space/?__theme=system&deep_link=ch9jDRTRylM)


## Installation

If you want to run this application locally:

```bash
# Clone the repository
git clone [repository-url]
cd ai-image-caption-generator

# Install dependencies
pip install transformers pillow gradio torch

# Run the application
python app.py
```

## Usage

1. Open the application in your web browser
2. Upload an image using the provided interface
3. Wait a moment while the AI processes your image
4. View the generated caption that describes your image


## Dependencies

- transformers
- pillow
- gradio
- pytorch

## Model Information

This project uses the `Salesforce/blip-image-captioning-base` model, which is designed to generate natural language descriptions of images.

## License

MIT License



## Acknowledgments

- Salesforce for the BLIP model
- Hugging Face for hosting the space
