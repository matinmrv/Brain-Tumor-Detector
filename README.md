# Brain-Tumor-Detector

Building a Tumor detection model using cnn in Tensorflow

Data:
I found the data on kaggle. Here is the link to the dataset https://www.kaggle.com/navoneel/brain-mri-images-for-brain-tumor-detection. It contains 2 folders. yes and no. The folder yes contains images that are tumorous and the folder no contains non-tumorous images.

Different parts of the code is explained in the notebook.

Final Note:
I applied transfer learning using ResNet50 and vgg-16, but these models were overfitting(this problem is solvable with data augmentation).Of course I had to take into consideration computational complexity and memory limits.

