# Facial Image Generation using Style GAN

## Description

This repository contains an implementation of Facial Image Generation using Style Generative Adversarial Networks (StyleGAN). StyleGAN is a cutting-edge generative model designed for synthesizing high-quality facial images with realistic details and diverse styles. This project provides a comprehensive framework for generating facial images using pre-trained StyleGAN models and custom datasets.

## Getting Started

### Prerequisites

- Python 3.x
- TensorFlow
- NumPy
- OpenCV
- PIL
- StyleGAN pre-trained model (not included in this repository)

### Usage

1. Place the pre-trained StyleGAN model in the root directory of the repository.

2. Prepare your custom dataset of facial images. Ensure that the images are aligned and cropped to the desired size.

3. Modify the configuration parameters in `config.py` to specify the paths to your dataset and the pre-trained model.

4. Run the `generate_images.py` script to generate facial images.

5. The generated images will be saved in the specified output directory.

## Customization

You can customize the image generation process according to your requirements:

- Adjust various parameters such as batch size, latent space dimensions, and interpolation steps in the `config.py` file.
- Experiment with different pre-trained models and datasets to generate facial images with diverse styles and characteristics.

## Citation

If you use this code for your research or project, please consider citing the original StyleGAN paper.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Special thanks to the authors of StyleGAN for their groundbreaking work in the field of generative modeling.
- Thanks to the open-source community for providing valuable resources and inspiration for this project.

## Result

[https://drive.google.com/file/d/1VIA46L8LTkumyraxxK2JgX4cymSI8L7v/view?usp=sharing]
