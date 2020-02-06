# Notes

My implementation of the [paper](https://arxiv.org/pdf/1903.11323v3.pdf) A novel machine learning based framework for detection of Autism Spectrum Disorder (ASD)

- [ABIDE-I dataset](http://fcon_1000.projects.nitrc.org/indi/abide/abide_I.html) 
- VGG16, top layer re-trained on image data
- softmax activation and ADAM optimizer
- learning rate 0.01, use fastai's LR optimizer for improvements?
- 80/20 train/test split
