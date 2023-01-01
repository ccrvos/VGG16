# VGG16

A simple image classifier using the PyTorch framework and the VGG16 architecture, following [Simonyan, K., & Zisserman, A. (2014)](https://doi.org/10.48550/arXiv.1409.1556).
However, I changed the batch size for GPU stability, and therefore also the learning rate. As for the learning rate, I also used a scheduler, as to reduce the learning rate when we stop seeing improvements on the validation set. 

I used the [Intel Image Classification dataset](https://www.kaggle.com/datasets/puneet6060/intel-image-classification). It should be noted that some of the images in the dataset are misclassified. 