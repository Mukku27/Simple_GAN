## Simple GAN (Generative Adversarial Network) for MNIST Dataset
This project implements a simple Generative Adversarial Network (GAN) for generating handwritten digits from the MNIST dataset using PyTorch. GANs are a class of machine learning models composed of two neural networks, the Generator and the Discriminator, which are trained simultaneously in a competitive manner.
This repository contains a simple implementation of a Generative Adversarial Network (GAN) for generating handwritten digits from the MNIST dataset using PyTorch.

### Installation

To run this code, ensure you have Python and pip installed. Then, install the required packages using the following command:

```bash
pip install torch torchvision
```

### Description

The GAN consists of two neural networks:

1. **Discriminator**: A neural network that distinguishes between real and fake images.
2. **Generator**: A neural network that generates fake images to try to fool the discriminator.

### Usage

1. Clone the repository:

```bash
git clone <repository_url>
```

2. Navigate to the repository directory:

```bash
cd <repository_name>
```

3. Run the code:

```bash
python simple_gan.py
```

### Results

During training, the GAN produces both real and fake images. These images are visualized using TensorBoard. You can view the generated images and real images to track the training progress.

