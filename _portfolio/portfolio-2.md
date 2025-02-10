---
title: "Chest X-ray classification"
excerpt: "Reproducing ARK: Accruing and Reusing Annotations for Medical Image Classification<br/><img src='chest_xray2_0.png.webp'>"
collection: portfolio
---

In this project, I reproduced the classification results from the [Foundation Ark](https://arxiv.org/abs/2310.09507) framework by Ma et al., which explores how combining annotations from multiple datasets enhances deep learning models for medical imaging. Using the [CheXpert dataset](https://arxiv.org/abs/1901.07031), Irvin et al., which contains over 220,000 chest X-ray images, I conducted a detailed study by training models from scratch, utilizing pretrained models with different hyperparameter configurations, fine-tuning them, and comparing their performance.

🚀 Simply put: I tested whether AI models trained using annotations from different sources, fine-tuned under various settings, outperform those trained on a single dataset. Since I was able reproduce the results from the original paper, my study confirmed that accruing and reusing knowledge from diverse annotations leads to stronger and more reliable medical image classification models.

The code and study for my work can be found [here](https://github.com/ynitinreddy/ARK). I have also implemented the project on Kaggle for an easy understanding of the code and can be found [here](https://www.kaggle.com/code/ynitinreddy/chexpert-ark).