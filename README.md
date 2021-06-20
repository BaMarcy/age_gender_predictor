 ## Age👶👴 and Gender♀️♂️ Estimation with Transfer and Multi-Task Learning
 
[**💾 DATASET**](https://github.com/joojs/fairface) **|** [**💡 ORIGINAL IMPLEMENTATION**](https://github.com/dchen236/FairFace) **|** [**💻 Jupyter Notebook**](https://jupyter.org/install) **|** [**🔥 PyTorch**](https://pytorch.org/get-started/locally/) **|** **👁 CNN** **|** **💪🏽 CPU/GPU** **|**  [**🔗 LinkedIn**](https://www.linkedin.com/in/marcellbalogh) 👈🏽
#### 🔍 Description
...
![Project Image](project-image-url)
> caption Implementing age estimation and gender classification.
---
#### ☑️ Prerequisites
- Python3
- See [requirements.txt](requirements.txt) for required packages
- Windows, Linux, MacOS
---
#### 🛠️ Train
###### ⚙️ Installation

```html
   git clone https://github.com/BaMarcy/age_gender_predictor
```
```html
   pip install -r requirements.txt
```
###### ⚙️ Run
```html
   jupyter notebook
```
---
#### 💊 Predict
CNN Model | Test Acc | Inference
| :--- | ---: | :---:
Vgg16  | Gender: 82% - Age: 44.5% | [vgg16.pt](inferences/vgg16.pt)
ResNet34  | Gender: % - Age: %| [resnet34.pt](inferences/resnet34.pt)
###### ⚙️ Installation
```html
   pip install age_gender_predictor
```
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
- [ ] PyPI
---
