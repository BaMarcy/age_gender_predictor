 ## AgeπΆπ΄ and GenderβοΈβοΈ Estimation with Transfer and Multi-Task Learning
 
[**πΎ DATASET**](https://github.com/joojs/fairface) **|** [**π‘ ORIGINAL IMPLEMENTATION**](https://github.com/dchen236/FairFace) **|** [**π» Jupyter Notebook**](https://jupyter.org/install) **|** [**π₯ PyTorch**](https://pytorch.org/get-started/locally/) **|** **π CNN** **|** **πͺπ½ CPU/GPU** **|**  [**π LinkedIn**](https://www.linkedin.com/in/marcellbalogh) ππ½ 

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://bamarcy-age-gender-streamlit-streamlit-app-fr1omm.streamlitapp.com/)

#### π Description
<p align="justify">Multi-task learning is a subfield of Deep Learning in which multiple learning tasks (e.g. age and gender classification) are solved at the same time, while exploiting commonalities and differences across tasks. Transfer learning, on the other hand, is the reuse of pre-trained models (e.g. VGG16 RESNET18 and RESNET34) on a new problem. It's a very popular technique because it can train ANNs faster with comparatively little data. This project implements these two powerful techniques in PyTorch on FAIRFACE dataset to classify gender and age within a single model.</p>

<p align="center">
  <img src="test.PNG">
</p>

---
#### βοΈ Prerequisites
- Python3
- See [requirements.txt](requirements.txt) for required packages
- Windows, Linux, MacOS

###### βοΈ Installation
```html
   git clone https://github.com/BaMarcy/age_gender_predictor
```
```html
   pip install -r requirements.txt
```
---
#### π οΈ Train + π Predict
###### βοΈ Run
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
Vgg16  | Gender: 97% - Age: 82% | [vgg16.pt](https://drive.google.com/file/d/1wnBjWxKhj0gAPOci7T-vPL9Y6UIhKct2/view?usp=sharing) | -
ResNet18  | Gender: 98% - Age: 92% | [resnet18.pt](https://drive.google.com/file/d/1Of1QdPEFhom7w7eugqqcwoOR3BIOj31M/view?usp=sharing)| -
ResNet34  | Gender: 99% - Age: 89% | [resnet34.pt](https://drive.google.com/file/d/1vOz_Ey-dpQIyoG5yCBdtuwG2Rz-ursm6/view?usp=sharing)| -

---
#### π Tensorboard

![](tensorboard.png)
---
#### βοΈ TODO
- [x] Vgg16
- [x] ResNet18
- [x] ResNet34
- [ ] Ethnicity
- [ ] ONNX
- [x] Streamlit
---
