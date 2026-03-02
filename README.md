# Deep Convolutional Generative Adversarial Network

PyTorch implementation of a DCGAN, based on the [PyTorch DCGAN Tutorial](https://pytorch.org/tutorials/beginner/dcgan_faces_tutorial.html)

<img width="636" height="636" alt="butterfly" src="https://github.com/user-attachments/assets/58a210f9-3f99-4ea2-b10e-802f1e7ccea5" />

Trained on a dataset of butterfly images for 15 epochs.

### Training Workflow:
- Add an image dataset to the workspace
- Set up image dimensions in `config.py`
- Train models in `train.ipynb`
- Perform inferences in `inference.py` (Use the saving methods from `train_butterfly.ipynb`. They are NOT part of the PyTorch tutorial, which `train.ipynb` adheres to.)

The existing `train.ipynb` trains on the same celebA dataset as the PyTorch tutorial. Take a look at `train_butterfly.ipynb` as a step towards generalizing the procedure to other datasets.
