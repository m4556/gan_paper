###  Project Overview

A deep learning project that automatically generates colorized anime characters based on sketch drawings, using Conditional GANs. This is implementation of "Image-to-Image Translation with Conditional Adversarial Networks" from scratch.

### Demo
This section displays some outputs of the program. Each example contains an input image (left), a ground truth image (middle), and a generated image (right).

<img src="https://github.com/m4556/gan_paper/blob/main/gan.png" width="600" >


### Setup
1. Clone the Repository: git clone https://github.com/m4556/gan_paper ; cd gan_paper
2. Create virtual environment: python3 -m venv venv ; source venv/bin/activate
3. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/ktaebum/anime-sketch-colorization-pair). Extract it to data folder.
4. Install Dependencies: pip install -r requirements.txt
5. Run code to start training: python train.py


### References

- Isola, Phillip, et al. “Image-to-Image Translation with Conditional Adversarial Networks.” ArXiv:1611.07004 [Cs], Nov. 2018. arXiv.org, http://arxiv.org/abs/1611.07004.

