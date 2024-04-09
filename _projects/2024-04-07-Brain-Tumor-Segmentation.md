---
layout: page
title: Brain Tumor Segmentation
description: 🧠 Brain tumor detection and segmentation
img: assets/img/Brain-tumor-segmentation.png
importance: 4
category: project
---


n the contemporary landscape, brain tumors have emerged as a prominent cause of global mortality. These
tumors manifest through abnormal growth of brain cells, profoundly impacting neighboring cells. This growth can
encompass both cancerous and non-cancerous cell types, with symptoms varying based on factors such as location,
size, and type. Detecting and precisely classifying brain tumors at their onset poses a formidable challenge due
to their intricate and diverse structures, aimed at mitigating the potential loss of life. To address this challenge,
this study proposes an enhanced model leveraging Convolutional Neural Networks (CNN) fused with ResNet50 and
U-Net architectures. This model operates on the TCGA-LGG and TCIA datasets, publicly available repositories
comprising data from 120 patients. The devised CNN, along with the fine-tuned ResNet50 model, is employed
for the detection and classification of tumor or non-tumor images. Additionally, the integration of the U-Net
model facilitates accurate segmentation of tumor regions. Evaluation of model performance is conducted using
metrics including accuracy, Intersection over Union (IoU), Dice Similarity Coefficient (DSC), and Similarity
Index (SI). Results from the fine-tuned ResNet50 model showcase impressive metrics: IoU: 0.91, DSC: 0.95, SI:
0.95. Notably, the U-Net model in conjunction with ResNet50 surpasses all other models, exhibiting superior
performance in correctly classifying and segmenting tumor regions.


<div class="row mt-1">
    <div class="col-12 mt-1">
        <div class="embed-responsive embed-responsive-16by9">
            <iframe width="560" height="315" src="https://www.youtube.com/embed/YXQyyHQM8YQ?si=ey04Bm1BFgo2A1Gd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
        </div>
    </div>
</div>


# Run Project 

The Github repository can also be found here:

[![madanbaduwal/brain-tumor-segmentation - GitHub](https://gh-card.dev/repos/madanbaduwal/brain-tumor-segmentation.svg)](https://github.com/madanbaduwal/brain-tumor-segmentation)
```bash

git clone https://github.com/madanbaduwal/brain-tumor-segmentation


cd project

python -m venv myenv


source myenv/bin/activate


pip3 install -r requirements.txt


streamlit run app.py

```

