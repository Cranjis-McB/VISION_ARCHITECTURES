# CNN_ARCHITECTURES

1. Implementaion of the Popular CNN Architectures from Scratch.
2. Compare the performance with Standard Architecture of the same.

## Implemented Architectures as of now

1. ResNet (Versions - 18, 34, 50, 101, 152) :white_check_mark:
2. EfficientNet (Versions - b0-b7) :white_check_mark:

## cnn_architectures.ipynb file

You can import the mentioned CNN Architectures from this file.

**How to Use?**

```python
from cnn_architectures import ResNet18, ResNet34, ResNet50, ResNet101, ResNet152
from cnn_architectures import EffNet

# Initialize the model.
resnet = ResNet18(img_channel=3, num_classes=1000) # Resnets

version = 'b0'
effnet = EffNet(version, num_classes=1000) # Efficient-Nets

```

