 ## Age👶👴 and Gender♀️♂️ Estimation with Transfer and Multi-Task Learning
 
[**💾 DATASET**](https://github.com/joojs/fairface) **|** [**💡 ORIGINAL IMPLEMENTATION**](https://github.com/dchen236/FairFace) **|** [**💻 Jupyter Notebook**](https://jupyter.org/install) **|** [**🔥 PyTorch**](https://pytorch.org/get-started/locally/) **|** **👁 CNN** **|** **💪🏽 CPU/GPU** **|**  [**🔗 LinkedIn**](https://www.linkedin.com/in/marcellbalogh) 👈🏽 

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bamarcy-age-gender-streamlit-streamlit-app-fr1omm.streamlitapp.com/)

#### 🔍 Description
<p align="justify">Multi-task learning is a subfield of Deep Learning in which multiple learning tasks (e.g. age and gender classification) are solved at the same time, while exploiting commonalities and differences across tasks. Transfer learning, on the other hand, is the reuse of pre-trained models (e.g. VGG16 RESNET18 and RESNET34) on a new problem. It's a very popular technique because it can train ANNs faster with comparatively little data. This project implements these two powerful techniques in PyTorch on FAIRFACE dataset to classify gender and age within a single model.</p>

<p align="center">
  <img src="test.PNG">
</p>

---
#### ☑️ Prerequisites
- Python3
- See [requirements.txt](requirements.txt) for required packages

###### ⚙️ Installation
```html
   git clone https://github.com/BaMarcy/age_gender_predictor
```
```html
   pip install -r requirements.txt
```
---
#### 🛠️ Train + 💊 Predict
###### ⚙️ Run
```html
   jupyter notebook age_gender_predictor.ipynb
```
---
#### 
The available models were trained with the following hyperparameters:

Hyperparameter  | Value
------------- | -------------
No. of Epochs | 10
Batch Size | 32
Learning Rate | 0.0001

The available models can be dowloaded from the following links:

Model | Accuracy | Inference (PyTorch) | Inference (ONNX)
| :--- | ---: | ---: | :---:
Vgg16  | Gender: 98% - Age: 89% - Race: 95% | [vgg16.pt](https://drive.google.com/file/d/1wnBjWxKhj0gAPOci7T-vPL9Y6UIhKct2/view?usp=sharing) | | [vgg16.pt](https://drive.google.com/file/d/1wnBjWxKhj0gAPOci7T-vPL9Y6UIhKct2/view?usp=sharing) -
ResNet18  | Gender: 98% - Age: 89% - Race: 95% | [resnet18.pt](https://drive.google.com/file/d/1Of1QdPEFhom7w7eugqqcwoOR3BIOj31M/view?usp=sharing)| -
ResNet34  | Gender: 98% - Age: 90% - Race: 95% | [resnet34.pt](https://drive.google.com/file/d/1vOz_Ey-dpQIyoG5yCBdtuwG2Rz-ursm6/view?usp=sharing)| -

---
#### 📉 Tensorboard

![](tensorboard.png)
---
#### ☑️ TODO
- [x] Vgg16
- [x] ResNet18
- [x] ResNet34
- [x] Ethnicity
- [x] ONNX
- [x] Streamlit
---
