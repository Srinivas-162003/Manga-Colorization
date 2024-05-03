# Manga Colorization Using CycleGANs

## Overview
This project leverages CycleGANs, a type of Generative Adversarial Network, to colorize grayscale manga images automatically. It aims to enhance the accessibility and appeal of classic manga by adding color, making these cultural artifacts more engaging for modern audiences.

## Features
- *Automatic Colorization*: Convert black and white manga to color without manual intervention.
- *Preservation of Details*: Ensures that the original art's details are maintained.
- *Accessibility Improvement*: Makes manga more accessible to people who rely on color differentiation.

## Getting Started

### Prerequisites
- Python 3.8+
- OpenMMLab
- mmgeneration
- PyTorch 1.7.1+
- Torchvision
- OpenCV for Python
- Numpy

### Installation
Clone the repository and install the required packages:
bash
git clone https://github.com/Srinivas-162003/Manga-Colorization
cd manga-colorization
pip install -r requirements.txt


### Usage
Run the colorization script with the path to your manga image directory:
bash
python colorize.py --input_dir /path/to/manga --output_dir /path/to/colorized_manga



## How It Works
- *CycleGANs*: Utilizes two generator and two discriminator networks to learn and map the grayscale images to the color domain without paired examples.
- *Loss Functions*: Employs cycle consistency loss to ensure that the colorization can be reversed, preserving the original manga's integrity.

## Contributions
- *Revitalize Old Manga*: Brings new life to classic manga by colorizing them.
- *Research and Development*: Contributes to advancements in AI and image processing.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- CycleGAN authors for the foundational architecture and insights.
- The manga community for providing datasets and valuable feedback.

---

This README template is designed to be clear and concise, providing quick insights into what the project is about, how to get it running, and its benefits. Adjust the paths and URLs as necessary to fit where your code and images are hosted.
