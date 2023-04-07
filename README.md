# Skin diseases prediction using various deep neural networks
Here, I will be implementing various deep learning architectures to classify thirteen different types of skin diseases.
The target of this experiment is to compare various models on various parameters to draw possible conclusions about architectures.
Models implemented here are:
1. TinyVGG (without augmentation)
2. TinyVGG (with augmentation)
3. MobileNet
4. DenseNet
5. VGG19
6. Vision Transformers
<br>
As data is medical data, it is difficult to generate synthetic data which accurately represents specific diseases. That is why, I will be using resampling if required. Transfer learning will be used for some models while some will be trained from scratch.
<br>
Experiment is designed in a way that code can be understood easily with well written documentation following all methods of writing code suggested in PEP 8 style of python programming.
<br>
As this is experiment setup, code is in notebook. Once results are derived, code can be converted in modular format and packaged to be delievered for easy usage.
