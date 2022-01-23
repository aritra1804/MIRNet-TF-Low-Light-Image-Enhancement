# MIRNet-TF-Low-Light-Image-Enhancement


This repository shows the TensorFlow Lite and TensorRT model conversion and inference processes for the **MIRNet** model as proposed by [Learning Enriched Features for Real Image Restoration and Enhancement](https://arxiv.org/pdf/2003.06792v2.pdf). This model is able to enhance low-light images upto a great extent. 

<p align="center">
<img src="https://github.com/soumik12345/MIRNet/raw/master/assets/lol_results.gif"</img><br>
<small><a href="https://github.com/soumik12345/MIRNet/blob/master/assets/lol_results.gif">Source</a></small>
</p>

Model training code and pre-trained weights are provided by **Soumik** through [this repository](https://github.com/soumik12345/MIRNet/). 

## Comparison between the TensorFlow Lite and original models

**TensorFlow Lite model (dynamic-range quantized)**

<p align="center">
<img src="https://i.ibb.co/MswgSSg/image.png"></img>
</p>
  
**Original model**

<p align="center">
<img src="https://i.ibb.co/LJVSG01/image.png"></img>
</p>

## TensorFlow Lite models

* [Dynamic shape](https://github.com/aritra1804/MIRNet-TF-Low-Light-Image-Enhancement/blob/94ef26781fa45981cbc0d32d3140d23351dca1f4/MIRNet_TFLite.ipynb)(contains dynamic-range and fp16 quantized models)


