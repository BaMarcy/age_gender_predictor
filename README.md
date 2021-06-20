 ## Age👶👴 and Gender♀️♂️ Estimation with Transfer and Multi-Task Learning
 
[**💾 DATASET**](https://github.com/joojs/fairface) **|** [**💡 ORIGINAL IMPLEMENTATION**](https://github.com/dchen236/FairFace) **|** [**💻 Jupyter Notebook**](https://jupyter.org/install) **|** [**🔥 PyTorch**](https://pytorch.org/get-started/locally/) **|** **👁 CNN** **|** **💪🏽 CPU/GPU** **|**  [**🔗 LinkedIn**](https://www.linkedin.com/in/marcellbalogh) 👈🏽
#### 🔍 Description
<p align="justify">Multi-task learning is a subfield of Deep Learning in which multiple learning tasks (e.g. age and gender classification) are solved at the same time, while exploiting commonalities and differences across tasks. Transfer learning, on the otherhand, is the reuse of pre-trained models (e.g. VGG16 and RESNET34) on a new problem. It's a very popular technique because it can train ANNs faster with comparatively little data. This project implements these two powerful techniques in PyTorch on FAIRFACE dataset to classify gender and age within a single model.</p>

![Project Image](project-image-url)
> caption Implementing age estimation and gender classification.
---
#### ☑️ Prerequisites
- Python3
- See [requirements.txt](requirements.txt) for required packages
- Windows, Linux, MacOS

###### ⚙️ Installation
```html
   git clone https://github.com/BaMarcy/age_gender_predictor
```
```html
   pip install -r requirements.txt
```
---
#### 🛠️ Train
###### ⚙️ Run
```html
   jupyter notebook
```
---
#### 💊 Predict
The available models were trained with the following hyperparameters:

Hyperparameter  | Value
------------- | -------------
Epoch | 1
Batch Size | 32
Learning Rate | 0.0001

The available models can be dowloaded from the following links:

CNN Model | Test Accuracy | Inference
| :--- | ---: | :---:
Vgg16  | Gender: 82% - Age: 44.5% | [vgg16.pt](inferences/vgg16.pt)
ResNet34  | Gender: 79% - Age: 41.4 %| [resnet34.pt](inferences/resnet34.pt)

###### ⚙️ Run
```html
   python predict.py
```
---
#### 📉 Tensorboard
---
#### ☑️ TODO
- [x] Vgg16
- [x] ResNet34
---
