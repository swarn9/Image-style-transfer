# Image Style Transfer Using PyTorch

This project implements an **Image Style Transfer** using a pretrained VGG16 network in PyTorch. The goal is to combine the texture and style of a famous painting (style image) with the structure of another image (content image). The result is a new image that retains the content but adopts the texture and visual appearance of the style image.

## Features
- **Content Image:** Provides the main structure for the final image.
- **Style Image:** Extracts the artistic features (colors, textures, patterns) to blend with the content.
- **Neural Network:** Utilizes a VGG16 model pre-trained on ImageNet for feature extraction.
- **Gram Matrix:** Calculates the style representation of the style image to be transferred.

## Steps
1. **Image Preprocessing:** Both content and style images are loaded and transformed.
2. **Feature Extraction:** VGG16 layers are used to extract content and style features.
3. **Optimization:** The content and style losses are minimized to blend the two images.
4. **Final Output:** The generated image takes on the texture of the style image while preserving the structure of the content image.

