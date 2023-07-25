# Image-Classification
image classification with fine tuning the BEiT vision transformer on CIFAR 10 dataset

---
## Model
The [BEiT](https://huggingface.co/microsoft/beit-base-patch16-224) model is a Vision Transformer (ViT), which is a transformer encoder model (BERT-like). In contrast to the original ViT model, BEiT is pretrained on a large collection of images in a self-supervised fashion, namely ImageNet-21k, at a resolution of 224x224 pixels.
- paper : https://arxiv.org/abs/2106.08254

## Results
|    Train Acc.   | Validation loss. |  Test Acc.  |  Test loss.  |
| :-------------: | :-------------:  | :---------: | :----------: |
|      0.978      |      0.073       |    0.983    |    0.059     |

## Data
The [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset is a collection of 60,000 32x32 colour images in 10 classes, with 6000 images per class.