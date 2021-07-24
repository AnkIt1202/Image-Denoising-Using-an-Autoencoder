# Image-Denoising-Using-an-Autoencoder

Autoencoders are a type of Unsupervised Neural Network that compresses the input into a latent-space representation(contains latent variables extracted from the input data) and, then reconstructs the output from this latent representation with some loss known as Reconstruction Error
Architecture of an Autoencoder consists of:

- **Encoder** - Learns how the data is structured and compresses it into latent-space representation (s)
- **Code** - Represents the Compressed Input which is fed to the Decoder
- **Decoder** - Reconstructs the Input from the Latent Space Representation

Autoencoders are widely used with the image data and some of their use cases are:
- Image Compression
- Image Denoising
- Dimensionality Reduction
- Image Generation
- Feature Extraction

# Image Denoising using an Autoencoder

## Problem Statement

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

As a Deep Learning Engineer, your goal is to reconstruct digits images from a dataset of thousands of handwritten images using an Autoencoder.

### Tasks to be Performed

- Import the Required Libraries, Load, Analyze, and Visualize the Dataset - Beginner
- Pre-process the dataset - Intermediate
   - Normalize all the values between 0 and 1 
   - Induce Salt and Pepper Noise to the Images and then, visualize the noisy images
- Build & Train Auto-Encoder Deep Learning Model - Advance
- Evaluating the Trained Model Performance - Beginner
- Visualize the Denoised Images using Matplotlib - Intermediate
