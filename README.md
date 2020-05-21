# αGAN-GP for images augmentation in PyTorch
Based on αGAN and train with wasserstein loss.

## Environment
* [Python 3.6]
* [PyTorch 1.3.1]

## Implementation Details
One training can take about ~17hours for 100,000 epochs on one NVIDIA GTX 2080Ti.

## Training
Please put your images in `./data/YourDataset/` before training

and then use

`python train.py`

to begin.