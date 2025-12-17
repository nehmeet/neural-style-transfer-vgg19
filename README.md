## Neural Style Transfer using VGG19

This project implements neural style transfer by optimizing an input image to
match the content of one image and the style of another using a pretrained VGG19 network.

### Key Ideas
- VGG19 used as a fixed feature extractor
- Content loss from conv4_2
- Style loss computed using Gram matrices
- Image pixels optimized using backpropagation

### Tech Stack
Python, PyTorch, VGG19, NumPy, Matplotlib
