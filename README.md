# CNN_ARCHITECTURES

1. Implementaion of the Popular CNN Architectures from Scratch.
2. [Performance Comparison](https://github.com/Cranjis-McB/CNN_ARCHITECTURES/tree/main/kaggle_notebooks) with the Pytorch Standard Architectures.
3. Implementation of the Popular Vision Data Augmentation Techniques from Scratch.

## Implemented Architectures as of now

1. ResNet (Versions - 18, 34, 50, 101, 152) :white_check_mark:
2. EfficientNet (Versions - b0-b7) :white_check_mark:
3. EfficientNet-V2 (Versions - S, M, L) :white_check_mark:

## [cnn_architectures.ipynb](https://github.com/Cranjis-McB/CNN_ARCHITECTURES/blob/main/cnn_architectures.ipynb) file

You can import the mentioned CNN Architectures from this file.

**How to Use?**

```python
from cnn_architectures import ResNet18, ResNet34, ResNet50, ResNet101, ResNet152
from cnn_architectures import EffNet
from cnn_architectures import EffNetV2

# Initialize the model.
resnet = ResNet18(img_channel=3, num_classes=1000) # Resnets

version = 'b0' # b0-b7
effnet = EffNet(version, num_classes=1000) # Efficient-Nets

version = 's' # s, m, l
effnetV2 = EffNetV2(version, num_classes=1000) # EfficientNet-V2

```

## [Data Augmentations](https://github.com/Cranjis-McB/CNN_ARCHITECTURES/tree/main/Data%20Augmentation)

This folder consists of the Pytorch Implementation of the Popular SOTA Vision Data Augmentations techniques.

### Implemented Data Augmentations as of now

1. [Cutout](https://arxiv.org/abs/1708.04552)
2. [Mixup](https://arxiv.org/pdf/1710.09412.pdf)
3. [CutMix](https://arxiv.org/abs/1905.04899v2)
4. [AugMix](https://arxiv.org/abs/1912.02781)
5. [GridMask](https://arxiv.org/abs/2001.04086v2)

